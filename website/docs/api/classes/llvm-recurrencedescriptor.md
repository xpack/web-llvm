---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/recurrencedescriptor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RecurrenceDescriptor` Class

<p>The <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor">RecurrenceDescriptor</a> is used to identify recurrences variables in a loop. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::RecurrenceDescriptor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">llvm/Analysis/IVDescriptors.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e9a6d9348306b3d62804dac54e358a7">RecurrenceDescriptor</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c77d83940680b94992ef3ca58e755bb">RecurrenceDescriptor</a> (Value *Start, Instruction *Exit, StoreInst *Store, RecurKind K, FastMathFlags FMF, Instruction *ExactFP, Type *RT, bool Signed, bool Ordered, SmallPtrSetImpl&lt; Instruction * &gt; &amp;CI, unsigned MinWidthCastToRecurTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830e">RecurKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89e9d5a5838c63159df1aed56f600ef1">getRecurrenceKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32c8ad694911bf6dcf6cb07824f2823e">getOpcode</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d5c759e770c1c6032d077a1b9cf7172">getFastMathFlags</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/trackingvh">TrackingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61351428b7eb226cbad866ccf2382817">getRecurrenceStartValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b34d6e86d376d6857ccf7dd75d7dcf2">getLoopExitInstr</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25187781de77a2ccf8406804fe510ce8">hasExactFPMath</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the recurrence has floating-point math that requires precise (ordered) operations. <a href="#a25187781de77a2ccf8406804fe510ce8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07c7bed45660a4891e7661114e16d839">getExactFPMathInst</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns 1st non-reassociative FP instruction in the PHI node's use-chain. <a href="#a07c7bed45660a4891e7661114e16d839">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f29fefacd6bdd966f6ba021cc656a2f">getRecurrenceType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the type of the recurrence. <a href="#a4f29fefacd6bdd966f6ba021cc656a2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed10715d943d3e1b4ca75b585ea96ab8">getSentinelValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the sentinel value for FindLastIV recurrences to replace the start value. <a href="#aed10715d943d3e1b4ca75b585ea96ab8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 8 &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5691507e6742c90b796d82fb8cb2d70d">getCastInsts</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a reference to the instructions used for type-promoting the recurrence. <a href="#a5691507e6742c90b796d82fb8cb2d70d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f64b98dd7b1371ddda6c24bf2163be6">getMinWidthCastToRecurrenceTypeInBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the minimum width used by the recurrence in bits. <a href="#a5f64b98dd7b1371ddda6c24bf2163be6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a855906f5a6f429db8978680fd6de7886">isSigned</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if all source operands of the recurrence are SExtInsts. <a href="#a855906f5a6f429db8978680fd6de7886">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dad5abc2bd929acd8391643b2dbe4c5">isOrdered</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expose an ordered FP reduction to the instance users. <a href="#a8dad5abc2bd929acd8391643b2dbe4c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6415fb68bc55f3a316aa414a5c2c0ab2">getReductionOpChain</a> (PHINode *Phi, Loop *L) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempts to find a chain of operations from Phi to LoopExitInst that can be treated as a set of reductions instructions for in-loop reductions. <a href="#a6415fb68bc55f3a316aa414a5c2c0ab2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e4044de402972428a2101b8afcaa1b7">IntermediateStore</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reductions may store temporary or final result to an invariant address. <a href="#a9e4044de402972428a2101b8afcaa1b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/trackingvh">TrackingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35bf39501349f5c721c1791601c1de54">StartValue</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5b0acc4b9c1c6d987e7fe2b97342039">LoopExitInstr</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830e">RecurKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f20712d57a3986d675da2a40bc72664">Kind</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea6adf97f83acf6453d4a6a4b1070f3754">RecurKind::None</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a127d045f00e3150019d2020b42dd094a">FMF</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09e5483706ce0d210c5fabf41d5005d8">ExactFPMathInst</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73288440b37dc3ca87bea5c2d4f17c3f">RecurrenceType</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7deb2536001ecd9371ac5a241f9f0a65">IsSigned</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c2b64c4e5ad0aff706b7d56b54124b2">IsOrdered</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaca8dacc9c1e9cfb993cdca0200b3f35">CastInsts</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a286b4f46e6708dfe51f7543d8c709186">MinWidthCastToRecurrenceType</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/instdesc">InstDesc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa35caaec45d90bbc9c564181b77c109e">isRecurrenceInstr</a> (Loop *L, PHINode *Phi, Instruction *I, RecurKind Kind, InstDesc &amp;Prev, FastMathFlags FuncFMF, ScalarEvolution *SE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a struct describing if the instruction 'I' can be a recurrence variable of type 'Kind' for a <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> <span class="doxyComputerOutput">L</span> and reduction PHI <span class="doxyComputerOutput">Phi</span>. <a href="#aa35caaec45d90bbc9c564181b77c109e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a416f5cbc600b5d4da0c80d1dab29b1d8">hasMultipleUsesOf</a> (Instruction *I, SmallPtrSetImpl&lt; Instruction * &gt; &amp;Insts, unsigned MaxNumUses)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if instruction I has multiple uses in Insts. <a href="#a416f5cbc600b5d4da0c80d1dab29b1d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58acdd346629e1384dbbf4ccd46fcf79">areAllUsesIn</a> (Instruction *I, SmallPtrSetImpl&lt; Instruction * &gt; &amp;Set)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if all uses of the instruction I is within the Set. <a href="#a58acdd346629e1384dbbf4ccd46fcf79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/instdesc">InstDesc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae318fdb278df4aaf9e229584fb769b41">isMinMaxPattern</a> (Instruction *I, RecurKind Kind, const InstDesc &amp;Prev)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a struct describing if the instruction is a llvm. <a href="#ae318fdb278df4aaf9e229584fb769b41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/instdesc">InstDesc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7af4f3d780a4c92809414d5e43d98337">isAnyOfPattern</a> (Loop *Loop, PHINode *OrigPhi, Instruction *I, InstDesc &amp;Prev)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a struct describing whether the instruction is either a <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp/#a09bc27545df3b02401428427d0b5ce6f">Select(ICmp(A, B), X, Y)</a>, or <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp/#a09bc27545df3b02401428427d0b5ce6f">Select(FCmp(A, B), X, Y)</a> where one of (X, Y) is a loop invariant integer and the other is a PHI value. <a href="#a7af4f3d780a4c92809414d5e43d98337">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/instdesc">InstDesc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a797a268a4ac8802907a1b36ee57166e2">isFindLastIVPattern</a> (Loop *TheLoop, PHINode *OrigPhi, Instruction *I, ScalarEvolution &amp;SE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a struct describing whether the instruction is either a <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp/#a09bc27545df3b02401428427d0b5ce6f">Select(ICmp(A, B), X, Y)</a>, or <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp/#a09bc27545df3b02401428427d0b5ce6f">Select(FCmp(A, B), X, Y)</a> where one of (X, Y) is an increasing loop induction variable, and the other is a PHI value. <a href="#a797a268a4ac8802907a1b36ee57166e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/instdesc">InstDesc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89705a5029e6850fc3d6445ebc775c15">isConditionalRdxPattern</a> (RecurKind Kind, Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a struct describing if the instruction is a Select(FCmp(X, Y), (Z = X op <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a>), <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a>) instruction pattern. <a href="#a89705a5029e6850fc3d6445ebc775c15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30ee597b72598bc7939d3a40d2a5ba20">getOpcode</a> (RecurKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the opcode corresponding to the RecurrenceKind. <a href="#a30ee597b72598bc7939d3a40d2a5ba20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3b1b80ef450d6706f42f3a929e51ce5">AddReductionVar</a> (PHINode *Phi, RecurKind Kind, Loop *TheLoop, FastMathFlags FuncFMF, RecurrenceDescriptor &amp;RedDes, DemandedBits *DB=nullptr, AssumptionCache *AC=nullptr, DominatorTree *DT=nullptr, ScalarEvolution *SE=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if Phi is a reduction of type Kind and adds it to the <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor">RecurrenceDescriptor</a>. <a href="#ae3b1b80ef450d6706f42f3a929e51ce5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a484f974fc232e862a87a6380d3a7587d">isReductionPHI</a> (PHINode *Phi, Loop *TheLoop, RecurrenceDescriptor &amp;RedDes, DemandedBits *DB=nullptr, AssumptionCache *AC=nullptr, DominatorTree *DT=nullptr, ScalarEvolution *SE=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if Phi is a reduction in TheLoop. <a href="#a484f974fc232e862a87a6380d3a7587d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a203487323e0aa341b6c24f9ef20b5909">isFixedOrderRecurrence</a> (PHINode *Phi, Loop *TheLoop, DominatorTree *DT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if Phi is a fixed-order recurrence. <a href="#a203487323e0aa341b6c24f9ef20b5909">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebf484d18c0adaa365f5307d2d8e00a7">isIntegerRecurrenceKind</a> (RecurKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the recurrence kind is an integer kind. <a href="#aebf484d18c0adaa365f5307d2d8e00a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac70d0e0d91dcd02d08a23638be772bac">isFloatingPointRecurrenceKind</a> (RecurKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the recurrence kind is a floating point kind. <a href="#ac70d0e0d91dcd02d08a23638be772bac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef4824e1c55ce3d04e8759c333dbc5c5">isIntMinMaxRecurrenceKind</a> (RecurKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the recurrence kind is an integer min/max kind. <a href="#aef4824e1c55ce3d04e8759c333dbc5c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05ee667a3bd7353c72f9be938471af17">isFPMinMaxRecurrenceKind</a> (RecurKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the recurrence kind is a floating-point min/max kind. <a href="#a05ee667a3bd7353c72f9be938471af17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af08d243545b64f4b77161992d0e2366e">isMinMaxRecurrenceKind</a> (RecurKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the recurrence kind is any min/max kind. <a href="#af08d243545b64f4b77161992d0e2366e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69df67c7d92481ae63a5d8017e96c716">isAnyOfRecurrenceKind</a> (RecurKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the recurrence kind is of the form select(cmp(),x,y) where one of (x,y) is loop invariant. <a href="#a69df67c7d92481ae63a5d8017e96c716">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bc46d4489f4d6cb4a4e486ce5f6184b">isFindLastIVRecurrenceKind</a> (RecurKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the recurrence kind is of the form select(cmp(),x,y) where one of (x,y) is increasing loop induction. <a href="#a7bc46d4489f4d6cb4a4e486ce5f6184b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08416fb970e8c177c7d78452d927c606">isFMulAddIntrinsic</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the instruction is a call to the llvm.fmuladd intrinsic. <a href="#a08416fb970e8c177c7d78452d927c606">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor">RecurrenceDescriptor</a> is used to identify recurrences variables in a loop.</p>


<p>Reduction is a special case of recurrence that has uses of the recurrence variable outside the loop. The method isReductionPHI identifies reductions that are basic recurrences.</p>


<p>Basic recurrences are defined as the summation, product, OR, AND, XOR, min, or max of a set of terms. For example: for(i=0; i&lt;n; i++) { total += array[i]; } is a summation of array elements. Basic recurrences are a special case of chains of recurrences (CR). See <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> for CR references. This struct holds information about recurrence variables.</p>


<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RecurrenceDescriptor() {#a5e9a6d9348306b3d62804dac54e358a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RecurrenceDescriptor::RecurrenceDescriptor ()</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>Referenced by <a href="#ae3b1b80ef450d6706f42f3a929e51ce5">AddReductionVar</a> and <a href="#a484f974fc232e862a87a6380d3a7587d">isReductionPHI</a>.</p>

</div>
</div>

### RecurrenceDescriptor() {#a4c77d83940680b94992ef3ca58e755bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RecurrenceDescriptor::RecurrenceDescriptor (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Start, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Exit, <a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * Store, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830e">RecurKind</a> K, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * ExactFP, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RT, bool Signed, bool Ordered, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; CI, unsigned MinWidthCastToRecurTy)</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#abf73a826b5d6f739eb4af48ddf14c5b4">llvm::SmallPtrSetImpl&lt; PtrType &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a7004354fbee1c8cd74ed9001915e1db5">llvm::SmallPtrSetImpl&lt; PtrType &gt;::end</a>, <a href="#a9e4044de402972428a2101b8afcaa1b7">IntermediateStore</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCastInsts() {#a5691507e6742c90b796d82fb8cb2d70d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallPtrSet&lt; Instruction *, 8 &gt; &amp; llvm::RecurrenceDescriptor::getCastInsts ()</td>
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

<p>Returns a reference to the instructions used for type-promoting the recurrence.</p>

<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a0ac5df8f0304981180d602dacb13512c">llvm::LoopVectorizationCostModel::collectValuesToIgnore</a>.</p>

</div>
</div>

### getExactFPMathInst() {#a07c7bed45660a4891e7661114e16d839}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::RecurrenceDescriptor::getExactFPMathInst ()</td>
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

<p>Returns 1st non-reassociative FP instruction in the PHI node's use-chain.</p>

<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a206a95af7fd1177ef8396cd69b888de2">findInnerReductionPhi</a>.</p>

</div>
</div>

### getFastMathFlags() {#a0d5c759e770c1c6032d077a1b9cf7172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastMathFlags llvm::RecurrenceDescriptor::getFastMathFlags ()</td>
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



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a4e307866e6d65e87d1e6884b0d13306c">llvm::LoopVectorizationCostModel::getReductionPatternCost</a>.</p>

</div>
</div>

### getLoopExitInstr() {#a2b34d6e86d376d6857ccf7dd75d7dcf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::RecurrenceDescriptor::getLoopExitInstr ()</td>
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



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#a760fb390c24b907500c0a181fada9590">llvm::VPRecipeBuilder::tryToCreateWidenRecipe</a>.</p>

</div>
</div>

### getMinWidthCastToRecurrenceTypeInBits() {#a5f64b98dd7b1371ddda6c24bf2163be6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RecurrenceDescriptor::getMinWidthCastToRecurrenceTypeInBits ()</td>
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

<p>Returns the minimum width used by the recurrence in bits.</p>

<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a1fa63b37ad2ac06f289e9962a3703e9e">llvm::LoopVectorizationCostModel::getSmallestAndWidestTypes</a>.</p>

</div>
</div>

### getOpcode() {#a32c8ad694911bf6dcf6cb07824f2823e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RecurrenceDescriptor::getOpcode ()</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>References <a href="#a32c8ad694911bf6dcf6cb07824f2823e">getOpcode</a> and <a href="#a89e9d5a5838c63159df1aed56f600ef1">getRecurrenceKind</a>.</p>


<p>Referenced by <a href="#a32c8ad694911bf6dcf6cb07824f2823e">getOpcode</a> and <a href="#a6415fb68bc55f3a316aa414a5c2c0ab2">getReductionOpChain</a>.</p>

</div>
</div>

### getRecurrenceKind() {#a89e9d5a5838c63159df1aed56f600ef1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecurKind llvm::RecurrenceDescriptor::getRecurrenceKind ()</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ace9e1e6e7295914973dec18350b382ca">llvm::VPlanTransforms::clearReductionWrapFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a90ad8ccd396152c749068f986f2b751a">fixReductionScalarResumeWhenVectorizingEpilog</a>, <a href="#a32c8ad694911bf6dcf6cb07824f2823e">getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a4e307866e6d65e87d1e6884b0d13306c">llvm::LoopVectorizationCostModel::getReductionPatternCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a31212d6ba24ec9ee5e31110dae47ee94">llvm::AArch64TTIImpl::isLegalToVectorizeReduction</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#ae7200479e50b7404b1b98874993c341d">llvm::RISCVTTIImpl::isLegalToVectorizeReduction</a>, <a href="#a484f974fc232e862a87a6380d3a7587d">isReductionPHI</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#aae23f7e6fc37b0f1bb756f938023512c">preparePlanForEpilogueVectorLoop</a>.</p>

</div>
</div>

### getRecurrenceStartValue() {#a61351428b7eb226cbad866ccf2382817}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TrackingVH&lt; Value &gt; llvm::RecurrenceDescriptor::getRecurrenceStartValue ()</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a90ad8ccd396152c749068f986f2b751a">fixReductionScalarResumeWhenVectorizingEpilog</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#aae23f7e6fc37b0f1bb756f938023512c">preparePlanForEpilogueVectorLoop</a> and <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#a760fb390c24b907500c0a181fada9590">llvm::VPRecipeBuilder::tryToCreateWidenRecipe</a>.</p>

</div>
</div>

### getRecurrenceType() {#a4f29fefacd6bdd966f6ba021cc656a2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::RecurrenceDescriptor::getRecurrenceType ()</td>
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

<p>Returns the type of the recurrence.</p>


<p>This type can be narrower than the actual type of the Phi if the recurrence has been type-promoted.</p>


<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a06f5d9725a2b1f7b06e8bf51f7d31417">llvm::LoopVectorizationCostModel::collectElementTypesForWidening</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a12d2850f420726c4acb262b626e95b7d">llvm::LoopVectorizationCostModel::collectInLoopReductions</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a4e307866e6d65e87d1e6884b0d13306c">llvm::LoopVectorizationCostModel::getReductionPatternCost</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a1fa63b37ad2ac06f289e9962a3703e9e">llvm::LoopVectorizationCostModel::getSmallestAndWidestTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a31212d6ba24ec9ee5e31110dae47ee94">llvm::AArch64TTIImpl::isLegalToVectorizeReduction</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#ae7200479e50b7404b1b98874993c341d">llvm::RISCVTTIImpl::isLegalToVectorizeReduction</a>.</p>

</div>
</div>

### getReductionOpChain() {#a6415fb68bc55f3a316aa414a5c2c0ab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; Instruction *, 4 &gt; RecurrenceDescriptor::getReductionOpChain (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * Phi, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempts to find a chain of operations from Phi to LoopExitInst that can be treated as a set of reductions instructions for in-loop reductions.</p>

<p>Declaration at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>, definition at line 1167 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a32c8ad694911bf6dcf6cb07824f2823e">getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a7c779ce2ba55bc94f52014fc25f3d520">llvm::Value::hasNUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a08416fb970e8c177c7d78452d927c606">isFMulAddIntrinsic</a>, <a href="/web-llvm/docs/api/structs/llvm/selectpatternresult/#a94c732c9e96c40976f0509fe0233fe7b">llvm::SelectPatternResult::isMinOrMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7aad5a0e62a54747f455651ee2dd08ed">llvm::matchSelectPattern</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a12d2850f420726c4acb262b626e95b7d">llvm::LoopVectorizationCostModel::collectInLoopReductions</a>.</p>

</div>
</div>

### getSentinelValue() {#aed10715d943d3e1b4ca75b585ea96ab8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::RecurrenceDescriptor::getSentinelValue ()</td>
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

<p>Returns the sentinel value for FindLastIV recurrences to replace the start value.</p>

<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a> and <a href="#a7bc46d4489f4d6cb4a4e486ce5f6184b">isFindLastIVRecurrenceKind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a90ad8ccd396152c749068f986f2b751a">fixReductionScalarResumeWhenVectorizingEpilog</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#aae23f7e6fc37b0f1bb756f938023512c">preparePlanForEpilogueVectorLoop</a>.</p>

</div>
</div>

### hasExactFPMath() {#a25187781de77a2ccf8406804fe510ce8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RecurrenceDescriptor::hasExactFPMath ()</td>
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

<p>Returns true if the recurrence has floating-point math that requires precise (ordered) operations.</p>

<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality/#a552a158f5a673da0a26461d1471cea41">llvm::LoopVectorizationLegality::canVectorizeFPMath</a>.</p>

</div>
</div>

### isOrdered() {#a8dad5abc2bd929acd8391643b2dbe4c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RecurrenceDescriptor::isOrdered ()</td>
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

<p>Expose an ordered FP reduction to the instance users.</p>

<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality/#a552a158f5a673da0a26461d1471cea41">llvm::LoopVectorizationLegality::canVectorizeFPMath</a> and <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ad508b8cfa31c0e7a1ac8f9d733bb8eed">llvm::LoopVectorizationCostModel::useOrderedReductions</a>.</p>

</div>
</div>

### isSigned() {#a855906f5a6f429db8978680fd6de7886}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RecurrenceDescriptor::isSigned ()</td>
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

<p>Returns true if all source operands of the recurrence are SExtInsts.</p>

<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### IntermediateStore {#a9e4044de402972428a2101b8afcaa1b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StoreInst* llvm::RecurrenceDescriptor::IntermediateStore = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reductions may store temporary or final result to an invariant address.</p>


<p>If there is such a store in the loop then, after successfull run of AddReductionVar method, this field will be assigned the last met store.</p>


<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>Referenced by <a href="#ae3b1b80ef450d6706f42f3a929e51ce5">AddReductionVar</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality/#a34f384c7ff8e4b23cc79156daf2a5c11">llvm::LoopVectorizationLegality::isInvariantAddressOfReduction</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality/#a1c9fd1c0627dfa3e013a1b2c7416ae90">llvm::LoopVectorizationLegality::isInvariantStoreOfReduction</a> and <a href="#a4c77d83940680b94992ef3ca58e755bb">RecurrenceDescriptor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CastInsts {#aaca8dacc9c1e9cfb993cdca0200b3f35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Instruction *, 8&gt; llvm::RecurrenceDescriptor::CastInsts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>

</div>
</div>

### ExactFPMathInst {#a09e5483706ce0d210c5fabf41d5005d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* llvm::RecurrenceDescriptor::ExactFPMathInst = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>

</div>
</div>

### FMF {#a127d045f00e3150019d2020b42dd094a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastMathFlags llvm::RecurrenceDescriptor::FMF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>

</div>
</div>

### IsOrdered {#a4c2b64c4e5ad0aff706b7d56b54124b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RecurrenceDescriptor::IsOrdered = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>

</div>
</div>

### IsSigned {#a7deb2536001ecd9371ac5a241f9f0a65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RecurrenceDescriptor::IsSigned = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>

</div>
</div>

### Kind {#a5f20712d57a3986d675da2a40bc72664}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecurKind llvm::RecurrenceDescriptor::Kind = <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea6adf97f83acf6453d4a6a4b1070f3754">RecurKind::None</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>

</div>
</div>

### LoopExitInstr {#ae5b0acc4b9c1c6d987e7fe2b97342039}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* llvm::RecurrenceDescriptor::LoopExitInstr = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>

</div>
</div>

### MinWidthCastToRecurrenceType {#a286b4f46e6708dfe51f7543d8c709186}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RecurrenceDescriptor::MinWidthCastToRecurrenceType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>

</div>
</div>

### RecurrenceType {#a73288440b37dc3ca87bea5c2d4f17c3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* llvm::RecurrenceDescriptor::RecurrenceType = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>

</div>
</div>

### StartValue {#a35bf39501349f5c721c1791601c1de54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TrackingVH&lt;Value&gt; llvm::RecurrenceDescriptor::StartValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### AddReductionVar() {#ae3b1b80ef450d6706f42f3a929e51ce5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RecurrenceDescriptor::AddReductionVar (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * Phi, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830e">RecurKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * TheLoop, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FuncFMF, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor">RecurrenceDescriptor</a> &amp; RedDes, <a href="/web-llvm/docs/api/classes/llvm/demandedbits">DemandedBits</a> * DB=nullptr, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC=nullptr, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT=nullptr, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE=nullptr)</td>
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

<p>Returns true if Phi is a reduction of type Kind and adds it to the <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor">RecurrenceDescriptor</a>.</p>


<p>If either <span class="doxyComputerOutput">DB</span> is non-null or <span class="doxyComputerOutput">AC</span> and <span class="doxyComputerOutput">DT</span> are non-null, the minimal bit width needed to compute the reduction will be computed.</p>


<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>, definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="#a58acdd346629e1384dbbf4ccd46fcf79">areAllUsesIn</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp/#a65aa908de5625be851aa7b97327d194b">checkOrderedReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp/#a586a0928ddd8c387ebb2032e9f61e55b">collectCastInstrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp/#af481dabda60939ffaa5c0da35892dc96">computeRecurrenceType</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaf552e181879ad14956985859308d77d9">llvm::FAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3276c083ed6e470fc7ce908151c3ffec">llvm::FAnyOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eab48b2a9934af7a531cfd7236ded9d50e">llvm::FMul</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/instdesc/#a4e5fa9293b8cc92ad77f1f7c84f3902f">llvm::RecurrenceDescriptor::InstDesc::getExactFPMathInst</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#acd492b88eb98461e692085ed400db114">llvm::FastMathFlags::getFast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9a167f91db810097d281b1ed627f4575">llvm::Instruction::getFastMathFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ac3280e7f76f955403fe17eacf126b90d">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopPreheader</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/instdesc/#a29f533f38ba438c9509e7de5db3ef386">llvm::RecurrenceDescriptor::InstDesc::getPatternInst</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/instdesc/#a27f1e170050db66311c01670d5347890">llvm::RecurrenceDescriptor::InstDesc::getRecKind</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a30bd18ac905eacf3601bc6a553a9ff49">llvm::ScalarEvolution::getSCEV</a>, <a href="#a416f5cbc600b5d4da0c80d1dab29b1d8">hasMultipleUsesOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaf574002db61510c589ee98a24ebca627">llvm::IAnyOf</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="#a9e4044de402972428a2101b8afcaa1b7">IntermediateStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a7af4f3d780a4c92809414d5e43d98337">isAnyOfPattern</a>, <a href="#a69df67c7d92481ae63a5d8017e96c716">isAnyOfRecurrenceKind</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a55743bd32282bf6f87aeb49237b1fb68">llvm::Instruction::isCommutative</a>, <a href="#a89705a5029e6850fc3d6445ebc775c15">isConditionalRdxPattern</a>, <a href="#ac70d0e0d91dcd02d08a23638be772bac">isFloatingPointRecurrenceKind</a>, <a href="#a08416fb970e8c177c7d78452d927c606">isFMulAddIntrinsic</a>, <a href="#a05ee667a3bd7353c72f9be938471af17">isFPMinMaxRecurrenceKind</a>, <a href="#aebf484d18c0adaa365f5307d2d8e00a7">isIntegerRecurrenceKind</a>, <a href="#aef4824e1c55ce3d04e8759c333dbc5c5">isIntMinMaxRecurrenceKind</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a5a19768af81df7e5fe571bc08dcd48b3">llvm::ScalarEvolution::isLoopInvariant</a>, <a href="#ae318fdb278df4aaf9e229584fb769b41">isMinMaxPattern</a>, <a href="#af08d243545b64f4b77161992d0e2366e">isMinMaxRecurrenceKind</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/instdesc/#a3229b03ebdd522056dc363eda387472c">llvm::RecurrenceDescriptor::InstDesc::isRecurrence</a>, <a href="#aa35caaec45d90bbc9c564181b77c109e">isRecurrenceInstr</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp/#aa78d689f88c58652639663f07a64ca41">lookThroughAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a5e9a6d9348306b3d62804dac54e358a7">RecurrenceDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>


<p>Referenced by <a href="#a484f974fc232e862a87a6380d3a7587d">isReductionPHI</a>.</p>

</div>
</div>

### areAllUsesIn() {#a58acdd346629e1384dbbf4ccd46fcf79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RecurrenceDescriptor::areAllUsesIn (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; Set)</td>
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

<p>Returns true if all uses of the instruction I is within the Set.</p>

<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>, definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#ae3b1b80ef450d6706f42f3a929e51ce5">AddReductionVar</a>.</p>

</div>
</div>

### getOpcode() {#a30ee597b72598bc7939d3a40d2a5ba20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned RecurrenceDescriptor::getOpcode (<a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830e">RecurKind</a> Kind)</td>
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

<p>Returns the opcode corresponding to the RecurrenceKind.</p>

<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>, definition at line 1130 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eac33315685a0cba3ce53be378b3c7874b">llvm::And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaf552e181879ad14956985859308d77d9">llvm::FAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3276c083ed6e470fc7ce908151c3ffec">llvm::FAnyOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ead4c3e0abb938f94c273edbc5e291cbe2">llvm::FFindLastIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea8764eae15a1f2cf1c964d14dcf9283ee">llvm::FMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea8bdc72f64bbc121d5c6fa14cdef4c8bf">llvm::FMaximum</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ead76b595f89852f41ac50173abae6da05">llvm::FMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea4e137992425232e2d0b0142b7062378b">llvm::FMinimum</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eab48b2a9934af7a531cfd7236ded9d50e">llvm::FMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaa7dad289ea38506fb1c9b5b148405d0c">llvm::FMulAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaf574002db61510c589ee98a24ebca627">llvm::IAnyOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea258973cbb0e48644fbb62d22ce6314bf">llvm::IFindLastIV</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea62b6d55816cf737bfc6f42e60df1a3f2">llvm::Mul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">llvm::Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eabccd0de85dfbe7aef83629b318a4df6e">llvm::SMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ead6bb6a2eca7d60c75e349ea45e138d74">llvm::SMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eafaa1f94cd925672925f691e7f5727a6b">llvm::UMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea1c692ed4bf463fb08fca4d8cb8201ac0">llvm::UMin</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea76feb79109026728a20736a8c6504548">llvm::Xor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a06f5d9725a2b1f7b06e8bf51f7d31417">llvm::LoopVectorizationCostModel::collectElementTypesForWidening</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a12d2850f420726c4acb262b626e95b7d">llvm::LoopVectorizationCostModel::collectInLoopReductions</a> and <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a4e307866e6d65e87d1e6884b0d13306c">llvm::LoopVectorizationCostModel::getReductionPatternCost</a>.</p>

</div>
</div>

### hasMultipleUsesOf() {#a416f5cbc600b5d4da0c80d1dab29b1d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RecurrenceDescriptor::hasMultipleUsesOf (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; Insts, unsigned MaxNumUses)</td>
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

<p>Returns true if instruction I has multiple uses in Insts.</p>

<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>, definition at line 910 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#ae3b1b80ef450d6706f42f3a929e51ce5">AddReductionVar</a>.</p>

</div>
</div>

### isAnyOfPattern() {#a7af4f3d780a4c92809414d5e43d98337}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecurrenceDescriptor::InstDesc RecurrenceDescriptor::isAnyOfPattern (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * Loop, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * OrigPhi, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/instdesc">InstDesc</a> &amp; Prev)</td>
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

<p>Returns a struct describing whether the instruction is either a <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp/#a09bc27545df3b02401428427d0b5ce6f">Select(ICmp(A, B), X, Y)</a>, or <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp/#a09bc27545df3b02401428427d0b5ce6f">Select(FCmp(A, B), X, Y)</a> where one of (X, Y) is a loop invariant integer and the other is a PHI value.</p>


<p><span class="doxyComputerOutput">Prev</span> specifies the description of an already processed select instruction, so its corresponding cmp can be matched to it.</p>


<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>, definition at line 629 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3276c083ed6e470fc7ce908151c3ffec">llvm::FAnyOf</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/instdesc/#a27f1e170050db66311c01670d5347890">llvm::RecurrenceDescriptor::InstDesc::getRecKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaf574002db61510c589ee98a24ebca627">llvm::IAnyOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#a6cb6a58fb0ded82b4c7755fc4c27c86d">llvm::Loop::isLoopInvariant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a7d9ab823fe85606fa795c0c6fc75aca6">llvm::PatternMatch::m_Cmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5be13f3abb6bddf7ad9747b077da5a0e">llvm::PatternMatch::m_OneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3ccd94f6a7507492b47c7351e3fb78c6">llvm::PatternMatch::m_Select</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp/#a09bc27545df3b02401428427d0b5ce6f">Select</a>.</p>


<p>Referenced by <a href="#ae3b1b80ef450d6706f42f3a929e51ce5">AddReductionVar</a> and <a href="#aa35caaec45d90bbc9c564181b77c109e">isRecurrenceInstr</a>.</p>

</div>
</div>

### isAnyOfRecurrenceKind() {#a69df67c7d92481ae63a5d8017e96c716}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RecurrenceDescriptor::isAnyOfRecurrenceKind (<a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830e">RecurKind</a> Kind)</td>
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

<p>Returns true if the recurrence kind is of the form select(cmp(),x,y) where one of (x,y) is loop invariant.</p>

<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3276c083ed6e470fc7ce908151c3ffec">llvm::FAnyOf</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaf574002db61510c589ee98a24ebca627">llvm::IAnyOf</a>.</p>


<p>Referenced by <a href="#ae3b1b80ef450d6706f42f3a929e51ce5">AddReductionVar</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#a45ff90e525c3f3879a1a7f5297d8857d">llvm::VPReductionRecipe::computeCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5897728042dea4157da81dc8fe3fe160">llvm::createAnyOfReduction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a855f1a63640f9dfdabbe1df5fd39d31e">llvm::createReduction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaad6ad14450e1c8538ecb5729060e4aa">llvm::createSimpleReduction</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionphirecipe/#ad481483dac767c09d773266ba8b877e5">llvm::VPReductionPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#ac66885d3ce04a263a03746461eac12b1">llvm::VPReductionRecipe::execute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a90ad8ccd396152c749068f986f2b751a">fixReductionScalarResumeWhenVectorizingEpilog</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a556ec90a0fa1e168a9f22db1deb1fee6">llvm::LoopVectorizationCostModel::getInstructionCost</a>, <a href="#aa35caaec45d90bbc9c564181b77c109e">isRecurrenceInstr</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#aae23f7e6fc37b0f1bb756f938023512c">preparePlanForEpilogueVectorLoop</a>.</p>

</div>
</div>

### isConditionalRdxPattern() {#a89705a5029e6850fc3d6445ebc775c15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecurrenceDescriptor::InstDesc RecurrenceDescriptor::isConditionalRdxPattern (<a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830e">RecurKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Returns a struct describing if the instruction is a Select(FCmp(X, Y), (Z = X op <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a>), <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a>) instruction pattern.</p>


<p>Returns true if the select instruction has users in the compare-and-add reduction pattern below.</p>


<p>The select instruction argument is the last one in the sequence.</p>


<p>sum.1 = phi ... ... cmp = fcmp pred %0, CFP add = fadd %0, sum.1 sum.2 = select cmp, add, sum.1</p>


<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>, definition at line 809 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3a402430a1bbe70a9282dcb0e0b6a2cd">llvm::Value::hasOneUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a062ccd76a126632721e9aa09775d6c0e">llvm::PatternMatch::m_Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a4ea054dc4c7dd6b5a27eaf33b7fa20b5">llvm::PatternMatch::m_FAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2473234214d47e1991056897d735d82d">llvm::PatternMatch::m_FMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0fa2fe47478bcc6676ec49dd76544e3a">llvm::PatternMatch::m_FSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a532515120d78196926b68c48460087ab">llvm::PatternMatch::m_Mul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af5c293ba602295963ee06dd6f22e6335">llvm::PatternMatch::m_Sub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="#ae3b1b80ef450d6706f42f3a929e51ce5">AddReductionVar</a> and <a href="#aa35caaec45d90bbc9c564181b77c109e">isRecurrenceInstr</a>.</p>

</div>
</div>

### isFindLastIVPattern() {#a797a268a4ac8802907a1b36ee57166e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecurrenceDescriptor::InstDesc RecurrenceDescriptor::isFindLastIVPattern (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * TheLoop, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * OrigPhi, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
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

<p>Returns a struct describing whether the instruction is either a <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp/#a09bc27545df3b02401428427d0b5ce6f">Select(ICmp(A, B), X, Y)</a>, or <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp/#a09bc27545df3b02401428427d0b5ce6f">Select(FCmp(A, B), X, Y)</a> where one of (X, Y) is an increasing loop induction variable, and the other is a PHI value.</p>

<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>, definition at line 691 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aaca3a4d2b25c24b11179cbd01079b73c">llvm::ConstantRange::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ead4c3e0abb938f94c273edbc5e291cbe2">llvm::FFindLastIV</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#acd8afecbb15ee69487d5339371f64a76">llvm::ConstantRange::getNonEmpty</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a30bd18ac905eacf3601bc6a553a9ff49">llvm::ScalarEvolution::getSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a3498df9755182f44e759fd3eeb688e9f">llvm::ScalarEvolution::getSignedRange</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3a402430a1bbe70a9282dcb0e0b6a2cd">llvm::Value::hasOneUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea258973cbb0e48644fbb62d22ce6314bf">llvm::IFindLastIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a5a672708a81ae8da8fb56e32638ca9b3">llvm::ScalarEvolution::isKnownPositive</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a6d8769a72303e2b06ef63129cb231855">llvm::ScalarEvolution::isSCEVable</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a7d9ab823fe85606fa795c0c6fc75aca6">llvm::PatternMatch::m_Cmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#afc43bc5ec4b20c7c5d663bef90da6066">llvm::PatternMatch::m_CombineOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5be13f3abb6bddf7ad9747b077da5a0e">llvm::PatternMatch::m_OneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3ccd94f6a7507492b47c7351e3fb78c6">llvm::PatternMatch::m_Select</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae9dabebeb083ad5885642b5e6a84c9c0a7b71dfec5c8dd524069eed634dc0a3a5">llvm::Sentinel</a>.</p>


<p>Referenced by <a href="#aa35caaec45d90bbc9c564181b77c109e">isRecurrenceInstr</a>.</p>

</div>
</div>

### isFindLastIVRecurrenceKind() {#a7bc46d4489f4d6cb4a4e486ce5f6184b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RecurrenceDescriptor::isFindLastIVRecurrenceKind (<a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830e">RecurKind</a> Kind)</td>
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

<p>Returns true if the recurrence kind is of the form select(cmp(),x,y) where one of (x,y) is increasing loop induction.</p>

<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ead4c3e0abb938f94c273edbc5e291cbe2">llvm::FFindLastIV</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea258973cbb0e48644fbb62d22ce6314bf">llvm::IFindLastIV</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aa39d91b48bf7db69fa9ea091f4861a84">llvm::createFindLastIVReduction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a855f1a63640f9dfdabbe1df5fd39d31e">llvm::createReduction</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionphirecipe/#ad481483dac767c09d773266ba8b877e5">llvm::VPReductionPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a90ad8ccd396152c749068f986f2b751a">fixReductionScalarResumeWhenVectorizingEpilog</a>, <a href="#aed10715d943d3e1b4ca75b585ea96ab8">getSentinelValue</a>, <a href="#aa35caaec45d90bbc9c564181b77c109e">isRecurrenceInstr</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#aae23f7e6fc37b0f1bb756f938023512c">preparePlanForEpilogueVectorLoop</a>.</p>

</div>
</div>

### isFixedOrderRecurrence() {#a203487323e0aa341b6c24f9ef20b5909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RecurrenceDescriptor::isFixedOrderRecurrence (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * Phi, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * TheLoop, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT)</td>
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

<p>Returns true if Phi is a fixed-order recurrence.</p>


<p>A fixed-order recurrence is a non-reduction recurrence relation in which the value of the recurrence in the current loop iteration equals a value defined in a previous iteration (e.g. if the value is defined in the previous iteration, we refer to it as first-order recurrence, if it is defined in the iteration before the previous, we refer to it as second-order recurrence and so on). Note that this function optimistically assumes that uses of the recurrence can be re-ordered if necessary and users need to check and perform the re-ordering.</p>


<p>Declaration at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>, definition at line 1042 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a5c69311e8d44898dac36a155c3d8691d">llvm::DominatorTree::dominates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ac3280e7f76f955403fe17eacf126b90d">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopPreheader</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>

</div>
</div>

### isFloatingPointRecurrenceKind() {#ac70d0e0d91dcd02d08a23638be772bac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RecurrenceDescriptor::isFloatingPointRecurrenceKind (<a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830e">RecurKind</a> Kind)</td>
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

<p>Returns true if the recurrence kind is a floating point kind.</p>

<p>Declaration at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>, definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>


<p>References <a href="#aebf484d18c0adaa365f5307d2d8e00a7">isIntegerRecurrenceKind</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>


<p>Referenced by <a href="#ae3b1b80ef450d6706f42f3a929e51ce5">AddReductionVar</a>.</p>

</div>
</div>

### isFMulAddIntrinsic() {#a08416fb970e8c177c7d78452d927c606}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RecurrenceDescriptor::isFMulAddIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Returns true if the instruction is a call to the llvm.fmuladd intrinsic.</p>

<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#ae3b1b80ef450d6706f42f3a929e51ce5">AddReductionVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp/#a65aa908de5625be851aa7b97327d194b">checkOrderedReduction</a>, <a href="#a6415fb68bc55f3a316aa414a5c2c0ab2">getReductionOpChain</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ad1f0755693a05c2b008e9a576c3b162b">llvm::LoopVectorizationCostModel::getVectorCallCost</a>, <a href="#aa35caaec45d90bbc9c564181b77c109e">isRecurrenceInstr</a> and <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a8178cc5e49d5251d7ca3413b8a434f8f">llvm::LoopVectorizationCostModel::setVectorizedCallDecision</a>.</p>

</div>
</div>

### isFPMinMaxRecurrenceKind() {#a05ee667a3bd7353c72f9be938471af17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RecurrenceDescriptor::isFPMinMaxRecurrenceKind (<a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830e">RecurKind</a> Kind)</td>
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

<p>Returns true if the recurrence kind is a floating-point min/max kind.</p>

<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea8764eae15a1f2cf1c964d14dcf9283ee">llvm::FMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea8bdc72f64bbc121d5c6fa14cdef4c8bf">llvm::FMaximum</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ead76b595f89852f41ac50173abae6da05">llvm::FMin</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea4e137992425232e2d0b0142b7062378b">llvm::FMinimum</a>.</p>


<p>Referenced by <a href="#ae3b1b80ef450d6706f42f3a929e51ce5">AddReductionVar</a>, <a href="#af08d243545b64f4b77161992d0e2366e">isMinMaxRecurrenceKind</a> and <a href="#aa35caaec45d90bbc9c564181b77c109e">isRecurrenceInstr</a>.</p>

</div>
</div>

### isIntegerRecurrenceKind() {#aebf484d18c0adaa365f5307d2d8e00a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RecurrenceDescriptor::isIntegerRecurrenceKind (<a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830e">RecurKind</a> Kind)</td>
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

<p>Returns true if the recurrence kind is an integer kind.</p>

<p>Declaration at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>, definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eac33315685a0cba3ce53be378b3c7874b">llvm::And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3276c083ed6e470fc7ce908151c3ffec">llvm::FAnyOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ead4c3e0abb938f94c273edbc5e291cbe2">llvm::FFindLastIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaf574002db61510c589ee98a24ebca627">llvm::IAnyOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea258973cbb0e48644fbb62d22ce6314bf">llvm::IFindLastIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea62b6d55816cf737bfc6f42e60df1a3f2">llvm::Mul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">llvm::Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eabccd0de85dfbe7aef83629b318a4df6e">llvm::SMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ead6bb6a2eca7d60c75e349ea45e138d74">llvm::SMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eafaa1f94cd925672925f691e7f5727a6b">llvm::UMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea1c692ed4bf463fb08fca4d8cb8201ac0">llvm::UMin</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea76feb79109026728a20736a8c6504548">llvm::Xor</a>.</p>


<p>Referenced by <a href="#ae3b1b80ef450d6706f42f3a929e51ce5">AddReductionVar</a> and <a href="#ac70d0e0d91dcd02d08a23638be772bac">isFloatingPointRecurrenceKind</a>.</p>

</div>
</div>

### isIntMinMaxRecurrenceKind() {#aef4824e1c55ce3d04e8759c333dbc5c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RecurrenceDescriptor::isIntMinMaxRecurrenceKind (<a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830e">RecurKind</a> Kind)</td>
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

<p>Returns true if the recurrence kind is an integer min/max kind.</p>

<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eabccd0de85dfbe7aef83629b318a4df6e">llvm::SMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ead6bb6a2eca7d60c75e349ea45e138d74">llvm::SMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eafaa1f94cd925672925f691e7f5727a6b">llvm::UMax</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea1c692ed4bf463fb08fca4d8cb8201ac0">llvm::UMin</a>.</p>


<p>Referenced by <a href="#ae3b1b80ef450d6706f42f3a929e51ce5">AddReductionVar</a>, <a href="#af08d243545b64f4b77161992d0e2366e">isMinMaxRecurrenceKind</a> and <a href="#aa35caaec45d90bbc9c564181b77c109e">isRecurrenceInstr</a>.</p>

</div>
</div>

### isMinMaxPattern() {#ae318fdb278df4aaf9e229584fb769b41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecurrenceDescriptor::InstDesc RecurrenceDescriptor::isMinMaxPattern (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830e">RecurKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/instdesc">InstDesc</a> &amp; Prev)</td>
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

<p>Returns a struct describing if the instruction is a llvm.</p>


<p>(s/u)(min/max), <a href="/web-llvm/docs/api/namespaces/llvm/#aa656aa475d13ec6a900414eadabe86b0">llvm.minnum</a>/maxnum or a <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp/#a09bc27545df3b02401428427d0b5ce6f">Select(ICmp(X, Y), X, Y)</a> pair of instructions corresponding to a min(X, Y) or max(X, Y), matching the recurrence kind <span class="doxyComputerOutput">Kind</span>. <span class="doxyComputerOutput">Prev</span> specifies the description of an already processed select instruction, so its corresponding cmp can be matched to it.</p>


<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>, definition at line 753 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea8764eae15a1f2cf1c964d14dcf9283ee">llvm::FMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea8bdc72f64bbc121d5c6fa14cdef4c8bf">llvm::FMaximum</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ead76b595f89852f41ac50173abae6da05">llvm::FMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea4e137992425232e2d0b0142b7062378b">llvm::FMinimum</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/instdesc/#a27f1e170050db66311c01670d5347890">llvm::RecurrenceDescriptor::InstDesc::getRecKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#af08d243545b64f4b77161992d0e2366e">isMinMaxRecurrenceKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a7d9ab823fe85606fa795c0c6fc75aca6">llvm::PatternMatch::m_Cmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5be13f3abb6bddf7ad9747b077da5a0e">llvm::PatternMatch::m_OneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a9980e616ec74a8f0f04bfcaaaca16a24">llvm::PatternMatch::m_OrdOrUnordFMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a4281b0a9d1379f7c9135784c116f775e">llvm::PatternMatch::m_OrdOrUnordFMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3ccd94f6a7507492b47c7351e3fb78c6">llvm::PatternMatch::m_Select</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aac981768f6aa97f560e4cb0290f0aaa9">llvm::PatternMatch::m_SMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a4709b4ef085b4ded2f9c2c888b35ee25">llvm::PatternMatch::m_SMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a7c1d2015b4d26f5afe0baf87f9e75782">llvm::PatternMatch::m_UMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af627036178ac57e62dd894233ce10fcb">llvm::PatternMatch::m_UMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp/#a09bc27545df3b02401428427d0b5ce6f">Select</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eabccd0de85dfbe7aef83629b318a4df6e">llvm::SMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ead6bb6a2eca7d60c75e349ea45e138d74">llvm::SMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eafaa1f94cd925672925f691e7f5727a6b">llvm::UMax</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea1c692ed4bf463fb08fca4d8cb8201ac0">llvm::UMin</a>.</p>


<p>Referenced by <a href="#ae3b1b80ef450d6706f42f3a929e51ce5">AddReductionVar</a> and <a href="#aa35caaec45d90bbc9c564181b77c109e">isRecurrenceInstr</a>.</p>

</div>
</div>

### isMinMaxRecurrenceKind() {#af08d243545b64f4b77161992d0e2366e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RecurrenceDescriptor::isMinMaxRecurrenceKind (<a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830e">RecurKind</a> Kind)</td>
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

<p>Returns true if the recurrence kind is any min/max kind.</p>

<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>.</p>


<p>References <a href="#a05ee667a3bd7353c72f9be938471af17">isFPMinMaxRecurrenceKind</a> and <a href="#aef4824e1c55ce3d04e8759c333dbc5c5">isIntMinMaxRecurrenceKind</a>.</p>


<p>Referenced by <a href="#ae3b1b80ef450d6706f42f3a929e51ce5">AddReductionVar</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#a45ff90e525c3f3879a1a7f5297d8857d">llvm::VPReductionRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionevlrecipe/#a26b8ad3bd938e53e6e4cbc5f6d1b6318">llvm::VPReductionEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionphirecipe/#ad481483dac767c09d773266ba8b877e5">llvm::VPReductionPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#ac66885d3ce04a263a03746461eac12b1">llvm::VPReductionRecipe::execute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af5734ee7e33749096f394ea392b8524c">llvm::getOrderedReduction</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a4e307866e6d65e87d1e6884b0d13306c">llvm::LoopVectorizationCostModel::getReductionPatternCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84a0cf35704ac6286dc4f1395a6893e3">llvm::getShuffleReduction</a> and <a href="#ae318fdb278df4aaf9e229584fb769b41">isMinMaxPattern</a>.</p>

</div>
</div>

### isRecurrenceInstr() {#aa35caaec45d90bbc9c564181b77c109e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecurrenceDescriptor::InstDesc RecurrenceDescriptor::isRecurrenceInstr (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * Phi, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830e">RecurKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/instdesc">InstDesc</a> &amp; Prev, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FuncFMF, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE)</td>
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

<p>Returns a struct describing if the instruction 'I' can be a recurrence variable of type 'Kind' for a <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> <span class="doxyComputerOutput">L</span> and reduction PHI <span class="doxyComputerOutput">Phi</span>.</p>


<p>If the recurrence is a min/max pattern of select(icmp()) this function advances the instruction pointer 'I' from the compare instruction to the select instruction and stores this pointer in 'PatternLastInst' member of the returned struct.</p>


<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>, definition at line 850 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eac33315685a0cba3ce53be378b3c7874b">llvm::And</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaf552e181879ad14956985859308d77d9">llvm::FAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eab48b2a9934af7a531cfd7236ded9d50e">llvm::FMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaa7dad289ea38506fb1c9b5b148405d0c">llvm::FMulAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/instdesc/#a4e5fa9293b8cc92ad77f1f7c84f3902f">llvm::RecurrenceDescriptor::InstDesc::getExactFPMathInst</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/instdesc/#a27f1e170050db66311c01670d5347890">llvm::RecurrenceDescriptor::InstDesc::getRecKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a7af4f3d780a4c92809414d5e43d98337">isAnyOfPattern</a>, <a href="#a69df67c7d92481ae63a5d8017e96c716">isAnyOfRecurrenceKind</a>, <a href="#a89705a5029e6850fc3d6445ebc775c15">isConditionalRdxPattern</a>, <a href="#a797a268a4ac8802907a1b36ee57166e2">isFindLastIVPattern</a>, <a href="#a7bc46d4489f4d6cb4a4e486ce5f6184b">isFindLastIVRecurrenceKind</a>, <a href="#a08416fb970e8c177c7d78452d927c606">isFMulAddIntrinsic</a>, <a href="#a05ee667a3bd7353c72f9be938471af17">isFPMinMaxRecurrenceKind</a>, <a href="#aef4824e1c55ce3d04e8759c333dbc5c5">isIntMinMaxRecurrenceKind</a>, <a href="#ae318fdb278df4aaf9e229584fb769b41">isMinMaxPattern</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea62b6d55816cf737bfc6f42e60df1a3f2">llvm::Mul</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#ac1d140361490d7847edf0c7503e3188a">llvm::FastMathFlags::noNaNs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a278a2e29bf56f2e2109fd35ae454b050">llvm::FastMathFlags::noSignedZeros</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">llvm::Or</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea76feb79109026728a20736a8c6504548">llvm::Xor</a>.</p>


<p>Referenced by <a href="#ae3b1b80ef450d6706f42f3a929e51ce5">AddReductionVar</a>.</p>

</div>
</div>

### isReductionPHI() {#a484f974fc232e862a87a6380d3a7587d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RecurrenceDescriptor::isReductionPHI (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * Phi, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * TheLoop, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor">RecurrenceDescriptor</a> &amp; RedDes, <a href="/web-llvm/docs/api/classes/llvm/demandedbits">DemandedBits</a> * DB=nullptr, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC=nullptr, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT=nullptr, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE=nullptr)</td>
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

<p>Returns true if Phi is a reduction in TheLoop.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor">RecurrenceDescriptor</a> is returned in RedDes. If either <span class="doxyComputerOutput">DB</span> is non-null or <span class="doxyComputerOutput">AC</span> and <span class="doxyComputerOutput">DT</span> are non-null, the minimal bit width needed to compute the reduction will be computed. If <span class="doxyComputerOutput">SE</span> is non-null, store instructions to loop invariant addresses are processed.</p>


<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a>, definition at line 924 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="#ae3b1b80ef450d6706f42f3a929e51ce5">AddReductionVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eac33315685a0cba3ce53be378b3c7874b">llvm::And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaf552e181879ad14956985859308d77d9">llvm::FAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3276c083ed6e470fc7ce908151c3ffec">llvm::FAnyOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ead4c3e0abb938f94c273edbc5e291cbe2">llvm::FFindLastIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea8764eae15a1f2cf1c964d14dcf9283ee">llvm::FMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea8bdc72f64bbc121d5c6fa14cdef4c8bf">llvm::FMaximum</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ead76b595f89852f41ac50173abae6da05">llvm::FMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea4e137992425232e2d0b0142b7062378b">llvm::FMinimum</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eab48b2a9934af7a531cfd7236ded9d50e">llvm::FMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaa7dad289ea38506fb1c9b5b148405d0c">llvm::FMulAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="#a89e9d5a5838c63159df1aed56f600ef1">getRecurrenceKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaf574002db61510c589ee98a24ebca627">llvm::IAnyOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea258973cbb0e48644fbb62d22ce6314bf">llvm::IFindLastIV</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea62b6d55816cf737bfc6f42e60df1a3f2">llvm::Mul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">llvm::Or</a>, <a href="#a5e9a6d9348306b3d62804dac54e358a7">RecurrenceDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#abbceb1c6e5c4b49f53b381a8fad9e12a">llvm::FastMathFlags::setNoNaNs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eabccd0de85dfbe7aef83629b318a4df6e">llvm::SMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ead6bb6a2eca7d60c75e349ea45e138d74">llvm::SMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eafaa1f94cd925672925f691e7f5727a6b">llvm::UMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea1c692ed4bf463fb08fca4d8cb8201ac0">llvm::UMin</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea76feb79109026728a20736a8c6504548">llvm::Xor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a206a95af7fd1177ef8396cd69b888de2">findInnerReductionPhi</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivdescriptors-h">IVDescriptors.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp">IVDescriptors.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
