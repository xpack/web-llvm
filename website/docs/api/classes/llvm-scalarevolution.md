---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/scalarevolution
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ScalarEvolution` Class Reference

<p>The main scalar evolution driver. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ScalarEvolution { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">llvm/Analysis/ScalarEvolution.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf8958a77c3f05a0bafd88a8f6d8bbfb">HasRecMapType</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, bool &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type for HasRecMap. <a href="#acf8958a77c3f05a0bafd88a8f6d8bbfb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47ad5ea07479ddbb9621280324bf6a2b">ValueSetVector</a> = <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 4 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type for ExprValueMap. <a href="#a47ad5ea07479ddbb9621280324bf6a2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a3ae111376590494c1f5b88c0fb701f">ExprValueMapType</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">ValueSetVector</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a637425b471ded8ede1f8bdc66abffd7c">ValueExprMapType</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; SCEVCallbackVH, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type for ValueExprMap. <a href="#a637425b471ded8ede1f8bdc66abffd7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7aac8e2fa36a1c6f2a2690b8345b26af">ExitLimitCacheTy</a> = ExitLimitCache</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LoopDisposition { <a href="#a9f7c88892cfe1646082bf6174a4b912c">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An enum describing the relationship between a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> and a loop. <a href="#a9f7c88892cfe1646082bf6174a4b912c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">BlockDisposition { <a href="#aae7c3ec1a0344306acbdc2dcb113995e">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An enum describing the relationship between a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> and a basic block. <a href="#aae7c3ec1a0344306acbdc2dcb113995e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ExitCountKind { <a href="#ace535ba3b8cc110f49b5db48a945ecef">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The terms "backedge taken count" and "exit count" are used interchangeably to refer to the number of times the backedge of a loop has executed before the loop is exited. <a href="#ace535ba3b8cc110f49b5db48a945ecef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MonotonicPredicateType { <a href="#a899d8027fa6af3ca29aae6d88b6050ef">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A predicate is said to be monotonically increasing if may go from being false to being true as the loop iterates, but never the other way around. <a href="#a899d8027fa6af3ca29aae6d88b6050ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">RangeSignHint { <a href="#af73615d7c8ce4d840cf2daf94432d964">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to parameterize getRange. <a href="#af73615d7c8ce4d840cf2daf94432d964">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f71542fd299c1a7502dfcefb1e74df0">ScalarEvolutionsTest</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fefddc47a698935163a34218708a00b">SCEVCallbackVH</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37dafb4cec590807a6126c6d9af469cc">SCEVExpander</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a1917da5135c7cd0431c35b583db2aa">SCEVUnknown</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f0118e315585ef6debe98a13336ae75">ScalarEvolution</a> (Function &amp;F, TargetLibraryInfo &amp;TLI, AssumptionCache &amp;AC, DominatorTree &amp;DT, LoopInfo &amp;LI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22e289929f2f90455f02bb5778cee6ca">ScalarEvolution</a> (ScalarEvolution &amp;&amp;Arg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec226c51f8bffbf8fa3319bf11821cb9">~ScalarEvolution</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff9e533399d91febd63fa4bfe82a42a7">getContext</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d8769a72303e2b06ef63129cb231855">isSCEVable</a> (Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if values of the given type are analyzable within the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> framework. <a href="#a6d8769a72303e2b06ef63129cb231855">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a> (Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the size in bits of the specified type, for which isSCEVable must return true. <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dcfa69ce27cf214caaf50f21bfe1f2f">getEffectiveSCEVType</a> (Type *Ty) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a type with the same bitwidth as the given type and which represents how <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> will treat the given type, for which isSCEVable must return true. <a href="#a6dcfa69ce27cf214caaf50f21bfe1f2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10cde7087f90dc664b6799814aa28584">getWiderType</a> (Type *Ty1, Type *Ty2) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a744bc2c6ff2e83909955ef714890cb14">instructionCouldExistWithOperands</a> (const SCEV *A, const SCEV *B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if there exists a point in the program at which both A and B could be operands to the same instruction. <a href="#a744bc2c6ff2e83909955ef714890cb14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62b3c09f031f2478ebd6c92b8c80aa2f">containsAddRecurrence</a> (const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> is a scAddRecExpr or it contains scAddRecExpr. <a href="#a62b3c09f031f2478ebd6c92b8c80aa2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a267fd27cb9e177fa5f48cbb8828339a1">willNotOverflow</a> (Instruction::BinaryOps BinOp, bool Signed, const SCEV *LHS, const SCEV *RHS, const Instruction *CtxI=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is operation <span class="doxyComputerOutput">BinOp</span> between <span class="doxyComputerOutput">LHS</span> and <span class="doxyComputerOutput">RHS</span> provably does not have a signed/unsigned overflow (<span class="doxyComputerOutput">Signed</span>)? <a href="#a267fd27cb9e177fa5f48cbb8828339a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6a8e1063693697569fead19a720c43c">getStrengthenedNoWrapFlagsFromBinOp</a> (const OverflowingBinaryOperator *OBO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse NSW/NUW flags from add/sub/mul IR binary operation <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> into <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> no-wrap flags, and deduce flag[s] that aren't known yet. <a href="#aa6a8e1063693697569fead19a720c43c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeefacaa2eccab8db38ff9ccdad1e0b1d">registerUser</a> (const SCEV *User, ArrayRef&lt; const SCEV * &gt; Ops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Notify this <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> that <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/user">User</a></span> directly uses SCEVs in <span class="doxyComputerOutput">Ops</span>. <a href="#aeefacaa2eccab8db38ff9ccdad1e0b1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8d280cc2c5792b3144274e675e36385">containsUndefs</a> (const SCEV *S) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression contains an undef value. <a href="#aa8d280cc2c5792b3144274e675e36385">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af327db7ab1b1996680bd467f6ce109bc">containsErasedValue</a> (const SCEV *S) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression contains a <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> that has been optimised out and is now a nullptr. <a href="#af327db7ab1b1996680bd467f6ce109bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30bd18ac905eacf3601bc6a553a9ff49">getSCEV</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression for the full generality of the specified expression. <a href="#a30bd18ac905eacf3601bc6a553a9ff49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d68d0e13d6aafb4a3ab1cdb5e83ff29">getExistingSCEV</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an existing <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> for V if there is one, otherwise return nullptr. <a href="#a9d68d0e13d6aafb4a3ab1cdb5e83ff29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2eb94d079d8416118f4aaed865ab05d7">getConstant</a> (ConstantInt *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5096723795092a9d871e520e78998c0">getConstant</a> (const APInt &amp;Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4171c1656e5184034c3b4a5a85e2c4f7">getConstant</a> (Type *Ty, uint64_t V, bool isSigned=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bab447a6422427e5fc92bbbc0c12fba">getLosslessPtrToIntExpr</a> (const SCEV *Op, unsigned Depth=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f28ee6ec3dad0938d2660c56168d91d">getPtrToIntExpr</a> (const SCEV *Op, Type *Ty)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83c084b0947edf4ae748f9a73babf7b8">getTruncateExpr</a> (const SCEV *Op, Type *Ty, unsigned Depth=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc6d543083aac1a4e161c0ed02b9b30a">getVScale</a> (Type *Ty)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfad3d829fd98014f225d55b4a924819">getElementCount</a> (Type *Ty, ElementCount EC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d745b25efdc69435508f1e936919f8b">getZeroExtendExpr</a> (const SCEV *Op, Type *Ty, unsigned Depth=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a> (const SCEV *Op, Type *Ty, unsigned Depth=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab26bea71791cf347c631d2072e41cfb5">getSignExtendExpr</a> (const SCEV *Op, Type *Ty, unsigned Depth=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a643b61ddaf17331f3ff1d4f85c7c9a23">getSignExtendExprImpl</a> (const SCEV *Op, Type *Ty, unsigned Depth=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48216fb35fa09727a5717cd28faca9bf">getCastExpr</a> (SCEVTypes Kind, const SCEV *Op, Type *Ty)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa35959e3f6bea8e35cffcfd8659e3156">getAnyExtendExpr</a> (const SCEV *Op, Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnyExtendExpr - Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> for the given operand extended with unspecified bits out to the given type. <a href="#aa35959e3f6bea8e35cffcfd8659e3156">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a> (SmallVectorImpl&lt; const SCEV * &gt; &amp;Ops, SCEV::NoWrapFlags Flags=SCEV::FlagAnyWrap, unsigned Depth=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a canonical add expression, or something simpler if possible. <a href="#aef6d2bea715d1793e956f41ddeea2320">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24a2018b8b1e93d86324f76ce216140d">getAddExpr</a> (const SCEV *LHS, const SCEV *RHS, SCEV::NoWrapFlags Flags=SCEV::FlagAnyWrap, unsigned Depth=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2fb91dc219f17dfe831eef7e2b90840">getAddExpr</a> (const SCEV *Op0, const SCEV *Op1, const SCEV *Op2, SCEV::NoWrapFlags Flags=SCEV::FlagAnyWrap, unsigned Depth=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a> (SmallVectorImpl&lt; const SCEV * &gt; &amp;Ops, SCEV::NoWrapFlags Flags=SCEV::FlagAnyWrap, unsigned Depth=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a canonical multiply expression, or something simpler if possible. <a href="#ad299b0f4378f644f67168c72c763716f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f8f80d383339b3d40cbeffce08cb4fb">getMulExpr</a> (const SCEV *LHS, const SCEV *RHS, SCEV::NoWrapFlags Flags=SCEV::FlagAnyWrap, unsigned Depth=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8160926d5f5c8da520ff3e01bf7cab2f">getMulExpr</a> (const SCEV *Op0, const SCEV *Op1, const SCEV *Op2, SCEV::NoWrapFlags Flags=SCEV::FlagAnyWrap, unsigned Depth=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c03d18ed744dc3b34829ec5485a68b0">getUDivExpr</a> (const SCEV *LHS, const SCEV *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a canonical unsigned division expression, or something simpler if possible. <a href="#a6c03d18ed744dc3b34829ec5485a68b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeca82ae7bafbb557b7026f7d035643b8">getUDivExactExpr</a> (const SCEV *LHS, const SCEV *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a canonical unsigned division expression, or something simpler if possible. <a href="#aeca82ae7bafbb557b7026f7d035643b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13b9eb961d35ad9ecb3b633f5703253a">getURemExpr</a> (const SCEV *LHS, const SCEV *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents an unsigned remainder expression based on unsigned division. <a href="#a13b9eb961d35ad9ecb3b633f5703253a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a659b27f6737fcb7eaf333b0279da1154">getAddRecExpr</a> (const SCEV *Start, const SCEV *Step, const Loop *L, SCEV::NoWrapFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an add recurrence expression for the specified loop. <a href="#a659b27f6737fcb7eaf333b0279da1154">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69f32678ea46cdda0318c0be9bdb1c7e">getAddRecExpr</a> (SmallVectorImpl&lt; const SCEV * &gt; &amp;Operands, const Loop *L, SCEV::NoWrapFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an add recurrence expression for the specified loop. <a href="#a69f32678ea46cdda0318c0be9bdb1c7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6df0ad4a470aaae9009ab0dc0e7b2149">getAddRecExpr</a> (const SmallVectorImpl&lt; const SCEV * &gt; &amp;Operands, const Loop *L, SCEV::NoWrapFlags Flags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> *, 3 &gt; &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada4b4e4637302939402932b866e82cf3">createAddRecFromPHIWithCasts</a> (const SCEVUnknown *SymbolicPHI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if <span class="doxyComputerOutput">SymbolicPHI</span> can be rewritten as an AddRecExpr under some Predicates. <a href="#ada4b4e4637302939402932b866e82cf3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f3039f831c483956c153ed9dee23dba">getGEPExpr</a> (GEPOperator *GEP, const SmallVectorImpl&lt; const SCEV * &gt; &amp;IndexExprs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an expression for a GEP. <a href="#a0f3039f831c483956c153ed9dee23dba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10f946da317366de10f25a7b59db8e72">getAbsExpr</a> (const SCEV *Op, bool IsNSW)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3221ac3fcd879a1c716aa954837df79">getMinMaxExpr</a> (SCEVTypes Kind, SmallVectorImpl&lt; const SCEV * &gt; &amp;Operands)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4976a99a4f39b4daee84f4f60319df03">getSequentialMinMaxExpr</a> (SCEVTypes Kind, SmallVectorImpl&lt; const SCEV * &gt; &amp;Operands)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d1d4b1c8787f465ce2c144757731f12">getSMaxExpr</a> (const SCEV *LHS, const SCEV *RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4ee621c2217d36c9e9f0bd823fb3e57">getSMaxExpr</a> (SmallVectorImpl&lt; const SCEV * &gt; &amp;Operands)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a238566881f41b81cd8ff51eb1b3f4a8b">getUMaxExpr</a> (const SCEV *LHS, const SCEV *RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a213bb9cc661533b20602b1e035d63791">getUMaxExpr</a> (SmallVectorImpl&lt; const SCEV * &gt; &amp;Operands)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a223d678f85ac9b7f03157edb6111e42e">getSMinExpr</a> (const SCEV *LHS, const SCEV *RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c1b89d3d26909f63f0243f35e3538ee">getSMinExpr</a> (SmallVectorImpl&lt; const SCEV * &gt; &amp;Operands)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a796339fe5ef91db7de6137a41e23083b">getUMinExpr</a> (const SCEV *LHS, const SCEV *RHS, bool Sequential=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a997ab75fad6de5dda923e63c28553834">getUMinExpr</a> (SmallVectorImpl&lt; const SCEV * &gt; &amp;Operands, bool Sequential=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8e4f5b2ced08ad7d138b598aefdd338">getUnknown</a> (Value *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa9b9055fd9c69fe14eb20f0d18d53d5">getCouldNotCompute</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2579491850c605c8b7cf3439a907fbed">getZero</a> (Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> for the constant 0 of a specific type. <a href="#a2579491850c605c8b7cf3439a907fbed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fbe8f529d36d76730550905d730a2a7">getOne</a> (Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> for the constant 1 of a specific type. <a href="#a3fbe8f529d36d76730550905d730a2a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2cf93c95893f413324a4645fc39bb1a">getPowerOfTwo</a> (Type *Ty, unsigned Power)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> for the constant <span class="doxyComputerOutput">Power</span> of two. <a href="#ac2cf93c95893f413324a4645fc39bb1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d5202095ab1b8b726dd1e9db728b997">getMinusOne</a> (Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> for the constant -1 of a specific type. <a href="#a8d5202095ab1b8b726dd1e9db728b997">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7409ed2347009a5163f410e69a94243">getSizeOfExpr</a> (Type *IntTy, TypeSize Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an expression for a <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a>. <a href="#ad7409ed2347009a5163f410e69a94243">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b01f1061607731f6d2953b935649570">getSizeOfExpr</a> (Type *IntTy, Type *AllocTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an expression for the alloc size of AllocTy that is type IntTy. <a href="#a5b01f1061607731f6d2953b935649570">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a954b66f08640930cebdd008bc65d4d">getStoreSizeOfExpr</a> (Type *IntTy, Type *StoreTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an expression for the store size of StoreTy that is type IntTy. <a href="#a8a954b66f08640930cebdd008bc65d4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60be12dda0289837dae43964608cf568">getOffsetOfExpr</a> (Type *IntTy, StructType *STy, unsigned FieldNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an expression for offsetof on the given field with type IntTy. <a href="#a60be12dda0289837dae43964608cf568">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a083bb1deb1d2ba244a99ceae9e734bc1">getNegativeSCEV</a> (const SCEV *V, SCEV::NoWrapFlags Flags=SCEV::FlagAnyWrap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> object corresponding to -V. <a href="#a083bb1deb1d2ba244a99ceae9e734bc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7391ca35e3a370a408a9b1967b6a9832">getNotSCEV</a> (const SCEV *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> object corresponding to ~V. <a href="#a7391ca35e3a370a408a9b1967b6a9832">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bcb86d8d126d95b0dc05f09e8f3df96">getMinusSCEV</a> (const SCEV *LHS, const SCEV *RHS, SCEV::NoWrapFlags Flags=SCEV::FlagAnyWrap, unsigned Depth=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return LHS-RHS. <a href="#a8bcb86d8d126d95b0dc05f09e8f3df96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0daed958320635f1a9d440819f5bd487">getUDivCeilSCEV</a> (const SCEV *N, const SCEV *D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute ceil(N / D). <a href="#a0daed958320635f1a9d440819f5bd487">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc040502444e4504cdbc04c87e4e3055">getTruncateOrZeroExtend</a> (const SCEV *V, Type *Ty, unsigned Depth=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> corresponding to a conversion of the input value to the specified type. <a href="#adc040502444e4504cdbc04c87e4e3055">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af156ea88617d19e05470b8af2bb62dd9">getTruncateOrSignExtend</a> (const SCEV *V, Type *Ty, unsigned Depth=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> corresponding to a conversion of the input value to the specified type. <a href="#af156ea88617d19e05470b8af2bb62dd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a933eb87303a6ce51c8894e431fbc389b">getNoopOrZeroExtend</a> (const SCEV *V, Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> corresponding to a conversion of the input value to the specified type. <a href="#a933eb87303a6ce51c8894e431fbc389b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38c440751f1bf5f19bc12b95f8f0f2a6">getNoopOrSignExtend</a> (const SCEV *V, Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> corresponding to a conversion of the input value to the specified type. <a href="#a38c440751f1bf5f19bc12b95f8f0f2a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a829bd04a95f833114e36a195c7e67f0a">getNoopOrAnyExtend</a> (const SCEV *V, Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> corresponding to a conversion of the input value to the specified type. <a href="#a829bd04a95f833114e36a195c7e67f0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a426976cfd81411f49f7e5fe77ee4e3a4">getTruncateOrNoop</a> (const SCEV *V, Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> corresponding to a conversion of the input value to the specified type. <a href="#a426976cfd81411f49f7e5fe77ee4e3a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a254484ad2e230cf0db1f2c779abfe39c">getUMaxFromMismatchedTypes</a> (const SCEV *LHS, const SCEV *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Promote the operands to the wider of the types using zero-extension, and then perform a umax operation with them. <a href="#a254484ad2e230cf0db1f2c779abfe39c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aba96071c763c3233ab9f7cea03f395">getUMinFromMismatchedTypes</a> (const SCEV *LHS, const SCEV *RHS, bool Sequential=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Promote the operands to the wider of the types using zero-extension, and then perform a umin operation with them. <a href="#a9aba96071c763c3233ab9f7cea03f395">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef86e2e34d31e4595f5a442fe55ecbe9">getUMinFromMismatchedTypes</a> (SmallVectorImpl&lt; const SCEV * &gt; &amp;Ops, bool Sequential=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Promote the operands to the wider of the types using zero-extension, and then perform a umin operation with them. <a href="#aef86e2e34d31e4595f5a442fe55ecbe9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac276ea1907c780c43d3637ae9bd1989e">getPointerBase</a> (const SCEV *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transitively follow the chain of pointer-type operands until reaching a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> that does not have a single pointer operand. <a href="#ac276ea1907c780c43d3637ae9bd1989e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e4038e28db703c29e5e3de1549806ca">removePointerBase</a> (const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute an expression equivalent to S - getPointerBase(S). <a href="#a1e4038e28db703c29e5e3de1549806ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21d6ee82eed29080d911dbb548a8bb68">getSCEVAtScope</a> (const SCEV *S, const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression for the specified value at the specified scope in the program. <a href="#a21d6ee82eed29080d911dbb548a8bb68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae219c962e224c9424b2ec40847496ff0">getSCEVAtScope</a> (Value *V, const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a convenience function which does getSCEVAtScope(getSCEV(V), L). <a href="#ae219c962e224c9424b2ec40847496ff0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e9fadcd7d58712f2a36fb635e35d2f5">isLoopEntryGuardedByCond</a> (const Loop *L, CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether entry to the loop is protected by a conditional between LHS and RHS. <a href="#a1e9fadcd7d58712f2a36fb635e35d2f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefc772d1808d513abc142b59844cfe45">isBasicBlockEntryGuardedByCond</a> (const BasicBlock *BB, CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether entry to the basic block is protected by a conditional between LHS and RHS. <a href="#aefc772d1808d513abc142b59844cfe45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b617baf7fc5914d8a245e702ea65a7d">isLoopBackedgeGuardedByCond</a> (const Loop *L, CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the backedge of the loop is protected by a conditional between LHS and RHS. <a href="#a8b617baf7fc5914d8a245e702ea65a7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e3935d45c4b79b85a117b47cc1d2e61">getTripCountFromExitCount</a> (const SCEV *ExitCount)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A version of getTripCountFromExitCount below which always picks an evaluation type which can not result in overflow. <a href="#a3e3935d45c4b79b85a117b47cc1d2e61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17e35fd9a6e590c201fd05105589ce47">getTripCountFromExitCount</a> (const SCEV *ExitCount, Type *EvalTy, const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert from an "exit count" (i.e. <a href="#a17e35fd9a6e590c201fd05105589ce47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abec0c616087c002528fcf80c6583eadd">getSmallConstantTripCount</a> (const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the exact trip count of the loop if we can compute it, and the result is a small constant. <a href="#abec0c616087c002528fcf80c6583eadd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bf0e851d8784ff477a3bc34ae007ced">getSmallConstantTripCount</a> (const Loop *L, const BasicBlock *ExitingBlock)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the exact trip count for this loop if we exit through ExitingBlock. <a href="#a2bf0e851d8784ff477a3bc34ae007ced">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c58444d7945f3d5eda96b9b4fb095b6">getSmallConstantMaxTripCount</a> (const Loop *L, SmallVectorImpl&lt; const SCEVPredicate * &gt; *Predicates=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the upper bound of the loop trip count as a normal unsigned value. <a href="#a4c58444d7945f3d5eda96b9b4fb095b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29ee697fe94374eae9689321e811f5e9">getSmallConstantTripMultiple</a> (const Loop *L, const SCEV *ExitCount)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the largest constant divisor of the trip count as a normal unsigned value, if possible. <a href="#a29ee697fe94374eae9689321e811f5e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a679b9639c06fbd0a28b01cdea9b5d639">getSmallConstantTripMultiple</a> (const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the largest constant divisor of the trip count of the loop. <a href="#a679b9639c06fbd0a28b01cdea9b5d639">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a187e4afb699cf8f508b886d219589c67">getSmallConstantTripMultiple</a> (const Loop *L, const BasicBlock *ExitingBlock)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the largest constant divisor of the trip count of this loop as a normal unsigned value, if possible. <a href="#a187e4afb699cf8f508b886d219589c67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab24add5df0874cdfa47b47b1d9926e9e">getExitCount</a> (const Loop *L, const BasicBlock *ExitingBlock, ExitCountKind Kind=Exact)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of times the backedge executes before the given exit would be taken; if not exactly computable, return <a href="/web-llvm/docs/api/structs/llvm/scevcouldnotcompute">SCEVCouldNotCompute</a>. <a href="#ab24add5df0874cdfa47b47b1d9926e9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a797d4a680e166f8cbd6b243e78514296">getPredicatedExitCount</a> (const Loop *L, const BasicBlock *ExitingBlock, SmallVectorImpl&lt; const SCEVPredicate * &gt; *Predicates, ExitCountKind Kind=Exact)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Same as above except this uses the predicated backedge taken info and may require predicates. <a href="#a797d4a680e166f8cbd6b243e78514296">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22d9bcbd44563106d7217f3bd9a4039e">getBackedgeTakenCount</a> (const Loop *L, ExitCountKind Kind=Exact)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the specified loop has a predictable backedge-taken count, return it, otherwise return a <a href="/web-llvm/docs/api/structs/llvm/scevcouldnotcompute">SCEVCouldNotCompute</a> object. <a href="#a22d9bcbd44563106d7217f3bd9a4039e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a308d1a1f7212f4e433b1cd404bb92ab0">getPredicatedBackedgeTakenCount</a> (const Loop *L, SmallVectorImpl&lt; const SCEVPredicate * &gt; &amp;Predicates)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to getBackedgeTakenCount, except it will add a set of <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicates to Predicates that are required to be true in order for the answer to be correct. <a href="#a308d1a1f7212f4e433b1cd404bb92ab0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0182f006bb2ae6411c2111427d58f242">getConstantMaxBackedgeTakenCount</a> (const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When successful, this returns a <a href="/web-llvm/docs/api/classes/llvm/scevconstant">SCEVConstant</a> that is greater than or equal to (i.e. <a href="#a0182f006bb2ae6411c2111427d58f242">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d2bc453a77ebf70015aae6e3c2a56be">getPredicatedConstantMaxBackedgeTakenCount</a> (const Loop *L, SmallVectorImpl&lt; const SCEVPredicate * &gt; &amp;Predicates)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to getConstantMaxBackedgeTakenCount, except it will add a set of <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicates to Predicates that are required to be true in order for the answer to be correct. <a href="#a1d2bc453a77ebf70015aae6e3c2a56be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd6dc21300db42769872f3be33ed5f2b">getSymbolicMaxBackedgeTakenCount</a> (const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When successful, this returns a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> that is greater than or equal to (i.e. <a href="#afd6dc21300db42769872f3be33ed5f2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aead0dd455170da0b701e1e02822d3e6f">getPredicatedSymbolicMaxBackedgeTakenCount</a> (const Loop *L, SmallVectorImpl&lt; const SCEVPredicate * &gt; &amp;Predicates)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to getSymbolicMaxBackedgeTakenCount, except it will add a set of <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicates to Predicates that are required to be true in order for the answer to be correct. <a href="#aead0dd455170da0b701e1e02822d3e6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57a6829dad387e7075a6325e3ec6ace5">isBackedgeTakenCountMaxOrZero</a> (const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the backedge taken count is either the value returned by getConstantMaxBackedgeTakenCount or zero. <a href="#a57a6829dad387e7075a6325e3ec6ace5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91ac801aa45c78e0d0edbc36115ef054">hasLoopInvariantBackedgeTakenCount</a> (const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified loop has an analyzable loop-invariant backedge-taken count. <a href="#a91ac801aa45c78e0d0edbc36115ef054">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5f5c8803494a746eb35e42f67abd0ec">forgetAllLoops</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a592bdd7731b14ff4ff5d646f6f399900">forgetLoop</a> (const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should be called by the client when it has changed a loop in a way that may effect <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a>'s ability to compute a trip count, or if the loop is deleted. <a href="#a592bdd7731b14ff4ff5d646f6f399900">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d5bfa1ac3c7c096af6b26fb95cd699d">forgetTopmostLoop</a> (const Loop *L)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a804545e5b568edec8b970da32cd37359">forgetValue</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should be called by the client when it has changed a value in a way that may effect its value, or which may disconnect it from a def-use chain linking it to a loop. <a href="#a804545e5b568edec8b970da32cd37359">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6dc58a1259941c7a17142e6103d059e">forgetLcssaPhiWithNewPredecessor</a> (Loop *L, PHINode *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Forget LCSSA phi node V of loop L to which a new predecessor was added, such that it may no longer be trivial. <a href="#aa6dc58a1259941c7a17142e6103d059e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb9c0178bec51fd25f95b4399faa569c">forgetLoopDispositions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called when the client has changed the disposition of values in this loop. <a href="#abb9c0178bec51fd25f95b4399faa569c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a830ba09d5969cd66878b05c17fdf66b6">forgetBlockAndLoopDispositions</a> (Value *V=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Called when the client has changed the disposition of values in a loop or block. <a href="#a830ba09d5969cd66878b05c17fdf66b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a765b135bf0191fca6004b4167bcfb493">getMinTrailingZeros</a> (const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the minimum number of zero bits that S is guaranteed to end in (at every loop iteration). <a href="#a765b135bf0191fca6004b4167bcfb493">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18000513ba14bd153f16edd92c4505b2">getConstantMultiple</a> (const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the max constant multiple of S. <a href="#a18000513ba14bd153f16edd92c4505b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cd15ddae8837842830d97285936440a">getNonZeroConstantMultiple</a> (const SCEV *S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7593d52f91ebe342de9fa72846ebe755">getUnsignedRange</a> (const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the unsigned range for a particular <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>. <a href="#a7593d52f91ebe342de9fa72846ebe755">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d61e3035097c0e57849c6d3f195597d">getUnsignedRangeMin</a> (const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the min of the unsigned range for a particular <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>. <a href="#a5d61e3035097c0e57849c6d3f195597d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8de32f4d40eae96f0e26f0728682c2e">getUnsignedRangeMax</a> (const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the max of the unsigned range for a particular <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>. <a href="#ac8de32f4d40eae96f0e26f0728682c2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3498df9755182f44e759fd3eeb688e9f">getSignedRange</a> (const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the signed range for a particular <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>. <a href="#a3498df9755182f44e759fd3eeb688e9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a809289b45cd6625629f5356f70dac72d">getSignedRangeMin</a> (const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the min of the signed range for a particular <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>. <a href="#a809289b45cd6625629f5356f70dac72d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afee50be11e579d3c510e73df2a21cb88">getSignedRangeMax</a> (const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the max of the signed range for a particular <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>. <a href="#afee50be11e579d3c510e73df2a21cb88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b9806d21518ef7fb4d5c4299e21411f">isKnownNegative</a> (const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if the given expression is known to be negative. <a href="#a1b9806d21518ef7fb4d5c4299e21411f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a672708a81ae8da8fb56e32638ca9b3">isKnownPositive</a> (const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if the given expression is known to be positive. <a href="#a5a672708a81ae8da8fb56e32638ca9b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06719fdab228f099aeac0c8ee40a7e34">isKnownNonNegative</a> (const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if the given expression is known to be non-negative. <a href="#a06719fdab228f099aeac0c8ee40a7e34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a121ee24f11c464f3b3197cac87b0980e">isKnownNonPositive</a> (const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if the given expression is known to be non-positive. <a href="#a121ee24f11c464f3b3197cac87b0980e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20c66c97bae0b3e6725d03cfa61c488b">isKnownNonZero</a> (const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if the given expression is known to be non-zero. <a href="#a20c66c97bae0b3e6725d03cfa61c488b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5e7bb544eab3ac6fa1f810ee068ab6b">isKnownToBeAPowerOfTwo</a> (const SCEV *S, bool OrZero=false, bool OrNegative=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if the given expression is known to be a power of 2. <a href="#aa5e7bb544eab3ac6fa1f810ee068ab6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7a40d693574be8048944e80774e6c1d">SplitIntoInitAndPostInc</a> (const Loop *L, const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Splits <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression <span class="doxyComputerOutput">S</span> into two SCEVs. <a href="#ae7a40d693574be8048944e80774e6c1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd0a71dc4e0ed5b83c50e875e6726661">isKnownViaInduction</a> (CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We'd like to check the predicate on every iteration of the most dominated loop between loops used in LHS and RHS. <a href="#afd0a71dc4e0ed5b83c50e875e6726661">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af74112dae88db73eb5484821b6f0fccd">isKnownPredicate</a> (CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if the given expression is known to satisfy the condition described by Pred, LHS, and RHS. <a href="#af74112dae88db73eb5484821b6f0fccd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad80020012061cb562a6f9c9f715c2cf0">evaluatePredicate</a> (CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the condition described by Pred, LHS, and RHS is true or false. <a href="#ad80020012061cb562a6f9c9f715c2cf0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaae2161ba70381e225ac6800af5d961">isKnownPredicateAt</a> (CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS, const Instruction *CtxI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if the given expression is known to satisfy the condition described by Pred, LHS, and RHS in the given Context. <a href="#aeaae2161ba70381e225ac6800af5d961">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bfb461a6adf8414747571a5f94a77fc">evaluatePredicateAt</a> (CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS, const Instruction *CtxI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the condition described by Pred, LHS, and RHS is true or false in the given <span class="doxyComputerOutput">Context</span>. <a href="#a4bfb461a6adf8414747571a5f94a77fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06b567827f9349ea154df08c2450b776">isKnownOnEveryIteration</a> (CmpPredicate Pred, const SCEVAddRecExpr *LHS, const SCEV *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if the condition described by Pred, LHS, RHS is known to be true on every iteration of the loop of the recurrency LHS. <a href="#a06b567827f9349ea154df08c2450b776">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/scalarevolution/exitlimit">ExitLimit</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26b05f5967d446ef422d44a79334542c">computeExitLimitFromCond</a> (const Loop *L, Value *ExitCond, bool ExitIfTrue, bool ControlsOnlyExit, bool AllowPredicates=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the number of times the backedge of the specified loop will execute if its exit condition were a conditional branch of ExitCond. <a href="#a26b05f5967d446ef422d44a79334542c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="#a899d8027fa6af3ca29aae6d88b6050ef">MonotonicPredicateType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa92b3e6375805368f9a24cf69ce73797">getMonotonicPredicateType</a> (const SCEVAddRecExpr *LHS, ICmpInst::Predicate Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If, for all loop invariant X, the predicate "LHS `Pred` X" is monotonically increasing or decreasing, returns Some(MonotonicallyIncreasing) and Some(MonotonicallyDecreasing) respectively. <a href="#aa92b3e6375805368f9a24cf69ce73797">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/scalarevolution/loopinvariantpredicate">LoopInvariantPredicate</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a741e5065c867d7dfd716eb8e16fccf12">getLoopInvariantPredicate</a> (ICmpInst::Predicate Pred, const SCEV *LHS, const SCEV *RHS, const Loop *L, const Instruction *CtxI=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the result of the predicate LHS <span class="doxyComputerOutput">Pred</span> RHS is loop invariant with respect to L, return a <a href="/web-llvm/docs/api/structs/llvm/scalarevolution/loopinvariantpredicate">LoopInvariantPredicate</a> with LHS and RHS being invariants, available at L's entry. <a href="#a741e5065c867d7dfd716eb8e16fccf12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/scalarevolution/loopinvariantpredicate">LoopInvariantPredicate</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1039aac093f6da8816c9dd415a711a20">getLoopInvariantExitCondDuringFirstIterations</a> (CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS, const Loop *L, const Instruction *CtxI, const SCEV *MaxIter)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the result of the predicate LHS <span class="doxyComputerOutput">Pred</span> RHS is loop invariant with respect to L at given Context during at least first MaxIter iterations, return a <a href="/web-llvm/docs/api/structs/llvm/scalarevolution/loopinvariantpredicate">LoopInvariantPredicate</a> with LHS and RHS being invariants, available at L's entry. <a href="#a1039aac093f6da8816c9dd415a711a20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/scalarevolution/loopinvariantpredicate">LoopInvariantPredicate</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a094d95c92490272d4b7a6bf4ab90009d">getLoopInvariantExitCondDuringFirstIterationsImpl</a> (CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS, const Loop *L, const Instruction *CtxI, const SCEV *MaxIter)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e9fc2b9bb75a684c20ca3fa6e14b63e">SimplifyICmpOperands</a> (CmpPredicate &amp;Pred, const SCEV *&amp;LHS, const SCEV *&amp;RHS, unsigned Depth=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simplify LHS and RHS in a comparison with predicate Pred. <a href="#a5e9fc2b9bb75a684c20ca3fa6e14b63e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9f7c88892cfe1646082bf6174a4b912c">LoopDisposition</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61f5098e98f972466ae233e6d01f9f9c">getLoopDisposition</a> (const SCEV *S, const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the "disposition" of the given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> with respect to the given loop. <a href="#a61f5098e98f972466ae233e6d01f9f9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a19768af81df7e5fe571bc08dcd48b3">isLoopInvariant</a> (const SCEV *S, const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the value of the given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> is unchanging in the specified loop. <a href="#a5a19768af81df7e5fe571bc08dcd48b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadf992d0faba329a1b5315dcde978e85">isAvailableAtLoopEntry</a> (const SCEV *S, const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> can be evaluated at loop's entry. <a href="#aadf992d0faba329a1b5315dcde978e85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac258f0361a1c35f5814a2b529139d15c">hasComputableLoopEvolution</a> (const SCEV *S, const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> changes value in a known way in the specified loop. <a href="#ac258f0361a1c35f5814a2b529139d15c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aae7c3ec1a0344306acbdc2dcb113995e">BlockDisposition</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92fb0984f10499fff4a7c9b32de2a0a6">getBlockDisposition</a> (const SCEV *S, const BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the "disposition" of the given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> with respect to the given block. <a href="#a92fb0984f10499fff4a7c9b32de2a0a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7ccf429f5c75676bdacadf3c9d1c7fa">dominates</a> (const SCEV *S, const BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if elements that makes up the given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> dominate the specified basic block. <a href="#ac7ccf429f5c75676bdacadf3c9d1c7fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0d036af111b8aafe90db0771b8e9ce3">properlyDominates</a> (const SCEV *S, const BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if elements that makes up the given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> properly dominate the specified basic block. <a href="#ae0d036af111b8aafe90db0771b8e9ce3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a694848007e26a83150b8dbd67e58fbdd">hasOperand</a> (const SCEV *S, const SCEV *Op) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> has <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> as a direct or indirect operand. <a href="#a694848007e26a83150b8dbd67e58fbdd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad61acd1c9fda9921a30f3ff510509873">getElementSize</a> (Instruction *Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the size of an element read or written by Inst. <a href="#ad61acd1c9fda9921a30f3ff510509873">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77b275a78beac200ef1f703d2a5fbb7d">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff82c03c1ce8b945170bcb1f0f624c17">verify</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93a455a6a60ac3b40d15464bc3b86e90">invalidate</a> (Function &amp;F, const PreservedAnalyses &amp;PA, FunctionAnalysisManager::Invalidator &amp;Inv)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a057ff1d04d6303e3402647132a66ab18">getDataLayout</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> associated with the module this <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> instance is operating on. <a href="#a057ff1d04d6303e3402647132a66ab18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29cffc9779968caccc3dd405819e55f5">getEqualPredicate</a> (const SCEV *LHS, const SCEV *RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fc5091677914fa41c25148564683090">getComparePredicate</a> (ICmpInst::Predicate Pred, const SCEV *LHS, const SCEV *RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b4da0fed92ca11bf8cb2fd763168d3c">getWrapPredicate</a> (const SCEVAddRecExpr *AR, SCEVWrapPredicate::IncrementWrapFlags AddedFlags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae78e890f2ef71a10fca3f21f0833b535">rewriteUsingPredicate</a> (const SCEV *S, const Loop *L, const SCEVPredicate &amp;A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Re-writes the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> according to the Predicates in <span class="doxyComputerOutput">A</span>. <a href="#ae78e890f2ef71a10fca3f21f0833b535">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad365e0d64063a233710fdba41a0da57e">convertSCEVToAddRecWithPredicates</a> (const SCEV *S, const Loop *L, SmallVectorImpl&lt; const SCEVPredicate * &gt; &amp;Preds)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tries to convert the <span class="doxyComputerOutput">S</span> expression to an AddRec expression, adding additional predicates to <span class="doxyComputerOutput">Preds</span> as required. <a href="#ad365e0d64063a233710fdba41a0da57e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0ca564918ec63a9b4d2229374fec747">computeConstantDifference</a> (const SCEV *LHS, const SCEV *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute <span class="doxyComputerOutput">LHS</span> - <span class="doxyComputerOutput">RHS</span> and returns the result as an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> if it is a constant, and std::nullopt if it isn't. <a href="#ae0ca564918ec63a9b4d2229374fec747">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a248dea99ef1d5a864269ac3a98014b37">setNoWrapFlags</a> (SCEVAddRecExpr *AddRec, SCEV::NoWrapFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update no-wrap flags of an AddRec. <a href="#a248dea99ef1d5a864269ac3a98014b37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad146072469181af4ccb7ef03c28999ba">applyLoopGuards</a> (const SCEV *Expr, const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to apply information from loop guards for <span class="doxyComputerOutput">L</span> to <span class="doxyComputerOutput">Expr</span>. <a href="#ad146072469181af4ccb7ef03c28999ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c0ce43396cc3c9640810339a90900a0">applyLoopGuards</a> (const SCEV *Expr, const LoopGuards &amp;Guards)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3db092f7661158b76135b3b7d39f0991">loopHasNoAbnormalExits</a> (const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the loop has no abnormal exits. <a href="#a3db092f7661158b76135b3b7d39f0991">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b1509388282f293de48b34276e5b538">loopIsFiniteByAssumption</a> (const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this loop is finite by assumption. <a href="#a9b1509388282f293de48b34276e5b538">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2a2b4d8e36b1369dc9aad73feba41e2">getPoisonGeneratingValues</a> (SmallPtrSetImpl&lt; const Value * &gt; &amp;Result, const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the set of Values that, if poison, will definitively result in S being poison as well. <a href="#ab2a2b4d8e36b1369dc9aad73feba41e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea73058623ab7225aabe7a95068784a4">canReuseInstruction</a> (const SCEV *S, Instruction *I, SmallVectorImpl&lt; Instruction * &gt; &amp;DropPoisonGeneratingInsts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether it is poison-safe to represent the expression S using the instruction I. <a href="#aea73058623ab7225aabe7a95068784a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac30767e8a68665a1b00cfef030d3199">getSCEVValues</a> (const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> set from which the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expr is generated. <a href="#aac30767e8a68665a1b00cfef030d3199">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e41ccb61c6c3cb64d14f122facbe911">getConstantMultipleImpl</a> (const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Private helper method for the getConstantMultiple method. <a href="#a5e41ccb61c6c3cb64d14f122facbe911">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">LoopProperties</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9abdda86f5368eea672ceff91bc0501e">getLoopProperties</a> (const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <span class="doxyComputerOutput">LoopProperties</span> instance for <span class="doxyComputerOutput">L</span>, creating one if necessary. <a href="#a9abdda86f5368eea672ceff91bc0501e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a392fcb7cb033043f3870a715c00aa283">loopHasNoSideEffects</a> (const Loop *L)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9f7c88892cfe1646082bf6174a4b912c">LoopDisposition</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac029348311bcc4bcbed0b090e0cc15ef">computeLoopDisposition</a> (const SCEV *S, const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute a <a href="#a9f7c88892cfe1646082bf6174a4b912c">LoopDisposition</a> value. <a href="#ac029348311bcc4bcbed0b090e0cc15ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aae7c3ec1a0344306acbdc2dcb113995e">BlockDisposition</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae68bff9bed0c19a8d6943110bdeb719d">computeBlockDisposition</a> (const SCEV *S, const BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute a <a href="#aae7c3ec1a0344306acbdc2dcb113995e">BlockDisposition</a> value. <a href="#ae68bff9bed0c19a8d6943110bdeb719d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5b6270038fd30531c691a51b57e8a0f">setRange</a> (const SCEV *S, RangeSignHint Hint, ConstantRange CR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the memoized range for the given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>. <a href="#af5b6270038fd30531c691a51b57e8a0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad719d3b695dcd6e1b05303e7f71bc29">getRangeRef</a> (const SCEV *S, RangeSignHint Hint, unsigned Depth=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the range for a particular <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>. <a href="#aad719d3b695dcd6e1b05303e7f71bc29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f0f97251f99dea6f5078398d5e6349f">getRangeRefIter</a> (const SCEV *S, RangeSignHint Hint)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the range for a particular <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>, but evaluates ranges for operands iteratively first. <a href="#a6f0f97251f99dea6f5078398d5e6349f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a220306abffc36e5272d96039ff721b59">getRangeForAffineAR</a> (const SCEV *Start, const SCEV *Step, const APInt &amp;MaxBECount)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determines the range for the affine <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> {<span class="doxyComputerOutput">Start</span>,+,<span class="doxyComputerOutput">Step}</span>. <a href="#a220306abffc36e5272d96039ff721b59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83ea8ea58d5a5ac71a1e6d9ed7dc1ee3">getRangeForAffineNoSelfWrappingAR</a> (const SCEVAddRecExpr *AddRec, const SCEV *MaxBECount, unsigned BitWidth, RangeSignHint SignHint)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determines the range for the affine non-self-wrapping <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> {<span class="doxyComputerOutput">Start</span>,+,<span class="doxyComputerOutput">Step}</span> &lt;nw&gt;. <a href="#a83ea8ea58d5a5ac71a1e6d9ed7dc1ee3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa23128e8702fac7c6e5c19e261ab8c28">getRangeViaFactoring</a> (const SCEV *Start, const SCEV *Step, const APInt &amp;MaxBECount)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to compute a range for the affine <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> {<span class="doxyComputerOutput">Start</span>,+,<span class="doxyComputerOutput">Step}</span> by "factoring out" a ternary expression from the add recurrence. <a href="#aa23128e8702fac7c6e5c19e261ab8c28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa46910cf61055949c6b833814b88cae">getRangeForUnknownRecurrence</a> (const SCEVUnknown *U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the unknown expression U corresponds to a simple recurrence, return a constant range which represents the entire recurrence. <a href="#aaa46910cf61055949c6b833814b88cae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2656ae0e17fe5d7da2e6def92ee4d00">createSCEV</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We know that there is no <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> for the specified value. <a href="#ad2656ae0e17fe5d7da2e6def92ee4d00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af50a59443360ee6580f9424ea440c374">createSCEVIter</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We know that there is no <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> for the specified value. <a href="#af50a59443360ee6580f9424ea440c374">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f06eed03071edf91894029713d20195">getOperandsToCreate</a> (Value *V, SmallVectorImpl&lt; Value * &gt; &amp;Ops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect operands of <span class="doxyComputerOutput">V</span> for which <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expressions should be constructed first. <a href="#a4f06eed03071edf91894029713d20195">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7f7c1841099ab8afd4c084a0eef97d5">createNodeForPHIWithIdenticalOperands</a> (PHINode *PN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> for the first operand of a phi if all phi operands have identical opcodes and operands. <a href="#aa7f7c1841099ab8afd4c084a0eef97d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd57b93f72e39162b5c322db730b32a6">createNodeForPHI</a> (PHINode *PN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide the special handling we need to analyze PHI SCEVs. <a href="#acd57b93f72e39162b5c322db730b32a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77be49741262b0ad114fb2aaa777570c">createAddRecFromPHI</a> (PHINode *PN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function called from createNodeForPHI. <a href="#a77be49741262b0ad114fb2aaa777570c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1091a8a57e832868a4c5a8b513fe002">createSimpleAffineAddRec</a> (PHINode *PN, Value *BEValueV, Value *StartValueV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper function for createAddRecFromPHI to handle simple cases. <a href="#aa1091a8a57e832868a4c5a8b513fe002">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cb3871e55141321ca2d62a82989d8c0">createNodeFromSelectLikePHI</a> (PHINode *PN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function called from createNodeForPHI. <a href="#a9cb3871e55141321ca2d62a82989d8c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a658f6372905ff1b7900113b0270bee48">createNodeForSelectOrPHIInstWithICmpInstCond</a> (Type *Ty, ICmpInst *Cond, Value *TrueVal, Value *FalseVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide special handling for a select-like instruction (currently this is either a select instruction or a phi node). <a href="#a658f6372905ff1b7900113b0270bee48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e55bf47ce597c176a203abe0058950a">createNodeForSelectOrPHIViaUMinSeq</a> (Value *I, Value *Cond, Value *TrueVal, Value *FalseVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See if we can model this select-like instruction via umin_seq expression. <a href="#a5e55bf47ce597c176a203abe0058950a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9ba4ef072ce4673921a8e5928651ce1">createNodeForSelectOrPHI</a> (Value *V, Value *Cond, Value *TrueVal, Value *FalseVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a value <span class="doxyComputerOutput">V</span>, which is a select-like instruction (currently this is either a select instruction or a phi node), which is assumed equivalent to Cond ? <a href="#ac9ba4ef072ce4673921a8e5928651ce1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a2efdf65c0d248d8834ae744d86f323">createNodeForGEP</a> (GEPOperator *GEP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide the special handling we need to analyze GEP SCEVs. <a href="#a4a2efdf65c0d248d8834ae744d86f323">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1366acc817c38a46ae6758e6fcc677c">computeSCEVAtScope</a> (const SCEV *S, const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementation code for getSCEVAtScope; called at most once for each SCEV+Loop pair. <a href="#af1366acc817c38a46ae6758e6fcc677c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">BackedgeTakenInfo &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a06b5bed55cce32bf8894dfe50d5001">getBackedgeTakenInfo</a> (const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the BackedgeTakenInfo for the given loop, lazily computing new values if the loop hasn't been analyzed yet. <a href="#a5a06b5bed55cce32bf8894dfe50d5001">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">BackedgeTakenInfo &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa285b48d25d9068add19a3fd29ff21d0">getPredicatedBackedgeTakenInfo</a> (const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to getBackedgeTakenInfo, but will add predicates as required with the purpose of returning complete information. <a href="#aa285b48d25d9068add19a3fd29ff21d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">BackedgeTakenInfo</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa76802ab848e6f5cd982fa9de101c31f">computeBackedgeTakenCount</a> (const Loop *L, bool AllowPredicates=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the number of times the specified loop will iterate. <a href="#aa76802ab848e6f5cd982fa9de101c31f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/scalarevolution/exitlimit">ExitLimit</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6409e7b9848a1a6c91f713b93ee7921">computeExitLimit</a> (const Loop *L, BasicBlock *ExitingBlock, bool IsOnlyExit, bool AllowPredicates=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the number of times the backedge of the specified loop will execute if it exits via the specified block. <a href="#aa6409e7b9848a1a6c91f713b93ee7921">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/scalarevolution/exitlimit">ExitLimit</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bd95793e2853d9355dd8ec9e1d61b31">computeExitLimitFromCondCached</a> (ExitLimitCacheTy &amp;Cache, const Loop *L, Value *ExitCond, bool ExitIfTrue, bool ControlsOnlyExit, bool AllowPredicates)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/scalarevolution/exitlimit">ExitLimit</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4442b5e96654bdcf0176687dc8cae5ba">computeExitLimitFromCondImpl</a> (ExitLimitCacheTy &amp;Cache, const Loop *L, Value *ExitCond, bool ExitIfTrue, bool ControlsOnlyExit, bool AllowPredicates)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/scalarevolution/exitlimit">ScalarEvolution::ExitLimit</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ba8e3fb91bc0a29bc632c29e9fffa7c">computeExitLimitFromCondFromBinOp</a> (ExitLimitCacheTy &amp;Cache, const Loop *L, Value *ExitCond, bool ExitIfTrue, bool ControlsOnlyExit, bool AllowPredicates)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/scalarevolution/exitlimit">ExitLimit</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa819a97e0537efe10494b69c0d208852">computeExitLimitFromICmp</a> (const Loop *L, ICmpInst *ExitCond, bool ExitIfTrue, bool IsSubExpr, bool AllowPredicates=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the number of times the backedge of the specified loop will execute if its exit condition were a conditional branch of the <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> ExitCond and ExitIfTrue. <a href="#aa819a97e0537efe10494b69c0d208852">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/scalarevolution/exitlimit">ExitLimit</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e7f526b39280a60de46b6419602a3a9">computeExitLimitFromICmp</a> (const Loop *L, CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS, bool IsSubExpr, bool AllowPredicates=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Variant of previous which takes the components representing an ICmp as opposed to the <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> itself. <a href="#a5e7f526b39280a60de46b6419602a3a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/scalarevolution/exitlimit">ExitLimit</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32a9e14782c38383d73d152a580045e2">computeExitLimitFromSingleExitSwitch</a> (const Loop *L, SwitchInst *Switch, BasicBlock *ExitingBB, bool IsSubExpr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the number of times the backedge of the specified loop will execute if its exit condition were a switch with a single exiting case to ExitingBB. <a href="#a32a9e14782c38383d73d152a580045e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/scalarevolution/exitlimit">ExitLimit</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6acbf52a09b6861513769f4bdc0f2b36">computeShiftCompareExitLimit</a> (Value *LHS, Value *RHS, const Loop *L, ICmpInst::Predicate Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the exit limit of a loop that is controlled by a "(IV &gt;&gt; 1) != 0" type comparison. <a href="#a6acbf52a09b6861513769f4bdc0f2b36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af38c7c135bb3cb672d64efcdc2ce86a3">computeExitCountExhaustively</a> (const Loop *L, Value *Cond, bool ExitWhen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the loop is known to execute a constant number of times (the condition evolves only from constants), try to evaluate a few iterations of the loop until we get the exit condition gets a value of ExitWhen (true or false). <a href="#af38c7c135bb3cb672d64efcdc2ce86a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/scalarevolution/exitlimit">ExitLimit</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57dd341fa6ca92d37352cef792eff0b2">howFarToZero</a> (const SCEV *V, const Loop *L, bool IsSubExpr, bool AllowPredicates=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of times an exit condition comparing the specified value to zero will execute. <a href="#a57dd341fa6ca92d37352cef792eff0b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/scalarevolution/exitlimit">ExitLimit</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87326b020e522a883e2b1d5559b4ea26">howFarToNonZero</a> (const SCEV *V, const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of times an exit condition checking the specified value for nonzero will execute. <a href="#a87326b020e522a883e2b1d5559b4ea26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/scalarevolution/exitlimit">ExitLimit</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa059c79f1aa1bd0bc7f10105f5d185e8">howManyLessThans</a> (const SCEV *LHS, const SCEV *RHS, const Loop *L, bool isSigned, bool ControlsOnlyExit, bool AllowPredicates=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of times an exit condition containing the specified less-than comparison will execute. <a href="#aa059c79f1aa1bd0bc7f10105f5d185e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/scalarevolution/exitlimit">ExitLimit</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa2b86521a9188600cd0540e172beb28">howManyGreaterThans</a> (const SCEV *LHS, const SCEV *RHS, const Loop *L, bool isSigned, bool IsSubExpr, bool AllowPredicates=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88c31e9e244995ed33fb4962ee489de5">getPredecessorWithUniqueSuccessorForBB</a> (const BasicBlock *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a predecessor of BB (which may not be an immediate predecessor) which has exactly one successor from which BB is reachable, or null if no such block is found. <a href="#a88c31e9e244995ed33fb4962ee489de5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae77c33090e9ff44fd8f52df43549b10d">isImpliedCond</a> (CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS, const Value *FoundCondValue, bool Inverse, const Instruction *Context=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the condition described by Pred, LHS, and RHS is true whenever the given FoundCondValue value evaluates to true in given Context. <a href="#ae77c33090e9ff44fd8f52df43549b10d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4027c2e0684dc379274040864895640">isImpliedCondBalancedTypes</a> (CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS, CmpPredicate FoundPred, const SCEV *FoundLHS, const SCEV *FoundRHS, const Instruction *CtxI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the condition described by Pred, LHS, and RHS is true whenever the given FoundCondValue value evaluates to true in given Context. <a href="#ab4027c2e0684dc379274040864895640">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba8789e821f00a5978b272c6056254da">isImpliedCond</a> (CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS, CmpPredicate FoundPred, const SCEV *FoundLHS, const SCEV *FoundRHS, const Instruction *Context=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the condition described by Pred, LHS, and RHS is true whenever the condition described by FoundPred, FoundLHS, FoundRHS is true in given Context. <a href="#aba8789e821f00a5978b272c6056254da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b932e599117f9276492f30f78aa0fa4">isImpliedCondOperands</a> (CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS, const SCEV *FoundLHS, const SCEV *FoundRHS, const Instruction *Context=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the condition described by Pred, LHS, and RHS is true whenever the condition described by Pred, FoundLHS, and FoundRHS is true in given Context. <a href="#a3b932e599117f9276492f30f78aa0fa4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99b54d832a5c3eaa10272eedfc04c12f">isImpliedViaOperations</a> (CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS, const SCEV *FoundLHS, const SCEV *FoundRHS, unsigned Depth=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the condition described by Pred, LHS, and RHS is true whenever the condition described by Pred, FoundLHS, and FoundRHS is true. <a href="#a99b54d832a5c3eaa10272eedfc04c12f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21fd8c714c15a8ba7c329280de85922f">isKnownViaNonRecursiveReasoning</a> (CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the condition described by Pred, LHS, and RHS is true. <a href="#a21fd8c714c15a8ba7c329280de85922f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa015ca257dd77d3969e71137a8d65f08">isImpliedCondOperandsHelper</a> (CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS, const SCEV *FoundLHS, const SCEV *FoundRHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the condition described by Pred, LHS, and RHS is true whenever the condition described by Pred, FoundLHS, and FoundRHS is true. <a href="#aa015ca257dd77d3969e71137a8d65f08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41851a452bcf256bc44b0ca0d22c16d3">isImpliedCondOperandsViaRanges</a> (CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS, CmpPredicate FoundPred, const SCEV *FoundLHS, const SCEV *FoundRHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the condition described by Pred, LHS, and RHS is true whenever the condition described by Pred, FoundLHS, and FoundRHS is true. <a href="#a41851a452bcf256bc44b0ca0d22c16d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af148ca3fb0f88b825b9af5d5e1202547">isImpliedViaGuard</a> (const BasicBlock *BB, CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the condition denoted by <span class="doxyComputerOutput">LHS</span> <span class="doxyComputerOutput">Pred</span> <span class="doxyComputerOutput">RHS</span> is implied by a call to @llvm.experimental.guard in <span class="doxyComputerOutput">BB</span>. <a href="#af148ca3fb0f88b825b9af5d5e1202547">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f2c428d1e89761be24199170248ebae">isImpliedCondOperandsViaNoOverflow</a> (CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS, const SCEV *FoundLHS, const SCEV *FoundRHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the condition described by Pred, LHS, and RHS is true whenever the condition described by Pred, FoundLHS, and FoundRHS is true. <a href="#a8f2c428d1e89761be24199170248ebae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38e7e112d2cb6b911dcffaf94fa2c869">isImpliedCondOperandsViaAddRecStart</a> (CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS, const SCEV *FoundLHS, const SCEV *FoundRHS, const Instruction *CtxI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the condition described by Pred, LHS, and RHS is true whenever the condition described by Pred, FoundLHS, and FoundRHS is true. <a href="#a38e7e112d2cb6b911dcffaf94fa2c869">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21dcbae8aa0ddadb4c4cbabd57805a7a">isImpliedViaMerge</a> (CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS, const SCEV *FoundLHS, const SCEV *FoundRHS, unsigned Depth)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the condition described by Pred, LHS, and RHS is true whenever the condition described by Pred, FoundLHS, and FoundRHS is true. <a href="#a21dcbae8aa0ddadb4c4cbabd57805a7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c83e4560b53692ce12cad5e4ab629f8">isImpliedCondOperandsViaShift</a> (CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS, const SCEV *FoundLHS, const SCEV *FoundRHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the condition described by Pred, LHS, and RHS is true whenever the condition described by Pred, FoundLHS, and FoundRHS is true. <a href="#a8c83e4560b53692ce12cad5e4ab629f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbb1d45f9fec6bfdfd2c21f5d79e7d58">getConstantEvolutionLoopExitValue</a> (PHINode *PN, const APInt &amp;BEs, const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If we know that the specified Phi is in the header of its containing loop, we know the loop executes a constant number of times, and the PHI node is just a recurrence involving constants, fold it. <a href="#afbb1d45f9fec6bfdfd2c21f5d79e7d58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab83027d11737fb24ab23867b8b1f2227">isKnownPredicateViaConstantRanges</a> (CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if the given expression is known to satisfy the condition described by Pred and the known constant ranges of LHS and RHS. <a href="#ab83027d11737fb24ab23867b8b1f2227">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa79768fbd252f8de092490503bcd776a">isKnownPredicateViaNoOverflow</a> (CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to prove the condition described by "LHS Pred RHS" by ruling out integer overflow. <a href="#aa79768fbd252f8de092490503bcd776a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b471480bf02920d1caddf36fc3a797e">isKnownPredicateViaSplitting</a> (CmpPredicate Pred, const SCEV *LHS, const SCEV *RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to split Pred LHS RHS into logical conjunctions (and's) and try to prove them individually. <a href="#a3b471480bf02920d1caddf36fc3a797e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a617f77bccf5b0defac6741f9bac477f0">splitBinaryAdd</a> (const SCEV *Expr, const SCEV *&amp;L, const SCEV *&amp;R, SCEV::NoWrapFlags &amp;Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to match the Expr as "(L + R)&lt;Flags&gt;". <a href="#a617f77bccf5b0defac6741f9bac477f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf4763d7397ff28867970f6aedf9c47e">forgetBackedgeTakenCounts</a> (const Loop *L, bool Predicated)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Forget predicated/non-predicated backedge taken counts for the given loop. <a href="#acf4763d7397ff28867970f6aedf9c47e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1adcf075a7f9844b55ce4f3d1094192c">forgetMemoizedResults</a> (ArrayRef&lt; const SCEV * &gt; SCEVs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drop memoized information for all <span class="doxyComputerOutput">SCEVs</span>. <a href="#a1adcf075a7f9844b55ce4f3d1094192c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa147db85cb7b1070e8b496db8e4fb108">forgetMemoizedResultsImpl</a> (const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for forgetMemoizedResults. <a href="#aa147db85cb7b1070e8b496db8e4fb108">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47dde7c7c74e75731b103529cef47586">visitAndClearUsers</a> (SmallVectorImpl&lt; Instruction * &gt; &amp;Worklist, SmallPtrSetImpl&lt; Instruction * &gt; &amp;Visited, SmallVectorImpl&lt; const SCEV * &gt; &amp;ToForget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterate over instructions in <span class="doxyComputerOutput">Worklist</span> and their users. <a href="#a47dde7c7c74e75731b103529cef47586">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0f0298991197b4afda45dad52dc6abc">eraseValueFromMap</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> from ValueExprMap and ExprValueMap. <a href="#af0f0298991197b4afda45dad52dc6abc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d426e6db7edacb47bd1934b2315d6d4">insertValueToMap</a> (Value *V, const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert V to S mapping into ValueExprMap and ExprValueMap. <a href="#a6d426e6db7edacb47bd1934b2315d6d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adee32c2f1921223f5acacae278f3c167">checkValidity</a> (const SCEV *S) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return false iff given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> contains a <a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a> with NULL value- pointer. <a href="#adee32c2f1921223f5acacae278f3c167">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ExtendOpTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a93dea5275169c80999e1f74e522a69fb">proveNoWrapByVaryingStart</a> (const SCEV *Start, const SCEV *Step, const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">ExtendOpTy</span>({<span class="doxyComputerOutput">Start</span>,+,<span class="doxyComputerOutput">Step</span>}) can be proved to be equal to {<span class="doxyComputerOutput">ExtendOpTy</span>(<span class="doxyComputerOutput">Start</span>),+,<span class="doxyComputerOutput">ExtendOpTy</span>(<span class="doxyComputerOutput">Step</span>)}. <a href="#a93dea5275169c80999e1f74e522a69fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f27763749613527c7d2fa8e5cdc84a2">proveNoWrapViaConstantRanges</a> (const SCEVAddRecExpr *AR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to prove NSW or NUW on <span class="doxyComputerOutput">AR</span> relying on <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> manipulation. <a href="#a7f27763749613527c7d2fa8e5cdc84a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac77d8ec075ce875713036ca1439d25e6">proveNoSignedWrapViaInduction</a> (const SCEVAddRecExpr *AR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to prove NSW on <span class="doxyComputerOutput">AR</span> by proving facts about conditions known on entry and backedge. <a href="#ac77d8ec075ce875713036ca1439d25e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b08bbacf652ea6888acde49f097b1ff">proveNoUnsignedWrapViaInduction</a> (const SCEVAddRecExpr *AR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to prove NUW on <span class="doxyComputerOutput">AR</span> by proving facts about conditions known on entry and backedge. <a href="#a7b08bbacf652ea6888acde49f097b1ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="#a899d8027fa6af3ca29aae6d88b6050ef">MonotonicPredicateType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa89bb41b2b40957875bab58d1a800182">getMonotonicPredicateTypeImpl</a> (const SCEVAddRecExpr *LHS, ICmpInst::Predicate Pred)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46cd40c1296e0a2ea4793aa9ebe4c7f3">getNoWrapFlagsFromUB</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> no-wrap flags that can be proven based on reasoning about how poison produced from no-wrap flags on this value (e.g. <a href="#a46cd40c1296e0a2ea4793aa9ebe4c7f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afedbfa75eee412fbacef2b57bfd79ede">getNonTrivialDefiningScopeBound</a> (const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a scope which provides an upper bound on the defining scope of 'S'. <a href="#afedbfa75eee412fbacef2b57bfd79ede">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89e5c9c0e24c3cf489959b38c1a64fd6">getDefiningScopeBound</a> (ArrayRef&lt; const SCEV * &gt; Ops, bool &amp;Precise)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a scope which provides an upper bound on the defining scope for a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> with the operands in Ops. <a href="#a89e5c9c0e24c3cf489959b38c1a64fd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2110fcdb61cc336dd096f1f91daa0f9">getDefiningScopeBound</a> (ArrayRef&lt; const SCEV * &gt; Ops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wrapper around the above for cases which don't care if the bound is precise. <a href="#ac2110fcdb61cc336dd096f1f91daa0f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bf499522b8033fb7cdd18d147b1c33e">isGuaranteedToTransferExecutionTo</a> (const Instruction *A, const Instruction *B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given two instructions in the same function, return true if we can prove B must execute given A executes. <a href="#a2bf499522b8033fb7cdd18d147b1c33e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7307068047c87a906260bc017910c92">isGuaranteedNotToCauseUB</a> (const SCEV *Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> is guaranteed not to cause immediate UB. <a href="#ad7307068047c87a906260bc017910c92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af42e38b421af577479ffa88c08aac1b9">isSCEVExprNeverPoison</a> (const Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> corresponding to <span class="doxyComputerOutput">I</span> is never poison. <a href="#af42e38b421af577479ffa88c08aac1b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02d12cb7ecf24114a48def3e16b10a73">isAddRecNeverPoison</a> (const Instruction *I, const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is like <span class="doxyComputerOutput">isSCEVExprNeverPoison</span> but it specifically works for instructions that will get mapped to <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> add recurrences. <a href="#a02d12cb7ecf24114a48def3e16b10a73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> *, 3 &gt; &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f2351e880db97150c09300d5f36857d">createAddRecFromPHIWithCastsImpl</a> (const SCEVUnknown *SymbolicPHI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to createAddRecFromPHI, but with the additional flexibility of suggesting runtime overflow checks in case casts are encountered. <a href="#a3f2351e880db97150c09300d5f36857d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb0ee2aa6765d464b5c6b2ab19cf97c4">computeMaxBECountForLT</a> (const SCEV *Start, const SCEV *Stride, const SCEV *End, unsigned BitWidth, bool IsSigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the maximum backedge count based on the range of values permitted by Start, End, and Stride. <a href="#acb0ee2aa6765d464b5c6b2ab19cf97c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae78c431412e92d16c80efff40339ada1">canIVOverflowOnLT</a> (const SCEV *RHS, const SCEV *Stride, bool IsSigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify if an linear IV with positive stride can overflow when in a less-than comparison, knowing the invariant term of the comparison, the stride. <a href="#ae78c431412e92d16c80efff40339ada1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5315a687d765fc01b5a2c50d009a2c3">canIVOverflowOnGT</a> (const SCEV *RHS, const SCEV *Stride, bool IsSigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify if an linear IV with negative stride can overflow when in a greater-than comparison, knowing the invariant term of the comparison, the stride. <a href="#aa5315a687d765fc01b5a2c50d009a2c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae837549254d3833922b6843ddf240543">getOrCreateAddExpr</a> (ArrayRef&lt; const SCEV * &gt; Ops, SCEV::NoWrapFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get add expr already created or create a new one. <a href="#ae837549254d3833922b6843ddf240543">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7968840b93f4e9cc3ffe1341d1791bba">getOrCreateMulExpr</a> (ArrayRef&lt; const SCEV * &gt; Ops, SCEV::NoWrapFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get mul expr already created or create a new one. <a href="#a7968840b93f4e9cc3ffe1341d1791bba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9448d65fa47e95eba66c447f6d17f068">getOrCreateAddRecExpr</a> (ArrayRef&lt; const SCEV * &gt; Ops, const Loop *L, SCEV::NoWrapFlags Flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c9e17f21a2fe5953cb49bc19b25de46">stripInjectiveFunctions</a> (const SCEV *Val) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return x if <span class="doxyComputerOutput">Val</span> is f(x) where f is a 1-1 function. <a href="#a7c9e17f21a2fe5953cb49bc19b25de46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61eaf3dd44d27eac001367d128b66781">getUsedLoops</a> (const SCEV *S, SmallPtrSetImpl&lt; const Loop * &gt; &amp;LoopsUsed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find all of the loops transitively used in <span class="doxyComputerOutput">S</span>, and fill <span class="doxyComputerOutput">LoopsUsed</span>. <a href="#a61eaf3dd44d27eac001367d128b66781">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82c3814bf2a8c5e8a7559d061cbdcc7f">matchURem</a> (const SCEV *Expr, const SCEV *&amp;LHS, const SCEV *&amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to match the pattern generated by getURemExpr(A, B). <a href="#a82c3814bf2a8c5e8a7559d061cbdcc7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9560ce040bda46ab2f01ae9d56ed9413">findExistingSCEVInCache</a> (SCEVTypes SCEVType, ArrayRef&lt; const SCEV * &gt; Ops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look for a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression with type <span class="doxyComputerOutput">SCEVType</span> and operands <span class="doxyComputerOutput">Ops</span> in <span class="doxyComputerOutput">UniqueSCEVs</span>. <a href="#a9560ce040bda46ab2f01ae9d56ed9413">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaabcc8eab6f40da52d8a18e14186b2b9">getReachableBlocks</a> (SmallPtrSetImpl&lt; BasicBlock * &gt; &amp;Reachable, Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get reachable blocks in this function, making limited use of <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> reasoning about conditions. <a href="#aaabcc8eab6f40da52d8a18e14186b2b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab70ae7f04d02aff973b59e1ae974989c">getWithOperands</a> (const SCEV *S, SmallVectorImpl&lt; const SCEV * &gt; &amp;NewOps)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression with a new set of operands. <a href="#ab70ae7f04d02aff973b59e1ae974989c">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5825b2ab428f470964dce4af0cf7eb61">F</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The function we are analyzing. <a href="#a5825b2ab428f470964dce4af0cf7eb61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6e7a482ff8862b8bc1af7d374df2ee7">DL</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Data layout of the module. <a href="#ac6e7a482ff8862b8bc1af7d374df2ee7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd3634c38fc9c45c9381be285e7d85ea">HasGuards</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does the module have any calls to the llvm.experimental.guard intrinsic at all? <a href="#afd3634c38fc9c45c9381be285e7d85ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae45f925f6052bd2a76d1986b711cfd81">TLI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The target library information for the target we are targeting. <a href="#ae45f925f6052bd2a76d1986b711cfd81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95f388a2e35d502a4d72436de42f54c3">AC</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The tracker for @llvm.assume intrinsics in this function. <a href="#a95f388a2e35d502a4d72436de42f54c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a279d7f0474381dddba0711877453614b">DT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The dominator tree. <a href="#a279d7f0474381dddba0711877453614b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1983fa914ca7e3befd135764d480bead">LI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The loop information for the function we are currently analyzing. <a href="#a1983fa914ca7e3befd135764d480bead">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/scevcouldnotcompute">SCEVCouldNotCompute</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70cc1e23af6aa81f94cfb9a66d7d1bd6">CouldNotCompute</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> is used to represent unknown trip counts and things. <a href="#a70cc1e23af6aa81f94cfb9a66d7d1bd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">HasRecMapType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4303770e6ff4a4d4e679c34c7bfc5e74">HasRecMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a cache to record whether a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> contains any scAddRecExpr. <a href="#a4303770e6ff4a4d4e679c34c7bfc5e74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">ExprValueMapType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a473dc76382b76b1a21bba57abf1177dc">ExprValueMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ExprValueMap – This map records the original values from which the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expr is generated from. <a href="#a473dc76382b76b1a21bba57abf1177dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">ValueExprMapType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab54d94b24d8f4ad8ac12cf94766d4911">ValueExprMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a cache of the values we have analyzed so far. <a href="#ab54d94b24d8f4ad8ac12cf94766d4911">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/foldid">FoldID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21970eefe17af743475eaf22846d6014">FoldCache</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a cache for expressions that got folded to a different existing <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>. <a href="#a21970eefe17af743475eaf22846d6014">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/foldid">FoldID</a>, 2 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e52946749c2ddb1db2b4289518b43ab">FoldCacheUser</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 6 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5abaf44364bc31d139458729eff2e408">PendingLoopPredicates</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark predicate values currently being processed by isImpliedCond. <a href="#a5abaf44364bc31d139458729eff2e408">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *, 6 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f130d46eaff809039b9eb67dbacaff5">PendingPhiRanges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark <a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a> Phis currently being processed by getRangeRef. <a href="#a7f130d46eaff809039b9eb67dbacaff5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *, 6 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14178d96fe55717767e4e205bc0b31b2">PendingPhiRangesIter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark <a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a> Phis currently being processed by getRangeRefIter. <a href="#a14178d96fe55717767e4e205bc0b31b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *, 6 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a619e8396e50f7ef40844ea5888257a41">PendingMerges</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76d754f47ab0bea94f4d683810f802b0">WalkingBEDominatingConds</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set to true by isLoopBackedgeGuardedByCond when we're walking the set of conditions dominating the backedge of a loop. <a href="#a76d754f47ab0bea94f4d683810f802b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a963bcbabea12a74f365a288c01e2d74f">ProvingSplitPredicate</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set to true by isKnownPredicateViaSplitting when we're trying to prove a predicate by splitting it into a set of independent predicates. <a href="#a963bcbabea12a74f365a288c01e2d74f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ffb674a228933a88d184ff873842b7e">ConstantMultipleCache</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Memoized values for the getConstantMultiple. <a href="#a9ffb674a228933a88d184ff873842b7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *, BackedgeTakenInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe5b64c7528afd464f11b71b1ff4898d">BackedgeTakenCounts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache the backedge-taken count of the loops for this function as they are computed. <a href="#afe5b64c7528afd464f11b71b1ff4898d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *, BackedgeTakenInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea8a1b691474325789b31cf0c930e15c">PredicatedBackedgeTakenCounts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache the predicated backedge-taken count of the loops for this function as they are computed. <a href="#aea8a1b691474325789b31cf0c930e15c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *, 1, bool &gt;, 4 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa85d303e9315b1858a6a8b7dce6f6124">BECountUsers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loops whose backedge taken counts directly use this non-constant <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>. <a href="#aa85d303e9315b1858a6a8b7dce6f6124">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dad2853aff20ad42044247b7cd5b3b4">ConstantEvolutionLoopExitValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This map contains entries for all of the PHI instructions that we attempt to compute constant evolutions for. <a href="#a1dad2853aff20ad42044247b7cd5b3b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt;, 2 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f8fe8ae570ffea98296d8d1863c8017">ValuesAtScopes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This map contains entries for all the expressions that we attempt to compute getSCEVAtScope information for, which can be expensive in extreme cases. <a href="#a6f8fe8ae570ffea98296d8d1863c8017">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt;, 2 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02da71cc634ae00e0d0fdcfaae95301e">ValuesAtScopesUsers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reverse map for invalidation purposes: Stores of which <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> and which loop this is the value-at-scope of. <a href="#a02da71cc634ae00e0d0fdcfaae95301e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *, 2, <a href="#a9f7c88892cfe1646082bf6174a4b912c">LoopDisposition</a> &gt;, 2 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa90ae9b03ef66ae8ceb7d6ae15f6e030">LoopDispositions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Memoized computeLoopDisposition results. <a href="#aa90ae9b03ef66ae8ceb7d6ae15f6e030">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *, LoopProperties &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7305b73843117a1653883028c061718">LoopPropertiesCache</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache for <span class="doxyComputerOutput">getLoopProperties</span>. <a href="#ad7305b73843117a1653883028c061718">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 2, <a href="#aae7c3ec1a0344306acbdc2dcb113995e">BlockDisposition</a> &gt;, 2 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b334bdd62bec64b325c1b85f97cbfd1">BlockDispositions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Memoized computeBlockDisposition results. <a href="#a4b334bdd62bec64b325c1b85f97cbfd1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, 8 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac885c764637faa8ca75f2f167cf667bb">SCEVUsers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stores all <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> that use a given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> as its direct operand. <a href="#ac885c764637faa8ca75f2f167cf667bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af76c2ccae76bb71fb6215d44fed1ebe1">UnsignedRanges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Memoized results from getRange. <a href="#af76c2ccae76bb71fb6215d44fed1ebe1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2eef82a0c6db08d9eed7c46d832bd63">SignedRanges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Memoized results from getRange. <a href="#ab2eef82a0c6db08d9eed7c46d832bd63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6e27585fed67608167af32f3544d590">UniqueSCEVs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77a2f3086ca5d88d73a55a0418d23e6e">UniquePreds</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e49741e6f337927533b85ffe42689fc">SCEVAllocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> *, 4 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab406e56dc4cb60fee23782a8163f8e06">LoopUsers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This maps loops to a list of addrecs that directly use said loop. <a href="#ab406e56dc4cb60fee23782a8163f8e06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * &gt;, std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> *, 3 &gt; &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60a0d1b47cb18b1c22b2a1d2fc2028cc">PredicatedSCEVRewrites</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache tentative mappings from UnknownSCEVs in a <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a>, to a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression they can be rewritten into under certain predicates. <a href="#a60a0d1b47cb18b1c22b2a1d2fc2028cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff5aa5a0e908338939e67aa37a1db92e">UnsignedWrapViaInductionTried</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of AddRecs for which proving NUW via an induction has already been tried. <a href="#aff5aa5a0e908338939e67aa37a1db92e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3b95a93308cb96930df6ea207b76bea">SignedWrapViaInductionTried</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of AddRecs for which proving NSW via an induction has already been tried. <a href="#ad3b95a93308cb96930df6ea207b76bea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14f654bf9a426b609db7fc834847650e">FirstUnknown</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The head of a linked list of all <a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a> values that have been allocated. <a href="#a14f654bf9a426b609db7fc834847650e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfe987ba0fa56ab9ecdb606c2462b6b9">maskFlags</a> (SCEV::NoWrapFlags Flags, int Mask)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenient NoWrapFlags manipulation that hides enum casts and is visible in the <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> name space. <a href="#adfe987ba0fa56ab9ecdb606c2462b6b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fed3b807739f2ff6942c12407ab00fa">setFlags</a> (SCEV::NoWrapFlags Flags, SCEV::NoWrapFlags OnFlags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7abfe35425aead3383db5d8a311c1671">clearFlags</a> (SCEV::NoWrapFlags Flags, SCEV::NoWrapFlags OffFlags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0410d63819514e3062a73eb48a5ecc82">hasFlags</a> (SCEV::NoWrapFlags Flags, SCEV::NoWrapFlags TestFlags)</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cc538e271abf38ff3b19e672355426a">isGuaranteedNotToBePoison</a> (const SCEV *Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> is guaranteed to not be poison. <a href="#a3cc538e271abf38ff3b19e672355426a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The main scalar evolution driver.</p>


<p>Because client code (intentionally) can't do much with the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> objects directly, they must ask this class for services.</p>


<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### ExitLimitCacheTy {#a7aac8e2fa36a1c6f2a2690b8345b26af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ScalarEvolution::ExitLimitCacheTy =  ExitLimitCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1875 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### ExprValueMapType {#a6a3ae111376590494c1f5b88c0fb701f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ScalarEvolution::ExprValueMapType =  DenseMap&lt;const SCEV *, ValueSetVector&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### HasRecMapType {#acf8958a77c3f05a0bafd88a8f6d8bbfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ScalarEvolution::HasRecMapType =  DenseMap&lt;const SCEV *, bool&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type for HasRecMap.</p>

<p>Definition at line 1442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### ValueExprMapType {#a637425b471ded8ede1f8bdc66abffd7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ScalarEvolution::ValueExprMapType = 
      DenseMap&lt;SCEVCallbackVH, const SCEV *, DenseMapInfo&lt;Value *&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type for ValueExprMap.</p>

<p>Definition at line 1456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### ValueSetVector {#a47ad5ea07479ddbb9621280324bf6a2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ScalarEvolution::ValueSetVector =  SmallSetVector&lt;Value *, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type for ExprValueMap.</p>

<p>Definition at line 1448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### BlockDisposition {#aae7c3ec1a0344306acbdc2dcb113995e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ScalarEvolution::BlockDisposition </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An enum describing the relationship between a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> and a basic block.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DoesNotDominateBlock<a id="aae7c3ec1a0344306acbdc2dcb113995eab597dd799bf69ea3ce93e263587ebc77"></a></td>
<td class="doxyEnumItemDescription">The <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> does not dominate the block</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DominatesBlock<a id="aae7c3ec1a0344306acbdc2dcb113995ea5eafe073dddfe773ed400352abe80d85"></a></td>
<td class="doxyEnumItemDescription">The <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> dominates the block</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ProperlyDominatesBlock<a id="aae7c3ec1a0344306acbdc2dcb113995ea95af43f9c06d0fe35d8c8ec1786028cb"></a></td>
<td class="doxyEnumItemDescription">The <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> properly dominates the block</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### ExitCountKind {#ace535ba3b8cc110f49b5db48a945ecef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ScalarEvolution::ExitCountKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The terms "backedge taken count" and "exit count" are used interchangeably to refer to the number of times the backedge of a loop has executed before the loop is exited.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Exact<a id="ace535ba3b8cc110f49b5db48a945ecefab1761348a1f6ac41658c85ffdd2d9361"></a></td>
<td class="doxyEnumItemDescription">An expression exactly describing the number of times the backedge has executed when a loop is exited</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ConstantMaximum<a id="ace535ba3b8cc110f49b5db48a945ecefa707795ac384dd38bc1fc47cded39f5de"></a></td>
<td class="doxyEnumItemDescription">A constant which provides an upper bound on the exact trip count</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SymbolicMaximum<a id="ace535ba3b8cc110f49b5db48a945ecefa007c52805d507c0cc6d53cbea782eaf4"></a></td>
<td class="doxyEnumItemDescription">An expression which provides an upper bound on the exact trip count</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 858 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### LoopDisposition {#a9f7c88892cfe1646082bf6174a4b912c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ScalarEvolution::LoopDisposition </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An enum describing the relationship between a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> and a loop.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LoopVariant<a id="a9f7c88892cfe1646082bf6174a4b912ca0f411f4871754e4f21f77ef949c5176e"></a></td>
<td class="doxyEnumItemDescription">The <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> is loop-variant (unknown)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LoopInvariant<a id="a9f7c88892cfe1646082bf6174a4b912ca1b7d4316c0866b0b0b7a510e1800f4a8"></a></td>
<td class="doxyEnumItemDescription">The <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> is loop-invariant</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LoopComputable<a id="a9f7c88892cfe1646082bf6174a4b912ca01f7990cbee1565b32df02333aeffb9b"></a></td>
<td class="doxyEnumItemDescription">The <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> varies predictably with the loop</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### MonotonicPredicateType {#a899d8027fa6af3ca29aae6d88b6050ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ScalarEvolution::MonotonicPredicateType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A predicate is said to be monotonically increasing if may go from being false to being true as the loop iterates, but never the other way around.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MonotonicallyIncreasing<a id="a899d8027fa6af3ca29aae6d88b6050efab8a33d7289e160c15fb2a8d84a3eade8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MonotonicallyDecreasing<a id="a899d8027fa6af3ca29aae6d88b6050efa085821bc8d4415d64b66a10d517612fb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>A predicate is said to be monotonically decreasing if may go from being true to being false as the loop iterates, but never the other way around.</p>


<p>Definition at line 1176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### RangeSignHint {#af73615d7c8ce4d840cf2daf94432d964}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ScalarEvolution::RangeSignHint </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used to parameterize getRange.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HINT_RANGE_UNSIGNED<a id="af73615d7c8ce4d840cf2daf94432d964aa53f62fba67d11638e2ab6342638b5c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HINT_RANGE_SIGNED<a id="af73615d7c8ce4d840cf2daf94432d964a869dbcbc6468ec406ff00250aa19a658"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1723 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### ScalarEvolutionsTest {#a7f71542fd299c1a7502dfcefb1e74df0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class ScalarEvolutionsTest</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Reference <a href="#a7f71542fd299c1a7502dfcefb1e74df0">ScalarEvolutionsTest</a>.</p>


<p>Referenced by <a href="#a7f71542fd299c1a7502dfcefb1e74df0">ScalarEvolutionsTest</a>.</p>

</div>
</div>

### SCEVCallbackVH {#a9fefddc47a698935163a34218708a00b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class SCEVCallbackVH</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### SCEVExpander {#a37dafb4cec590807a6126c6d9af469cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Reference <a href="#a37dafb4cec590807a6126c6d9af469cc">SCEVExpander</a>.</p>


<p>Referenced by <a href="#a37dafb4cec590807a6126c6d9af469cc">SCEVExpander</a>.</p>

</div>
</div>

### SCEVUnknown {#a9a1917da5135c7cd0431c35b583db2aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Reference <a href="#a9a1917da5135c7cd0431c35b583db2aa">SCEVUnknown</a>.</p>


<p>Referenced by <a href="#ada4b4e4637302939402932b866e82cf3">createAddRecFromPHIWithCasts</a>, <a href="#a4bab447a6422427e5fc92bbbc0c12fba">getLosslessPtrToIntExpr</a>, <a href="#ab2a2b4d8e36b1369dc9aad73feba41e2">getPoisonGeneratingValues</a>, <a href="#ad8e4f5b2ced08ad7d138b598aefdd338">getUnknown</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/loopguards/#afc980d8379c6a1d12d091ba6b33aa05f">llvm::ScalarEvolution::LoopGuards::rewrite</a>, <a href="#a9a1917da5135c7cd0431c35b583db2aa">SCEVUnknown</a>, <a href="#aff82c03c1ce8b945170bcb1f0f624c17">verify</a> and <a href="#aec226c51f8bffbf8fa3319bf11821cb9">~ScalarEvolution</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ScalarEvolution() {#a3f0118e315585ef6debe98a13336ae75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution::ScalarEvolution (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 13642 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a057ff1d04d6303e3402647132a66ab18">getDataLayout</a> and <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#aa1731508126b77035ab3ba9d71d5374b">llvm::Intrinsic::getDeclarationIfExists</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/loopguards/#ad8df7e7d0d1775311c1e6ee548e468c8">llvm::ScalarEvolution::LoopGuards::collect</a>, <a href="#a4bab447a6422427e5fc92bbbc0c12fba">getLosslessPtrToIntExpr</a>, <a href="#a77b275a78beac200ef1f703d2a5fbb7d">print</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/loopguards/#afc980d8379c6a1d12d091ba6b33aa05f">llvm::ScalarEvolution::LoopGuards::rewrite</a>, <a href="#a22e289929f2f90455f02bb5778cee6ca">ScalarEvolution</a>, <a href="#aff82c03c1ce8b945170bcb1f0f624c17">verify</a> and <a href="#a267fd27cb9e177fa5f48cbb8828339a1">willNotOverflow</a>.</p>

</div>
</div>

### ScalarEvolution() {#a22e289929f2f90455f02bb5778cee6ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution::ScalarEvolution (<a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp;&amp; Arg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 13663 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#a3f0118e315585ef6debe98a13336ae75">ScalarEvolution</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ScalarEvolution() {#aec226c51f8bffbf8fa3319bf11821cb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution::~ScalarEvolution ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 13694 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a9a1917da5135c7cd0431c35b583db2aa">SCEVUnknown</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### applyLoopGuards() {#ad146072469181af4ccb7ef03c28999ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::applyLoopGuards (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Expr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to apply information from loop guards for <span class="doxyComputerOutput">L</span> to <span class="doxyComputerOutput">Expr</span>.</p>

<p>Declaration at line 1346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 15972 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#ad146072469181af4ccb7ef03c28999ba">applyLoopGuards</a> and <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/loopguards/#ad8df7e7d0d1775311c1e6ee548e468c8">llvm::ScalarEvolution::LoopGuards::collect</a>.</p>


<p>Referenced by <a href="#ad146072469181af4ccb7ef03c28999ba">applyLoopGuards</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a65ab4267c6c132d06451b5d97bc9ee83">llvm::LoopVectorizationCostModel::computeMaxVF</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a72c491cdf8cf0283d87008831431f917">llvm::InnerLoopVectorizer::emitIterationCountCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a43288882d546aed1ef0a23ffc620ddff">expandBounds</a>, <a href="#a29ee697fe94374eae9689321e811f5e9">getSmallConstantTripMultiple</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#ac8cf3aa27282d640f5acbc3a676e03c5">isSafeDecreasingBound</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#adbc17f3ace73f701522eefe28104c06c">isSafeIncreasingBound</a>.</p>

</div>
</div>

### applyLoopGuards() {#a2c0ce43396cc3c9640810339a90900a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::applyLoopGuards (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Expr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/loopguards">LoopGuards</a> &amp; Guards)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 15976 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/loopguards/#afc980d8379c6a1d12d091ba6b33aa05f">llvm::ScalarEvolution::LoopGuards::rewrite</a>.</p>

</div>
</div>

### canReuseInstruction() {#aea73058623ab7225aabe7a95068784a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::canReuseInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; DropPoisonGeneratingInsts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether it is poison-safe to represent the expression S using the instruction I.</p>


<p>If such a replacement is performed, the poison flags of instructions in DropPoisonGeneratingInsts must be dropped.</p>


<p>Declaration at line 1370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4168 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a118b2507b9f8c68c87b2592913406e86">llvm::canCreatePoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#af74676a3c7447be34bd2c1da76ec0c48">llvm::SmallPtrSetImpl&lt; PtrType &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#ab2a2b4d8e36b1369dc9aad73feba41e2">getPoisonGeneratingValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7a3935517c67d2e9aa8e04f1cfc9f983">llvm::programUndefinedIfPoison</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a0e1c3175b0ac22fe3853651c28e1ecb8">llvm::SmallPtrSetImplBase::size</a>.</p>

</div>
</div>

### computeConstantDifference() {#ae0ca564918ec63a9b4d2229374fec747}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; APInt &gt; ScalarEvolution::computeConstantDifference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute <span class="doxyComputerOutput">LHS</span> - <span class="doxyComputerOutput">RHS</span> and returns the result as an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> if it is a constant, and std::nullopt if it isn't.</p>


<p>This is intended to be a cheaper version of getMinusSCEV. We can be frugal here since we just bail out of actually constructing and canonicalizing an expression in the cases where the result isn't going to be a constant.</p>


<p>Declaration at line 1301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 12058 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>, <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a1cfdf0e8d0c87a228c1f40d9bee7888b">llvm::Less</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea62b6d55816cf737bfc6f42e60df1a3f2">llvm::Mul</a> and <a href="/web-llvm/docs/api/classes/llvm/scev/#a0b675a820ab094d694d602eb16ef02e5">llvm::SCEV::operands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#abfce07b67c63527dc293c398e5629066">getMinFromExprs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a034d66b8c0aeb72ea13fd26392083446">llvm::getPointersDiff</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a6c630dc63715497e5e49ab1ca9dc6ccb">IsSimplerBaseSCEVForTarget</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a02cf9d6ac96ae27b406798da5c2eb7ea">SalvageDVI</a>.</p>

</div>
</div>

### computeExitLimitFromCond() {#a26b05f5967d446ef422d44a79334542c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution::ExitLimit ScalarEvolution::computeExitLimitFromCond (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ExitCond, bool ExitIfTrue, bool ControlsOnlyExit, bool AllowPredicates=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the number of times the backedge of the specified loop will execute if its exit condition were a conditional branch of ExitCond.</p>


<p><span class="doxyComputerOutput">ControlsOnlyExit</span> is true if ExitCond directly controls the only exit branch. In this case, we can assume that the loop exits only if the condition is true and can infer that failing to meet the condition prior to integer wraparound results in undefined behavior.</p>


<p>If <span class="doxyComputerOutput">AllowPredicates</span> is set, this call will try to use a minimal set of <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicates in order to return an exact answer.</p>


<p>Declaration at line 1167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8971 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a740a442f349b36821071c21e265e23e1">optimizeLoopExitWithUnknownExitCount</a>.</p>

</div>
</div>

### containsAddRecurrence() {#a62b3c09f031f2478ebd6c92b8c80aa2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::containsAddRecurrence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> is a scAddRecExpr or it contains scAddRecExpr.</p>


<p>The result will be cached in HasRecMap.</p>


<p>Declaration at line 527 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4500 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#affb88623037a9864e030154052747ba1">llvm::SCEVExprContains</a>.</p>

</div>
</div>

### containsErasedValue() {#af327db7ab1b1996680bd467f6ce109bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::containsErasedValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression contains a <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> that has been optimised out and is now a nullptr.</p>

<p>Declaration at line 552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 13591 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scevunknown/#a9528d1498a3a1b2f06800cabc45a7f42">llvm::SCEVUnknown::getValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#affb88623037a9864e030154052747ba1">llvm::SCEVExprContains</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a02cf9d6ac96ae27b406798da5c2eb7ea">SalvageDVI</a>.</p>

</div>
</div>

### containsUndefs() {#aa8d280cc2c5792b3144274e675e36385}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::containsUndefs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression contains an undef value.</p>

<p>Declaration at line 548 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 13582 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scevunknown/#a9528d1498a3a1b2f06800cabc45a7f42">llvm::SCEVUnknown::getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#affb88623037a9864e030154052747ba1">llvm::SCEVExprContains</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a9766c807d5c90cf726463e300d0787d8">DbgGatherSalvagableDVI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a6612c20f7ca23077265026ea4991e2b6">GetInductionVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a02cf9d6ac96ae27b406798da5c2eb7ea">SalvageDVI</a> and <a href="#aff82c03c1ce8b945170bcb1f0f624c17">verify</a>.</p>

</div>
</div>

### convertSCEVToAddRecWithPredicates() {#ad365e0d64063a233710fdba41a0da57e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEVAddRecExpr * ScalarEvolution::convertSCEVToAddRecWithPredicates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> * &gt; &amp; Preds)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tries to convert the <span class="doxyComputerOutput">S</span> expression to an AddRec expression, adding additional predicates to <span class="doxyComputerOutput">Preds</span> as required.</p>

<p>Declaration at line 1290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 14907 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a> and <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevpredicaterewriter/#aa0dfcf92c2eba1cb8bb38be9ac1e6eef">anonymous{ScalarEvolution.cpp}::SCEVPredicateRewriter::rewrite</a>.</p>

</div>
</div>

### createAddRecFromPHIWithCasts() {#ada4b4e4637302939402932b866e82cf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::pair&lt; const SCEV *, SmallVector&lt; const SCEVPredicate *, 3 &gt; &gt; &gt; ScalarEvolution::createAddRecFromPHIWithCasts (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a> * SymbolicPHI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if <span class="doxyComputerOutput">SymbolicPHI</span> can be rewritten as an AddRecExpr under some Predicates.</p>


<p>If successful return these &lt;AddRecExpr, Predicates&gt;; The function is intended to be called from PSCEV (the caller will decide whether to actually add the predicates and carry out the rewrites).</p>


<p>Declaration at line 625 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 5663 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scevunknown/#a9528d1498a3a1b2f06800cabc45a7f42">llvm::SCEVUnknown::getValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a08188d419e040050ef28ea516afebf98">isIntegerLoopHeaderPHI</a> and <a href="#a9a1917da5135c7cd0431c35b583db2aa">SCEVUnknown</a>.</p>

</div>
</div>

### dominates() {#ac7ccf429f5c75676bdacadf3c9d1c7fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::dominates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if elements that makes up the given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> dominate the specified basic block.</p>

<p>Declaration at line 1256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 14188 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#aae7c3ec1a0344306acbdc2dcb113995ea5eafe073dddfe773ed400352abe80d85">DominatesBlock</a> and <a href="#a92fb0984f10499fff4a7c9b32de2a0a6">getBlockDisposition</a>.</p>

</div>
</div>

### evaluatePredicate() {#ad80020012061cb562a6f9c9f715c2cf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; ScalarEvolution::evaluatePredicate (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the condition described by Pred, LHS, and RHS is true or false.</p>


<p>If we know it, return the evaluation of this condition. If neither is proved, return std::nullopt.</p>


<p>Declaration at line 1093 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 11064 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#aa871088f4c6eb5f26f7e0edc491b5676">llvm::ICmpInst::getInverseCmpPredicate</a> and <a href="#af74112dae88db73eb5484821b6f0fccd">isKnownPredicate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a7098623cafc05376a44b27d202b03372">countToEliminateCompares</a> and <a href="#a4bfb461a6adf8414747571a5f94a77fc">evaluatePredicateAt</a>.</p>

</div>
</div>

### evaluatePredicateAt() {#a4bfb461a6adf8414747571a5f94a77fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; ScalarEvolution::evaluatePredicateAt (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the condition described by Pred, LHS, and RHS is true or false in the given <span class="doxyComputerOutput">Context</span>.</p>


<p>If we know it, return the evaluation of this condition. If neither is proved, return std::nullopt.</p>


<p>Declaration at line 1104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 11083 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#ad80020012061cb562a6f9c9f715c2cf0">evaluatePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#aa871088f4c6eb5f26f7e0edc491b5676">llvm::ICmpInst::getInverseCmpPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a> and <a href="#aefc772d1808d513abc142b59844cfe45">isBasicBlockEntryGuardedByCond</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a8160c4d5a8fc34f6085af951980dbaa6">createReplacement</a>.</p>

</div>
</div>

### forgetAllLoops() {#ac5f5c8803494a746eb35e42f67abd0ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScalarEvolution::forgetAllLoops ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 946 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8447 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>.</p>

</div>
</div>

### forgetBlockAndLoopDispositions() {#a830ba09d5969cd66878b05c17fdf66b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScalarEvolution::forgetBlockAndLoopDispositions (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Called when the client has changed the disposition of values in a loop or block.</p>


<p>We don't have a way to invalidate per-loop/per-block dispositions. Clear and recompute is simpler.</p>


<p>Declaration at line 981 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8595 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#a9d68d0e13d6aafb4a3ab1cdb5e83ff29">getExistingSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="#a6d8769a72303e2b06ef63129cb231855">isSCEVable</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp/#a4e5b9edb51eec9dbca592075eb64dfcb">Users</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a9267cf9acba995fd1b10ae1015d048c8">llvm::breakLoopBackedge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aeabcdff1c388af9ac5a98f1ec4ba2471">deleteDeadBlocksFromLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74b422e2c15d859ba49911cc329f11d7">llvm::deleteDeadLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a5e53eb62d81882a5586764e2a9378a49">DoFlattenLoopPair</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#a9f134722dec96eeaf23085a29b5da9f7">llvm::Loop::makeLoopInvariant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsimplifycfg-cpp/#a5a5d8a7a6d46886bfb6350ed47c0f225">mergeBlocksIntoPredecessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a22d7cc599c50e811dff1546c5ccb8794">moveInstructionBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdb3eec2f46233c924c30c0838a3c8fe">llvm::peelLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#ab79f3dcf9607c6a8908cda57cc964f49">rebuildLoopAfterUnswitch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsink-cpp/#a925d8eaf1d93c7d13870ae5948c48140">sinkLoopInvariantInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a>.</p>

</div>
</div>

### forgetLcssaPhiWithNewPredecessor() {#aa6dc58a1259941c7a17142e6103d059e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScalarEvolution::forgetLcssaPhiWithNewPredecessor (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Forget LCSSA phi node V of loop L to which a new predecessor was added, such that it may no longer be trivial.</p>

<p>Declaration at line 967 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8555 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a804545e5b568edec8b970da32cd37359">forgetValue</a>, <a href="#a9d68d0e13d6aafb4a3ab1cdb5e83ff29">getExistingSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a99ab4a82c6d7373e2e367986b9527bf0">llvm::SCEVAddRecExpr::getLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a6d8769a72303e2b06ef63129cb231855">isSCEVable</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a002c7b1beef8b58691fe7aa42ffa2fe7">llvm::visitAll</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aea49493e2ae224d30cda2b3235d180b0">buildClonedLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a8478b291f8a10892334ba0bcf6a18528">cloneLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#af700561cb065af85122cd321d6c4b989">ConnectProlog</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>.</p>

</div>
</div>

### forgetLoop() {#a592bdd7731b14ff4ff5d646f6f399900}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScalarEvolution::forgetLoop (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method should be called by the client when it has changed a loop in a way that may effect <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a>'s ability to compute a trip count, or if the loop is deleted.</p>


<p>This call is potentially expensive for large loop bodies.</p>


<p>Declaration at line 952 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8494 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a94d23373106467003722f7d6c17b1528">llvm::SmallVectorImpl&lt; T &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a1be30af6ed42477abe149692b7b8a44c">PushLoopPHIs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a9267cf9acba995fd1b10ae1015d048c8">llvm::breakLoopBackedge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74b422e2c15d859ba49911cc329f11d7">llvm::deleteDeadLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a49a9acd58935033c9716f1b45d7df68a">deleteLoopIfDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a5e53eb62d81882a5586764e2a9378a49">DoFlattenLoopPair</a>, <a href="#a7d5bfa1ac3c7c096af6b26fb95cd699d">forgetTopmostLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#add9d8e7cc38ac083f42ce6873a8defdd">separateNestedLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>.</p>

</div>
</div>

### forgetLoopDispositions() {#abb9c0178bec51fd25f95b4399faa569c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScalarEvolution::forgetLoopDispositions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Called when the client has changed the disposition of values in this loop.</p>


<p>We don't have a way to invalidate per-loop dispositions. Clear and recompute is simpler.</p>


<p>Declaration at line 974 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8593 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### forgetTopmostLoop() {#a7d5bfa1ac3c7c096af6b26fb95cd699d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScalarEvolution::forgetTopmostLoop (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 958 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8536 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Reference <a href="#a592bdd7731b14ff4ff5d646f6f399900">forgetLoop</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#afdb3eec2f46233c924c30c0838a3c8fe">llvm::peelLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0083a69883e0f97e111dbff064c60f42">llvm::simplifyLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsimplifycfg-cpp/#a60e230d8627166d20b465abb6820fa80">simplifyLoopCFG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>.</p>

</div>
</div>

### forgetValue() {#a804545e5b568edec8b970da32cd37359}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScalarEvolution::forgetValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method should be called by the client when it has changed a value in a way that may effect its value, or which may disconnect it from a def-use chain linking it to a loop.</p>

<p>Declaration at line 963 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8540 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a4ebed10d3e842e81a2df6974c2fd3760">ConnectEpilog</a>, <a href="#aa6dc58a1259941c7a17142e6103d059e">forgetLcssaPhiWithNewPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a649ac561acbab510055b0e8f48ca0617">replaceLoopPHINodesWithPreheaderValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb5b48f89efd60ea799bb09abc1971ba">llvm::rewriteLoopExitValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looprotationutils-cpp/#aea660fd3de70e7854de06b7e212f0ecd">RewriteUsesOfClonedInstructions</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ad54a3c6c671e583284ff935bfde3368c">simplifyOneLoop</a>.</p>

</div>
</div>

### getAbsExpr() {#a10f946da317366de10f25a7b59db8e72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getAbsExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Op, bool IsNSW)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 634 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 3823 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">llvm::SCEV::FlagAnyWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa2f7a8775a783f7ea3ad24b3f9cb5d949">llvm::SCEV::FlagNSW</a>, <a href="#a083bb1deb1d2ba244a99ceae9e734bc1">getNegativeSCEV</a> and <a href="#a0d1d4b1c8787f465ce2c144757731f12">getSMaxExpr</a>.</p>

</div>
</div>

### getAddExpr() {#aef6d2bea715d1793e956f41ddeea2320}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getAddExpr (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; Ops, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> Flags=<a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">SCEV::FlagAnyWrap</a>, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a canonical add expression, or something simpler if possible.</p>

<p>Declaration at line 577 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 2526 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a38e964f0cadf077725453884734a6c99">llvm::APInt::abs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a25a147e07733b3dc8294661330aa68c2">AddOpsInlineThreshold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#aef5fe3787940afbf550b4cd5ae8ac03f">CollectAddOperandsWithScales</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a50c59d15149b5f4d109e99683ee68e9d">constantFoldAndGroupOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac214df91cdc242f4710ea5a93939c678">llvm::count_if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">llvm::SCEV::FlagAnyWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa2f7a8775a783f7ea3ad24b3f9cb5d949">llvm::SCEV::FlagNSW</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faafb62cd6afdc004ef6e8a1f6288eb382">llvm::SCEV::FlagNUW</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faf763167030e97d18e8f8c8ed3dba28e3">llvm::SCEV::FlagNW</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#a659b27f6737fcb7eaf333b0279da1154">getAddRecExpr</a>, <a href="#aa35959e3f6bea8e35cffcfd8659e3156">getAnyExtendExpr</a>, <a href="#a2eb94d079d8416118f4aaed865ab05d7">getConstant</a>, <a href="#a6dcfa69ce27cf214caaf50f21bfe1f2f">getEffectiveSCEVType</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a99ab4a82c6d7373e2e367986b9527bf0">llvm::SCEVAddRecExpr::getLoop</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a7275347a4dce174f4fecd548fd3255dc">llvm::SCEVNAryExpr::getNoWrapFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a689b72d735546bcbfc4b48a266503085">llvm::SCEVNAryExpr::getNumOperands</a>, <a href="#a3fbe8f529d36d76730550905d730a2a7">getOne</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#ad99e00da7acb7973ae006f5b53ce04f6">llvm::SCEVNAryExpr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a19c13fe96d59c787e900b7bbf7173263">llvm::SCEVAddRecExpr::getStart</a>, <a href="#a83c084b0947edf4ae748f9a73babf7b8">getTruncateExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a>, <a href="#a6c03d18ed744dc3b34829ec5485a68b0">getUDivExpr</a>, <a href="#a2579491850c605c8b7cf3439a907fbed">getZero</a>, <a href="#a0410d63819514e3062a73eb48a5ecc82">hasFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a81a7153270eb1fafa4502adc85f49adf">hasHugeExpression</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#aadf992d0faba329a1b5315dcde978e85">isAvailableAtLoopEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ada19a89b7c62ce0bb713a7254b002445">llvm::APInt::isSignBitSet</a>, <a href="#adfe987ba0fa56ab9ecdb606c2462b6b9">maskFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ae9b791cf02e9d499d0ac88b48023a130">MaxArithDepth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea62b6d55816cf737bfc6f42e60df1a3f2">llvm::Mul</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#ae77d0f7b81cbde08d5fd75fcf2fcf36b">llvm::SCEVNAryExpr::operands</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ad97688dfe9cd802e2a0691cbe620218a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::pop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea3a80b1a7dda48464be1849ee1fb85868">llvm::scAddExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea222c9c7b5d5e742d5d1238a3256b1ea5">llvm::scAddRecExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eafd56f054da3d1f9b827ae1003da3a38b">llvm::scMulExpr</a>, <a href="#a8fed3b807739f2ff6942c12407ab00fa">setFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ae99f51fb7f4e120a8ebeb76e3c53cf2b">StrengthenNoWrapFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aca14d9ec64ba4ab7fb2cef37c57d9ce4">llvm::APInt::ule</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a0a8a72a5038e4a261d35418751506868">calculateRtStride</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#ae8c79e4794997f6c26f54250c088e4e5">calculateSubRanges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad3c7760a82783f7d9aea9166ad4b0fcb">llvm::calculateUpperBound</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a65ab4267c6c132d06451b5d97bc9ee83">llvm::LoopVectorizationCostModel::computeMaxVF</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a5591acf152c652226d89a2b5ea436d05">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::computeSafeIterationSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a7098623cafc05376a44b27d202b03372">countToEliminateCompares</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a51c0653682103a713b0c3695aae3a1ff">createNodeForSelectViaUMinSeq</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#aa6f92c963408bac18b86bf6f0cfeb06f">llvm::SCEVAddRecExpr::evaluateAtIteration</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a1a0afc5106fca20f0a81eac37db70ab9">ExtractImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a45b1664e25bf2a7220367462f2580044">ExtractSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a202c5827957336be308d423d78ff7119">findForkedSCEVs</a>, <a href="#a24a2018b8b1e93d86324f76ce216140d">getAddExpr</a>, <a href="#ae2fb91dc219f17dfe831eef7e2b90840">getAddExpr</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ad0ad0c0f486f8ea43158a1227e610a9c">getExactSDiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a7762f1d99f297ecb6ccb4375e715c2ea">getExtendAddRecStart</a>, <a href="#a0f3039f831c483956c153ed9dee23dba">getGEPExpr</a>, <a href="#a4bab447a6422427e5fc92bbbc0c12fba">getLosslessPtrToIntExpr</a>, <a href="#a8bcb86d8d126d95b0dc05f09e8f3df96">getMinusSCEV</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/alignmentfromassumptions-cpp/#af2917523aba1c4fae828904ab0992254">getNewAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a8e3dc6f52dcd0a9cf61508d5703cbe57">llvm::SCEVAddRecExpr::getPostIncExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a359235e468f7ab6f4dccbed37c17dee1">getPreStartForExtend</a>, <a href="#a643b61ddaf17331f3ff1d4f85c7c9a23">getSignExtendExprImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdd1ebe6412f9afb43d0639420afffe0">llvm::getStartAndEndForAccess</a>, <a href="#a17e35fd9a6e590c201fd05105589ce47">getTripCountFromExitCount</a>, <a href="#a83c084b0947edf4ae748f9a73babf7b8">getTruncateExpr</a>, <a href="#a0daed958320635f1a9d440819f5bd487">getUDivCeilSCEV</a>, <a href="#a6c03d18ed744dc3b34829ec5485a68b0">getUDivExpr</a>, <a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula/#a5e104e7ceecb5b2eddfc08e66e925c09">anonymous{LoopStrengthReduce.cpp}::Formula::initialMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a50702846ece6b5c6ef8826ca0e137bc5">llvm::ARMTTIImpl::isHardwareLoopProfitable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp/#a9780ca905174166ea524a30801e7e69b">IsIncrementNSW</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp/#a202c702ced6d0c47a226adf851aba6eb">IsIncrementNUW</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#ac8cf3aa27282d640f5acbc3a676e03c5">isSafeDecreasingBound</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#adbc17f3ace73f701522eefe28104c06c">isSafeIncreasingBound</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstructure/#adc8650d6098e0949f6ecc6368c2ebb99">llvm::LoopStructure::parseLoopStructure</a>, <a href="#a1e4038e28db703c29e5e3de1549806ca">removePointerBase</a>, <a href="#a5e9fc2b9bb75a684c20ca3fa6e14b63e">SimplifyICmpOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a> and <a href="#a267fd27cb9e177fa5f48cbb8828339a1">willNotOverflow</a>.</p>

</div>
</div>

### getAddExpr() {#a24a2018b8b1e93d86324f76ce216140d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::ScalarEvolution::getAddExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> Flags=<a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">SCEV::FlagAnyWrap</a>, unsigned Depth=0)</td>
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



<p>Definition at line 580 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">llvm::SCEV::FlagAnyWrap</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### getAddExpr() {#ae2fb91dc219f17dfe831eef7e2b90840}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::ScalarEvolution::getAddExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Op0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Op2, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> Flags=<a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">SCEV::FlagAnyWrap</a>, unsigned Depth=0)</td>
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



<p>Definition at line 586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">llvm::SCEV::FlagAnyWrap</a> and <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>.</p>

</div>
</div>

### getAddRecExpr() {#a659b27f6737fcb7eaf333b0279da1154}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getAddRecExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Start, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Step, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get an add recurrence expression for the specified loop.</p>


<p>Simplify the expression as much as possible.</p>


<p>Declaration at line 610 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 3641 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faf763167030e97d18e8f8c8ed3dba28e3">llvm::SCEV::FlagNW</a>, <a href="#a659b27f6737fcb7eaf333b0279da1154">getAddRecExpr</a>, <a href="#adfe987ba0fa56ab9ecdb606c2462b6b9">maskFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ad0531a07d7868c1577980524cf2add3a">CollectSubexprs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#aa59a46776e15b1f1bd597c4e1e769f59">DoInitialMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a1a0afc5106fca20f0a81eac37db70ab9">ExtractImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a45b1664e25bf2a7220367462f2580044">ExtractSymbol</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#a659b27f6737fcb7eaf333b0279da1154">getAddRecExpr</a>, <a href="#a6df0ad4a470aaae9009ab0dc0e7b2149">getAddRecExpr</a>, <a href="#a69f32678ea46cdda0318c0be9bdb1c7e">getAddRecExpr</a>, <a href="#aa35959e3f6bea8e35cffcfd8659e3156">getAnyExtendExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ad0ad0c0f486f8ea43158a1227e610a9c">getExactSDiv</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a7e688afe102c3fa48ea49cb972a0f00c">llvm::SCEVAddRecExpr::getNumIterationsInRange</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a8e3dc6f52dcd0a9cf61508d5703cbe57">llvm::SCEVAddRecExpr::getPostIncExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a359235e468f7ab6f4dccbed37c17dee1">getPreStartForExtend</a>, <a href="#a643b61ddaf17331f3ff1d4f85c7c9a23">getSignExtendExprImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a4049f7040a4628b15f182c3c9aaf802a">llvm::SCEVAddRecExpr::getStepRecurrence</a>, <a href="#a83c084b0947edf4ae748f9a73babf7b8">getTruncateExpr</a>, <a href="#a6c03d18ed744dc3b34829ec5485a68b0">getUDivExpr</a>, <a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a>, <a href="#a8b617baf7fc5914d8a245e702ea65a7d">isLoopBackedgeGuardedByCond</a> and <a href="#a1e4038e28db703c29e5e3de1549806ca">removePointerBase</a>.</p>

</div>
</div>

### getAddRecExpr() {#a69f32678ea46cdda0318c0be9bdb1c7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getAddRecExpr (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; Operands, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get an add recurrence expression for the specified loop.</p>


<p>Simplify the expression as much as possible.</p>


<p>Declaration at line 612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 3659 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a04337b572d34ea413c35dbac5d75530b">llvm::LoopBase&lt; BlockT, LoopT &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">llvm::SCEV::FlagAnyWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faf763167030e97d18e8f8c8ed3dba28e3">llvm::SCEV::FlagNW</a>, <a href="#a659b27f6737fcb7eaf333b0279da1154">getAddRecExpr</a>, <a href="#a6dcfa69ce27cf214caaf50f21bfe1f2f">getEffectiveSCEVType</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a57994482c17097d9f936acff3a6598ac">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopDepth</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="#aadf992d0faba329a1b5315dcde978e85">isAvailableAtLoopEntry</a>, <a href="#a5a19768af81df7e5fe571bc08dcd48b3">isLoopInvariant</a>, <a href="#adfe987ba0fa56ab9ecdb606c2462b6b9">maskFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea222c9c7b5d5e742d5d1238a3256b1ea5">llvm::scAddRecExpr</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ae99f51fb7f4e120a8ebeb76e3c53cf2b">StrengthenNoWrapFlags</a>.</p>

</div>
</div>

### getAddRecExpr() {#a6df0ad4a470aaae9009ab0dc0e7b2149}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::ScalarEvolution::getAddRecExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; Operands, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> Flags)</td>
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



<p>Definition at line 614 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>References <a href="#a659b27f6737fcb7eaf333b0279da1154">getAddRecExpr</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>

</div>
</div>

### getAnyExtendExpr() {#aa35959e3f6bea8e35cffcfd8659e3156}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getAnyExtendExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Op, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getAnyExtendExpr - Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> for the given operand extended with unspecified bits out to the given type.</p>

<p>Declaration at line 576 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 2180 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faf763167030e97d18e8f8c8ed3dba28e3">llvm::SCEV::FlagNW</a>, <a href="#a659b27f6737fcb7eaf333b0279da1154">getAddRecExpr</a>, <a href="#aa35959e3f6bea8e35cffcfd8659e3156">getAnyExtendExpr</a>, <a href="#a6dcfa69ce27cf214caaf50f21bfe1f2f">getEffectiveSCEVType</a>, <a href="#ab26bea71791cf347c631d2072e41cfb5">getSignExtendExpr</a>, <a href="#a426976cfd81411f49f7e5fe77ee4e3a4">getTruncateOrNoop</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>, <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a>, <a href="#a6d745b25efdc69435508f1e936919f8b">getZeroExtendExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a6d8769a72303e2b06ef63129cb231855">isSCEVable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ae0228f64a74eb3e9fc5343b024ab9a42">getAnyExtendConsideringPostIncUses</a>, <a href="#aa35959e3f6bea8e35cffcfd8659e3156">getAnyExtendExpr</a> and <a href="#a829bd04a95f833114e36a195c7e67f0a">getNoopOrAnyExtend</a>.</p>

</div>
</div>

### getBackedgeTakenCount() {#a22d9bcbd44563106d7217f3bd9a4039e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getBackedgeTakenCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="#ace535ba3b8cc110f49b5db48a945ecef">ExitCountKind</a> Kind=<a href="#ace535ba3b8cc110f49b5db48a945ecefab1761348a1f6ac41658c85ffdd2d9361">Exact</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the specified loop has a predictable backedge-taken count, return it, otherwise return a <a href="/web-llvm/docs/api/structs/llvm/scevcouldnotcompute">SCEVCouldNotCompute</a> object.</p>


<p>The backedge-taken count is the number of times the loop header will be branched to from within the loop, assuming there are no abnormal exists like exception throws. This is one less than the trip count of the loop, since it doesn't count the first iteration, when the header is branched to from outside the loop.</p>


<p>Note that it is not valid to call this method on a loop without a loop-invariant backedge-taken count (see hasLoopInvariantBackedgeTakenCount).</p>


<p>Declaration at line 894 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8348 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#ace535ba3b8cc110f49b5db48a945ecefa707795ac384dd38bc1fc47cded39f5de">ConstantMaximum</a>, <a href="#ace535ba3b8cc110f49b5db48a945ecefab1761348a1f6ac41658c85ffdd2d9361">Exact</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#ace535ba3b8cc110f49b5db48a945ecefa007c52805d507c0cc6d53cbea782eaf4">SymbolicMaximum</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a11da3451c68e56248a152964e5915cd8">breakBackedgeIfNotTaken</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#a0e67dc55f94f7419d24a39fa5b79c42f">canFoldTermCondOfLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a65ab4267c6c132d06451b5d97bc9ee83">llvm::LoopVectorizationCostModel::computeMaxVF</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp/#a605f4ae007c6b19244c175eb1990abc1">computeTripCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a78171da3a30a449d469ccebbff57760e">getAppleRuntimeUnrollPreferences</a>, <a href="#a0182f006bb2ae6411c2111427d58f242">getConstantMaxBackedgeTakenCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a359235e468f7ab6f4dccbed37c17dee1">getPreStartForExtend</a>, <a href="#abec0c616087c002528fcf80c6583eadd">getSmallConstantTripCount</a>, <a href="#afd6dc21300db42769872f3be33ed5f2b">getSymbolicMaxBackedgeTakenCount</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a6c22989c03e43928e4b09cfa60a804f5">llvm::ARMTTIImpl::getUnrollingPreferences</a>, <a href="#a91ac801aa45c78e0d0edbc36115ef054">hasLoopInvariantBackedgeTakenCount</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a50702846ece6b5c6ef8826ca0e137bc5">llvm::ARMTTIImpl::isHardwareLoopProfitable</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a7170e1b99a9c472642f756b8cf098afa">PrintLoopInfo</a>, <a href="#aff82c03c1ce8b945170bcb1f0f624c17">verify</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a11a65ce1550eac260dca320a7028328e">verifyTripCount</a>.</p>

</div>
</div>

### getBlockDisposition() {#a92fb0984f10499fff4a7c9b32de2a0a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution::BlockDisposition ScalarEvolution::getBlockDisposition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the "disposition" of the given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> with respect to the given block.</p>

<p>Declaration at line 1252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 14114 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#aae7c3ec1a0344306acbdc2dcb113995eab597dd799bf69ea3ce93e263587ebc77">DoesNotDominateBlock</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>


<p>Referenced by <a href="#ac7ccf429f5c75676bdacadf3c9d1c7fa">dominates</a>, <a href="#ae0d036af111b8aafe90db0771b8e9ce3">properlyDominates</a> and <a href="#aff82c03c1ce8b945170bcb1f0f624c17">verify</a>.</p>

</div>
</div>

### getCastExpr() {#a48216fb35fa09727a5717cd28faca9bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getCastExpr (<a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5e">SCEVTypes</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Op, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 575 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 2162 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a4f28ee6ec3dad0938d2660c56168d91d">getPtrToIntExpr</a>, <a href="#ab26bea71791cf347c631d2072e41cfb5">getSignExtendExpr</a>, <a href="#a83c084b0947edf4ae748f9a73babf7b8">getTruncateExpr</a>, <a href="#a6d745b25efdc69435508f1e936919f8b">getZeroExtendExpr</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eae996cdd31b3e2df5dbd55ff638d2d456">llvm::scPtrToInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ead05711646a19cb20775cfbc8ef0a8c09">llvm::scSignExtend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ead3656bcc84af213cc488acb56c60de22">llvm::scTruncate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eadd4a8d5cb0d78c9be22d01e1546bafc6">llvm::scZeroExtend</a>.</p>

</div>
</div>

### getComparePredicate() {#a6fc5091677914fa41c25148564683090}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEVPredicate * ScalarEvolution::getComparePredicate (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">ICmpInst::Predicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 14741 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/scevpredicate/#a75f4943e861ac0b6d41439c7d5c07adba319b527f8f84903a6c37695faf0bc2c8">llvm::SCEVPredicate::P_Compare</a>.</p>


<p>Referenced by <a href="#a29cffc9779968caccc3dd405819e55f5">getEqualPredicate</a>.</p>

</div>
</div>

### getConstant() {#a2eb94d079d8416118f4aaed865ab05d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getConstant (<a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 561 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eabcb1f797cb330e61a5879fc260aaec5b">llvm::scConstant</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a55aceb0318074f694f763d011f71cd90">BinomialCoefficient</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a0a8a72a5038e4a261d35418751506868">calculateRtStride</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad3c7760a82783f7d9aea9166ad4b0fcb">llvm::calculateUpperBound</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5704370a1379cfd0062d47b73ba65cb0">llvm::cannotBeMaxInLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef5f1583da883ba28cb113c02d29f1d9">llvm::cannotBeMinInLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ad0531a07d7868c1577980524cf2add3a">CollectSubexprs</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a65ab4267c6c132d06451b5d97bc9ee83">llvm::LoopVectorizationCostModel::computeMaxVF</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a5591acf152c652226d89a2b5ea436d05">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::computeSafeIterationSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp/#a605f4ae007c6b19244c175eb1990abc1">computeTripCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a50c59d15149b5f4d109e99683ee68e9d">constantFoldAndGroupOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a7098623cafc05376a44b27d202b03372">countToEliminateCompares</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#aa59a46776e15b1f1bd597c4e1e769f59">DoInitialMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a54dedd456f8ee5d9877d13c9717ef94b">EvaluateConstantChrecAtConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a1a0afc5106fca20f0a81eac37db70ab9">ExtractImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a45b1664e25bf2a7220367462f2580044">ExtractSymbol</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#aa5096723795092a9d871e520e78998c0">getConstant</a>, <a href="#a4171c1656e5184034c3b4a5a85e2c4f7">getConstant</a>, <a href="#adfad3d829fd98014f225d55b4a924819">getElementCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ad0ad0c0f486f8ea43158a1227e610a9c">getExactSDiv</a>, <a href="#a8d5202095ab1b8b726dd1e9db728b997">getMinusOne</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate/#a81bada52d17e453e10221581a1bda050">anonymous{LoopStrengthReduce.cpp}::Immediate::getNegativeSCEV</a>, <a href="#a083bb1deb1d2ba244a99ceae9e734bc1">getNegativeSCEV</a>, <a href="#a7391ca35e3a370a408a9b1967b6a9832">getNotSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a7e688afe102c3fa48ea49cb972a0f00c">llvm::SCEVAddRecExpr::getNumIterationsInRange</a>, <a href="#a60be12dda0289837dae43964608cf568">getOffsetOfExpr</a>, <a href="#a3fbe8f529d36d76730550905d730a2a7">getOne</a>, <a href="#ac2cf93c95893f413324a4645fc39bb1a">getPowerOfTwo</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate/#a51c730254cd6b346d9fa4588c58a7517">anonymous{LoopStrengthReduce.cpp}::Immediate::getSCEV</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ae8a19e1b12d26ad87bc379e576ff5a7f">getSignedOverflowLimitForStep</a>, <a href="#a643b61ddaf17331f3ff1d4f85c7c9a23">getSignExtendExprImpl</a>, <a href="#ad7409ed2347009a5163f410e69a94243">getSizeOfExpr</a>, <a href="#a83c084b0947edf4ae748f9a73babf7b8">getTruncateExpr</a>, <a href="#aeca82ae7bafbb557b7026f7d035643b8">getUDivExactExpr</a>, <a href="#a6c03d18ed744dc3b34829ec5485a68b0">getUDivExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#aff0515f214b4d4e5d5a3197b11d5eacc">getUnsignedOverflowLimitForStep</a>, <a href="#a2579491850c605c8b7cf3439a907fbed">getZero</a>, <a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#ac8cf3aa27282d640f5acbc3a676e03c5">isSafeDecreasingBound</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a917578aa4ba03c192fa1c048ed3b5b00">isSafeDependenceDistance</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#adbc17f3ace73f701522eefe28104c06c">isSafeIncreasingBound</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a0b6b1ae088cb8ca3aa4f26c4098daa3d">llvm::LoopVectorizationPlanner::selectEpilogueVectorizationFactor</a>, <a href="#a5e9fc2b9bb75a684c20ca3fa6e14b63e">SimplifyICmpOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ac4e11266d1da4632ff23afce04d8499f">SolveLinEquationWithOverflow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>, <a href="#aff82c03c1ce8b945170bcb1f0f624c17">verify</a> and <a href="#a267fd27cb9e177fa5f48cbb8828339a1">willNotOverflow</a>.</p>

</div>
</div>

### getConstant() {#aa5096723795092a9d871e520e78998c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 562 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a2eb94d079d8416118f4aaed865ab05d7">getConstant</a> and <a href="#aff9e533399d91febd63fa4bfe82a42a7">getContext</a>.</p>

</div>
</div>

### getConstant() {#a4171c1656e5184034c3b4a5a85e2c4f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getConstant (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, uint64_t V, bool isSigned=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 563 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a2eb94d079d8416118f4aaed865ab05d7">getConstant</a>, <a href="#a6dcfa69ce27cf214caaf50f21bfe1f2f">getEffectiveSCEVType</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a49b2092a066cfbc24bc6925bdea9682a">isSigned</a>.</p>

</div>
</div>

### getConstantMaxBackedgeTakenCount() {#a0182f006bb2ae6411c2111427d58f242}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::ScalarEvolution::getConstantMaxBackedgeTakenCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
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

<p>When successful, this returns a <a href="/web-llvm/docs/api/classes/llvm/scevconstant">SCEVConstant</a> that is greater than or equal to (i.e.</p>


<p>a "conservative over-approximation") of the value returend by getBackedgeTakenCount. If such a value cannot be computed, it returns the <a href="/web-llvm/docs/api/structs/llvm/scevcouldnotcompute">SCEVCouldNotCompute</a> object.</p>


<p>Definition at line 907 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>References <a href="#ace535ba3b8cc110f49b5db48a945ecefa707795ac384dd38bc1fc47cded39f5de">ConstantMaximum</a> and <a href="#a22d9bcbd44563106d7217f3bd9a4039e">getBackedgeTakenCount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a11da3451c68e56248a152964e5915cd8">breakBackedgeIfNotTaken</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a7098623cafc05376a44b27d202b03372">countToEliminateCompares</a>, <a href="#a643b61ddaf17331f3ff1d4f85c7c9a23">getSignExtendExprImpl</a>, <a href="#a4c58444d7945f3d5eda96b9b4fb095b6">getSmallConstantMaxTripCount</a>, <a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeba325403d8d6430ee4a41b2cea631f5">llvm::isDereferenceableAndAlignedInLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#aef5a823f024815a31e9be15d48d037dc">isLoopDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/placesafepoints-cpp/#a2003053288ba4f0e1cd9ebf82b6a1987">mustBeFiniteCountedLoop</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a7170e1b99a9c472642f756b8cf098afa">PrintLoopInfo</a>.</p>

</div>
</div>

### getConstantMultiple() {#a18000513ba14bd153f16edd92c4505b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt ScalarEvolution::getConstantMultiple (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the max constant multiple of S.</p>

<p>Declaration at line 990 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 6393 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a765b135bf0191fca6004b4167bcfb493">getMinTrailingZeros</a>, <a href="#a8cd15ddae8837842830d97285936440a">getNonZeroConstantMultiple</a> and <a href="#aff82c03c1ce8b945170bcb1f0f624c17">verify</a>.</p>

</div>
</div>

### getContext() {#aff9e533399d91febd63fa4bfe82a42a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext &amp; llvm::ScalarEvolution::getContext ()</td>
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



<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a55aceb0318074f694f763d011f71cd90">BinomialCoefficient</a>, <a href="#aa5096723795092a9d871e520e78998c0">getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a7e688afe102c3fa48ea49cb972a0f00c">llvm::SCEVAddRecExpr::getNumIterationsInRange</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/utils/#a52c21a2bc9e5238472dabfd4183158e5">llvm::sandboxir::Utils::getPointerDiffInBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a359235e468f7ab6f4dccbed37c17dee1">getPreStartForExtend</a>, <a href="#a643b61ddaf17331f3ff1d4f85c7c9a23">getSignExtendExprImpl</a>, <a href="#a6c03d18ed744dc3b34829ec5485a68b0">getUDivExpr</a>, <a href="#a13b9eb961d35ad9ecb3b633f5703253a">getURemExpr</a>, <a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a9b6b892760677b9b11c517eb5a46557f">isAddRecSExtable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a1509f8a0c11e955037b00ce7542e24a7">isAddSExtable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a32cdb4a97c185f1acbe11f45fcc70d12">isMulSExtable</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#af25d938764b8634e70e95ff3f0c35129">llvm::VPlanTransforms::optimizeForVFAndUF</a>, <a href="#a5e9fc2b9bb75a684c20ca3fa6e14b63e">SimplifyICmpOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#aa56962cd91575fdb66d94a5e01aa9113">SolveQuadraticAddRecExact</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a8fa1050509c4edb3c4683179e01035a2">SolveQuadraticAddRecRange</a>.</p>

</div>
</div>

### getCouldNotCompute() {#aaa9b9055fd9c69fe14eb20f0d18d53d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getCouldNotCompute ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 650 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4487 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a55aceb0318074f694f763d011f71cd90">BinomialCoefficient</a>, <a href="#a4bab447a6422427e5fc92bbbc0c12fba">getLosslessPtrToIntExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp/#a56378412b516c96bbab7cd31b530e0ff">getMinAnalyzeableBackedgeTakenCount</a>, <a href="#a8bcb86d8d126d95b0dc05f09e8f3df96">getMinusSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a7e688afe102c3fa48ea49cb972a0f00c">llvm::SCEVAddRecExpr::getNumIterationsInRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a5999b0390c92ee4af2544fe9772454bf">llvm::vputils::getSCEVExprForVPValue</a>, <a href="#a29ee697fe94374eae9689321e811f5e9">getSmallConstantTripMultiple</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdd1ebe6412f9afb43d0639420afffe0">llvm::getStartAndEndForAccess</a>, <a href="#a3e3935d45c4b79b85a117b47cc1d2e61">getTripCountFromExitCount</a>, <a href="#a17e35fd9a6e590c201fd05105589ce47">getTripCountFromExitCount</a>, <a href="#afd0a71dc4e0ed5b83c50e875e6726661">isKnownViaInduction</a>, <a href="#a8b617baf7fc5914d8a245e702ea65a7d">isLoopBackedgeGuardedByCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ac4e11266d1da4632ff23afce04d8499f">SolveLinEquationWithOverflow</a>, <a href="#ae7a40d693574be8048944e80774e6c1d">SplitIntoInitAndPostInc</a> and <a href="#aff82c03c1ce8b945170bcb1f0f624c17">verify</a>.</p>

</div>
</div>

### getDataLayout() {#a057ff1d04d6303e3402647132a66ab18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout &amp; llvm::ScalarEvolution::getDataLayout ()</td>
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

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> associated with the module this <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> instance is operating on.</p>

<p>Definition at line 1275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Referenced by <a href="#a6dcfa69ce27cf214caaf50f21bfe1f2f">getEffectiveSCEVType</a>, <a href="#a4bab447a6422427e5fc92bbbc0c12fba">getLosslessPtrToIntExpr</a>, <a href="#a60be12dda0289837dae43964608cf568">getOffsetOfExpr</a>, <a href="#a5b01f1061607731f6d2953b935649570">getSizeOfExpr</a>, <a href="#a8a954b66f08640930cebdd008bc65d4d">getStoreSizeOfExpr</a>, <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a>, <a href="#a3f0118e315585ef6debe98a13336ae75">ScalarEvolution</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8413a9136fa25e3dfdebc5cb8c111002">llvm::simplifyLoopIVs</a>.</p>

</div>
</div>

### getEffectiveSCEVType() {#a6dcfa69ce27cf214caaf50f21bfe1f2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * ScalarEvolution::getEffectiveSCEVType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a type with the same bitwidth as the given type and which represents how <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> will treat the given type, for which isSCEVable must return true.</p>


<p>For pointer types, this is the pointer-sized integer type.</p>


<p>For pointer types, this is the pointer index sized integer type.</p>


<p>Declaration at line 504 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4458 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a057ff1d04d6303e3402647132a66ab18">getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a98477b82eae8654fb3e711d95ea127ec">llvm::DataLayout::getIndexType</a> and <a href="#a6d8769a72303e2b06ef63129cb231855">isSCEVable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolutionaliasanalysis-cpp/#a8a1c5d80e64a493b2bd6414551740151">canComputePointerDiff</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#aa59a46776e15b1f1bd597c4e1e769f59">DoInitialMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a202c5827957336be308d423d78ff7119">findForkedSCEVs</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#a69f32678ea46cdda0318c0be9bdb1c7e">getAddRecExpr</a>, <a href="#aa35959e3f6bea8e35cffcfd8659e3156">getAnyExtendExpr</a>, <a href="#a4171c1656e5184034c3b4a5a85e2c4f7">getConstant</a>, <a href="#ad61acd1c9fda9921a30f3ff510509873">getElementSize</a>, <a href="#a0f3039f831c483956c153ed9dee23dba">getGEPExpr</a>, <a href="#a4bab447a6422427e5fc92bbbc0c12fba">getLosslessPtrToIntExpr</a>, <a href="#ac3221ac3fcd879a1c716aa954837df79">getMinMaxExpr</a>, <a href="#a083bb1deb1d2ba244a99ceae9e734bc1">getNegativeSCEV</a>, <a href="#a7391ca35e3a370a408a9b1967b6a9832">getNotSCEV</a>, <a href="#a4976a99a4f39b4daee84f4f60319df03">getSequentialMinMaxExpr</a>, <a href="#ab26bea71791cf347c631d2072e41cfb5">getSignExtendExpr</a>, <a href="#a643b61ddaf17331f3ff1d4f85c7c9a23">getSignExtendExprImpl</a>, <a href="#a83c084b0947edf4ae748f9a73babf7b8">getTruncateExpr</a>, <a href="#a13b9eb961d35ad9ecb3b633f5703253a">getURemExpr</a>, <a href="#a6d745b25efdc69435508f1e936919f8b">getZeroExtendExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a3c81223cabf643af27adba3b3ceb680c">isExistingPhi</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a57aff0646c7151c4158d839c386332cc">visitIVCast</a>.</p>

</div>
</div>

### getElementCount() {#adfad3d829fd98014f225d55b4a924819}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getElementCount (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> EC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 568 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a2eb94d079d8416118f4aaed865ab05d7">getConstant</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a> and <a href="#abc6d543083aac1a4e161c0ed02b9b30a">getVScale</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#af25d938764b8634e70e95ff3f0c35129">llvm::VPlanTransforms::optimizeForVFAndUF</a>.</p>

</div>
</div>

### getElementSize() {#ad61acd1c9fda9921a30f3ff510509873}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getElementSize (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the size of an element read or written by Inst.</p>

<p>Declaration at line 1266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 13600 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="#a6dcfa69ce27cf214caaf50f21bfe1f2f">getEffectiveSCEVType</a>, <a href="#ad7409ed2347009a5163f410e69a94243">getSizeOfExpr</a> and <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-delinearization-cpp-/#a5c53d773e653f349a53c8796896bfaed">anonymous{Delinearization.cpp}::printDelinearization</a>.</p>

</div>
</div>

### getEqualPredicate() {#a29cffc9779968caccc3dd405819e55f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEVPredicate * ScalarEvolution::getEqualPredicate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 14735 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a6fc5091677914fa41c25148564683090">getComparePredicate</a> and <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aaec5d8efaa82dedb3a3b23f4482f31eb">llvm::replaceSymbolicStrideSCEV</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ac4e11266d1da4632ff23afce04d8499f">SolveLinEquationWithOverflow</a>.</p>

</div>
</div>

### getExistingSCEV() {#a9d68d0e13d6aafb4a3ab1cdb5e83ff29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getExistingSCEV (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an existing <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> for V if there is one, otherwise return nullptr.</p>

<p>Declaration at line 559 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4555 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a6d8769a72303e2b06ef63129cb231855">isSCEVable</a>.</p>


<p>Referenced by <a href="#a830ba09d5969cd66878b05c17fdf66b6">forgetBlockAndLoopDispositions</a>, <a href="#aa6dc58a1259941c7a17142e6103d059e">forgetLcssaPhiWithNewPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a> and <a href="#a30bd18ac905eacf3601bc6a553a9ff49">getSCEV</a>.</p>

</div>
</div>

### getExitCount() {#ab24add5df0874cdfa47b47b1d9926e9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getExitCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * ExitingBlock, <a href="#ace535ba3b8cc110f49b5db48a945ecef">ExitCountKind</a> Kind=<a href="#ace535ba3b8cc110f49b5db48a945ecefab1761348a1f6ac41658c85ffdd2d9361">Exact</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of times the backedge executes before the given exit would be taken; if not exactly computable, return <a href="/web-llvm/docs/api/structs/llvm/scevcouldnotcompute">SCEVCouldNotCompute</a>.</p>


<p>For a single exit loop, this value is equivelent to the result of getBackedgeTakenCount. The loop is guaranteed to exit (via <em>some</em> exit) before the backedge is executed (ExitCount + 1) times. Note that there is no guarantee about <em>which</em> exit is taken on the exiting iteration.</p>


<p>Declaration at line 874 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8312 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#ace535ba3b8cc110f49b5db48a945ecefa707795ac384dd38bc1fc47cded39f5de">ConstantMaximum</a>, <a href="#ace535ba3b8cc110f49b5db48a945ecefab1761348a1f6ac41658c85ffdd2d9361">Exact</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#ace535ba3b8cc110f49b5db48a945ecefa007c52805d507c0cc6d53cbea782eaf4">SymbolicMaximum</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad3c7760a82783f7d9aea9166ad4b0fcb">llvm::calculateUpperBound</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a43288882d546aed1ef0a23ffc620ddff">expandBounds</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp/#a56378412b516c96bbab7cd31b530e0ff">getMinAnalyzeableBackedgeTakenCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#a70f4b828aa79115f971f0306926dfa85">getNarrowestLatchMaxTakenCountEstimate</a>, <a href="#a2bf0e851d8784ff477a3bc34ae007ced">getSmallConstantTripCount</a>, <a href="#a187e4afb699cf8f508b886d219589c67">getSmallConstantTripMultiple</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac438183b3cdb70d2fa78265512238514">llvm::hasIterationCountInvariantInParent</a>, <a href="/web-llvm/docs/api/structs/llvm/hardwareloopinfo/#aef4460eccacc720018aa15086026c11d">llvm::HardwareLoopInfo::isHardwareLoopCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/placesafepoints-cpp/#a2003053288ba4f0e1cd9ebf82b6a1987">mustBeFiniteCountedLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a740a442f349b36821071c21e265e23e1">optimizeLoopExitWithUnknownExitCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a7170e1b99a9c472642f756b8cf098afa">PrintLoopInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb5b48f89efd60ea799bb09abc1971ba">llvm::rewriteLoopExitValues</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>.</p>

</div>
</div>

### getGEPExpr() {#a0f3039f831c483956c153ed9dee23dba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getGEPExpr (<a href="/web-llvm/docs/api/classes/llvm/gepoperator">GEPOperator</a> * GEP, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; IndexExprs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns an expression for a GEP.</p>


<p><span class="doxyComputerOutput">GEP</span> The GEP. The indices contained in the GEP itself are ignored, instead we use IndexExprs. <span class="doxyComputerOutput">IndexExprs</span> The expressions for the indices.</p>


<p>Declaration at line 632 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 3736 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">llvm::SCEV::FlagAnyWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa2f7a8775a783f7ea3ad24b3f9cb5d949">llvm::SCEV::FlagNSW</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faafb62cd6afdc004ef6e8a1f6288eb382">llvm::SCEV::FlagNUW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#a6dcfa69ce27cf214caaf50f21bfe1f2f">getEffectiveSCEVType</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>, <a href="#a60be12dda0289837dae43964608cf568">getOffsetOfExpr</a>, <a href="#a30bd18ac905eacf3601bc6a553a9ff49">getSCEV</a>, <a href="#ad7409ed2347009a5163f410e69a94243">getSizeOfExpr</a>, <a href="#af156ea88617d19e05470b8af2bb62dd9">getTruncateOrSignExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#a056eabb719f475aa4c5a7e2ba11973b9">llvm::GetElementPtrInst::getTypeAtIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#af7e1934ed72a405ef073ea5f9bbe828e">llvm::ConstantInt::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags/#a992b9efb797f896ae2cc7f1d043eb68f">llvm::GEPNoWrapFlags::hasNoUnsignedSignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags/#a9f5326edaaa9f5ad4e786d473b7c000a">llvm::GEPNoWrapFlags::hasNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a06719fdab228f099aeac0c8ee40a7e34">isKnownNonNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags/#ad41d3c975038ec4a4fc791601729124e">llvm::GEPNoWrapFlags::none</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#a8fed3b807739f2ff6942c12407ab00fa">setFlags</a>.</p>

</div>
</div>

### getLoopDisposition() {#a61f5098e98f972466ae233e6d01f9f9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution::LoopDisposition ScalarEvolution::getLoopDisposition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the "disposition" of the given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> with respect to the given loop.</p>

<p>Declaration at line 1233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 14015 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#a9f7c88892cfe1646082bf6174a4b912ca0f411f4871754e4f21f77ef949c5176e">LoopVariant</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>


<p>Referenced by <a href="#ac258f0361a1c35f5814a2b529139d15c">hasComputableLoopEvolution</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac438183b3cdb70d2fa78265512238514">llvm::hasIterationCountInvariantInParent</a>, <a href="#a5a19768af81df7e5fe571bc08dcd48b3">isLoopInvariant</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstructure/#adc8650d6098e0949f6ecc6368c2ebb99">llvm::LoopStructure::parseLoopStructure</a>, <a href="#a77b275a78beac200ef1f703d2a5fbb7d">print</a> and <a href="#aff82c03c1ce8b945170bcb1f0f624c17">verify</a>.</p>

</div>
</div>

### getLoopInvariantExitCondDuringFirstIterations() {#a1039aac093f6da8816c9dd415a711a20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ScalarEvolution::LoopInvariantPredicate &gt; ScalarEvolution::getLoopInvariantExitCondDuringFirstIterations (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * MaxIter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the result of the predicate LHS <span class="doxyComputerOutput">Pred</span> RHS is loop invariant with respect to L at given Context during at least first MaxIter iterations, return a <a href="/web-llvm/docs/api/structs/llvm/scalarevolution/loopinvariantpredicate">LoopInvariantPredicate</a> with LHS and RHS being invariants, available at L's entry.</p>


<p>Otherwise, return std::nullopt. The predicate should be the loop's exit condition.</p>


<p>Declaration at line 1213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 11255 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a094d95c92490272d4b7a6bf4ab90009d">getLoopInvariantExitCondDuringFirstIterationsImpl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea1c692ed4bf463fb08fca4d8cb8201ac0">llvm::UMin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a8160c4d5a8fc34f6085af951980dbaa6">createReplacement</a>.</p>

</div>
</div>

### getLoopInvariantExitCondDuringFirstIterationsImpl() {#a094d95c92490272d4b7a6bf4ab90009d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ScalarEvolution::LoopInvariantPredicate &gt; ScalarEvolution::getLoopInvariantExitCondDuringFirstIterationsImpl (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * MaxIter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 11275 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a33583576f220997d1c415df033559a57">llvm::SCEVAddRecExpr::evaluateAtIteration</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a99ab4a82c6d7373e2e367986b9527bf0">llvm::SCEVAddRecExpr::getLoop</a>, <a href="#a083bb1deb1d2ba244a99ceae9e734bc1">getNegativeSCEV</a>, <a href="#a3fbe8f529d36d76730550905d730a2a7">getOne</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a19c13fe96d59c787e900b7bbf7173263">llvm::SCEVAddRecExpr::getStart</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a4049f7040a4628b15f182c3c9aaf802a">llvm::SCEVAddRecExpr::getStepRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a5661ce1d8f7e67d51e712ee12ea1e29f">llvm::ICmpInst::getSwappedCmpPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a1596600146d065022af8b9c4a1d0b427">llvm::SCEVAddRecExpr::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="#aeaae2161ba70381e225ac6800af5d961">isKnownPredicateAt</a>, <a href="#a8b617baf7fc5914d8a245e702ea65a7d">isLoopBackedgeGuardedByCond</a>, <a href="#a5a19768af81df7e5fe571bc08dcd48b3">isLoopInvariant</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#ae955171baab3d9254f3ffb089c082206">llvm::ICmpInst::isRelational</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a3712279d70deeec90a93db09deb12d02">llvm::CmpInst::isSigned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#a1039aac093f6da8816c9dd415a711a20">getLoopInvariantExitCondDuringFirstIterations</a>.</p>

</div>
</div>

### getLoopInvariantPredicate() {#a741e5065c867d7dfd716eb8e16fccf12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ScalarEvolution::LoopInvariantPredicate &gt; ScalarEvolution::getLoopInvariantPredicate (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">ICmpInst::Predicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the result of the predicate LHS <span class="doxyComputerOutput">Pred</span> RHS is loop invariant with respect to L, return a <a href="/web-llvm/docs/api/structs/llvm/scalarevolution/loopinvariantpredicate">LoopInvariantPredicate</a> with LHS and RHS being invariants, available at L's entry.</p>


<p>Otherwise, return std::nullopt.</p>


<p>Declaration at line 1203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 11169 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a972c176c0737e91145863040aef6cbd9">llvm::ICmpInst::getFlippedSignednessPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa2a54b545d237ecfe450fd1292f7675e">llvm::CmpInst::getInversePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a99ab4a82c6d7373e2e367986b9527bf0">llvm::SCEVAddRecExpr::getLoop</a>, <a href="#aa92b3e6375805368f9a24cf69ce73797">getMonotonicPredicateType</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a19c13fe96d59c787e900b7bbf7173263">llvm::SCEVAddRecExpr::getStart</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a4049f7040a4628b15f182c3c9aaf802a">llvm::SCEVAddRecExpr::getStepRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a71deee7ef49ab5407b7e1aa758b6ec0a">llvm::SCEVNAryExpr::hasNoSignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a09cc70290a71475141063b6dff42a5d2">llvm::SCEVNAryExpr::hasNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a54bb7394d874cbbef1d81e6bea89d4f3">llvm::SCEVAddRecExpr::isAffine</a>, <a href="#a06719fdab228f099aeac0c8ee40a7e34">isKnownNonNegative</a>, <a href="#a5a672708a81ae8da8fb56e32638ca9b3">isKnownPositive</a>, <a href="#aeaae2161ba70381e225ac6800af5d961">isKnownPredicateAt</a>, <a href="#a8b617baf7fc5914d8a245e702ea65a7d">isLoopBackedgeGuardedByCond</a>, <a href="#a5a19768af81df7e5fe571bc08dcd48b3">isLoopInvariant</a>, <a href="#a899d8027fa6af3ca29aae6d88b6050efab8a33d7289e160c15fb2a8d84a3eade8">MonotonicallyIncreasing</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### getLosslessPtrToIntExpr() {#a4bab447a6422427e5fc92bbbc0c12fba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getLosslessPtrToIntExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Op, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 564 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 1016 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#aaa9b9055fd9c69fe14eb20f0d18d53d5">getCouldNotCompute</a>, <a href="#a057ff1d04d6303e3402647132a66ab18">getDataLayout</a>, <a href="#a6dcfa69ce27cf214caaf50f21bfe1f2f">getEffectiveSCEVType</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a7a2619d0e489a4ba9c19a0d86a041d59">llvm::DataLayout::getIntPtrType</a>, <a href="#a4bab447a6422427e5fc92bbbc0c12fba">getLosslessPtrToIntExpr</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a7275347a4dce174f4fecd548fd3255dc">llvm::SCEVNAryExpr::getNoWrapFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/scevunknown/#a94abfc169f1ff22a179d219f781fcc94">llvm::SCEVUnknown::getType</a>, <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a>, <a href="#a2579491850c605c8b7cf3439a907fbed">getZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#ae77d0f7b81cbde08d5fd75fcf2fcf36b">llvm::SCEVNAryExpr::operands</a>, <a href="#aeefacaa2eccab8db38ff9ccdad1e0b1d">registerUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/virtregmap-cpp/#a1ad52109a2ff430460c8776286b97b2e">Rewriter</a>, <a href="#a3f0118e315585ef6debe98a13336ae75">ScalarEvolution</a>, <a href="#a9a1917da5135c7cd0431c35b583db2aa">SCEVUnknown</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eae996cdd31b3e2df5dbd55ff638d2d456">llvm::scPtrToInt</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpostlegalizer-cpp/#a090736355958192cac4db32336c48bbd">visit</a>.</p>


<p>Referenced by <a href="#a4bab447a6422427e5fc92bbbc0c12fba">getLosslessPtrToIntExpr</a> and <a href="#a4f28ee6ec3dad0938d2660c56168d91d">getPtrToIntExpr</a>.</p>

</div>
</div>

### getMinMaxExpr() {#ac3221ac3fcd879a1c716aa954837df79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getMinMaxExpr (<a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5e">SCEVTypes</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 635 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 3828 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a50c59d15149b5f4d109e99683ee68e9d">constantFoldAndGroupOps</a>, <a href="#a6dcfa69ce27cf214caaf50f21bfe1f2f">getEffectiveSCEVType</a>, <a href="#ac3221ac3fcd879a1c716aa954837df79">getMinMaxExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7db94a9fa353cc7a297edd4e8601b184">llvm::isPointerTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#ae77d0f7b81cbde08d5fd75fcf2fcf36b">llvm::SCEVNAryExpr::operands</a>, <a href="#aeefacaa2eccab8db38ff9ccdad1e0b1d">registerUser</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea684b8e2484b12d494e82f7053d005754">llvm::scSMaxExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea88dad4534f471d79d0a7a094d809ef55">llvm::scSMinExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ead3d0abdf8125de904320df332dbefedb">llvm::scUMaxExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea0bf2fc9a454ce237fde0906ee24b0acc">llvm::scUMinExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a6d2ea807ef8eb6d40335d6f11edf942c">llvm::APIntOps::smax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a688eca8fbe6295f4b002f1e705d3e916">llvm::APIntOps::smin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#ad790c9bc3f8cce98f4d714041f2e4589">llvm::APIntOps::umax</a> and <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a954b694b93f10aba174cb5d0378975b2">llvm::APIntOps::umin</a>.</p>


<p>Referenced by <a href="#ac3221ac3fcd879a1c716aa954837df79">getMinMaxExpr</a>, <a href="#a7391ca35e3a370a408a9b1967b6a9832">getNotSCEV</a>, <a href="#a4976a99a4f39b4daee84f4f60319df03">getSequentialMinMaxExpr</a>, <a href="#ae4ee621c2217d36c9e9f0bd823fb3e57">getSMaxExpr</a>, <a href="#a5c1b89d3d26909f63f0243f35e3538ee">getSMinExpr</a>, <a href="#a213bb9cc661533b20602b1e035d63791">getUMaxExpr</a> and <a href="#a997ab75fad6de5dda923e63c28553834">getUMinExpr</a>.</p>

</div>
</div>

### getMinTrailingZeros() {#a765b135bf0191fca6004b4167bcfb493}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t ScalarEvolution::getMinTrailingZeros (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine the minimum number of zero bits that S is guaranteed to end in (at every loop iteration).</p>


<p>It is, at the same time, the minimum number of times S is divisible by 2. For example, given {4,+,8} it returns 2. If S is guaranteed to be 0, it returns the bitwidth of S.</p>


<p>Declaration at line 987 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 6409 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a18000513ba14bd153f16edd92c4505b2">getConstantMultiple</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a> and <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a5589e186b84c92aaeecbaeaf6253ebc8">extractConstantWithoutWrapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ab1ecca94c1ac1a616d83f565a4aeaeae">extractConstantWithoutWrapping</a>, <a href="#a83c084b0947edf4ae748f9a73babf7b8">getTruncateExpr</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ac4e11266d1da4632ff23afce04d8499f">SolveLinEquationWithOverflow</a>.</p>

</div>
</div>

### getMinusOne() {#a8d5202095ab1b8b726dd1e9db728b997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::ScalarEvolution::getMinusOne (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> for the constant -1 of a specific type.</p>

<p>Definition at line 665 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Reference <a href="#a2eb94d079d8416118f4aaed865ab05d7">getConstant</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a65ab4267c6c132d06451b5d97bc9ee83">llvm::LoopVectorizationCostModel::computeMaxVF</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a8160c4d5a8fc34f6085af951980dbaa6">createReplacement</a>, <a href="#a083bb1deb1d2ba244a99ceae9e734bc1">getNegativeSCEV</a>, <a href="#a7391ca35e3a370a408a9b1967b6a9832">getNotSCEV</a> and <a href="#a17e35fd9a6e590c201fd05105589ce47">getTripCountFromExitCount</a>.</p>

</div>
</div>

### getMinusSCEV() {#a8bcb86d8d126d95b0dc05f09e8f3df96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getMinusSCEV (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> Flags=<a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">SCEV::FlagAnyWrap</a>, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return LHS-RHS.</p>


<p>Minus is represented in <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> as A+B*-1.</p>


<p>If the LHS and RHS are pointers which don't share a common base (according to <a href="#ac276ea1907c780c43d3637ae9bd1989e">getPointerBase()</a>), this returns a <a href="/web-llvm/docs/api/structs/llvm/scevcouldnotcompute">SCEVCouldNotCompute</a>. To compute the difference between two unrelated pointers, you can explicitly convert the arguments using <a href="#a4f28ee6ec3dad0938d2660c56168d91d">getPtrToIntExpr()</a>, for pointer types that support it.</p>


<p>Declaration at line 695 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4655 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">llvm::SCEV::FlagAnyWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa2f7a8775a783f7ea3ad24b3f9cb5d949">llvm::SCEV::FlagNSW</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#aaa9b9055fd9c69fe14eb20f0d18d53d5">getCouldNotCompute</a>, <a href="#a083bb1deb1d2ba244a99ceae9e734bc1">getNegativeSCEV</a>, <a href="#ac276ea1907c780c43d3637ae9bd1989e">getPointerBase</a>, <a href="#a809289b45cd6625629f5356f70dac72d">getSignedRangeMin</a>, <a href="#a2579491850c605c8b7cf3439a907fbed">getZero</a>, <a href="#a0410d63819514e3062a73eb48a5ecc82">hasFlags</a>, <a href="#a06719fdab228f099aeac0c8ee40a7e34">isKnownNonNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a1f04e382556a817950fd0390aeaf9b0e">llvm::APInt::isMinSignedValue</a> and <a href="#a1e4038e28db703c29e5e3de1549806ca">removePointerBase</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a55aceb0318074f694f763d011f71cd90">BinomialCoefficient</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a0a8a72a5038e4a261d35418751506868">calculateRtStride</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#ae8c79e4794997f6c26f54250c088e4e5">calculateSubRanges</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp/#ac9683831e3a4c794ca05bf81af366e5e">canBeCheaplyTransformed</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a5591acf152c652226d89a2b5ea436d05">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::computeSafeIterationSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a51c0653682103a713b0c3695aae3a1ff">createNodeForSelectViaUMinSeq</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a8160c4d5a8fc34f6085af951980dbaa6">createReplacement</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a202c5827957336be308d423d78ff7119">findForkedSCEVs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/alignmentfromassumptions-cpp/#af2917523aba1c4fae828904ab0992254">getNewAlignment</a>, <a href="#a7391ca35e3a370a408a9b1967b6a9832">getNotSCEV</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ab0f2467f35df49e4d9d0c9623e2530cf">getStartForNegStride</a>, <a href="#a0daed958320635f1a9d440819f5bd487">getUDivCeilSCEV</a>, <a href="#a13b9eb961d35ad9ecb3b633f5703253a">getURemExpr</a>, <a href="/web-llvm/docs/api/structs/anonymous-looploadelimination-cpp-/storetoloadforwardingcandidate/#af7b88a2a7449e4edc75721e2ab686d9e">anonymous{LoopLoadElimination.cpp}::StoreToLoadForwardingCandidate::isDependenceDistanceOfOne</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeba325403d8d6430ee4a41b2cea631f5">llvm::isDereferenceableAndAlignedInLoop</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/ivchain/#ade9271834ae6b0312cf662fe231a75c4">anonymous{LoopStrengthReduce.cpp}::IVChain::isProfitableIncrement</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#ac8cf3aa27282d640f5acbc3a676e03c5">isSafeDecreasingBound</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a917578aa4ba03c192fa1c048ed3b5b00">isSafeDependenceDistance</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#adbc17f3ace73f701522eefe28104c06c">isSafeIncreasingBound</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstructure/#adc8650d6098e0949f6ecc6368c2ebb99">llvm::LoopStructure::parseLoopStructure</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-delinearization-cpp-/#a5c53d773e653f349a53c8796896bfaed">anonymous{Delinearization.cpp}::printDelinearization</a>, <a href="#aff82c03c1ce8b945170bcb1f0f624c17">verify</a> and <a href="#a267fd27cb9e177fa5f48cbb8828339a1">willNotOverflow</a>.</p>

</div>
</div>

### getMonotonicPredicateType() {#aa92b3e6375805368f9a24cf69ce73797}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ScalarEvolution::MonotonicPredicateType &gt; ScalarEvolution::getMonotonicPredicateType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">ICmpInst::Predicate</a> Pred)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If, for all loop invariant X, the predicate "LHS `Pred` X" is monotonically increasing or decreasing, returns Some(MonotonicallyIncreasing) and Some(MonotonicallyDecreasing) respectively.</p>


<p>If we could not prove either of these facts, returns std::nullopt.</p>


<p>Declaration at line 1187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 11106 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a7098623cafc05376a44b27d202b03372">countToEliminateCompares</a>, <a href="#a741e5065c867d7dfd716eb8e16fccf12">getLoopInvariantPredicate</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp/#aad4139f2ea3959f2e9b10ea746e1265e">isSafeToTruncateWideIVType</a>.</p>

</div>
</div>

### getMulExpr() {#ad299b0f4378f644f67168c72c763716f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getMulExpr (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; Ops, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> Flags=<a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">SCEV::FlagAnyWrap</a>, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a canonical multiply expression, or something simpler if possible.</p>

<p>Declaration at line 592 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 3106 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#aeab53b73cc54e312fd1745ebffccc7dc">Choose</a>, <a href="#a7abfe35425aead3383db5d8a311c1671">clearFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a50c59d15149b5f4d109e99683ee68e9d">constantFoldAndGroupOps</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aaca3a4d2b25c24b11179cbd01079b73c">llvm::ConstantRange::contains</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a75a63c2d772bc6e774e216072117b95a">containsConstantInAddMulChain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">llvm::SCEV::FlagAnyWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa2f7a8775a783f7ea3ad24b3f9cb5d949">llvm::SCEV::FlagNSW</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faafb62cd6afdc004ef6e8a1f6288eb382">llvm::SCEV::FlagNUW</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faf763167030e97d18e8f8c8ed3dba28e3">llvm::SCEV::FlagNW</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#a659b27f6737fcb7eaf333b0279da1154">getAddRecExpr</a>, <a href="#a2eb94d079d8416118f4aaed865ab05d7">getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a99ab4a82c6d7373e2e367986b9527bf0">llvm::SCEVAddRecExpr::getLoop</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a7275347a4dce174f4fecd548fd3255dc">llvm::SCEVNAryExpr::getNoWrapFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a689b72d735546bcbfc4b48a266503085">llvm::SCEVNAryExpr::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#ad99e00da7acb7973ae006f5b53ce04f6">llvm::SCEVNAryExpr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="#a3498df9755182f44e759fd3eeb688e9f">getSignedRange</a>, <a href="#a809289b45cd6625629f5356f70dac72d">getSignedRangeMin</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a1596600146d065022af8b9c4a1d0b427">llvm::SCEVAddRecExpr::getType</a>, <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a>, <a href="#a2579491850c605c8b7cf3439a907fbed">getZero</a>, <a href="#a0410d63819514e3062a73eb48a5ecc82">hasFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a81a7153270eb1fafa4502adc85f49adf">hasHugeExpression</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#aadf992d0faba329a1b5315dcde978e85">isAvailableAtLoopEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ace208c0bd1d845fe49f319be6a954764">llvm::ConstantRange::makeGuaranteedNoWrapRegion</a>, <a href="#adfe987ba0fa56ab9ecdb606c2462b6b9">maskFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a042ea462e73bf264fc55e6549ff94899">MaxAddRecSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ae9b791cf02e9d499d0ac88b48023a130">MaxArithDepth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea62b6d55816cf737bfc6f42e60df1a3f2">llvm::Mul</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a4b04c98df46596841460239431b2a3ea">MulOpsInlineThreshold</a>, <a href="/web-llvm/docs/api/classes/llvm/overflowingbinaryoperator/#a1d0f9e84fb5d277edd8530e7afbb674aac3172f238278728e355fc9a87c439dd5">llvm::OverflowingBinaryOperator::NoSignedWrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#a0b675a820ab094d694d602eb16ef02e5">llvm::SCEV::operands</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea222c9c7b5d5e742d5d1238a3256b1ea5">llvm::scAddRecExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eafd56f054da3d1f9b827ae1003da3a38b">llvm::scMulExpr</a>, <a href="#a8fed3b807739f2ff6942c12407ab00fa">setFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8fc529c79977cdd01e187986f960a07f">llvm::SmallVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ae99f51fb7f4e120a8ebeb76e3c53cf2b">StrengthenNoWrapFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a6c073d72f1aa69d68ffb88bf12a9c1b0">umul_ov</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a55aceb0318074f694f763d011f71cd90">BinomialCoefficient</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a0a8a72a5038e4a261d35418751506868">calculateRtStride</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#aef5fe3787940afbf550b4cd5ae8ac03f">CollectAddOperandsWithScales</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ad0531a07d7868c1577980524cf2add3a">CollectSubexprs</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a5591acf152c652226d89a2b5ea436d05">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::computeSafeIterationSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#aa59a46776e15b1f1bd597c4e1e769f59">DoInitialMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#aa6f92c963408bac18b86bf6f0cfeb06f">llvm::SCEVAddRecExpr::evaluateAtIteration</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/delinearization-cpp/#a80f3984cb81d6b8e7810c8b313739043">findArrayDimensionsRec</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a202c5827957336be308d423d78ff7119">findForkedSCEVs</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#adfad3d829fd98014f225d55b4a924819">getElementCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ad0ad0c0f486f8ea43158a1227e610a9c">getExactSDiv</a>, <a href="#a0f3039f831c483956c153ed9dee23dba">getGEPExpr</a>, <a href="#a4bab447a6422427e5fc92bbbc0c12fba">getLosslessPtrToIntExpr</a>, <a href="#a4f8f80d383339b3d40cbeffce08cb4fb">getMulExpr</a>, <a href="#a8160926d5f5c8da520ff3e01bf7cab2f">getMulExpr</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate/#a81bada52d17e453e10221581a1bda050">anonymous{LoopStrengthReduce.cpp}::Immediate::getNegativeSCEV</a>, <a href="#a083bb1deb1d2ba244a99ceae9e734bc1">getNegativeSCEV</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a7bdf6d6bf51cc1a22329cd775255d0c8">getNumBytes</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate/#a51c730254cd6b346d9fa4588c58a7517">anonymous{LoopStrengthReduce.cpp}::Immediate::getSCEV</a>, <a href="#a643b61ddaf17331f3ff1d4f85c7c9a23">getSignExtendExprImpl</a>, <a href="#ad7409ed2347009a5163f410e69a94243">getSizeOfExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ab0f2467f35df49e4d9d0c9623e2530cf">getStartForNegStride</a>, <a href="#a83c084b0947edf4ae748f9a73babf7b8">getTruncateExpr</a>, <a href="#aeca82ae7bafbb557b7026f7d035643b8">getUDivExactExpr</a>, <a href="#a6c03d18ed744dc3b34829ec5485a68b0">getUDivExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate/#a8829aacd47e6a4f3dbaf6c359d5afdfb">anonymous{LoopStrengthReduce.cpp}::Immediate::getUnknownSCEV</a>, <a href="#a13b9eb961d35ad9ecb3b633f5703253a">getURemExpr</a>, <a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a917578aa4ba03c192fa1c048ed3b5b00">isSafeDependenceDistance</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/delinearization-cpp/#a161de17b2db4a6bdb9b4ce1ea13da113">removeConstantFactors</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ac4e11266d1da4632ff23afce04d8499f">SolveLinEquationWithOverflow</a> and <a href="#a267fd27cb9e177fa5f48cbb8828339a1">willNotOverflow</a>.</p>

</div>
</div>

### getMulExpr() {#a4f8f80d383339b3d40cbeffce08cb4fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::ScalarEvolution::getMulExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> Flags=<a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">SCEV::FlagAnyWrap</a>, unsigned Depth=0)</td>
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



<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">llvm::SCEV::FlagAnyWrap</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### getMulExpr() {#a8160926d5f5c8da520ff3e01bf7cab2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::ScalarEvolution::getMulExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Op0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Op1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Op2, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> Flags=<a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">SCEV::FlagAnyWrap</a>, unsigned Depth=0)</td>
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



<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">llvm::SCEV::FlagAnyWrap</a> and <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>.</p>

</div>
</div>

### getNegativeSCEV() {#a083bb1deb1d2ba244a99ceae9e734bc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getNegativeSCEV (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * V, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> Flags=<a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">SCEV::FlagAnyWrap</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> object corresponding to -V.</p>


<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> corresponding to -V = -1*V.</p>


<p>Declaration at line 682 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4569 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a2eb94d079d8416118f4aaed865ab05d7">getConstant</a>, <a href="#a6dcfa69ce27cf214caaf50f21bfe1f2f">getEffectiveSCEVType</a>, <a href="#a8d5202095ab1b8b726dd1e9db728b997">getMinusOne</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a> and <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#aefdfcd6977f799b0f35e93d75114121c">llvm::ConstantExpr::getNeg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a5591acf152c652226d89a2b5ea436d05">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::computeSafeIterationSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ab329d363cb73927378483de592986282">detectShiftUntilZeroIdiom</a>, <a href="#a10f946da317366de10f25a7b59db8e72">getAbsExpr</a>, <a href="#a094d95c92490272d4b7a6bf4ab90009d">getLoopInvariantExitCondDuringFirstIterationsImpl</a>, <a href="#a8bcb86d8d126d95b0dc05f09e8f3df96">getMinusSCEV</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp/#a04de41a04706e275a5161b62cfe2b790">isOneDimensionalArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a917578aa4ba03c192fa1c048ed3b5b00">isSafeDependenceDistance</a>, <a href="/web-llvm/docs/api/classes/llvm/fulldependence/#aeff14a86a3c66da54488ee9634663cf7">llvm::FullDependence::normalize</a> and <a href="/web-llvm/docs/api/structs/llvm/loopstructure/#adc8650d6098e0949f6ecc6368c2ebb99">llvm::LoopStructure::parseLoopStructure</a>.</p>

</div>
</div>

### getNonZeroConstantMultiple() {#a8cd15ddae8837842830d97285936440a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt ScalarEvolution::getNonZeroConstantMultiple (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 993 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 6404 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a> and <a href="#a18000513ba14bd153f16edd92c4505b2">getConstantMultiple</a>.</p>


<p>Referenced by <a href="#a29ee697fe94374eae9689321e811f5e9">getSmallConstantTripMultiple</a>.</p>

</div>
</div>

### getNoopOrAnyExtend() {#a829bd04a95f833114e36a195c7e67f0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getNoopOrAnyExtend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * V, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> corresponding to a conversion of the input value to the specified type.</p>


<p>If the type must be extended, it is extended with unspecified bits. The conversion must not be narrowing.</p>


<p>Declaration at line 732 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4754 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa35959e3f6bea8e35cffcfd8659e3156">getAnyExtendExpr</a> and <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a>.</p>

</div>
</div>

### getNoopOrSignExtend() {#a38c440751f1bf5f19bc12b95f8f0f2a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getNoopOrSignExtend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * V, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> corresponding to a conversion of the input value to the specified type.</p>


<p>If the type must be extended, it is sign extended. The conversion must not be narrowing.</p>


<p>Declaration at line 727 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4742 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab26bea71791cf347c631d2072e41cfb5">getSignExtendExpr</a> and <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/alignmentfromassumptions-cpp/#af2917523aba1c4fae828904ab0992254">getNewAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate/#a1bb4ca5c2810fc70f58fcf2581fa5bca">llvm::SCEVWrapPredicate::implies</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a917578aa4ba03c192fa1c048ed3b5b00">isSafeDependenceDistance</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#a07d028b54d5d81f7eb266f852632d86b">NoopOrExtend</a>.</p>

</div>
</div>

### getNoopOrZeroExtend() {#a933eb87303a6ce51c8894e431fbc389b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getNoopOrZeroExtend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * V, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> corresponding to a conversion of the input value to the specified type.</p>


<p>If the type must be extended, it is zero extended. The conversion must not be narrowing.</p>


<p>Declaration at line 722 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4730 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a> and <a href="#a6d745b25efdc69435508f1e936919f8b">getZeroExtendExpr</a>.</p>


<p>Referenced by <a href="#a254484ad2e230cf0db1f2c779abfe39c">getUMaxFromMismatchedTypes</a>, <a href="#aef86e2e34d31e4595f5a442fe55ecbe9">getUMinFromMismatchedTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate/#a1bb4ca5c2810fc70f58fcf2581fa5bca">llvm::SCEVWrapPredicate::implies</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#a07d028b54d5d81f7eb266f852632d86b">NoopOrExtend</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a740a442f349b36821071c21e265e23e1">optimizeLoopExitWithUnknownExitCount</a>.</p>

</div>
</div>

### getNotSCEV() {#a7391ca35e3a370a408a9b1967b6a9832}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getNotSCEV (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> object corresponding to ~V.</p>


<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> corresponding to ~V = -1-V.</p>


<p>Declaration at line 686 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4596 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a2eb94d079d8416118f4aaed865ab05d7">getConstant</a>, <a href="#a6dcfa69ce27cf214caaf50f21bfe1f2f">getEffectiveSCEVType</a>, <a href="#ac3221ac3fcd879a1c716aa954837df79">getMinMaxExpr</a>, <a href="#a8d5202095ab1b8b726dd1e9db728b997">getMinusOne</a>, <a href="#a8bcb86d8d126d95b0dc05f09e8f3df96">getMinusSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a5b43a866f0fca605556f0f69f70c522a">llvm::ConstantExpr::getNot</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#adaa8fd1f2af30380d7080ef96b976209">MatchNotExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevminmaxexpr/#a42279dc4cc3028a574cae6d8168067b9">llvm::SCEVMinMaxExpr::negate</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#a0b675a820ab094d694d602eb16ef02e5">llvm::SCEV::operands</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a51c0653682103a713b0c3695aae3a1ff">createNodeForSelectViaUMinSeq</a>.</p>

</div>
</div>

### getOffsetOfExpr() {#a60be12dda0289837dae43964608cf568}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getOffsetOfExpr (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * IntTy, <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> * STy, unsigned FieldNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an expression for offsetof on the given field with type IntTy.</p>

<p>Declaration at line 679 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4399 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2eb94d079d8416118f4aaed865ab05d7">getConstant</a>, <a href="#a057ff1d04d6303e3402647132a66ab18">getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/structlayout/#a3932cc53acb297750961bfdaa86425bc">llvm::StructLayout::getElementOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/structlayout/#a7ca2273f2f77565f65ba98039c69b3a8">llvm::StructLayout::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a61135fb8666f0b7a37b4e1bbcf1db131">llvm::DataLayout::getStructLayout</a> and <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a9188f84e1dd67530330dcab9cae787d7">llvm::details::FixedOrScalableQuantity&lt; LeafTy, ValueTy &gt;::isScalable</a>.</p>


<p>Referenced by <a href="#a0f3039f831c483956c153ed9dee23dba">getGEPExpr</a>.</p>

</div>
</div>

### getOne() {#a3fbe8f529d36d76730550905d730a2a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::ScalarEvolution::getOne (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> for the constant 1 of a specific type.</p>

<p>Definition at line 656 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Reference <a href="#a2eb94d079d8416118f4aaed865ab05d7">getConstant</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#ae8c79e4794997f6c26f54250c088e4e5">calculateSubRanges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad3c7760a82783f7d9aea9166ad4b0fcb">llvm::calculateUpperBound</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a65ab4267c6c132d06451b5d97bc9ee83">llvm::LoopVectorizationCostModel::computeMaxVF</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a5591acf152c652226d89a2b5ea436d05">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::computeSafeIterationSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a8160c4d5a8fc34f6085af951980dbaa6">createReplacement</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#a094d95c92490272d4b7a6bf4ab90009d">getLoopInvariantExitCondDuringFirstIterationsImpl</a>, <a href="#a17e35fd9a6e590c201fd05105589ce47">getTripCountFromExitCount</a>, <a href="#a0daed958320635f1a9d440819f5bd487">getUDivCeilSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a50702846ece6b5c6ef8826ca0e137bc5">llvm::ARMTTIImpl::isHardwareLoopProfitable</a>, <a href="#a8b617baf7fc5914d8a245e702ea65a7d">isLoopBackedgeGuardedByCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#ac8cf3aa27282d640f5acbc3a676e03c5">isSafeDecreasingBound</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#adbc17f3ace73f701522eefe28104c06c">isSafeIncreasingBound</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstructure/#adc8650d6098e0949f6ecc6368c2ebb99">llvm::LoopStructure::parseLoopStructure</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aaec5d8efaa82dedb3a3b23f4482f31eb">llvm::replaceSymbolicStrideSCEV</a>.</p>

</div>
</div>

### getPointerBase() {#ac276ea1907c780c43d3637ae9bd1989e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getPointerBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transitively follow the chain of pointer-type operands until reaching a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> that does not have a single pointer operand.</p>


<p>This returns a <a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a> pointer for well-formed pointer-type expressions, but corner cases do exist.</p>


<p>Declaration at line 756 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4823 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="#a8bcb86d8d126d95b0dc05f09e8f3df96">getMinusSCEV</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-delinearization-cpp-/#a5c53d773e653f349a53c8796896bfaed">anonymous{Delinearization.cpp}::printDelinearization</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab73239c9eac42ae767c00ecc64e98dff">llvm::tryDelinearizeFixedSizeImpl</a>.</p>

</div>
</div>

### getPoisonGeneratingValues() {#ab2a2b4d8e36b1369dc9aad73feba41e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScalarEvolution::getPoisonGeneratingValues (<a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; Result, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the set of Values that, if poison, will definitively result in S being poison as well.</p>


<p>The returned set may be incomplete, i.e. there can be additional Values that also result in S being poison.</p>


<p>Declaration at line 1364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4160 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scevunknown/#a9528d1498a3a1b2f06800cabc45a7f42">llvm::SCEVUnknown::getValue</a>, <a href="#a9a1917da5135c7cd0431c35b583db2aa">SCEVUnknown</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a002c7b1beef8b58691fe7aa42ffa2fe7">llvm::visitAll</a>.</p>


<p>Referenced by <a href="#aea73058623ab7225aabe7a95068784a4">canReuseInstruction</a>.</p>

</div>
</div>

### getPowerOfTwo() {#ac2cf93c95893f413324a4645fc39bb1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::ScalarEvolution::getPowerOfTwo (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned Power)</td>
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

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> for the constant <span class="doxyComputerOutput">Power</span> of two.</p>

<p>Definition at line 659 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2eb94d079d8416118f4aaed865ab05d7">getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aec662ee6ab1490a4cabebf2812e5b9ca">llvm::APInt::getOneBitSet</a> and <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a>.</p>

</div>
</div>

### getPredicatedBackedgeTakenCount() {#a308d1a1f7212f4e433b1cd404bb92ab0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getPredicatedBackedgeTakenCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> * &gt; &amp; Predicates)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Similar to getBackedgeTakenCount, except it will add a set of <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicates to Predicates that are required to be true in order for the answer to be correct.</p>


<p>Predicates can be checked with run-time checks and can be used to perform loop versioning.</p>


<p>Declaration at line 900 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8343 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a7170e1b99a9c472642f756b8cf098afa">PrintLoopInfo</a>.</p>

</div>
</div>

### getPredicatedConstantMaxBackedgeTakenCount() {#a1d2bc453a77ebf70015aae6e3c2a56be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getPredicatedConstantMaxBackedgeTakenCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> * &gt; &amp; Predicates)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Similar to getConstantMaxBackedgeTakenCount, except it will add a set of <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicates to Predicates that are required to be true in order for the answer to be correct.</p>


<p>Predicates can be checked with run-time checks and can be used to perform loop versioning.</p>


<p>Declaration at line 915 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8366 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Referenced by <a href="#a4c58444d7945f3d5eda96b9b4fb095b6">getSmallConstantMaxTripCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeba325403d8d6430ee4a41b2cea631f5">llvm::isDereferenceableAndAlignedInLoop</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a7170e1b99a9c472642f756b8cf098afa">PrintLoopInfo</a>.</p>

</div>
</div>

### getPredicatedExitCount() {#a797d4a680e166f8cbd6b243e78514296}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getPredicatedExitCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * ExitingBlock, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> * &gt; * Predicates, <a href="#ace535ba3b8cc110f49b5db48a945ecef">ExitCountKind</a> Kind=<a href="#ace535ba3b8cc110f49b5db48a945ecefab1761348a1f6ac41658c85ffdd2d9361">Exact</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Same as above except this uses the predicated backedge taken info and may require predicates.</p>

<p>Declaration at line 880 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8326 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#ace535ba3b8cc110f49b5db48a945ecefa707795ac384dd38bc1fc47cded39f5de">ConstantMaximum</a>, <a href="#ace535ba3b8cc110f49b5db48a945ecefab1761348a1f6ac41658c85ffdd2d9361">Exact</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#ace535ba3b8cc110f49b5db48a945ecefa007c52805d507c0cc6d53cbea782eaf4">SymbolicMaximum</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a7170e1b99a9c472642f756b8cf098afa">PrintLoopInfo</a>.</p>

</div>
</div>

### getPredicatedSymbolicMaxBackedgeTakenCount() {#aead0dd455170da0b701e1e02822d3e6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getPredicatedSymbolicMaxBackedgeTakenCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> * &gt; &amp; Predicates)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Similar to getSymbolicMaxBackedgeTakenCount, except it will add a set of <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicates to Predicates that are required to be true in order for the answer to be correct.</p>


<p>Predicates can be checked with run-time checks and can be used to perform loop versioning.</p>


<p>Declaration at line 930 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8361 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a7170e1b99a9c472642f756b8cf098afa">PrintLoopInfo</a>.</p>

</div>
</div>

### getPtrToIntExpr() {#a4f28ee6ec3dad0938d2660c56168d91d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getPtrToIntExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Op, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 565 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 1140 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4bab447a6422427e5fc92bbbc0c12fba">getLosslessPtrToIntExpr</a>, <a href="#adc040502444e4504cdbc04c87e4e3055">getTruncateOrZeroExtend</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a48216fb35fa09727a5717cd28faca9bf">getCastExpr</a>.</p>

</div>
</div>

### getSCEV() {#a30bd18ac905eacf3601bc6a553a9ff49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getSCEV (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression for the full generality of the specified expression.</p>


<p>Return an existing <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> if it exists, otherwise analyze the expression and create a new one.</p>


<p>Declaration at line 556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4547 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9d68d0e13d6aafb4a3ab1cdb5e83ff29">getExistingSCEV</a> and <a href="#a6d8769a72303e2b06ef63129cb231855">isSCEVable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#ae3b1b80ef450d6706f42f3a929e51ce5">llvm::RecurrenceDescriptor::AddReductionVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeacc9805af138ccb1d72bc3000ec5013">llvm::analyzeICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a0a8a72a5038e4a261d35418751506868">calculateRtStride</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#ae8c79e4794997f6c26f54250c088e4e5">calculateSubRanges</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#a0e67dc55f94f7419d24a39fa5b79c42f">canFoldTermCondOfLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#a233a4dda6b9b4c37b906fa288ffb1807">canOverlap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargettransforminfo-cpp/#a786a99e437c617417c56b4b4678138b9">canTailPredicateLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a7098623cafc05376a44b27d202b03372">countToEliminateCompares</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a28177487ddcd7b40b1c1fde085be536a">createNodeForSelectViaUMinSeq</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a9766c807d5c90cf726463e300d0787d8">DbgGatherSalvagableDVI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a9188ba3c048bf8057af2b2ac144b9f0f">DbgRewriteSalvageableDVIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ab329d363cb73927378483de592986282">detectShiftUntilZeroIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#aa59a46776e15b1f1bd597c4e1e769f59">DoInitialMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a72c491cdf8cf0283d87008831431f917">llvm::InnerLoopVectorizer::emitIterationCountCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a202c5827957336be308d423d78ff7119">findForkedSCEVs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adf87a16be872504ce4d0ab9714dc6217">llvm::findHistogram</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a262aeb2eecfb752ae2eecb90bab7ec8a">findIVOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#adc183a6edc37f305ee9ca5ff0bc33a6e">FindLoopCounter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a14bc7872374f530d4ed193d9921825c5">genLoopLimit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a78171da3a30a449d469ccebbff57760e">getAppleRuntimeUnrollPreferences</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a4d34a6e13a44aa2f7c490762cbd3afb7">getBoundsCheckCond</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopvectorize-cpp-/generatedrtchecks/#ad7b44d9befce70f070d4355d10ffc419">anonymous{LoopVectorize.cpp}::GeneratedRTChecks::getCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a0ef183a0f2f6e678cc5f7223aca82535">getFalkorUnrollingPreferences</a>, <a href="#a0f3039f831c483956c153ed9dee23dba">getGEPExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8287f8eaeb936bb75dc1bb6ef39fbdd1">llvm::getIndexExpressionsFromGEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a6612c20f7ca23077265026ea4991e2b6">GetInductionVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/alignmentfromassumptions-cpp/#af2917523aba1c4fae828904ab0992254">getNewAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a034d66b8c0aeb72ea13fd26392083446">llvm::getPointersDiff</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#a0b1acdea3aaa8e166e24b51e22def764">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::getSCEV</a>, <a href="#ae219c962e224c9424b2ec40847496ff0">getSCEVAtScope</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a5999b0390c92ee4af2544fe9772454bf">llvm::vputils::getSCEVExprForVPValue</a>, <a href="#aa6a8e1063693697569fead19a720c43c">getStrengthenedNoWrapFlagsFromBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a4736b509c1f8cc3d4f7a44e2a4283ee0">getStrideFromPointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeba325403d8d6430ee4a41b2cea631f5">llvm::isDereferenceableAndAlignedInLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a3c81223cabf643af27adba3b3ceb680c">isExistingPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a797a268a4ac8802907a1b36ee57166e2">llvm::RecurrenceDescriptor::isFindLastIVPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a7ac21134b2aaca2a7d55f6ff9d92f5b2">isHighCostExpansion</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#acdb97daf1829f811db20dff44887fe9e">llvm::InductionDescriptor::isInductionPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo/#a7c8ab4f18a9d6acb6ad8a02fcf89c705">llvm::LoopAccessInfo::isInvariant</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationlegality/#a34f384c7ff8e4b23cc79156daf2a5c11">llvm::LoopVectorizationLegality::isInvariantAddressOfReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a7803cd22b4405090d0cb0b87d697a612">isLoopCounter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#aca012302770ad32503de5e2c62344290">isProfitableChain</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/ivchain/#ade9271834ae6b0312cf662fe231a75c4">anonymous{LoopStrengthReduce.cpp}::IVChain::isProfitableIncrement</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp/#a3e219df8a1368668aa0aac77616a4ce9">isSimpleIVUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunroll-cpp/#a8ed485ff9b2526376525b8f792929a31">loadCSE</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstructure/#adc8650d6098e0949f6ecc6368c2ebb99">llvm::LoopStructure::parseLoopStructure</a>, <a href="#a77b275a78beac200ef1f703d2a5fbb7d">print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb5b48f89efd60ea799bb09abc1971ba">llvm::rewriteLoopExitValues</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a8178cc5e49d5251d7ca3413b8a434f8f">llvm::LoopVectorizationCostModel::setVectorizedCallDecision</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a89ad752842d42f055dc74cc19303c3">llvm::storeToSameAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#aa079180719a27f78e40cfa3f4412a7b2">stripGetElementPtr</a>, <a href="#aff82c03c1ce8b945170bcb1f0f624c17">verify</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a11a65ce1550eac260dca320a7028328e">verifyTripCount</a>.</p>

</div>
</div>

### getSCEVAtScope() {#a21d6ee82eed29080d911dbb548a8bb68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getSCEVAtScope (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression for the specified value at the specified scope in the program.</p>


<p>The L value specifies a loop nest to evaluate the expression at, where null is the top-level or a specified loop is immediately inside of the loop.</p>


<p>This method can be used to compute the exit value for a variable defined in a loop by querying what the value will hold in the parent loop.</p>


<p>In the case that a relevant loop exit value cannot be computed, the original value V is returned.</p>


<p>Declaration at line 771 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 9854 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a3f16b49acc2669722d78d71f3163bbe6">computeUnrollAndJamCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a8160c4d5a8fc34f6085af951980dbaa6">createReplacement</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#a0b1acdea3aaa8e166e24b51e22def764">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::getSCEV</a>, <a href="#ae219c962e224c9424b2ec40847496ff0">getSCEVAtScope</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp/#a5a81ec50ef587462736e1ba010fab186">isInteresting</a>, <a href="#a77b275a78beac200ef1f703d2a5fbb7d">print</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-delinearization-cpp-/#a5c53d773e653f349a53c8796896bfaed">anonymous{Delinearization.cpp}::printDelinearization</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acb5b48f89efd60ea799bb09abc1971ba">llvm::rewriteLoopExitValues</a>.</p>

</div>
</div>

### getSCEVAtScope() {#ae219c962e224c9424b2ec40847496ff0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getSCEVAtScope (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is a convenience function which does getSCEVAtScope(getSCEV(V), L).</p>

<p>Declaration at line 774 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 10176 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a30bd18ac905eacf3601bc6a553a9ff49">getSCEV</a> and <a href="#a21d6ee82eed29080d911dbb548a8bb68">getSCEVAtScope</a>.</p>

</div>
</div>

### getSequentialMinMaxExpr() {#a4976a99a4f39b4daee84f4f60319df03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getSequentialMinMaxExpr (<a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5e">SCEVTypes</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 637 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4231 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a6dcfa69ce27cf214caaf50f21bfe1f2f">getEffectiveSCEVType</a>, <a href="/web-llvm/docs/api/classes/llvm/scevsequentialminmaxexpr/#aa3f8f0bd363d186089f7f5d36a317292">llvm::SCEVSequentialMinMaxExpr::getEquivalentNonSequentialSCEVType</a>, <a href="#ac3221ac3fcd879a1c716aa954837df79">getMinMaxExpr</a>, <a href="#a4976a99a4f39b4daee84f4f60319df03">getSequentialMinMaxExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="#a2579491850c605c8b7cf3439a907fbed">getZero</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71a4a4e0f6178682ef05a0d85891e5a9">llvm::impliesPoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7db94a9fa353cc7a297edd4e8601b184">llvm::isPointerTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#aeefacaa2eccab8db38ff9ccdad1e0b1d">registerUser</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea376414ac1f3ac8cb449fd5167a2db091">llvm::scSequentialUMinExpr</a>.</p>


<p>Referenced by <a href="#a4976a99a4f39b4daee84f4f60319df03">getSequentialMinMaxExpr</a> and <a href="#a997ab75fad6de5dda923e63c28553834">getUMinExpr</a>.</p>

</div>
</div>

### getSignedRange() {#a3498df9755182f44e759fd3eeb688e9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange llvm::ScalarEvolution::getSignedRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
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

<p>Determine the signed range for a particular <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>.</p>


<p>NOTE: This returns a copy of the reference returned by getRangeRef.</p>


<p>Definition at line 1013 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Referenced by <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>, <a href="#a643b61ddaf17331f3ff1d4f85c7c9a23">getSignExtendExprImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a797a268a4ac8802907a1b36ee57166e2">llvm::RecurrenceDescriptor::isFindLastIVPattern</a>, <a href="#a77b275a78beac200ef1f703d2a5fbb7d">print</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ae99f51fb7f4e120a8ebeb76e3c53cf2b">StrengthenNoWrapFlags</a>.</p>

</div>
</div>

### getSignedRangeMax() {#afee50be11e579d3c510e73df2a21cb88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::ScalarEvolution::getSignedRangeMax (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
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

<p>Determine the max of the signed range for a particular <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>.</p>

<p>Definition at line 1023 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ae8a19e1b12d26ad87bc379e576ff5a7f">getSignedOverflowLimitForStep</a>, <a href="#a1b9806d21518ef7fb4d5c4299e21411f">isKnownNegative</a>, <a href="#a121ee24f11c464f3b3197cac87b0980e">isKnownNonPositive</a> and <a href="#a5e9fc2b9bb75a684c20ca3fa6e14b63e">SimplifyICmpOperands</a>.</p>

</div>
</div>

### getSignedRangeMin() {#a809289b45cd6625629f5356f70dac72d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::ScalarEvolution::getSignedRangeMin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
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

<p>Determine the min of the signed range for a particular <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>.</p>

<p>Definition at line 1018 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Referenced by <a href="#a8bcb86d8d126d95b0dc05f09e8f3df96">getMinusSCEV</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ae8a19e1b12d26ad87bc379e576ff5a7f">getSignedOverflowLimitForStep</a>, <a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a>, <a href="#a06719fdab228f099aeac0c8ee40a7e34">isKnownNonNegative</a>, <a href="#a5a672708a81ae8da8fb56e32638ca9b3">isKnownPositive</a> and <a href="#a5e9fc2b9bb75a684c20ca3fa6e14b63e">SimplifyICmpOperands</a>.</p>

</div>
</div>

### getSignExtendExpr() {#ab26bea71791cf347c631d2072e41cfb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getSignExtendExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Op, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 572 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 1900 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="#a6dcfa69ce27cf214caaf50f21bfe1f2f">getEffectiveSCEVType</a>, <a href="#a643b61ddaf17331f3ff1d4f85c7c9a23">getSignExtendExprImpl</a>, <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a1fb622dcdf9f011b6776856b103e358e">insertFoldCacheEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a6d8769a72303e2b06ef63129cb231855">isSCEVable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ead05711646a19cb20775cfbc8ef0a8c09">llvm::scSignExtend</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a5591acf152c652226d89a2b5ea436d05">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::computeSafeIterationSpace</a>, <a href="#aa35959e3f6bea8e35cffcfd8659e3156">getAnyExtendExpr</a>, <a href="#a48216fb35fa09727a5717cd28faca9bf">getCastExpr</a>, <a href="#a38c440751f1bf5f19bc12b95f8f0f2a6">getNoopOrSignExtend</a>, <a href="#a643b61ddaf17331f3ff1d4f85c7c9a23">getSignExtendExprImpl</a>, <a href="#af156ea88617d19e05470b8af2bb62dd9">getTruncateOrSignExtend</a>, <a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a9b6b892760677b9b11c517eb5a46557f">isAddRecSExtable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a1509f8a0c11e955037b00ce7542e24a7">isAddSExtable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp/#a9780ca905174166ea524a30801e7e69b">IsIncrementNSW</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a32cdb4a97c185f1acbe11f45fcc70d12">isMulSExtable</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstructure/#adc8650d6098e0949f6ecc6368c2ebb99">llvm::LoopStructure::parseLoopStructure</a> and <a href="#a267fd27cb9e177fa5f48cbb8828339a1">willNotOverflow</a>.</p>

</div>
</div>

### getSignExtendExprImpl() {#a643b61ddaf17331f3ff1d4f85c7c9a23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getSignExtendExprImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Op, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 573 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 1919 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aaca3a4d2b25c24b11179cbd01079b73c">llvm::ConstantRange::contains</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ab1ecca94c1ac1a616d83f565a4aeaeae">extractConstantWithoutWrapping</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">llvm::SCEV::FlagAnyWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa2f7a8775a783f7ea3ad24b3f9cb5d949">llvm::SCEV::FlagNSW</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faafb62cd6afdc004ef6e8a1f6288eb382">llvm::SCEV::FlagNUW</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faf763167030e97d18e8f8c8ed3dba28e3">llvm::SCEV::FlagNW</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#a659b27f6737fcb7eaf333b0279da1154">getAddRecExpr</a>, <a href="#a2eb94d079d8416118f4aaed865ab05d7">getConstant</a>, <a href="#a0182f006bb2ae6411c2111427d58f242">getConstantMaxBackedgeTakenCount</a>, <a href="#aff9e533399d91febd63fa4bfe82a42a7">getContext</a>, <a href="#a6dcfa69ce27cf214caaf50f21bfe1f2f">getEffectiveSCEVType</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a7762f1d99f297ecb6ccb4375e715c2ea">getExtendAddRecStart</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>, <a href="#a3498df9755182f44e759fd3eeb688e9f">getSignedRange</a>, <a href="#ab26bea71791cf347c631d2072e41cfb5">getSignExtendExpr</a>, <a href="#a0d1d4b1c8787f465ce2c144757731f12">getSMaxExpr</a>, <a href="#a223d678f85ac9b7f03157edb6111e42e">getSMinExpr</a>, <a href="#af156ea88617d19e05470b8af2bb62dd9">getTruncateOrSignExtend</a>, <a href="#adc040502444e4504cdbc04c87e4e3055">getTruncateOrZeroExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>, <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a>, <a href="#a6d745b25efdc69435508f1e936919f8b">getZeroExtendExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a06719fdab228f099aeac0c8ee40a7e34">isKnownNonNegative</a>, <a href="#a6d8769a72303e2b06ef63129cb231855">isSCEVable</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a58f74b4f08e8ade02bb12bfff74b0c50">MaxCastDepth</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#aeefacaa2eccab8db38ff9ccdad1e0b1d">registerUser</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ead05711646a19cb20775cfbc8ef0a8c09">llvm::scSignExtend</a>, <a href="#a248dea99ef1d5a864269ac3a98014b37">setNoWrapFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aebc1456c2e4f9d6d95aa0b089b3df535">llvm::ConstantRange::sextOrTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a9c8872e25eeddcc398a41e003e7c3f55">llvm::ConstantRange::signExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a2bc441c8fe8dfeea5471f11d2d823ec1">llvm::ConstantRange::truncate</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#ab26bea71791cf347c631d2072e41cfb5">getSignExtendExpr</a>.</p>

</div>
</div>

### getSizeOfExpr() {#ad7409ed2347009a5163f410e69a94243}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getSizeOfExpr (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * IntTy, <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an expression for a <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a>.</p>

<p>Declaration at line 670 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4384 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a2eb94d079d8416118f4aaed865ab05d7">getConstant</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>, <a href="#abc6d543083aac1a4e161c0ed02b9b30a">getVScale</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a202c5827957336be308d423d78ff7119">findForkedSCEVs</a>, <a href="#ad61acd1c9fda9921a30f3ff510509873">getElementSize</a>, <a href="#a0f3039f831c483956c153ed9dee23dba">getGEPExpr</a>, <a href="#a5b01f1061607731f6d2953b935649570">getSizeOfExpr</a> and <a href="#a8a954b66f08640930cebdd008bc65d4d">getStoreSizeOfExpr</a>.</p>

</div>
</div>

### getSizeOfExpr() {#a5b01f1061607731f6d2953b935649570}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getSizeOfExpr (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * IntTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * AllocTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an expression for the alloc size of AllocTy that is type IntTy.</p>

<p>Declaration at line 673 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4391 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a057ff1d04d6303e3402647132a66ab18">getDataLayout</a> and <a href="#ad7409ed2347009a5163f410e69a94243">getSizeOfExpr</a>.</p>

</div>
</div>

### getSmallConstantMaxTripCount() {#a4c58444d7945f3d5eda96b9b4fb095b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ScalarEvolution::getSmallConstantMaxTripCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> * &gt; * Predicates=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the upper bound of the loop trip count as a normal unsigned value.</p>


<p>Returns 0 if the trip count is unknown, not constant or requires <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicates and <span class="doxyComputerOutput">Predicates</span> is nullptr.</p>


<p>Declaration at line 828 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8251 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a0182f006bb2ae6411c2111427d58f242">getConstantMaxBackedgeTakenCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a0bf0cf316748d2fb01a45268ffc10a02">getConstantTripCount</a> and <a href="#a1d2bc453a77ebf70015aae6e3c2a56be">getPredicatedConstantMaxBackedgeTakenCount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#a0e67dc55f94f7419d24a39fa5b79c42f">canFoldTermCondOfLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a78171da3a30a449d469ccebbff57760e">getAppleRuntimeUnrollPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonttiimpl/#a9b9400acc54f0441d15d8bda0d27caf7">llvm::HexagonTTIImpl::getPeelingPreferences</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#aaec3f462db4f2df25d3caa667a10d413">anonymous{AttributorAttributes.cpp}::mayContainUnboundedCycle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#ab6df82212b20d28e61ff9417744420ff">tryToUnrollLoop</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>.</p>

</div>
</div>

### getSmallConstantTripCount() {#abec0c616087c002528fcf80c6583eadd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ScalarEvolution::getSmallConstantTripCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the exact trip count of the loop if we can compute it, and the result is a small constant.</p>


<p>'0' is used to represent an unknown or non-constant trip count. Note that a trip count is simply one more than the backedge taken count for the loop.</p>


<p>Declaration at line 810 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8235 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ace535ba3b8cc110f49b5db48a945ecefab1761348a1f6ac41658c85ffdd2d9361">Exact</a>, <a href="#a22d9bcbd44563106d7217f3bd9a4039e">getBackedgeTakenCount</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a0bf0cf316748d2fb01a45268ffc10a02">getConstantTripCount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a65ab4267c6c132d06451b5d97bc9ee83">llvm::LoopVectorizationCostModel::computeMaxVF</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonttiimpl/#a9b9400acc54f0441d15d8bda0d27caf7">llvm::HexagonTTIImpl::getPeelingPreferences</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a84375e6536d9214c7895013078055aff">getSmallBestKnownTC</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#ae46906a076a2ec35cf6a38e433b48219">llvm::PPCTTIImpl::isHardwareLoopProfitable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a671b52d0f3cddc29dcd1f5acfcd1e664">tryToUnrollAndJamLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#ab6df82212b20d28e61ff9417744420ff">tryToUnrollLoop</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>.</p>

</div>
</div>

### getSmallConstantTripCount() {#a2bf0e851d8784ff477a3bc34ae007ced}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ScalarEvolution::getSmallConstantTripCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * ExitingBlock)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the exact trip count for this loop if we exit through ExitingBlock.</p>


<p>'0' is used to represent an unknown or non-constant trip count. Note that a trip count is simply one more than the backedge taken count for the same exit. This "trip count" assumes that control exits via ExitingBlock. More precisely, it is the number of times that control will reach ExitingBlock before taking the branch. For loops with multiple exits, it may not be the number times that the loop header executes if the loop exits prematurely via another branch.</p>


<p>Declaration at line 821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8241 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a0bf0cf316748d2fb01a45268ffc10a02">getConstantTripCount</a> and <a href="#ab24add5df0874cdfa47b47b1d9926e9e">getExitCount</a>.</p>

</div>
</div>

### getSmallConstantTripMultiple() {#a29ee697fe94374eae9689321e811f5e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ScalarEvolution::getSmallConstantTripMultiple (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * ExitCount)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the largest constant divisor of the trip count as a normal unsigned value, if possible.</p>


<p>This means that the actual trip count is always a multiple of the returned value. Returns 1 if the trip count is unknown or not guaranteed to be the multiple of a constant., Will also return 1 if the trip count is very large (&gt;= 2^32). Note that the argument is an exit count for loop L, NOT a trip count.</p>


<p>Declaration at line 838 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8274 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#ad146072469181af4ccb7ef03c28999ba">applyLoopGuards</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a9a99431f0828d0222c617eb876bc5d34">llvm::APInt::countTrailingZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a3015474e70e59c0a3ed4f9f0e8644b75">llvm::APInt::getActiveBits</a>, <a href="#aaa9b9055fd9c69fe14eb20f0d18d53d5">getCouldNotCompute</a>, <a href="#a8cd15ddae8837842830d97285936440a">getNonZeroConstantMultiple</a>, <a href="#a3e3935d45c4b79b85a117b47cc1d2e61">getTripCountFromExitCount</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a2ed912a28808268e35bd58e8f11251aa">llvm::APInt::zextOrTrunc</a>.</p>


<p>Referenced by <a href="#a679b9639c06fbd0a28b01cdea9b5d639">getSmallConstantTripMultiple</a>, <a href="#a187e4afb699cf8f508b886d219589c67">getSmallConstantTripMultiple</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a7170e1b99a9c472642f756b8cf098afa">PrintLoopInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a671b52d0f3cddc29dcd1f5acfcd1e664">tryToUnrollAndJamLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#ab6df82212b20d28e61ff9417744420ff">tryToUnrollLoop</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>.</p>

</div>
</div>

### getSmallConstantTripMultiple() {#a679b9639c06fbd0a28b01cdea9b5d639}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ScalarEvolution::getSmallConstantTripMultiple (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the largest constant divisor of the trip count of the loop.</p>


<p>Will return 1 if no trip count could be computed, or if a divisor could not be found.</p>


<p>Declaration at line 844 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8260 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Reference <a href="#a29ee697fe94374eae9689321e811f5e9">getSmallConstantTripMultiple</a>.</p>

</div>
</div>

### getSmallConstantTripMultiple() {#a187e4afb699cf8f508b886d219589c67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ScalarEvolution::getSmallConstantTripMultiple (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * ExitingBlock)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the largest constant divisor of the trip count of this loop as a normal unsigned value, if possible.</p>


<p>This means that the actual trip count is always a multiple of the returned value (don't forget the trip count could very well be zero as well!). As explained in the comments for getSmallConstantTripCount, this assumes that control exits the loop via ExitingBlock.</p>


<p>This means that the actual trip count is always a multiple of the returned value (don't forget the trip count could very well be zero as well!).</p>


<p>Returns 1 if the trip count is unknown or not guaranteed to be the multiple of a constant (which is also the case if the trip count is simply constant, use getSmallConstantTripCount for that case), Will also return 1 if the trip count is very large (&gt;= 2^32).</p>


<p>As explained in the comments for getSmallConstantTripCount, this assumes that control exits the loop via ExitingBlock.</p>


<p>Declaration at line 852 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8303 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab24add5df0874cdfa47b47b1d9926e9e">getExitCount</a> and <a href="#a29ee697fe94374eae9689321e811f5e9">getSmallConstantTripMultiple</a>.</p>

</div>
</div>

### getSMaxExpr() {#a0d1d4b1c8787f465ce2c144757731f12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getSMaxExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 639 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4343 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a> and <a href="#a0d1d4b1c8787f465ce2c144757731f12">getSMaxExpr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#ae8c79e4794997f6c26f54250c088e4e5">calculateSubRanges</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a5591acf152c652226d89a2b5ea436d05">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::computeSafeIterationSpace</a>, <a href="#a10f946da317366de10f25a7b59db8e72">getAbsExpr</a>, <a href="#a643b61ddaf17331f3ff1d4f85c7c9a23">getSignExtendExprImpl</a>, <a href="#a0d1d4b1c8787f465ce2c144757731f12">getSMaxExpr</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#a446af5357a9d75c1c6230bb23792a9f8">IntersectSignedRange</a>.</p>

</div>
</div>

### getSMaxExpr() {#ae4ee621c2217d36c9e9f0bd823fb3e57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getSMaxExpr (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 640 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4348 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#ac3221ac3fcd879a1c716aa954837df79">getMinMaxExpr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea684b8e2484b12d494e82f7053d005754">llvm::scSMaxExpr</a>.</p>

</div>
</div>

### getSMinExpr() {#a223d678f85ac9b7f03157edb6111e42e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getSMinExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4361 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a> and <a href="#a223d678f85ac9b7f03157edb6111e42e">getSMinExpr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#ae8c79e4794997f6c26f54250c088e4e5">calculateSubRanges</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a5591acf152c652226d89a2b5ea436d05">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::computeSafeIterationSpace</a>, <a href="#a643b61ddaf17331f3ff1d4f85c7c9a23">getSignExtendExprImpl</a>, <a href="#a223d678f85ac9b7f03157edb6111e42e">getSMinExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#a446af5357a9d75c1c6230bb23792a9f8">IntersectSignedRange</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a>.</p>

</div>
</div>

### getSMinExpr() {#a5c1b89d3d26909f63f0243f35e3538ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getSMinExpr (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 644 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4367 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#ac3221ac3fcd879a1c716aa954837df79">getMinMaxExpr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea88dad4534f471d79d0a7a094d809ef55">llvm::scSMinExpr</a>.</p>

</div>
</div>

### getStoreSizeOfExpr() {#a8a954b66f08640930cebdd008bc65d4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getStoreSizeOfExpr (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * IntTy, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * StoreTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an expression for the store size of StoreTy that is type IntTy.</p>

<p>Declaration at line 676 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4395 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a057ff1d04d6303e3402647132a66ab18">getDataLayout</a> and <a href="#ad7409ed2347009a5163f410e69a94243">getSizeOfExpr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#afdd1ebe6412f9afb43d0639420afffe0">llvm::getStartAndEndForAccess</a>.</p>

</div>
</div>

### getStrengthenedNoWrapFlagsFromBinOp() {#aa6a8e1063693697569fead19a720c43c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; SCEV::NoWrapFlags &gt; ScalarEvolution::getStrengthenedNoWrapFlagsFromBinOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/overflowingbinaryoperator">OverflowingBinaryOperator</a> * OBO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse NSW/NUW flags from add/sub/mul IR binary operation <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> into <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> no-wrap flags, and deduce flag[s] that aren't known yet.</p>


<p>Does not mutate the original instruction. Returns std::nullopt if it could not deduce more precise flags than the instruction already has, otherwise returns proven flags.</p>


<p>Declaration at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 2391 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">llvm::SCEV::FlagAnyWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa2f7a8775a783f7ea3ad24b3f9cb5d949">llvm::SCEV::FlagNSW</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faafb62cd6afdc004ef6e8a1f6288eb382">llvm::SCEV::FlagNUW</a>, <a href="/web-llvm/docs/api/classes/llvm/operator/#aca4ffddc11c10477a4a76ada6fd5da46">llvm::Operator::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="#a30bd18ac905eacf3601bc6a553a9ff49">getSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/overflowingbinaryoperator/#a7876c618729b8764493aa340b53b574f">llvm::OverflowingBinaryOperator::hasNoSignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/overflowingbinaryoperator/#a95474ea140862464db7ea0580f01eae9">llvm::OverflowingBinaryOperator::hasNoUnsignedWrap</a>, <a href="#a8fed3b807739f2ff6942c12407ab00fa">setFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a9081f79e15a055f4314b7f24e6eae17d">UseContextForNoWrapFlagInference</a> and <a href="#a267fd27cb9e177fa5f48cbb8828339a1">willNotOverflow</a>.</p>

</div>
</div>

### getSymbolicMaxBackedgeTakenCount() {#afd6dc21300db42769872f3be33ed5f2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::ScalarEvolution::getSymbolicMaxBackedgeTakenCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
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

<p>When successful, this returns a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> that is greater than or equal to (i.e.</p>


<p>a "conservative over-approximation") of the value returend by getBackedgeTakenCount. If such a value cannot be computed, it returns the <a href="/web-llvm/docs/api/structs/llvm/scevcouldnotcompute">SCEVCouldNotCompute</a> object.</p>


<p>Definition at line 922 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>References <a href="#a22d9bcbd44563106d7217f3bd9a4039e">getBackedgeTakenCount</a> and <a href="#ace535ba3b8cc110f49b5db48a945ecefa007c52805d507c0cc6d53cbea782eaf4">SymbolicMaximum</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#a70f4b828aa79115f971f0306926dfa85">getNarrowestLatchMaxTakenCountEstimate</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a7170e1b99a9c472642f756b8cf098afa">PrintLoopInfo</a>.</p>

</div>
</div>

### getTripCountFromExitCount() {#a3e3935d45c4b79b85a117b47cc1d2e61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getTripCountFromExitCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * ExitCount)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A version of getTripCountFromExitCount below which always picks an evaluation type which can not result in overflow.</p>

<p>Declaration at line 794 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8180 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aaa9b9055fd9c69fe14eb20f0d18d53d5">getCouldNotCompute</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#acaf8e4c3e40e01e848c1fad5f05b81cd">llvm::Type::getIntNTy</a>, <a href="#a3e3935d45c4b79b85a117b47cc1d2e61">getTripCountFromExitCount</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp/#a605f4ae007c6b19244c175eb1990abc1">computeTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a5a956378c8f267d4b2afc6e036a08d42">llvm::VPlan::createInitialVPlan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a7bdf6d6bf51cc1a22329cd775255d0c8">getNumBytes</a>, <a href="#a29ee697fe94374eae9689321e811f5e9">getSmallConstantTripMultiple</a>, <a href="#a3e3935d45c4b79b85a117b47cc1d2e61">getTripCountFromExitCount</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a11a65ce1550eac260dca320a7028328e">verifyTripCount</a>.</p>

</div>
</div>

### getTripCountFromExitCount() {#a17e35fd9a6e590c201fd05105589ce47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getTripCountFromExitCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * ExitCount, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * EvalTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert from an "exit count" (i.e.</p>


<p>"backedge taken count") to a "trip
count". A "trip count" is the number of times the header of the loop will execute if an exit is taken after the specified number of backedges have been taken. (e.g. TripCount = ExitCount + 1). Note that the expression can overflow if ExitCount = UINT_MAX. If EvalTy is not wide enough to hold the result without overflow, result unsigned wraps with 2s-complement semantics. ex: EC = 255 (i8), TC = 0 (i8)</p>


<p>Declaration at line 803 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8191 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aaca3a4d2b25c24b11179cbd01079b73c">llvm::ConstantRange::contains</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#aaa9b9055fd9c69fe14eb20f0d18d53d5">getCouldNotCompute</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a331d69b5f93e47e7c596062b77dd5913">llvm::APInt::getMaxValue</a>, <a href="#a8d5202095ab1b8b726dd1e9db728b997">getMinusOne</a>, <a href="#a3fbe8f529d36d76730550905d730a2a7">getOne</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="#adc040502444e4504cdbc04c87e4e3055">getTruncateOrZeroExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>, <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a>, <a href="#a6d745b25efdc69435508f1e936919f8b">getZeroExtendExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a1e9fadcd7d58712f2a36fb635e35d2f5">isLoopEntryGuardedByCond</a>.</p>

</div>
</div>

### getTruncateExpr() {#a83c084b0947edf4ae748f9a73babf7b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getTruncateExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Op, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 566 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 1150 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">llvm::SCEV::FlagAnyWrap</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#a659b27f6737fcb7eaf333b0279da1154">getAddRecExpr</a>, <a href="#a2eb94d079d8416118f4aaed865ab05d7">getConstant</a>, <a href="#a6dcfa69ce27cf214caaf50f21bfe1f2f">getEffectiveSCEVType</a>, <a href="#a765b135bf0191fca6004b4167bcfb493">getMinTrailingZeros</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#af238147cf5453729781a0fcc7322e1c6">llvm::ConstantExpr::getTrunc</a>, <a href="#a83c084b0947edf4ae748f9a73babf7b8">getTruncateExpr</a>, <a href="#af156ea88617d19e05470b8af2bb62dd9">getTruncateOrSignExtend</a>, <a href="#adc040502444e4504cdbc04c87e4e3055">getTruncateOrZeroExtend</a>, <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a>, <a href="#a2579491850c605c8b7cf3439a907fbed">getZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a6d8769a72303e2b06ef63129cb231855">isSCEVable</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a58f74b4f08e8ade02bb12bfff74b0c50">MaxCastDepth</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#aeefacaa2eccab8db38ff9ccdad1e0b1d">registerUser</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ead3656bcc84af213cc488acb56c60de22">llvm::scTruncate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a5591acf152c652226d89a2b5ea436d05">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::computeSafeIterationSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a8160c4d5a8fc34f6085af951980dbaa6">createReplacement</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp/#a87a3062e354c5f250442f6ec5b819674">generateLoopLatchCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a14bc7872374f530d4ed193d9921825c5">genLoopLimit</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#a48216fb35fa09727a5717cd28faca9bf">getCastExpr</a>, <a href="#a83c084b0947edf4ae748f9a73babf7b8">getTruncateExpr</a>, <a href="#a426976cfd81411f49f7e5fe77ee4e3a4">getTruncateOrNoop</a>, <a href="#af156ea88617d19e05470b8af2bb62dd9">getTruncateOrSignExtend</a>, <a href="#adc040502444e4504cdbc04c87e4e3055">getTruncateOrZeroExtend</a>, <a href="#a13b9eb961d35ad9ecb3b633f5703253a">getURemExpr</a> and <a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a>.</p>

</div>
</div>

### getTruncateOrNoop() {#a426976cfd81411f49f7e5fe77ee4e3a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getTruncateOrNoop (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * V, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> corresponding to a conversion of the input value to the specified type.</p>


<p>The conversion must not be widening.</p>


<p>Declaration at line 736 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4766 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a83c084b0947edf4ae748f9a73babf7b8">getTruncateExpr</a> and <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp/#ac9683831e3a4c794ca05bf81af366e5e">canBeCheaplyTransformed</a> and <a href="#aa35959e3f6bea8e35cffcfd8659e3156">getAnyExtendExpr</a>.</p>

</div>
</div>

### getTruncateOrSignExtend() {#af156ea88617d19e05470b8af2bb62dd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getTruncateOrSignExtend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * V, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> corresponding to a conversion of the input value to the specified type.</p>


<p>If the type must be extended, it is sign extended.</p>


<p>Declaration at line 716 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4717 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="#ab26bea71791cf347c631d2072e41cfb5">getSignExtendExpr</a>, <a href="#a83c084b0947edf4ae748f9a73babf7b8">getTruncateExpr</a> and <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a202c5827957336be308d423d78ff7119">findForkedSCEVs</a>, <a href="#a0f3039f831c483956c153ed9dee23dba">getGEPExpr</a>, <a href="#a643b61ddaf17331f3ff1d4f85c7c9a23">getSignExtendExprImpl</a> and <a href="#a83c084b0947edf4ae748f9a73babf7b8">getTruncateExpr</a>.</p>

</div>
</div>

### getTruncateOrZeroExtend() {#adc040502444e4504cdbc04c87e4e3055}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getTruncateOrZeroExtend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * V, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> corresponding to a conversion of the input value to the specified type.</p>


<p>If the type must be extended, it is zero extended.</p>


<p>Declaration at line 711 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4705 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="#a83c084b0947edf4ae748f9a73babf7b8">getTruncateExpr</a>, <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a> and <a href="#a6d745b25efdc69435508f1e936919f8b">getZeroExtendExpr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a55aceb0318074f694f763d011f71cd90">BinomialCoefficient</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a7bdf6d6bf51cc1a22329cd775255d0c8">getNumBytes</a>, <a href="#a4f28ee6ec3dad0938d2660c56168d91d">getPtrToIntExpr</a>, <a href="#a643b61ddaf17331f3ff1d4f85c7c9a23">getSignExtendExprImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ab0f2467f35df49e4d9d0c9623e2530cf">getStartForNegStride</a>, <a href="#a17e35fd9a6e590c201fd05105589ce47">getTripCountFromExitCount</a>, <a href="#a83c084b0947edf4ae748f9a73babf7b8">getTruncateExpr</a> and <a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a>.</p>

</div>
</div>

### getTypeSizeInBits() {#a2c96114e89e8cf2122ebe8bc4d929c7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t ScalarEvolution::getTypeSizeInBits (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the size in bits of the specified type, for which isSCEVable must return true.</p>

<p>Declaration at line 499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4448 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a057ff1d04d6303e3402647132a66ab18">getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a822fce84743a12eba6f9c83c9c719140">llvm::DataLayout::getIndexTypeSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#acf0b1898efd7f81a078e9288befd9290">llvm::DataLayout::getTypeSizeInBits</a> and <a href="#a6d8769a72303e2b06ef63129cb231855">isSCEVable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a55aceb0318074f694f763d011f71cd90">BinomialCoefficient</a>, <a href="#ae0ca564918ec63a9b4d2229374fec747">computeConstantDifference</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a8160c4d5a8fc34f6085af951980dbaa6">createReplacement</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#adc183a6edc37f305ee9ca5ff0bc33a6e">FindLoopCounter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a14bc7872374f530d4ed193d9921825c5">genLoopLimit</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#aa35959e3f6bea8e35cffcfd8659e3156">getAnyExtendExpr</a>, <a href="#a4bab447a6422427e5fc92bbbc0c12fba">getLosslessPtrToIntExpr</a>, <a href="#a765b135bf0191fca6004b4167bcfb493">getMinTrailingZeros</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>, <a href="#a829bd04a95f833114e36a195c7e67f0a">getNoopOrAnyExtend</a>, <a href="#a38c440751f1bf5f19bc12b95f8f0f2a6">getNoopOrSignExtend</a>, <a href="#a933eb87303a6ce51c8894e431fbc389b">getNoopOrZeroExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a7e688afe102c3fa48ea49cb972a0f00c">llvm::SCEVAddRecExpr::getNumIterationsInRange</a>, <a href="#ac2cf93c95893f413324a4645fc39bb1a">getPowerOfTwo</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a359235e468f7ab6f4dccbed37c17dee1">getPreStartForExtend</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ae8a19e1b12d26ad87bc379e576ff5a7f">getSignedOverflowLimitForStep</a>, <a href="#ab26bea71791cf347c631d2072e41cfb5">getSignExtendExpr</a>, <a href="#a643b61ddaf17331f3ff1d4f85c7c9a23">getSignExtendExprImpl</a>, <a href="#a17e35fd9a6e590c201fd05105589ce47">getTripCountFromExitCount</a>, <a href="#a83c084b0947edf4ae748f9a73babf7b8">getTruncateExpr</a>, <a href="#a426976cfd81411f49f7e5fe77ee4e3a4">getTruncateOrNoop</a>, <a href="#af156ea88617d19e05470b8af2bb62dd9">getTruncateOrSignExtend</a>, <a href="#adc040502444e4504cdbc04c87e4e3055">getTruncateOrZeroExtend</a>, <a href="#a6c03d18ed744dc3b34829ec5485a68b0">getUDivExpr</a>, <a href="#a254484ad2e230cf0db1f2c779abfe39c">getUMaxFromMismatchedTypes</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#aff0515f214b4d4e5d5a3197b11d5eacc">getUnsignedOverflowLimitForStep</a>, <a href="#a10cde7087f90dc664b6799814aa28584">getWiderType</a>, <a href="#a6d745b25efdc69435508f1e936919f8b">getZeroExtendExpr</a>, <a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a9b6b892760677b9b11c517eb5a46557f">isAddRecSExtable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a1509f8a0c11e955037b00ce7542e24a7">isAddSExtable</a>, <a href="/web-llvm/docs/api/structs/llvm/hardwareloopinfo/#aef4460eccacc720018aa15086026c11d">llvm::HardwareLoopInfo::isHardwareLoopCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a32cdb4a97c185f1acbe11f45fcc70d12">isMulSExtable</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ad5a0854a75b9e8d760fd95387759569c">isSimpleCastedPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ac4e11266d1da4632ff23afce04d8499f">SolveLinEquationWithOverflow</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a8fa1050509c4edb3c4683179e01035a2">SolveQuadraticAddRecRange</a>, <a href="#aff82c03c1ce8b945170bcb1f0f624c17">verify</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a57aff0646c7151c4158d839c386332cc">visitIVCast</a>.</p>

</div>
</div>

### getUDivCeilSCEV() {#a0daed958320635f1a9d440819f5bd487}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getUDivCeilSCEV (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * D)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute ceil(N / D).</p>


<p>N and D are treated as unsigned values.</p>


<p>Since <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> doesn't have native ceiling division, this generates a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression of the following form:</p>


<p>umin(N, 1) + floor((N - umin(N, 1)) / D)</p>


<p>A denominator of zero or poison is handled the same way as <a href="#a6c03d18ed744dc3b34829ec5485a68b0">getUDivExpr()</a>.</p>


<p>Declaration at line 707 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 12887 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#a8bcb86d8d126d95b0dc05f09e8f3df96">getMinusSCEV</a>, <a href="#a3fbe8f529d36d76730550905d730a2a7">getOne</a>, <a href="#a6c03d18ed744dc3b34829ec5485a68b0">getUDivExpr</a>, <a href="#a796339fe5ef91db7de6137a41e23083b">getUMinExpr</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getUDivExactExpr() {#aeca82ae7bafbb557b7026f7d035643b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getUDivExactExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a canonical unsigned division expression, or something simpler if possible.</p>


<p>There is no representation for an exact udiv in <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> IR, but we can attempt to remove factors from the LHS and RHS. We can't do this when it's not exact because the udiv may be clearing bits.</p>


<p>Declaration at line 608 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 3587 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a06d3404df40c1a89d00d5abf367d19ae">llvm::gcd</a>, <a href="#a2eb94d079d8416118f4aaed865ab05d7">getConstant</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>, <a href="#aeca82ae7bafbb557b7026f7d035643b8">getUDivExactExpr</a>, <a href="#a6c03d18ed744dc3b34829ec5485a68b0">getUDivExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ae00c35cb040107c05f3fe00c15bb3da0">llvm::APInt::isIntN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea62b6d55816cf737bfc6f42e60df1a3f2">llvm::Mul</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a0a8a72a5038e4a261d35418751506868">calculateRtStride</a>, <a href="#aeca82ae7bafbb557b7026f7d035643b8">getUDivExactExpr</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ac4e11266d1da4632ff23afce04d8499f">SolveLinEquationWithOverflow</a>.</p>

</div>
</div>

### getUDivExpr() {#a6c03d18ed744dc3b34829ec5485a68b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getUDivExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a canonical unsigned division expression, or something simpler if possible.</p>

<p>Declaration at line 607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 3400 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">llvm::SCEV::FlagAnyWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faf763167030e97d18e8f8c8ed3dba28e3">llvm::SCEV::FlagNW</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#a659b27f6737fcb7eaf333b0279da1154">getAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevconstant/#a6caf7f3a0a4303e4c0bc06ed8e205126">llvm::SCEVConstant::getAPInt</a>, <a href="#a2eb94d079d8416118f4aaed865ab05d7">getConstant</a>, <a href="#aff9e533399d91febd63fa4bfe82a42a7">getContext</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>, <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a>, <a href="#a6c03d18ed744dc3b34829ec5485a68b0">getUDivExpr</a>, <a href="#a2579491850c605c8b7cf3439a907fbed">getZero</a>, <a href="#a6d745b25efdc69435508f1e936919f8b">getZeroExtendExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a1f04e382556a817950fd0390aeaf9b0e">llvm::APInt::isMinSignedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a6804d9caf15411f55e7b9e9f397f0422">llvm::APInt::isNegative</a>, <a href="/web-llvm/docs/api/namespaces/llvm/scevpatternmatch/#a62d53a67714c66eee08eeabddc553f90">llvm::SCEVPatternMatch::m_scev_Zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#aeefacaa2eccab8db38ff9ccdad1e0b1d">registerUser</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eaee62cac87c0dc1f483d783aae69101c4">llvm::scUDivExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a028f4d1eead63cc33499ce3459bd27c7">llvm::APInt::umul_ov</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a4e3a2187cacdec76028617a403c47d89">llvm::APInt::urem</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a55aceb0318074f694f763d011f71cd90">BinomialCoefficient</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#a0daed958320635f1a9d440819f5bd487">getUDivCeilSCEV</a>, <a href="#aeca82ae7bafbb557b7026f7d035643b8">getUDivExactExpr</a>, <a href="#a6c03d18ed744dc3b34829ec5485a68b0">getUDivExpr</a>, <a href="#a13b9eb961d35ad9ecb3b633f5703253a">getURemExpr</a> and <a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a>.</p>

</div>
</div>

### getUMaxExpr() {#a238566881f41b81cd8ff51eb1b3f4a8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getUMaxExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 641 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4352 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a> and <a href="#a238566881f41b81cd8ff51eb1b3f4a8b">getUMaxExpr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#ae8c79e4794997f6c26f54250c088e4e5">calculateSubRanges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdd1ebe6412f9afb43d0639420afffe0">llvm::getStartAndEndForAccess</a>, <a href="#a238566881f41b81cd8ff51eb1b3f4a8b">getUMaxExpr</a>, <a href="#a254484ad2e230cf0db1f2c779abfe39c">getUMaxFromMismatchedTypes</a>, <a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#aac7331d34e77a2d041b4ecc387db1318">IntersectUnsignedRange</a>.</p>

</div>
</div>

### getUMaxExpr() {#a213bb9cc661533b20602b1e035d63791}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getUMaxExpr (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 642 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4357 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#ac3221ac3fcd879a1c716aa954837df79">getMinMaxExpr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ead3d0abdf8125de904320df332dbefedb">llvm::scUMaxExpr</a>.</p>

</div>
</div>

### getUMaxFromMismatchedTypes() {#a254484ad2e230cf0db1f2c779abfe39c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getUMaxFromMismatchedTypes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Promote the operands to the wider of the types using zero-extension, and then perform a umax operation with them.</p>

<p>Declaration at line 740 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4777 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a933eb87303a6ce51c8894e431fbc389b">getNoopOrZeroExtend</a>, <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a>, <a href="#a238566881f41b81cd8ff51eb1b3f4a8b">getUMaxExpr</a> and <a href="#a6d745b25efdc69435508f1e936919f8b">getZeroExtendExpr</a>.</p>

</div>
</div>

### getUMinExpr() {#a796339fe5ef91db7de6137a41e23083b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getUMinExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, bool Sequential=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 645 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4371 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a> and <a href="#a796339fe5ef91db7de6137a41e23083b">getUMinExpr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#ae8c79e4794997f6c26f54250c088e4e5">calculateSubRanges</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a51c0653682103a713b0c3695aae3a1ff">createNodeForSelectViaUMinSeq</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdd1ebe6412f9afb43d0639420afffe0">llvm::getStartAndEndForAccess</a>, <a href="#a0daed958320635f1a9d440819f5bd487">getUDivCeilSCEV</a>, <a href="#a796339fe5ef91db7de6137a41e23083b">getUMinExpr</a>, <a href="#aef86e2e34d31e4595f5a442fe55ecbe9">getUMinFromMismatchedTypes</a>, <a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#aac7331d34e77a2d041b4ecc387db1318">IntersectUnsignedRange</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a>.</p>

</div>
</div>

### getUMinExpr() {#a997ab75fad6de5dda923e63c28553834}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getUMinExpr (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; Operands, bool Sequential=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 647 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4377 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="#ac3221ac3fcd879a1c716aa954837df79">getMinMaxExpr</a>, <a href="#a4976a99a4f39b4daee84f4f60319df03">getSequentialMinMaxExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea376414ac1f3ac8cb449fd5167a2db091">llvm::scSequentialUMinExpr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea0bf2fc9a454ce237fde0906ee24b0acc">llvm::scUMinExpr</a>.</p>

</div>
</div>

### getUMinFromMismatchedTypes() {#a9aba96071c763c3233ab9f7cea03f395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getUMinFromMismatchedTypes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, bool Sequential=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Promote the operands to the wider of the types using zero-extension, and then perform a umin operation with them.</p>

<p>Declaration at line 744 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4790 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a> and <a href="#a9aba96071c763c3233ab9f7cea03f395">getUMinFromMismatchedTypes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a8160c4d5a8fc34f6085af951980dbaa6">createReplacement</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp/#a56378412b516c96bbab7cd31b530e0ff">getMinAnalyzeableBackedgeTakenCount</a> and <a href="#a9aba96071c763c3233ab9f7cea03f395">getUMinFromMismatchedTypes</a>.</p>

</div>
</div>

### getUMinFromMismatchedTypes() {#aef86e2e34d31e4595f5a442fe55ecbe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getUMinFromMismatchedTypes (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; Ops, bool Sequential=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Promote the operands to the wider of the types using zero-extension, and then perform a umin operation with them.</p>


<p>N-ary function.</p>


<p>Declaration at line 749 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4798 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a933eb87303a6ce51c8894e431fbc389b">getNoopOrZeroExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>, <a href="#a796339fe5ef91db7de6137a41e23083b">getUMinExpr</a>, <a href="#a10cde7087f90dc664b6799814aa28584">getWiderType</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### getUnknown() {#ad8e4f5b2ced08ad7d138b598aefdd338}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getUnknown (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 649 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4411 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a9a1917da5135c7cd0431c35b583db2aa">SCEVUnknown</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea80488550b42b6548ec4d5c7118c7ff1d">llvm::scUnknown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate/#a8829aacd47e6a4f3dbaf6c359d5afdfb">anonymous{LoopStrengthReduce.cpp}::Immediate::getUnknownSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#adb1a03152610d15e008c2fdcb93602ed">llvm::InductionDescriptor::isFPInductionPHI</a> and <a href="#aff82c03c1ce8b945170bcb1f0f624c17">verify</a>.</p>

</div>
</div>

### getUnsignedRange() {#a7593d52f91ebe342de9fa72846ebe755}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange llvm::ScalarEvolution::getUnsignedRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
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

<p>Determine the unsigned range for a particular <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>.</p>


<p>NOTE: This returns a copy of the reference returned by getRangeRef.</p>


<p>Definition at line 997 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a4d34a6e13a44aa2f7c490762cbd3afb7">getBoundsCheckCond</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#aa917f47e75cf32ee8a1abf71f2ebde01">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::getConstantRangeFromSCEV</a>, <a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/placesafepoints-cpp/#a2003053288ba4f0e1cd9ebf82b6a1987">mustBeFiniteCountedLoop</a>, <a href="#a77b275a78beac200ef1f703d2a5fbb7d">print</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ae99f51fb7f4e120a8ebeb76e3c53cf2b">StrengthenNoWrapFlags</a>.</p>

</div>
</div>

### getUnsignedRangeMax() {#ac8de32f4d40eae96f0e26f0728682c2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::ScalarEvolution::getUnsignedRangeMax (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
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

<p>Determine the max of the unsigned range for a particular <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>.</p>

<p>Definition at line 1007 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#aff0515f214b4d4e5d5a3197b11d5eacc">getUnsignedOverflowLimitForStep</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeba325403d8d6430ee4a41b2cea631f5">llvm::isDereferenceableAndAlignedInLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a50702846ece6b5c6ef8826ca0e137bc5">llvm::ARMTTIImpl::isHardwareLoopProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a0b6b1ae088cb8ca3aa4f26c4098daa3d">llvm::LoopVectorizationPlanner::selectEpilogueVectorizationFactor</a> and <a href="#a5e9fc2b9bb75a684c20ca3fa6e14b63e">SimplifyICmpOperands</a>.</p>

</div>
</div>

### getUnsignedRangeMin() {#a5d61e3035097c0e57849c6d3f195597d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::ScalarEvolution::getUnsignedRangeMin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
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

<p>Determine the min of the unsigned range for a particular <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>.</p>

<p>Definition at line 1002 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Referenced by <a href="#a20c66c97bae0b3e6725d03cfa61c488b">isKnownNonZero</a> and <a href="#a5e9fc2b9bb75a684c20ca3fa6e14b63e">SimplifyICmpOperands</a>.</p>

</div>
</div>

### getURemExpr() {#a13b9eb961d35ad9ecb3b633f5703253a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getURemExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represents an unsigned remainder expression based on unsigned division.</p>

<p>Declaration at line 609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 3371 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faafb62cd6afdc004ef6e8a1f6288eb382">llvm::SCEV::FlagNUW</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="#aff9e533399d91febd63fa4bfe82a42a7">getContext</a>, <a href="#a6dcfa69ce27cf214caaf50f21bfe1f2f">getEffectiveSCEVType</a>, <a href="#a8bcb86d8d126d95b0dc05f09e8f3df96">getMinusSCEV</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>, <a href="#a83c084b0947edf4ae748f9a73babf7b8">getTruncateExpr</a>, <a href="#a6c03d18ed744dc3b34829ec5485a68b0">getUDivExpr</a>, <a href="#a2579491850c605c8b7cf3439a907fbed">getZero</a> and <a href="#a6d745b25efdc69435508f1e936919f8b">getZeroExtendExpr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a65ab4267c6c132d06451b5d97bc9ee83">llvm::LoopVectorizationCostModel::computeMaxVF</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/alignmentfromassumptions-cpp/#a6a5d252746b8261a4f76454c49bb8437">getNewAlignmentDiff</a>, <a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a0b6b1ae088cb8ca3aa4f26c4098daa3d">llvm::LoopVectorizationPlanner::selectEpilogueVectorizationFactor</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ac4e11266d1da4632ff23afce04d8499f">SolveLinEquationWithOverflow</a>.</p>

</div>
</div>

### getVScale() {#abc6d543083aac1a4e161c0ed02b9b30a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getVScale (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 567 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea61df12d6bb21842a8f766c4433c85717">llvm::scVScale</a>.</p>


<p>Referenced by <a href="#adfad3d829fd98014f225d55b4a924819">getElementCount</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate/#a81bada52d17e453e10221581a1bda050">anonymous{LoopStrengthReduce.cpp}::Immediate::getNegativeSCEV</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate/#a51c730254cd6b346d9fa4588c58a7517">anonymous{LoopStrengthReduce.cpp}::Immediate::getSCEV</a>, <a href="#ad7409ed2347009a5163f410e69a94243">getSizeOfExpr</a> and <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate/#a8829aacd47e6a4f3dbaf6c359d5afdfb">anonymous{LoopStrengthReduce.cpp}::Immediate::getUnknownSCEV</a>.</p>

</div>
</div>

### getWiderType() {#a10cde7087f90dc664b6799814aa28584}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * ScalarEvolution::getWiderType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty1, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4469 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Reference <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a>.</p>


<p>Referenced by <a href="#aef86e2e34d31e4595f5a442fe55ecbe9">getUMinFromMismatchedTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate/#a1bb4ca5c2810fc70f58fcf2581fa5bca">llvm::SCEVWrapPredicate::implies</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a740a442f349b36821071c21e265e23e1">optimizeLoopExitWithUnknownExitCount</a>.</p>

</div>
</div>

### getWrapPredicate() {#a8b4da0fed92ca11bf8cb2fd763168d3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEVPredicate * ScalarEvolution::getWrapPredicate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * AR, <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate/#a0cfd938ff9c572d287e5e7923624db70">SCEVWrapPredicate::IncrementWrapFlags</a> AddedFlags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 14760 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scevpredicate/#a75f4943e861ac0b6d41439c7d5c07adbaac3069eca0cb48a03eaa7d95fb84829c">llvm::SCEVPredicate::P_Wrap</a>.</p>

</div>
</div>

### getZero() {#a2579491850c605c8b7cf3439a907fbed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::ScalarEvolution::getZero (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> for the constant 0 of a specific type.</p>

<p>Definition at line 653 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Reference <a href="#a2eb94d079d8416118f4aaed865ab05d7">getConstant</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a5591acf152c652226d89a2b5ea436d05">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::computeSafeIterationSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ab329d363cb73927378483de592986282">detectShiftUntilZeroIdiom</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#a4bab447a6422427e5fc92bbbc0c12fba">getLosslessPtrToIntExpr</a>, <a href="#a8bcb86d8d126d95b0dc05f09e8f3df96">getMinusSCEV</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a7e688afe102c3fa48ea49cb972a0f00c">llvm::SCEVAddRecExpr::getNumIterationsInRange</a>, <a href="#a4976a99a4f39b4daee84f4f60319df03">getSequentialMinMaxExpr</a>, <a href="#a83c084b0947edf4ae748f9a73babf7b8">getTruncateExpr</a>, <a href="#a6c03d18ed744dc3b34829ec5485a68b0">getUDivExpr</a>, <a href="#a13b9eb961d35ad9ecb3b633f5703253a">getURemExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc1d309b62fc59309659ac3fa7f3f68f">llvm::isKnownNegativeInLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af042aac9d86aacb5ee9e1af24590f4c2">llvm::isKnownNonNegativeInLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1dc474f11162cc2893aa0f7d208d6ea2">llvm::isKnownNonPositiveInLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a947ac955070bcb92444d3bb31077eb13">llvm::isKnownPositiveInLoop</a>, <a href="#a8b617baf7fc5914d8a245e702ea65a7d">isLoopBackedgeGuardedByCond</a>, <a href="#a1e4038e28db703c29e5e3de1549806ca">removePointerBase</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ac4e11266d1da4632ff23afce04d8499f">SolveLinEquationWithOverflow</a>.</p>

</div>
</div>

### getZeroExtendExpr() {#a6d745b25efdc69435508f1e936919f8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getZeroExtendExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Op, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 569 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 1565 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="#a6dcfa69ce27cf214caaf50f21bfe1f2f">getEffectiveSCEVType</a>, <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a>, <a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a1fb622dcdf9f011b6776856b103e358e">insertFoldCacheEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a6d8769a72303e2b06ef63129cb231855">isSCEVable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eadd4a8d5cb0d78c9be22d01e1546bafc6">llvm::scZeroExtend</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a8160c4d5a8fc34f6085af951980dbaa6">createReplacement</a>, <a href="#aa35959e3f6bea8e35cffcfd8659e3156">getAnyExtendExpr</a>, <a href="#a48216fb35fa09727a5717cd28faca9bf">getCastExpr</a>, <a href="#a933eb87303a6ce51c8894e431fbc389b">getNoopOrZeroExtend</a>, <a href="#a643b61ddaf17331f3ff1d4f85c7c9a23">getSignExtendExprImpl</a>, <a href="#a17e35fd9a6e590c201fd05105589ce47">getTripCountFromExitCount</a>, <a href="#adc040502444e4504cdbc04c87e4e3055">getTruncateOrZeroExtend</a>, <a href="#a6c03d18ed744dc3b34829ec5485a68b0">getUDivExpr</a>, <a href="#a254484ad2e230cf0db1f2c779abfe39c">getUMaxFromMismatchedTypes</a>, <a href="#a13b9eb961d35ad9ecb3b633f5703253a">getURemExpr</a>, <a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp/#a202c702ced6d0c47a226adf851aba6eb">IsIncrementNUW</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a917578aa4ba03c192fa1c048ed3b5b00">isSafeDependenceDistance</a>, <a href="#aff82c03c1ce8b945170bcb1f0f624c17">verify</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a11a65ce1550eac260dca320a7028328e">verifyTripCount</a> and <a href="#a267fd27cb9e177fa5f48cbb8828339a1">willNotOverflow</a>.</p>

</div>
</div>

### getZeroExtendExprImpl() {#a26ffa319e1953452b1d1df84923f2108}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getZeroExtendExprImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Op, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 570 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 1584 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aaca3a4d2b25c24b11179cbd01079b73c">llvm::ConstantRange::contains</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ab1ecca94c1ac1a616d83f565a4aeaeae">extractConstantWithoutWrapping</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">llvm::SCEV::FlagAnyWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa2f7a8775a783f7ea3ad24b3f9cb5d949">llvm::SCEV::FlagNSW</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faafb62cd6afdc004ef6e8a1f6288eb382">llvm::SCEV::FlagNUW</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faf763167030e97d18e8f8c8ed3dba28e3">llvm::SCEV::FlagNW</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#a659b27f6737fcb7eaf333b0279da1154">getAddRecExpr</a>, <a href="#a2eb94d079d8416118f4aaed865ab05d7">getConstant</a>, <a href="#a0182f006bb2ae6411c2111427d58f242">getConstantMaxBackedgeTakenCount</a>, <a href="#aff9e533399d91febd63fa4bfe82a42a7">getContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a7762f1d99f297ecb6ccb4375e715c2ea">getExtendAddRecStart</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a331d69b5f93e47e7c596062b77dd5913">llvm::APInt::getMaxValue</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>, <a href="#a809289b45cd6625629f5356f70dac72d">getSignedRangeMin</a>, <a href="#ab26bea71791cf347c631d2072e41cfb5">getSignExtendExpr</a>, <a href="#a83c084b0947edf4ae748f9a73babf7b8">getTruncateExpr</a>, <a href="#adc040502444e4504cdbc04c87e4e3055">getTruncateOrZeroExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>, <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a>, <a href="#a6c03d18ed744dc3b34829ec5485a68b0">getUDivExpr</a>, <a href="#a238566881f41b81cd8ff51eb1b3f4a8b">getUMaxExpr</a>, <a href="#a796339fe5ef91db7de6137a41e23083b">getUMinExpr</a>, <a href="#a7593d52f91ebe342de9fa72846ebe755">getUnsignedRange</a>, <a href="#a13b9eb961d35ad9ecb3b633f5703253a">getURemExpr</a>, <a href="#a6d745b25efdc69435508f1e936919f8b">getZeroExtendExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a1b9806d21518ef7fb4d5c4299e21411f">isKnownNegative</a>, <a href="#a06b567827f9349ea154df08c2450b776">isKnownOnEveryIteration</a>, <a href="#a8b617baf7fc5914d8a245e702ea65a7d">isLoopBackedgeGuardedByCond</a>, <a href="#a6d8769a72303e2b06ef63129cb231855">isSCEVable</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a58f74b4f08e8ade02bb12bfff74b0c50">MaxCastDepth</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="#aeefacaa2eccab8db38ff9ccdad1e0b1d">registerUser</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eadd4a8d5cb0d78c9be22d01e1546bafc6">llvm::scZeroExtend</a>, <a href="#a248dea99ef1d5a864269ac3a98014b37">setNoWrapFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a2bc441c8fe8dfeea5471f11d2d823ec1">llvm::ConstantRange::truncate</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a636ddf018d314a1d73f98e2fa4efbafb">llvm::ConstantRange::zeroExtend</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a05ef50c1573b919a575fccb31cc523b4">llvm::ConstantRange::zextOrTrunc</a>.</p>


<p>Referenced by <a href="#a6d745b25efdc69435508f1e936919f8b">getZeroExtendExpr</a>.</p>

</div>
</div>

### hasComputableLoopEvolution() {#ac258f0361a1c35f5814a2b529139d15c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::hasComputableLoopEvolution (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> changes value in a known way in the specified loop.</p>


<p>This property being true implies that the value is variant in the loop AND that we can emit an expression to compute the value of the expression at any particular loop iteration.</p>


<p>Declaration at line 1248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 14109 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a61f5098e98f972466ae233e6d01f9f9c">getLoopDisposition</a> and <a href="#a9f7c88892cfe1646082bf6174a4b912ca01f7990cbee1565b32df02333aeffb9b">LoopComputable</a>.</p>

</div>
</div>

### hasLoopInvariantBackedgeTakenCount() {#a91ac801aa45c78e0d0edbc36115ef054}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::hasLoopInvariantBackedgeTakenCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified loop has an analyzable loop-invariant backedge-taken count.</p>

<p>Declaration at line 939 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 13717 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a22d9bcbd44563106d7217f3bd9a4039e">getBackedgeTakenCount</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#a0e67dc55f94f7419d24a39fa5b79c42f">canFoldTermCondOfLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a6c22989c03e43928e4b09cfa60a804f5">llvm::ARMTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate/#a1f677960b0a306e237ee9fa3b838639d">anonymous{LoopFuse.cpp}::FusionCandidate::isEligibleForFusion</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a50702846ece6b5c6ef8826ca0e137bc5">llvm::ARMTTIImpl::isHardwareLoopProfitable</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a7170e1b99a9c472642f756b8cf098afa">PrintLoopInfo</a>.</p>

</div>
</div>

### hasOperand() {#a694848007e26a83150b8dbd67e58fbdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::hasOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether the given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> has <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> as a direct or indirect operand.</p>

<p>Declaration at line 1263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 14196 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#affb88623037a9864e030154052747ba1">llvm::SCEVExprContains</a>.</p>

</div>
</div>

### instructionCouldExistWithOperands() {#a744bc2c6ff2e83909955ef714890cb14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::instructionCouldExistWithOperands (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if there exists a point in the program at which both A and B could be operands to the same instruction.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expressions are generally assumed to correspond to instructions which could exists in IR. In general, this requires that there exists a use point in the program where all operands dominate the use.</p>


<p>Example: loop { if loop { v1 = load @global1; } else loop { v2 = load @global2; } } No <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> with operand V1, and v2 can exist in this program.</p>


<p>Declaration at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4473 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolutionaliasanalysis-cpp/#a8a1c5d80e64a493b2bd6414551740151">canComputePointerDiff</a>.</p>

</div>
</div>

### invalidate() {#a93a455a6a60ac3b40d15464bc3b86e90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::invalidate (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp; PA, FunctionAnalysisManager::Invalidator &amp; Inv)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 14650 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### isAvailableAtLoopEntry() {#aadf992d0faba329a1b5315dcde978e85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isAvailableAtLoopEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> can be evaluated at loop's entry.</p>


<p>It is true if it doesn't depend on a <a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a> of an instruction which is dominated by the header of loop L.</p>


<p>Declaration at line 1242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 2521 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a5a19768af81df7e5fe571bc08dcd48b3">isLoopInvariant</a> and <a href="#ae0d036af111b8aafe90db0771b8e9ce3">properlyDominates</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5704370a1379cfd0062d47b73ba65cb0">llvm::cannotBeMaxInLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef5f1583da883ba28cb113c02d29f1d9">llvm::cannotBeMinInLoop</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#a69f32678ea46cdda0318c0be9bdb1c7e">getAddRecExpr</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add13dc19bf2ad558a6de4028bf0f218c">llvm::hasProcessableCondition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc1d309b62fc59309659ac3fa7f3f68f">llvm::isKnownNegativeInLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af042aac9d86aacb5ee9e1af24590f4c2">llvm::isKnownNonNegativeInLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1dc474f11162cc2893aa0f7d208d6ea2">llvm::isKnownNonPositiveInLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a947ac955070bcb92444d3bb31077eb13">llvm::isKnownPositiveInLoop</a>, <a href="#afd0a71dc4e0ed5b83c50e875e6726661">isKnownViaInduction</a>, <a href="#a1e9fadcd7d58712f2a36fb635e35d2f5">isLoopEntryGuardedByCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#ac8cf3aa27282d640f5acbc3a676e03c5">isSafeDecreasingBound</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#adbc17f3ace73f701522eefe28104c06c">isSafeIncreasingBound</a>.</p>

</div>
</div>

### isBackedgeTakenCountMaxOrZero() {#a57a6829dad387e7075a6325e3ec6ace5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isBackedgeTakenCountMaxOrZero (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the backedge taken count is either the value returned by getConstantMaxBackedgeTakenCount or zero.</p>

<p>Declaration at line 935 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8371 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a7170e1b99a9c472642f756b8cf098afa">PrintLoopInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#ab6df82212b20d28e61ff9417744420ff">tryToUnrollLoop</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>.</p>

</div>
</div>

### isBasicBlockEntryGuardedByCond() {#aefc772d1808d513abc142b59844cfe45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isBasicBlockEntryGuardedByCond (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether entry to the basic block is protected by a conditional between LHS and RHS.</p>

<p>Declaration at line 784 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 11621 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4848d1a141ddc7cf0068460fba53ba37">llvm::BasicBlock::front</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aebd4af5642453ce3169094f08dd3d7b8">llvm::BranchInst::getCondition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#aa1731508126b77035ab3ba9d71d5374b">llvm::Intrinsic::getDeclarationIfExists</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a88575baf2ad9f4cd2e2432e6da4a976b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopPredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a6b13f2e75444202b854672a5fbf85e2e">llvm::CmpInst::getNonStrictPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a59fb91d1691350f7d1b8e8a114e3f2a4">llvm::BasicBlock::getSinglePredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aa05da2b94b366573d1651d5b163c521e">llvm::BranchInst::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#ad56f6a9b5cd05940017c4544df48bc30">llvm::BranchInst::isUnconditional</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26389c546573f058ad8ecbdc5c1933cf">llvm::verifyFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a280e6ef77f742141e0b63a8fac72323c">VerifyIR</a>.</p>


<p>Referenced by <a href="#a4bfb461a6adf8414747571a5f94a77fc">evaluatePredicateAt</a>, <a href="#aeaae2161ba70381e225ac6800af5d961">isKnownPredicateAt</a> and <a href="#a1e9fadcd7d58712f2a36fb635e35d2f5">isLoopEntryGuardedByCond</a>.</p>

</div>
</div>

### isKnownNegative() {#a1b9806d21518ef7fb4d5c4299e21411f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isKnownNegative (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test if the given expression is known to be negative.</p>

<p>Declaration at line 1028 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 10943 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#afee50be11e579d3c510e73df2a21cb88">getSignedRangeMax</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a6804d9caf15411f55e7b9e9f397f0422">llvm::APInt::isNegative</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a7098623cafc05376a44b27d202b03372">countToEliminateCompares</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ae8a19e1b12d26ad87bc379e576ff5a7f">getSignedOverflowLimitForStep</a>, <a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp/#a04de41a04706e275a5161b62cfe2b790">isOneDimensionalArray</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#ac8cf3aa27282d640f5acbc3a676e03c5">isSafeDecreasingBound</a>.</p>

</div>
</div>

### isKnownNonNegative() {#a06719fdab228f099aeac0c8ee40a7e34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isKnownNonNegative (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test if the given expression is known to be non-negative.</p>

<p>Declaration at line 1034 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 10951 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a809289b45cd6625629f5356f70dac72d">getSignedRangeMin</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a6804d9caf15411f55e7b9e9f397f0422">llvm::APInt::isNegative</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ab329d363cb73927378483de592986282">detectShiftUntilZeroIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a43288882d546aed1ef0a23ffc620ddff">expandBounds</a>, <a href="#a0f3039f831c483956c153ed9dee23dba">getGEPExpr</a>, <a href="#a741e5065c867d7dfd716eb8e16fccf12">getLoopInvariantPredicate</a>, <a href="#a8bcb86d8d126d95b0dc05f09e8f3df96">getMinusSCEV</a>, <a href="#a643b61ddaf17331f3ff1d4f85c7c9a23">getSignExtendExprImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ae99f51fb7f4e120a8ebeb76e3c53cf2b">StrengthenNoWrapFlags</a>.</p>

</div>
</div>

### isKnownNonPositive() {#a121ee24f11c464f3b3197cac87b0980e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isKnownNonPositive (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test if the given expression is known to be non-positive.</p>

<p>Declaration at line 1037 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 10955 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#afee50be11e579d3c510e73df2a21cb88">getSignedRangeMax</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#aa17c104fbda554c818cf87e53f32f20a">llvm::APInt::isStrictlyPositive</a>.</p>

</div>
</div>

### isKnownNonZero() {#a20c66c97bae0b3e6725d03cfa61c488b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isKnownNonZero (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test if the given expression is known to be non-zero.</p>

<p>Declaration at line 1040 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 10959 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5d61e3035097c0e57849c6d3f195597d">getUnsignedRangeMin</a> and <a href="#a20c66c97bae0b3e6725d03cfa61c488b">isKnownNonZero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a11da3451c68e56248a152964e5915cd8">breakBackedgeIfNotTaken</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#a0e67dc55f94f7419d24a39fa5b79c42f">canFoldTermCondOfLoop</a>, <a href="#a20c66c97bae0b3e6725d03cfa61c488b">isKnownNonZero</a> and <a href="#aa5e7bb544eab3ac6fa1f810ee068ab6b">isKnownToBeAPowerOfTwo</a>.</p>

</div>
</div>

### isKnownOnEveryIteration() {#a06b567827f9349ea154df08c2450b776}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isKnownOnEveryIteration (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test if the condition described by Pred, LHS, RHS is known to be true on every iteration of the loop of the recurrency LHS.</p>

<p>Declaration at line 1110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 11097 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a8b617baf7fc5914d8a245e702ea65a7d">isLoopBackedgeGuardedByCond</a> and <a href="#a1e9fadcd7d58712f2a36fb635e35d2f5">isLoopEntryGuardedByCond</a>.</p>


<p>Referenced by <a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a>.</p>

</div>
</div>

### isKnownPositive() {#a5a672708a81ae8da8fb56e32638ca9b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isKnownPositive (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test if the given expression is known to be positive.</p>

<p>Declaration at line 1031 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 10947 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a809289b45cd6625629f5356f70dac72d">getSignedRangeMin</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#aa17c104fbda554c818cf87e53f32f20a">llvm::APInt::isStrictlyPositive</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a7098623cafc05376a44b27d202b03372">countToEliminateCompares</a>, <a href="#a741e5065c867d7dfd716eb8e16fccf12">getLoopInvariantPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a359235e468f7ab6f4dccbed37c17dee1">getPreStartForExtend</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ae8a19e1b12d26ad87bc379e576ff5a7f">getSignedOverflowLimitForStep</a>, <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate/#a1bb4ca5c2810fc70f58fcf2581fa5bca">llvm::SCEVWrapPredicate::implies</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a797a268a4ac8802907a1b36ee57166e2">llvm::RecurrenceDescriptor::isFindLastIVPattern</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a917578aa4ba03c192fa1c048ed3b5b00">isSafeDependenceDistance</a>.</p>

</div>
</div>

### isKnownPredicate() {#af74112dae88db73eb5484821b6f0fccd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isKnownPredicate (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test if the given expression is known to satisfy the condition described by Pred, LHS, and RHS.</p>

<p>Declaration at line 1088 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 11049 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#afd0a71dc4e0ed5b83c50e875e6726661">isKnownViaInduction</a> and <a href="#a5e9fc2b9bb75a684c20ca3fa6e14b63e">SimplifyICmpOperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inductiverangecheckelimination-cpp/#ae8c79e4794997f6c26f54250c088e4e5">calculateSubRanges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad3c7760a82783f7d9aea9166ad4b0fcb">llvm::calculateUpperBound</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a65ab4267c6c132d06451b5d97bc9ee83">llvm::LoopVectorizationCostModel::computeMaxVF</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a7098623cafc05376a44b27d202b03372">countToEliminateCompares</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a72c491cdf8cf0283d87008831431f917">llvm::InnerLoopVectorizer::emitIterationCountCheck</a>, <a href="#ad80020012061cb562a6f9c9f715c2cf0">evaluatePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate/#a1bb4ca5c2810fc70f58fcf2581fa5bca">llvm::SCEVWrapPredicate::implies</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/range/#a18ae90407a801091335439ed8b4a5e70">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::Range::isEmpty</a>, <a href="#aeaae2161ba70381e225ac6800af5d961">isKnownPredicateAt</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a865c6ae11d94c83d4a7bcc0527f0fcef">IsKnownPredicateViaAddRecStart</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp/#a36394991a2449f5d347466a670a120e5">normalizePredicate</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#af25d938764b8634e70e95ff3f0c35129">llvm::VPlanTransforms::optimizeForVFAndUF</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#a0b6b1ae088cb8ca3aa4f26c4098daa3d">llvm::LoopVectorizationPlanner::selectEpilogueVectorizationFactor</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ac4e11266d1da4632ff23afce04d8499f">SolveLinEquationWithOverflow</a>.</p>

</div>
</div>

### isKnownPredicateAt() {#aeaae2161ba70381e225ac6800af5d961}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isKnownPredicateAt (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test if the given expression is known to satisfy the condition described by Pred, LHS, and RHS in the given Context.</p>

<p>Declaration at line 1098 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 11074 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="#aefc772d1808d513abc142b59844cfe45">isBasicBlockEntryGuardedByCond</a> and <a href="#af74112dae88db73eb5484821b6f0fccd">isKnownPredicate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#a233a4dda6b9b4c37b906fa288ffb1807">canOverlap</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a8160c4d5a8fc34f6085af951980dbaa6">createReplacement</a>, <a href="#a094d95c92490272d4b7a6bf4ab90009d">getLoopInvariantExitCondDuringFirstIterationsImpl</a>, <a href="#a741e5065c867d7dfd716eb8e16fccf12">getLoopInvariantPredicate</a> and <a href="#a267fd27cb9e177fa5f48cbb8828339a1">willNotOverflow</a>.</p>

</div>
</div>

### isKnownToBeAPowerOfTwo() {#aa5e7bb544eab3ac6fa1f810ee068ab6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isKnownToBeAPowerOfTwo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, bool OrZero=false, bool OrNegative=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test if the given expression is known to be a power of 2.</p>


<p>OrNegative allows matching negative power of 2s, and OrZero allows matching 0.</p>


<p>Declaration at line 1044 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 10967 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a20c66c97bae0b3e6725d03cfa61c488b">isKnownNonZero</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea62b6d55816cf737bfc6f42e60df1a3f2">llvm::Mul</a>.</p>

</div>
</div>

### isKnownViaInduction() {#afd0a71dc4e0ed5b83c50e875e6726661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isKnownViaInduction (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We'd like to check the predicate on every iteration of the most dominated loop between loops used in LHS and RHS.</p>


<p>To do this we use the following list of steps:</p>


<ol class="doxyList" type="1">
<li>Collect set S all loops on which either LHS or RHS depend.</li>
<li>If S is non-empty a. Let PD be the element of S which is dominated by all other elements. b. Let E(LHS) be value of LHS on entry of PD. To get E(LHS), we should just take LHS and replace all AddRecs that are attached to PD on with their entry values. Define E(RHS) in the same way. c. Let B(LHS) be value of L on backedge of PD. To get B(LHS), we should just take LHS and replace all AddRecs that are attached to PD on with their backedge values. Define B(RHS) in the same way. d. Note that E(LHS) and E(RHS) are automatically available on entry of PD, so we can assert on that. e. Return true if isLoopEntryGuardedByCond(Pred, E(LHS), E(RHS)) &amp;&amp; isLoopBackedgeGuardedByCond(Pred, B(LHS), B(RHS))</li>
</ol>

<p>Declaration at line 1084 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 10999 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#af8a50544090e81ac83601aff8f4b0142">llvm::SmallPtrSetImplBase::empty</a>, <a href="#aaa9b9055fd9c69fe14eb20f0d18d53d5">getCouldNotCompute</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="#aadf992d0faba329a1b5315dcde978e85">isAvailableAtLoopEntry</a>, <a href="#a8b617baf7fc5914d8a245e702ea65a7d">isLoopBackedgeGuardedByCond</a>, <a href="#a1e9fadcd7d58712f2a36fb635e35d2f5">isLoopEntryGuardedByCond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab4e6de707bff0fe8081c4da0711bba07">llvm::max_element</a> and <a href="#ae7a40d693574be8048944e80774e6c1d">SplitIntoInitAndPostInc</a>.</p>


<p>Referenced by <a href="#af74112dae88db73eb5484821b6f0fccd">isKnownPredicate</a>.</p>

</div>
</div>

### isLoopBackedgeGuardedByCond() {#a8b617baf7fc5914d8a245e702ea65a7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isLoopBackedgeGuardedByCond (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether the backedge of the loop is protected by a conditional between LHS and RHS.</p>


<p>isLoopBackedgeGuardedByCond - Test whether the backedge of the loop is protected by a conditional between LHS and RHS.</p>


<p>This is used to eliminate casts.</p>


<p>This is used to to eliminate casts.</p>


<p>Declaration at line 789 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 11515 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faafb62cd6afdc004ef6e8a1f6288eb382">llvm::SCEV::FlagNUW</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faf763167030e97d18e8f8c8ed3dba28e3">llvm::SCEV::FlagNW</a>, <a href="#a659b27f6737fcb7eaf333b0279da1154">getAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aebd4af5642453ce3169094f08dd3d7b8">llvm::BranchInst::getCondition</a>, <a href="#aaa9b9055fd9c69fe14eb20f0d18d53d5">getCouldNotCompute</a>, <a href="#a3fbe8f529d36d76730550905d730a2a7">getOne</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a59fb91d1691350f7d1b8e8a114e3f2a4">llvm::BasicBlock::getSinglePredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aa05da2b94b366573d1651d5b163c521e">llvm::BranchInst::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>, <a href="#a2579491850c605c8b7cf3439a907fbed">getZero</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a7e4be8b16fbd68c9045a388904044e01">llvm::BranchInst::isConditional</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblockedge/#a9c8df2ee2950f5957a98ca2bec57c399">llvm::BasicBlockEdge::isSingleEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26389c546573f058ad8ecbdc5c1933cf">llvm::verifyFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a280e6ef77f742141e0b63a8fac72323c">VerifyIR</a>.</p>


<p>Referenced by <a href="#a094d95c92490272d4b7a6bf4ab90009d">getLoopInvariantExitCondDuringFirstIterationsImpl</a>, <a href="#a741e5065c867d7dfd716eb8e16fccf12">getLoopInvariantPredicate</a>, <a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a>, <a href="#a06b567827f9349ea154df08c2450b776">isKnownOnEveryIteration</a> and <a href="#afd0a71dc4e0ed5b83c50e875e6726661">isKnownViaInduction</a>.</p>

</div>
</div>

### isLoopEntryGuardedByCond() {#a1e9fadcd7d58712f2a36fb635e35d2f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isLoopEntryGuardedByCond (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether entry to the loop is protected by a conditional between LHS and RHS.</p>


<p>This is used to help avoid max expressions in loop trip counts, and to eliminate casts.</p>


<p>Declaration at line 779 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 11720 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aadf992d0faba329a1b5315dcde978e85">isAvailableAtLoopEntry</a> and <a href="#aefc772d1808d513abc142b59844cfe45">isBasicBlockEntryGuardedByCond</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5704370a1379cfd0062d47b73ba65cb0">llvm::cannotBeMaxInLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef5f1583da883ba28cb113c02d29f1d9">llvm::cannotBeMinInLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2844f6f21008147f14f3156e06c3ac4">llvm::findSplitCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a359235e468f7ab6f4dccbed37c17dee1">getPreStartForExtend</a>, <a href="#a17e35fd9a6e590c201fd05105589ce47">getTripCountFromExitCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc1d309b62fc59309659ac3fa7f3f68f">llvm::isKnownNegativeInLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af042aac9d86aacb5ee9e1af24590f4c2">llvm::isKnownNonNegativeInLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1dc474f11162cc2893aa0f7d208d6ea2">llvm::isKnownNonPositiveInLoop</a>, <a href="#a06b567827f9349ea154df08c2450b776">isKnownOnEveryIteration</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a947ac955070bcb92444d3bb31077eb13">llvm::isKnownPositiveInLoop</a>, <a href="#afd0a71dc4e0ed5b83c50e875e6726661">isKnownViaInduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#ac8cf3aa27282d640f5acbc3a676e03c5">isSafeDecreasingBound</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#adbc17f3ace73f701522eefe28104c06c">isSafeIncreasingBound</a>.</p>

</div>
</div>

### isLoopInvariant() {#a5a19768af81df7e5fe571bc08dcd48b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isLoopInvariant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the value of the given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> is unchanging in the specified loop.</p>

<p>Declaration at line 1237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 14105 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a61f5098e98f972466ae233e6d01f9f9c">getLoopDisposition</a> and <a href="#a9f7c88892cfe1646082bf6174a4b912ca1b7d4316c0866b0b0b7a510e1800f4a8">LoopInvariant</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#ae3b1b80ef450d6706f42f3a929e51ce5">llvm::RecurrenceDescriptor::AddReductionVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargettransforminfo-cpp/#a786a99e437c617417c56b4b4678138b9">canTailPredicateLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a3f16b49acc2669722d78d71f3163bbe6">computeUnrollAndJamCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a9336eb7b4fbcee561dbb8c52d9eabe64">createWidenInductionRecipes</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#afe024d2bcdcaa9644b7270f84edd74a5">findForkedPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a14bc7872374f530d4ed193d9921825c5">genLoopLimit</a>, <a href="#a69f32678ea46cdda0318c0be9bdb1c7e">getAddRecExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a78171da3a30a449d469ccebbff57760e">getAppleRuntimeUnrollPreferences</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopvectorize-cpp-/generatedrtchecks/#ad7b44d9befce70f070d4355d10ffc419">anonymous{LoopVectorize.cpp}::GeneratedRTChecks::getCost</a>, <a href="#a094d95c92490272d4b7a6bf4ab90009d">getLoopInvariantExitCondDuringFirstIterationsImpl</a>, <a href="#a741e5065c867d7dfd716eb8e16fccf12">getLoopInvariantPredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8021a49018596bcbea563e6d5cac9a70">llvm::getPtrStride</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdd1ebe6412f9afb43d0639420afffe0">llvm::getStartAndEndForAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a4736b509c1f8cc3d4f7a44e2a4283ee0">getStrideFromPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a6c22989c03e43928e4b09cfa60a804f5">llvm::ARMTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a2d58e737d5b362a238d1b9cfbd961532">hasComputableBounds</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#afe702618f56478e67eb0f705efb648b6">llvm::Loop::isAuxiliaryInductionVariable</a>, <a href="#aadf992d0faba329a1b5315dcde978e85">isAvailableAtLoopEntry</a>, <a href="/web-llvm/docs/api/structs/llvm/hardwareloopinfo/#aef4460eccacc720018aa15086026c11d">llvm::HardwareLoopInfo::isHardwareLoopCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#acdb97daf1829f811db20dff44887fe9e">llvm::InductionDescriptor::isInductionPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo/#a7c8ab4f18a9d6acb6ad8a02fcf89c705">llvm::LoopAccessInfo::isInvariant</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a7f4bd2b45f0af65f9dd7ac1b949b528e">isNoWrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp/#a04de41a04706e275a5161b62cfe2b790">isOneDimensionalArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a187751c86d349fac41ddc1b807b40b22">mayUsePostIncMode</a>, <a href="#a77b275a78beac200ef1f703d2a5fbb7d">print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb5b48f89efd60ea799bb09abc1971ba">llvm::rewriteLoopExitValues</a>, <a href="#a5e9fc2b9bb75a684c20ca3fa6e14b63e">SimplifyICmpOperands</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#aa079180719a27f78e40cfa3f4412a7b2">stripGetElementPtr</a>.</p>

</div>
</div>

### isSCEVable() {#a6d8769a72303e2b06ef63129cb231855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isSCEVable (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test if values of the given type are analyzable within the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> framework.</p>


<p>This primarily includes integer types, and it can optionally include pointer types if the <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> class has access to target-specific information.</p>


<p>Declaration at line 495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4441 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#a0e67dc55f94f7419d24a39fa5b79c42f">canFoldTermCondOfLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a9766c807d5c90cf726463e300d0787d8">DbgGatherSalvagableDVI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#afe024d2bcdcaa9644b7270f84edd74a5">findForkedPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a262aeb2eecfb752ae2eecb90bab7ec8a">findIVOperand</a>, <a href="#a830ba09d5969cd66878b05c17fdf66b6">forgetBlockAndLoopDispositions</a>, <a href="#aa6dc58a1259941c7a17142e6103d059e">forgetLcssaPhiWithNewPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>, <a href="#aa35959e3f6bea8e35cffcfd8659e3156">getAnyExtendExpr</a>, <a href="#a6dcfa69ce27cf214caaf50f21bfe1f2f">getEffectiveSCEVType</a>, <a href="#a9d68d0e13d6aafb4a3ab1cdb5e83ff29">getExistingSCEV</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a6612c20f7ca23077265026ea4991e2b6">GetInductionVariable</a>, <a href="#a30bd18ac905eacf3601bc6a553a9ff49">getSCEV</a>, <a href="#ab26bea71791cf347c631d2072e41cfb5">getSignExtendExpr</a>, <a href="#a643b61ddaf17331f3ff1d4f85c7c9a23">getSignExtendExprImpl</a>, <a href="#a83c084b0947edf4ae748f9a73babf7b8">getTruncateExpr</a>, <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a>, <a href="#a6d745b25efdc69435508f1e936919f8b">getZeroExtendExpr</a>, <a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a3c81223cabf643af27adba3b3ceb680c">isExistingPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a797a268a4ac8802907a1b36ee57166e2">llvm::RecurrenceDescriptor::isFindLastIVPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a7ac21134b2aaca2a7d55f6ff9d92f5b2">isHighCostExpansion</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#acdb97daf1829f811db20dff44887fe9e">llvm::InductionDescriptor::isInductionPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo/#a7c8ab4f18a9d6acb6ad8a02fcf89c705">llvm::LoopAccessInfo::isInvariant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a7803cd22b4405090d0cb0b87d697a612">isLoopCounter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a20b9f8b4f6ae54271f0d5ef676cc036a">llvm::isProcessableCondBI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp/#a3e219df8a1368668aa0aac77616a4ce9">isSimpleIVUser</a>, <a href="#a77b275a78beac200ef1f703d2a5fbb7d">print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb5b48f89efd60ea799bb09abc1971ba">llvm::rewriteLoopExitValues</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a>.</p>

</div>
</div>

### loopHasNoAbnormalExits() {#a3db092f7661158b76135b3b7d39f0991}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ScalarEvolution::loopHasNoAbnormalExits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
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

<p>Return true if the loop has no abnormal exits.</p>


<p>That is, if the loop is not infinite, it must exit through an explicit edge in the CFG. (As opposed to either a) throwing out of the function or b) entering a well defined infinite loop in some callee.)</p>


<p>Definition at line 1353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>.</p>

</div>
</div>

### loopIsFiniteByAssumption() {#a9b1509388282f293de48b34276e5b538}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::loopIsFiniteByAssumption (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this loop is finite by assumption.</p>


<p>That is, to be infinite, it must also be undefined.</p>


<p>Declaration at line 1359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 7465 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a74f807e3ffa9720347aa991a0877eba7">llvm::isFinite</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6de4882dde0c939a449377f8f8abb8a8">llvm::isMustProgress</a>.</p>

</div>
</div>

### print() {#a77b275a78beac200ef1f703d2a5fbb7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScalarEvolution::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 13924 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a247228281134df11d6531a5925a9ba18">ClassifyExpressions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad6e19a09aeed4c56617c284e099c81de">llvm::depth_first</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="#a61f5098e98f972466ae233e6d01f9f9c">getLoopDisposition</a>, <a href="#a30bd18ac905eacf3601bc6a553a9ff49">getSCEV</a>, <a href="#a21d6ee82eed29080d911dbb548a8bb68">getSCEVAtScope</a>, <a href="#a3498df9755182f44e759fd3eeb688e9f">getSignedRange</a>, <a href="#a7593d52f91ebe342de9fa72846ebe755">getUnsignedRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a5a19768af81df7e5fe571bc08dcd48b3">isLoopInvariant</a>, <a href="#a6d8769a72303e2b06ef63129cb231855">isSCEVable</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a8831f85b65cbcc9cf42d70988845a9f6">llvm::ConstantRange::print</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#acdbe9e14ed6edbd5b5e3c252585902ec">llvm::SCEV::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a7170e1b99a9c472642f756b8cf098afa">PrintLoopInfo</a> and <a href="#a3f0118e315585ef6debe98a13336ae75">ScalarEvolution</a>.</p>

</div>
</div>

### properlyDominates() {#ae0d036af111b8aafe90db0771b8e9ce3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::properlyDominates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if elements that makes up the given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> properly dominate the specified basic block.</p>

<p>Declaration at line 1260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 14192 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a92fb0984f10499fff4a7c9b32de2a0a6">getBlockDisposition</a> and <a href="#aae7c3ec1a0344306acbdc2dcb113995ea95af43f9c06d0fe35d8c8ec1786028cb">ProperlyDominatesBlock</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#aa59a46776e15b1f1bd597c4e1e769f59">DoInitialMatch</a>, <a href="#aadf992d0faba329a1b5315dcde978e85">isAvailableAtLoopEntry</a> and <a href="#a5e9fc2b9bb75a684c20ca3fa6e14b63e">SimplifyICmpOperands</a>.</p>

</div>
</div>

### registerUser() {#aeefacaa2eccab8db38ff9ccdad1e0b1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScalarEvolution::registerUser (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * User, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Notify this <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> that <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/user">User</a></span> directly uses SCEVs in <span class="doxyComputerOutput">Ops</span>.</p>

<p>Declaration at line 545 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 15106 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a4bab447a6422427e5fc92bbbc0c12fba">getLosslessPtrToIntExpr</a>, <a href="#ac3221ac3fcd879a1c716aa954837df79">getMinMaxExpr</a>, <a href="#a4976a99a4f39b4daee84f4f60319df03">getSequentialMinMaxExpr</a>, <a href="#a643b61ddaf17331f3ff1d4f85c7c9a23">getSignExtendExprImpl</a>, <a href="#a83c084b0947edf4ae748f9a73babf7b8">getTruncateExpr</a>, <a href="#a6c03d18ed744dc3b34829ec5485a68b0">getUDivExpr</a> and <a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a>.</p>

</div>
</div>

### removePointerBase() {#a1e4038e28db703c29e5e3de1549806ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::removePointerBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute an expression equivalent to S - getPointerBase(S).</p>

<p>Declaration at line 759 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4625 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">llvm::SCEV::FlagAnyWrap</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#a659b27f6737fcb7eaf333b0279da1154">getAddRecExpr</a>, <a href="#a2579491850c605c8b7cf3439a907fbed">getZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#a1e4038e28db703c29e5e3de1549806ca">removePointerBase</a>.</p>


<p>Referenced by <a href="#a8bcb86d8d126d95b0dc05f09e8f3df96">getMinusSCEV</a> and <a href="#a1e4038e28db703c29e5e3de1549806ca">removePointerBase</a>.</p>

</div>
</div>

### rewriteUsingPredicate() {#ae78e890f2ef71a10fca3f21f0833b535}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::rewriteUsingPredicate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> &amp; A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Re-writes the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> according to the Predicates in <span class="doxyComputerOutput">A</span>.</p>

<p>Declaration at line 1286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 14902 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevpredicaterewriter/#aa0dfcf92c2eba1cb8bb38be9ac1e6eef">anonymous{ScalarEvolution.cpp}::SCEVPredicateRewriter::rewrite</a>.</p>

</div>
</div>

### setNoWrapFlags() {#a248dea99ef1d5a864269ac3a98014b37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScalarEvolution::setNoWrapFlags (<a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * AddRec, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update no-wrap flags of an AddRec.</p>


<p>This may drop the cached info about this AddRec (such as range info) in case if new flags may potentially sharpen it.</p>


<p>Declaration at line 1307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 6430 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a7275347a4dce174f4fecd548fd3255dc">llvm::SCEVNAryExpr::getNoWrapFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a5316a2763777f3670c1606452f4e99d7">llvm::SCEVAddRecExpr::setNoWrapFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a359235e468f7ab6f4dccbed37c17dee1">getPreStartForExtend</a>, <a href="#a643b61ddaf17331f3ff1d4f85c7c9a23">getSignExtendExprImpl</a> and <a href="#a26ffa319e1953452b1d1df84923f2108">getZeroExtendExprImpl</a>.</p>

</div>
</div>

### SimplifyICmpOperands() {#a5e9fc2b9bb75a684c20ca3fa6e14b63e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::SimplifyICmpOperands (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> &amp; Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *&amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *&amp; RHS, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Simplify LHS and RHS in a comparison with predicate Pred.</p>


<p>Return true iff any changes were made. If the operands are provably equal or unequal, LHS and RHS are set to the same value and Pred is set to either ICMP_EQ or ICMP_NE.</p>


<p>Declaration at line 1228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 10759 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a5769f1da829d6f6400b486d8e34e317f">llvm::ICmpInst::compare</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa2f7a8775a783f7ea3ad24b3f9cb5d949">llvm::SCEV::FlagNSW</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faafb62cd6afdc004ef6e8a1f6288eb382">llvm::SCEV::FlagNUW</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#a2eb94d079d8416118f4aaed865ab05d7">getConstant</a>, <a href="#aff9e533399d91febd63fa4bfe82a42a7">getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a1616515fc811646b8cc5e6625e36b954">llvm::ConstantRange::getEquivalentICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a99ab4a82c6d7373e2e367986b9527bf0">llvm::SCEVAddRecExpr::getLoop</a>, <a href="#afee50be11e579d3c510e73df2a21cb88">getSignedRangeMax</a>, <a href="#a809289b45cd6625629f5356f70dac72d">getSignedRangeMin</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a5661ce1d8f7e67d51e712ee12ea1e29f">llvm::ICmpInst::getSwappedCmpPredicate</a>, <a href="#ac8de32f4d40eae96f0e26f0728682c2e">getUnsignedRangeMax</a>, <a href="#a5d61e3035097c0e57849c6d3f195597d">getUnsignedRangeMin</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#aea8979aa7e40386835642f9f5f9f36d2">HasSameValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a5bd6d98b4a7ecc1dcdc571e4352fcc52">llvm::ConstantRange::isEmptySet</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#abe8988eef2e6fc2baba032cb22afedd7">llvm::ICmpInst::isEquality</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a1e32582702cf5b9d4484c0ce346b2f57">llvm::CmpInst::isFalseWhenEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a4f6242fab5145c424cee29230fefe746">llvm::ConstantRange::isFullSet</a>, <a href="#a5a19768af81df7e5fe571bc08dcd48b3">isLoopInvariant</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a5ba8484cef2818d14b85640a903b2598">llvm::CmpInst::isTrueWhenEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa89e9cec92a0b38d2f47a077bf12cc98">llvm::ConstantRange::makeExactICmpRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a64c01f06f3fbc87797023dbf0e8de702">MatchBinarySub</a>, <a href="#ae0d036af111b8aafe90db0771b8e9ce3">properlyDominates</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#a3e47bdb3e296b00df96eff7896fa57bf">RA</a>, <a href="#a5e9fc2b9bb75a684c20ca3fa6e14b63e">SimplifyICmpOperands</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#af74112dae88db73eb5484821b6f0fccd">isKnownPredicate</a> and <a href="#a5e9fc2b9bb75a684c20ca3fa6e14b63e">SimplifyICmpOperands</a>.</p>

</div>
</div>

### SplitIntoInitAndPostInc() {#ae7a40d693574be8048944e80774e6c1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; const SCEV *, const SCEV * &gt; ScalarEvolution::SplitIntoInitAndPostInc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Splits <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression <span class="doxyComputerOutput">S</span> into two SCEVs.</p>


<p>One of them is obtained from <span class="doxyComputerOutput">S</span> by substitution of all AddRec sub-expression related to loop <span class="doxyComputerOutput">L</span> with initial value of that <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>. The second is obtained from <span class="doxyComputerOutput">S</span> by substitution of all AddRec sub-expressions related to loop <span class="doxyComputerOutput">L</span> with post increment of this AddRec in the loop <span class="doxyComputerOutput">L</span>. In both cases all other AddRec sub-expressions (not related to <span class="doxyComputerOutput">L</span>) remain the same. If the <span class="doxyComputerOutput">S</span> contains non-invariant unknown <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> the function returns CouldNotCompute <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> in both values of std::pair. For example, for <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> S={0, +, 1}&lt;L1&gt; + {0, +, 1}&lt;L2&gt; and loop L=L1 the function returns pair: first = {0, +, 1}&lt;L2&gt; second = {1, +, 1}&lt;L1&gt; + {0, +, 1}&lt;L2&gt; We can see that for the first AddRec sub-expression it was replaced with 0 (initial value) for the first element and to {1, +, 1}&lt;L1&gt; (post increment value) for the second one. In both cases AddRec expression related to L2 remains the same.</p>


<p>Declaration at line 1063 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 10988 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aaa9b9055fd9c69fe14eb20f0d18d53d5">getCouldNotCompute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-cpp/#a5d6e37f3d036496321824378223ad718a1673ee57164ca23d9545b629b55e08d2">PostInc</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevinitrewriter/#ae81805394c188339347a77ae1725c4f4">anonymous{ScalarEvolution.cpp}::SCEVInitRewriter::rewrite</a> and <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevpostincrewriter/#a3955473b3f8330b2b6f3b94f378abe64">anonymous{ScalarEvolution.cpp}::SCEVPostIncRewriter::rewrite</a>.</p>


<p>Referenced by <a href="#afd0a71dc4e0ed5b83c50e875e6726661">isKnownViaInduction</a>.</p>

</div>
</div>

### verify() {#aff82c03c1ce8b945170bcb1f0f624c17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScalarEvolution::verify ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 14357 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#af74676a3c7447be34bd2c1da76ec0c48">llvm::SmallPtrSetImpl&lt; PtrType &gt;::contains</a>, <a href="#aa8d280cc2c5792b3144274e675e36385">containsUndefs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#a22d9bcbd44563106d7217f3bd9a4039e">getBackedgeTakenCount</a>, <a href="#a92fb0984f10499fff4a7c9b32de2a0a6">getBlockDisposition</a>, <a href="#a2eb94d079d8416118f4aaed865ab05d7">getConstant</a>, <a href="#a18000513ba14bd153f16edd92c4505b2">getConstantMultiple</a>, <a href="#aaa9b9055fd9c69fe14eb20f0d18d53d5">getCouldNotCompute</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a99ab4a82c6d7373e2e367986b9527bf0">llvm::SCEVAddRecExpr::getLoop</a>, <a href="#a61f5098e98f972466ae233e6d01f9f9c">getLoopDisposition</a>, <a href="#a8bcb86d8d126d95b0dc05f09e8f3df96">getMinusSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="#a30bd18ac905eacf3601bc6a553a9ff49">getSCEV</a>, <a href="#a2c96114e89e8cf2122ebe8bc4d929c7c">getTypeSizeInBits</a>, <a href="#ad8e4f5b2ced08ad7d138b598aefdd338">getUnknown</a>, <a href="/web-llvm/docs/api/classes/llvm/scevunknown/#a9528d1498a3a1b2f06800cabc45a7f42">llvm::SCEVUnknown::getValue</a>, <a href="#a6d745b25efdc69435508f1e936919f8b">getZeroExtendExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#a4541962f9c18aacceb7243520eb15e1f">llvm::SCEV::isZero</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#a0b675a820ab094d694d602eb16ef02e5">llvm::SCEV::operands</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a205029ee514828d0fb4988399ef3ece4af3b3369c27dc1c8355bcccdf3b7d5578">llvm::Predicated</a>, <a href="#a3f0118e315585ef6debe98a13336ae75">ScalarEvolution</a>, <a href="#a9a1917da5135c7cd0431c35b583db2aa">SCEVUnknown</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a4e3a2187cacdec76028617a403c47d89">llvm::APInt::urem</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#af70a3e718bdc53625c4122c3edd88b8d">VerifySCEVStrict</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/functiontolooppassadaptor/#aee681bfb37f62d30a1d0a1f47d73b4f1">llvm::FunctionToLoopPassAdaptor::run</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>.</p>

</div>
</div>

### willNotOverflow() {#a267fd27cb9e177fa5f48cbb8828339a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::willNotOverflow (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> BinOp, bool Signed, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is operation <span class="doxyComputerOutput">BinOp</span> between <span class="doxyComputerOutput">LHS</span> and <span class="doxyComputerOutput">RHS</span> provably does not have a signed/unsigned overflow (<span class="doxyComputerOutput">Signed</span>)?</p>


<p>If <span class="doxyComputerOutput">CtxI</span> is specified, the no-overflow fact should be true in the context of this instruction.</p>


<p>Declaration at line 532 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 2314 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">llvm::SCEV::FlagAnyWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#a2eb94d079d8416118f4aaed865ab05d7">getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a331d69b5f93e47e7c596062b77dd5913">llvm::APInt::getMaxValue</a>, <a href="#a8bcb86d8d126d95b0dc05f09e8f3df96">getMinusSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a65a6479206acd4113b8aa1c0fbc2158c">llvm::APInt::getMinValue</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a562c9513409b74f02cb3a5c9bae672ea">llvm::APInt::getSignedMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="#ab26bea71791cf347c631d2072e41cfb5">getSignExtendExpr</a>, <a href="#a6d745b25efdc69435508f1e936919f8b">getZeroExtendExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="#aeaae2161ba70381e225ac6800af5d961">isKnownPredicateAt</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a5b2aa9d3f9f3a7b2d123fef7c5328b8f">Operation</a>, <a href="#a3f0118e315585ef6debe98a13336ae75">ScalarEvolution</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>.</p>


<p>Referenced by <a href="#aa6a8e1063693697569fead19a720c43c">getStrengthenedNoWrapFlagsFromBinOp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### canIVOverflowOnGT() {#aa5315a687d765fc01b5a2c50d009a2c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::canIVOverflowOnGT (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Stride, bool IsSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify if an linear IV with negative stride can overflow when in a greater-than comparison, knowing the invariant term of the comparison, the stride.</p>

<p>Declaration at line 2251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 12864 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### canIVOverflowOnLT() {#ae78c431412e92d16c80efff40339ada1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::canIVOverflowOnLT (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Stride, bool IsSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify if an linear IV with positive stride can overflow when in a less-than comparison, knowing the invariant term of the comparison, the stride.</p>

<p>Declaration at line 2246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 12840 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### checkValidity() {#adee32c2f1921223f5acacae278f3c167}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::checkValidity (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return false iff given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> contains a <a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a> with NULL value- pointer.</p>

<p>Declaration at line 2135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4491 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### computeBackedgeTakenCount() {#aa76802ab848e6f5cd982fa9de101c31f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution::BackedgeTakenInfo ScalarEvolution::computeBackedgeTakenCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, bool AllowPredicates=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the number of times the specified loop will iterate.</p>


<p>Compute the number of times the backedge of the specified loop will execute.</p>


<p>If AllowPredicates is set, we will create new <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicates as necessary in order to return an exact answer.</p>


<p>Declaration at line 1837 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8830 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### computeBlockDisposition() {#ae68bff9bed0c19a8d6943110bdeb719d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution::BlockDisposition ScalarEvolution::computeBlockDisposition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute a <a href="#aae7c3ec1a0344306acbdc2dcb113995e">BlockDisposition</a> value.</p>

<p>Declaration at line 1711 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 14133 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### computeExitCountExhaustively() {#af38c7c135bb3cb672d64efcdc2ce86a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::computeExitCountExhaustively (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Cond, bool ExitWhen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the loop is known to execute a constant number of times (the condition evolves only from constants), try to evaluate a few iterations of the loop until we get the exit condition gets a value of ExitWhen (true or false).</p>


<p>If we cannot evaluate the exit count of the loop, return CouldNotCompute.</p>


<p>Declaration at line 1932 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 9787 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### computeExitLimit() {#aa6409e7b9848a1a6c91f713b93ee7921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution::ExitLimit ScalarEvolution::computeExitLimit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * ExitingBlock, bool IsOnlyExit, bool AllowPredicates=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the number of times the backedge of the specified loop will execute if it exits via the specified block.</p>


<p>If AllowPredicates is set, this call will try to use a minimal set of <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicates in order to return an exact answer.</p>


<p>Declaration at line 1844 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8933 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### computeExitLimitFromCondCached() {#a6bd95793e2853d9355dd8ec9e1d61b31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution::ExitLimit ScalarEvolution::computeExitLimitFromCondCached (ExitLimitCacheTy &amp; Cache, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ExitCond, bool ExitIfTrue, bool ControlsOnlyExit, bool AllowPredicates)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1877 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 9011 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### computeExitLimitFromCondFromBinOp() {#a4ba8e3fb91bc0a29bc632c29e9fffa7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ScalarEvolution::ExitLimit &gt; ScalarEvolution::computeExitLimitFromCondFromBinOp (ExitLimitCacheTy &amp; Cache, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ExitCond, bool ExitIfTrue, bool ControlsOnlyExit, bool AllowPredicates)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1886 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 9088 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### computeExitLimitFromCondImpl() {#a4442b5e96654bdcf0176687dc8cae5ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution::ExitLimit ScalarEvolution::computeExitLimitFromCondImpl (ExitLimitCacheTy &amp; Cache, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ExitCond, bool ExitIfTrue, bool ControlsOnlyExit, bool AllowPredicates)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1882 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 9025 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### computeExitLimitFromICmp() {#aa819a97e0537efe10494b69c0d208852}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution::ExitLimit ScalarEvolution::computeExitLimitFromICmp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * ExitCond, bool ExitIfTrue, bool IsSubExpr, bool AllowPredicates=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the number of times the backedge of the specified loop will execute if its exit condition were a conditional branch of the <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> ExitCond and ExitIfTrue.</p>


<p>If AllowPredicates is set, this call will try to use a minimal set of <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicates in order to return an exact answer.</p>


<p>Declaration at line 1895 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 9168 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### computeExitLimitFromICmp() {#a5e7f526b39280a60de46b6419602a3a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution::ExitLimit ScalarEvolution::computeExitLimitFromICmp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, bool IsSubExpr, bool AllowPredicates=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Variant of previous which takes the components representing an ICmp as opposed to the <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> itself.</p>


<p>Note that the prior version can return more precise results in some cases and is preferred when caller has a materialized ICmp.</p>


<p>Declaration at line 1904 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 9196 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### computeExitLimitFromSingleExitSwitch() {#a32a9e14782c38383d73d152a580045e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution::ExitLimit ScalarEvolution::computeExitLimitFromSingleExitSwitch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> * Switch, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * ExitingBB, bool IsSubExpr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the number of times the backedge of the specified loop will execute if its exit condition were a switch with a single exiting case to ExitingBB.</p>

<p>Declaration at line 1912 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 9369 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### computeLoopDisposition() {#ac029348311bcc4bcbed0b090e0cc15ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution::LoopDisposition ScalarEvolution::computeLoopDisposition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute a <a href="#a9f7c88892cfe1646082bf6174a4b912c">LoopDisposition</a> value.</p>

<p>Declaration at line 1702 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 14034 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### computeMaxBECountForLT() {#acb0ee2aa6765d464b5c6b2ab19cf97c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::computeMaxBECountForLT (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Start, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Stride, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * End, unsigned BitWidth, bool IsSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the maximum backedge count based on the range of values permitted by Start, End, and Stride.</p>


<p>This is for loops of the form {Start, +, Stride} LT End.</p>


<p>Preconditions:</p>


<ul class="doxyList ">
<li>the induction variable is known to be positive.</li>
<li>the induction variable is assumed not to overflow (i.e. either it actually doesn't, or we'd have to immediately execute UB) We <em>don't</em> assert these preconditions so please be careful.</li>
</ul>

<p>Declaration at line 2239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 12896 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### computeSCEVAtScope() {#af1366acc817c38a46ae6758e6fcc677c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::computeSCEVAtScope (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implementation code for getSCEVAtScope; called at most once for each SCEV+Loop pair.</p>

<p>Declaration at line 1823 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 9977 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### computeShiftCompareExitLimit() {#a6acbf52a09b6861513769f4bdc0f2b36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution::ExitLimit ScalarEvolution::computeShiftCompareExitLimit (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">ICmpInst::Predicate</a> Pred)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the exit limit of a loop that is controlled by a "(IV &gt;&gt; 1) != 0" type comparison.</p>


<p>We cannot compute the exact trip count in these cases (since <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> has no way of expressing them), but we can still sometimes compute an upper bound.</p>


<p>Return an <a href="/web-llvm/docs/api/structs/llvm/scalarevolution/exitlimit">ExitLimit</a> for a loop whose backedge is guarded by <span class="doxyComputerOutput">LHS Pred RHS</span>.</p>


<p>Declaration at line 1924 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 9402 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### createAddRecFromPHI() {#a77be49741262b0ad114fb2aaa777570c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::createAddRecFromPHI (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function called from createNodeForPHI.</p>

<p>Declaration at line 1789 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 5780 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### createAddRecFromPHIWithCastsImpl() {#a3f2351e880db97150c09300d5f36857d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::pair&lt; const SCEV *, SmallVector&lt; const SCEVPredicate *, 3 &gt; &gt; &gt; ScalarEvolution::createAddRecFromPHIWithCastsImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a> * SymbolicPHI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Similar to createAddRecFromPHI, but with the additional flexibility of suggesting runtime overflow checks in case casts are encountered.</p>


<p>If successful, the analysis records that for this loop, <span class="doxyComputerOutput">SymbolicPHI</span>, which is the UnknownSCEV currently representing the PHI, can be rewritten into an AddRec, assuming some predicates; The function then returns the AddRec and the predicates as a pair, and caches this pair in PredicatedSCEVRewrites. If the analysis is not successful, a mapping from the <span class="doxyComputerOutput">SymbolicPHI</span> to itself (with no predicates) is recorded, and a nullptr with an empty predicates vector is returned as a pair.</p>


<p>Declaration at line 2228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 5452 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### createNodeForGEP() {#a4a2efdf65c0d248d8834ae744d86f323}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::createNodeForGEP (<a href="/web-llvm/docs/api/classes/llvm/gepoperator">GEPOperator</a> * GEP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Provide the special handling we need to analyze GEP SCEVs.</p>


<p>Expand GEP instructions into add and multiply operations.</p>


<p>This allows them to be analyzed by regular <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> code.</p>


<p>Declaration at line 1819 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 6295 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### createNodeForPHI() {#acd57b93f72e39162b5c322db730b32a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::createNodeForPHI (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Provide the special handling we need to analyze PHI SCEVs.</p>

<p>Declaration at line 1786 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 6046 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### createNodeForPHIWithIdenticalOperands() {#aa7f7c1841099ab8afd4c084a0eef97d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::createNodeForPHIWithIdenticalOperands (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> for the first operand of a phi if all phi operands have identical opcodes and operands.</p>


<p>Returns <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> for the first operand of a phi if all phi operands have identical opcodes and operands eg.</p>


<p>a: add = a + b br c b: add1 = a + b br c c: phi = phi [add, a], [add1, b] scev(phi) =&gt; scev(add)</p>


<p>Declaration at line 1783 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 6020 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### createNodeForSelectOrPHI() {#ac9ba4ef072ce4673921a8e5928651ce1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::createNodeForSelectOrPHI (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Cond, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * TrueVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * FalseVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a value <span class="doxyComputerOutput">V</span>, which is a select-like instruction (currently this is either a select instruction or a phi node), which is assumed equivalent to Cond ?</p>


<p>TrueVal : FalseVal see if we can model it as a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression.</p>


<p>Declaration at line 1815 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 6273 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### createNodeForSelectOrPHIInstWithICmpInstCond() {#a658f6372905ff1b7900113b0270bee48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; const SCEV * &gt; ScalarEvolution::createNodeForSelectOrPHIInstWithICmpInstCond (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * Cond, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * TrueVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * FalseVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Provide special handling for a select-like instruction (currently this is either a select instruction or a phi node).</p>


<p><span class="doxyComputerOutput">Ty</span> is the type of the instruction being processed, that is assumed equivalent to "Cond ? TrueVal : FalseVal".</p>


<p>Declaration at line 1803 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 6104 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### createNodeForSelectOrPHIViaUMinSeq() {#a5e55bf47ce597c176a203abe0058950a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::createNodeForSelectOrPHIViaUMinSeq (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * I, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Cond, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * TrueVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * FalseVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See if we can model this select-like instruction via umin_seq expression.</p>

<p>Declaration at line 1807 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 6255 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### createNodeFromSelectLikePHI() {#a9cb3871e55141321ca2d62a82989d8c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::createNodeFromSelectLikePHI (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function called from createNodeForPHI.</p>

<p>Declaration at line 1796 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 5978 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### createSCEV() {#ad2656ae0e17fe5d7da2e6def92ee4d00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::createSCEV (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We know that there is no <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> for the specified value.</p>


<p>Analyze the expression recursively.</p>


<p>Declaration at line 1771 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 7700 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### createSCEVIter() {#af50a59443360ee6580f9424ea440c374}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::createSCEVIter (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We know that there is no <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> for the specified value.</p>


<p>Create a new <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> for <span class="doxyComputerOutput">V</span> iteratively.</p>


<p>Declaration at line 1775 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 7472 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### createSimpleAffineAddRec() {#aa1091a8a57e832868a4c5a8b513fe002}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::createSimpleAffineAddRec (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PN, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * BEValueV, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * StartValueV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A helper function for createAddRecFromPHI to handle simple cases.</p>


<p>This function tries to find an AddRec expression for the simplest (yet most common) cases: PN = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI(Start, OP(Self, LoopInvariant))</a>. If it fails, createAddRecFromPHI will use a more general, but slow, technique for finding the AddRec expression.</p>


<p>Declaration at line 1792 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 5728 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### eraseValueFromMap() {#af0f0298991197b4afda45dad52dc6abc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScalarEvolution::eraseValueFromMap (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Erase <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> from ValueExprMap and ExprValueMap.</p>


<p>ValueExprMap.erase(V) cannot be used separately. eraseValueFromMap should be used to remove V from ValueExprMap and ExprValueMap at the same time.</p>


<p>Declaration at line 2128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4523 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### findExistingSCEVInCache() {#a9560ce040bda46ab2f01ae9d56ed9413}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCEV * ScalarEvolution::findExistingSCEVInCache (<a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5e">SCEVTypes</a> SCEVType, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look for a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression with type <span class="doxyComputerOutput">SCEVType</span> and operands <span class="doxyComputerOutput">Ops</span> in <span class="doxyComputerOutput">UniqueSCEVs</span>.</p>


<p>Return if found, else nullptr.</p>


<p>Declaration at line 2279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 3813 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### forgetBackedgeTakenCounts() {#acf4763d7397ff28867970f6aedf9c47e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScalarEvolution::forgetBackedgeTakenCounts (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, bool Predicated)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Forget predicated/non-predicated backedge taken counts for the given loop.</p>

<p>Declaration at line 2113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 14200 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### forgetMemoizedResults() {#a1adcf075a7f9844b55ce4f3d1094192c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScalarEvolution::forgetMemoizedResults (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; SCEVs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Drop memoized information for all <span class="doxyComputerOutput">SCEVs</span>.</p>

<p>Declaration at line 2116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 14219 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### forgetMemoizedResultsImpl() {#aa147db85cb7b1070e8b496db8e4fb108}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScalarEvolution::forgetMemoizedResultsImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper for forgetMemoizedResults.</p>

<p>Declaration at line 2119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 14245 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getBackedgeTakenInfo() {#a5a06b5bed55cce32bf8894dfe50d5001}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution::BackedgeTakenInfo &amp; ScalarEvolution::getBackedgeTakenInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the BackedgeTakenInfo for the given loop, lazily computing new values if the loop hasn't been analyzed yet.</p>


<p>The returned result is guaranteed not to be predicated.</p>


<p>Declaration at line 1828 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8405 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getConstantEvolutionLoopExitValue() {#afbb1d45f9fec6bfdfd2c21f5d79e7d58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ScalarEvolution::getConstantEvolutionLoopExitValue (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PN, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; BEs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If we know that the specified Phi is in the header of its containing loop, we know the loop executes a constant number of times, and the PHI node is just a recurrence involving constants, fold it.</p>


<p>getConstantEvolutionLoopExitValue - If we know that the specified Phi is in the header of its containing loop, we know the loop executes a constant number of times, and the PHI node is just a recurrence involving constants, fold it.</p>


<p>Declaration at line 2087 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 9705 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getConstantMultipleImpl() {#a5e41ccb61c6c3cb64d14f122facbe911}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt ScalarEvolution::getConstantMultipleImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Private helper method for the getConstantMultiple method.</p>

<p>Declaration at line 1494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 6305 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getDefiningScopeBound() {#a89e5c9c0e24c3cf489959b38c1a64fd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Instruction * ScalarEvolution::getDefiningScopeBound (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; Ops, bool &amp; Precise)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a scope which provides an upper bound on the defining scope for a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> with the operands in Ops.</p>


<p>The outparam Precise is set if the bound found is a precise bound (i.e. must be the defining scope.)</p>


<p>Declaration at line 2175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 7286 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getDefiningScopeBound() {#ac2110fcdb61cc336dd096f1f91daa0f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Instruction * ScalarEvolution::getDefiningScopeBound (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Wrapper around the above for cases which don't care if the bound is precise.</p>

<p>Declaration at line 2180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 7321 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getLoopProperties() {#a9abdda86f5368eea672ceff91bc0501e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution::LoopProperties ScalarEvolution::getLoopProperties (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a <span class="doxyComputerOutput">LoopProperties</span> instance for <span class="doxyComputerOutput">L</span>, creating one if necessary.</p>

<p>Declaration at line 1695 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 7432 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getMonotonicPredicateTypeImpl() {#aa89bb41b2b40957875bab58d1a800182}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ScalarEvolution::MonotonicPredicateType &gt; ScalarEvolution::getMonotonicPredicateTypeImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">ICmpInst::Predicate</a> Pred)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 11126 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getNonTrivialDefiningScopeBound() {#afedbfa75eee412fbacef2b57bfd79ede}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Instruction * ScalarEvolution::getNonTrivialDefiningScopeBound (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a scope which provides an upper bound on the defining scope of 'S'.</p>


<p>Specifically, return the first instruction in said bounding scope. Return nullptr if the scope is trivial (function entry). (See scope definition rules associated with flag discussion above)</p>


<p>Declaration at line 2170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 7276 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getNoWrapFlagsFromUB() {#a46cd40c1296e0a2ea4793aa9ebe4c7f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCEV::NoWrapFlags ScalarEvolution::getNoWrapFlagsFromUB (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> no-wrap flags that can be proven based on reasoning about how poison produced from no-wrap flags on this value (e.g.</p>


<p>a nuw add) would trigger undefined behavior on overflow.</p>


<p>Declaration at line 2164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 7259 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getOperandsToCreate() {#a4f06eed03071edf91894029713d20195}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getOperandsToCreate (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect operands of <span class="doxyComputerOutput">V</span> for which <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expressions should be constructed first.</p>


<p>Returns a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> directly if it can be constructed trivially for <span class="doxyComputerOutput">V</span>.</p>


<p>Declaration at line 1779 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 7514 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getOrCreateAddExpr() {#ae837549254d3833922b6843ddf240543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getOrCreateAddExpr (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; Ops, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get add expr already created or create a new one.</p>

<p>Declaration at line 2254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 2984 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getOrCreateAddRecExpr() {#a9448d65fa47e95eba66c447f6d17f068}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getOrCreateAddRecExpr (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; Ops, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 3006 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getOrCreateMulExpr() {#a7968840b93f4e9cc3ffe1341d1791bba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getOrCreateMulExpr (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; Ops, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get mul expr already created or create a new one.</p>

<p>Declaration at line 2258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 3030 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getPredecessorWithUniqueSuccessorForBB() {#a88c31e9e244995ed33fb4962ee489de5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; const BasicBlock *, const BasicBlock * &gt; ScalarEvolution::getPredecessorWithUniqueSuccessorForBB (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a predecessor of BB (which may not be an immediate predecessor) which has exactly one successor from which BB is reachable, or null if no such block is found.</p>

<p>Declaration at line 1971 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 10695 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getPredicatedBackedgeTakenInfo() {#aa285b48d25d9068add19a3fd29ff21d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution::BackedgeTakenInfo &amp; ScalarEvolution::getPredicatedBackedgeTakenInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Similar to getBackedgeTakenInfo, but will add predicates as required with the purpose of returning complete information.</p>

<p>Declaration at line 1832 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8388 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getRangeForAffineAR() {#a220306abffc36e5272d96039ff721b59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ScalarEvolution::getRangeForAffineAR (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Start, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Step, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; MaxBECount)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determines the range for the affine <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> {<span class="doxyComputerOutput">Start</span>,+,<span class="doxyComputerOutput">Step}</span>.</p>


<p>Helper for <span class="doxyComputerOutput">getRange</span>.</p>


<p>Declaration at line 1747 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 7043 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getRangeForAffineNoSelfWrappingAR() {#a83ea8ea58d5a5ac71a1e6d9ed7dc1ee3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ScalarEvolution::getRangeForAffineNoSelfWrappingAR (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * AddRec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * MaxBECount, unsigned BitWidth, RangeSignHint SignHint)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determines the range for the affine non-self-wrapping <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> {<span class="doxyComputerOutput">Start</span>,+,<span class="doxyComputerOutput">Step}</span> &lt;nw&gt;.</p>

<p>Declaration at line 1752 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 7072 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getRangeForUnknownRecurrence() {#aaa46910cf61055949c6b833814b88cae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ScalarEvolution::getRangeForUnknownRecurrence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a> * U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the unknown expression U corresponds to a simple recurrence, return a constant range which represents the entire recurrence.</p>


<p>Note that <em>add</em> recurrences with loop invariant steps aren't represented by SCEVUnknowns and thus don't use this mechanism.</p>


<p>Declaration at line 1767 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 6441 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getRangeRef() {#aad719d3b695dcd6e1b05303e7f71bc29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ConstantRange &amp; ScalarEvolution::getRangeRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, RangeSignHint SignHint, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine the range for a particular <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>.</p>


<p>NOTE: This returns a reference to an entry in a cache. It must be copied if its needed for longer.</p>


<p>If SignHint is HINT_RANGE_UNSIGNED (resp. HINT_RANGE_SIGNED) then getRange prefers ranges with a "cleaner" unsigned (resp. signed) representation.</p>


<p>Declaration at line 1738 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 6641 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getRangeRefIter() {#a6f0f97251f99dea6f5078398d5e6349f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ConstantRange &amp; ScalarEvolution::getRangeRefIter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, RangeSignHint SignHint)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine the range for a particular <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>, but evaluates ranges for operands iteratively first.</p>

<p>Declaration at line 1743 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 6560 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getRangeViaFactoring() {#aa23128e8702fac7c6e5c19e261ab8c28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange ScalarEvolution::getRangeViaFactoring (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Start, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Step, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; MaxBECount)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to compute a range for the affine <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> {<span class="doxyComputerOutput">Start</span>,+,<span class="doxyComputerOutput">Step}</span> by "factoring out" a ternary expression from the add recurrence.</p>


<p>Helper called by <span class="doxyComputerOutput">getRange</span>.</p>


<p>Declaration at line 1760 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 7140 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getReachableBlocks() {#aaabcc8eab6f40da52d8a18e14186b2b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScalarEvolution::getReachableBlocks (<a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; Reachable, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get reachable blocks in this function, making limited use of <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> reasoning about conditions.</p>

<p>Declaration at line 2283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 14320 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getSCEVValues() {#aac30767e8a68665a1b00cfef030d3199}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; Value * &gt; ScalarEvolution::getSCEVValues (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> set from which the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expr is generated.</p>


<p>Return the ValueOffsetPair set for <span class="doxyComputerOutput">S</span>.</p>


<p><span class="doxyComputerOutput">S</span> can be represented by the value and offset from any ValueOffsetPair in the set.</p>


<p>Declaration at line 1491 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4513 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getUsedLoops() {#a61eaf3dd44d27eac001367d128b66781}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScalarEvolution::getUsedLoops (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * &gt; &amp; LoopsUsed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find all of the loops transitively used in <span class="doxyComputerOutput">S</span>, and fill <span class="doxyComputerOutput">LoopsUsed</span>.</p>


<p>A loop is considered "used" by an expression if it contains an add rec on said loop.</p>


<p>Declaration at line 2271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 14301 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### getWithOperands() {#ab70ae7f04d02aff973b59e1ae974989c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::getWithOperands (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; NewOps)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression with a new set of operands.</p>


<p>This preserves the origial nowrap flags.</p>


<p>Declaration at line 2288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 9942 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### howFarToNonZero() {#a87326b020e522a883e2b1d5559b4ea26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution::ExitLimit ScalarEvolution::howFarToNonZero (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of times an exit condition checking the specified value for nonzero will execute.</p>


<p>If not computable, return CouldNotCompute.</p>


<p>Declaration at line 1945 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 10676 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### howFarToZero() {#a57dd341fa6ca92d37352cef792eff0b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution::ExitLimit ScalarEvolution::howFarToZero (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, bool IsSubExpr, bool AllowPredicates=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of times an exit condition comparing the specified value to zero will execute.</p>


<p>If not computable, return CouldNotCompute. If AllowPredicates is set, this call will try to use a minimal set of <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicates in order to return an exact answer.</p>


<p>Declaration at line 1939 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 10523 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### howManyGreaterThans() {#afa2b86521a9188600cd0540e172beb28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution::ExitLimit ScalarEvolution::howManyGreaterThans (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, bool isSigned, bool IsSubExpr, bool AllowPredicates=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1963 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 13386 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### howManyLessThans() {#aa059c79f1aa1bd0bc7f10105f5d185e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution::ExitLimit ScalarEvolution::howManyLessThans (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, bool isSigned, bool ControlsOnlyExit, bool AllowPredicates=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of times an exit condition containing the specified less-than comparison will execute.</p>


<p>If not computable, return CouldNotCompute.</p>


<p><span class="doxyComputerOutput">isSigned</span> specifies whether the less-than is signed.</p>


<p><span class="doxyComputerOutput">ControlsOnlyExit</span> is true when the LHS &lt; RHS condition directly controls the branch (loops exits only if condition is true). In this case, we can use NoWrapFlags to skip overflow checks.</p>


<p>If <span class="doxyComputerOutput">AllowPredicates</span> is set, this call will try to use a minimal set of <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicates in order to return an exact answer.</p>


<p>Declaration at line 1959 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 12946 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### insertValueToMap() {#a6d426e6db7edacb47bd1934b2315d6d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScalarEvolution::insertValueToMap (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert V to S mapping into ValueExprMap and ExprValueMap.</p>

<p>Declaration at line 2131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 4534 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### isAddRecNeverPoison() {#a02d12cb7ecf24114a48def3e16b10a73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isAddRecNeverPoison (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is like <span class="doxyComputerOutput">isSCEVExprNeverPoison</span> but it specifically works for instructions that will get mapped to <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> add recurrences.</p>


<p>Return true if <span class="doxyComputerOutput">I</span> will never generate poison under the assumption that <span class="doxyComputerOutput">I</span> is an add recurrence on the loop <span class="doxyComputerOutput">L</span>.</p>


<p>Declaration at line 2215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 7387 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### isGuaranteedNotToCauseUB() {#ad7307068047c87a906260bc017910c92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isGuaranteedNotToCauseUB (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> is guaranteed not to cause immediate UB.</p>

<p>Declaration at line 2188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 7350 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### isGuaranteedToTransferExecutionTo() {#a2bf499522b8033fb7cdd18d147b1c33e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isGuaranteedToTransferExecutionTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given two instructions in the same function, return true if we can prove B must execute given A executes.</p>

<p>Declaration at line 2184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 7326 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### isImpliedCond() {#ae77c33090e9ff44fd8f52df43549b10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isImpliedCond (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * FoundCondValue, bool Inverse, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Context=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether the condition described by Pred, LHS, and RHS is true whenever the given FoundCondValue value evaluates to true in given Context.</p>


<p>If Context is nullptr, then the found predicate is true everywhere. LHS and FoundLHS may have different type width.</p>


<p>Declaration at line 1977 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 11740 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### isImpliedCond() {#aba8789e821f00a5978b272c6056254da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isImpliedCond (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> FoundPred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * FoundLHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * FoundRHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Context=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether the condition described by Pred, LHS, and RHS is true whenever the condition described by FoundPred, FoundLHS, FoundRHS is true in given Context.</p>


<p>If Context is nullptr, then the found predicate is true everywhere.</p>


<p>Declaration at line 1994 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 11784 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### isImpliedCondBalancedTypes() {#ab4027c2e0684dc379274040864895640}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isImpliedCondBalancedTypes (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> FoundPred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * FoundLHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * FoundRHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether the condition described by Pred, LHS, and RHS is true whenever the given FoundCondValue value evaluates to true in given Context.</p>


<p>If Context is nullptr, then the found predicate is true everywhere. LHS and FoundLHS must have same type width.</p>


<p>Declaration at line 1985 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 11838 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### isImpliedCondOperands() {#a3b932e599117f9276492f30f78aa0fa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isImpliedCondOperands (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * FoundLHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * FoundRHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Context=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether the condition described by Pred, LHS, and RHS is true whenever the condition described by Pred, FoundLHS, and FoundRHS is true in given Context.</p>


<p>If Context is nullptr, then the found predicate is true everywhere.</p>


<p>Declaration at line 2003 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 12461 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### isImpliedCondOperandsHelper() {#aa015ca257dd77d3969e71137a8d65f08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isImpliedCondOperandsHelper (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * FoundLHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * FoundRHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether the condition described by Pred, LHS, and RHS is true whenever the condition described by Pred, FoundLHS, and FoundRHS is true.</p>

<p>Declaration at line 2024 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 12764 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### isImpliedCondOperandsViaAddRecStart() {#a38e7e112d2cb6b911dcffaf94fa2c869}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isImpliedCondOperandsViaAddRecStart (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * FoundLHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * FoundRHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether the condition described by Pred, LHS, and RHS is true whenever the condition described by Pred, FoundLHS, and FoundRHS is true.</p>


<p>This routine tries to weaken the known condition basing on fact that FoundLHS is an AddRec.</p>


<p>Declaration at line 2058 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 12174 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### isImpliedCondOperandsViaNoOverflow() {#a8f2c428d1e89761be24199170248ebae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isImpliedCondOperandsViaNoOverflow (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * FoundLHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * FoundRHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether the condition described by Pred, LHS, and RHS is true whenever the condition described by Pred, FoundLHS, and FoundRHS is true.</p>


<p>This routine tries to rule out certain kinds of integer overflow, and then tries to reason about arithmetic properties of the predicates.</p>


<p>Declaration at line 2048 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 12219 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### isImpliedCondOperandsViaRanges() {#a41851a452bcf256bc44b0ca0d22c16d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isImpliedCondOperandsViaRanges (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> FoundPred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * FoundLHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * FoundRHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether the condition described by Pred, LHS, and RHS is true whenever the condition described by Pred, FoundLHS, and FoundRHS is true.</p>


<p>Utility function used by isImpliedCondOperands. Tries to get cases like "X `sgt` 0 =&gt; X - 1 `sgt` -1".</p>


<p>Declaration at line 2032 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 12810 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### isImpliedCondOperandsViaShift() {#a8c83e4560b53692ce12cad5e4ab629f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isImpliedCondOperandsViaShift (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * FoundLHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * FoundRHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether the condition described by Pred, LHS, and RHS is true whenever the condition described by Pred, FoundLHS, and FoundRHS is true.</p>


<p>This routine tries to reason about shifts.</p>


<p>Declaration at line 2080 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 12419 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### isImpliedViaGuard() {#af148ca3fb0f88b825b9af5d5e1202547}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isImpliedViaGuard (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the condition denoted by <span class="doxyComputerOutput">LHS</span> <span class="doxyComputerOutput">Pred</span> <span class="doxyComputerOutput">RHS</span> is implied by a call to @llvm.experimental.guard in <span class="doxyComputerOutput">BB</span>.</p>

<p>Declaration at line 2039 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 11496 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### isImpliedViaMerge() {#a21dcbae8aa0ddadb4c4cbabd57805a7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isImpliedViaMerge (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * FoundLHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * FoundRHS, unsigned Depth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether the condition described by Pred, LHS, and RHS is true whenever the condition described by Pred, FoundLHS, and FoundRHS is true.</p>


<p>This routine tries to figure out predicate for Phis which are <a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a> if it is true for every possible incoming value from their respective basic blocks.</p>


<p>Declaration at line 2071 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 12300 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### isImpliedViaOperations() {#a99b54d832a5c3eaa10272eedfc04c12f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isImpliedViaOperations (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * FoundLHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * FoundRHS, unsigned Depth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether the condition described by Pred, LHS, and RHS is true whenever the condition described by Pred, FoundLHS, and FoundRHS is true.</p>


<p>Here LHS is an operation that includes FoundLHS as one of its arguments.</p>


<p>Declaration at line 2012 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 12559 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### isKnownPredicateViaConstantRanges() {#ab83027d11737fb24ab23867b8b1f2227}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isKnownPredicateViaConstantRanges (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test if the given expression is known to satisfy the condition described by Pred and the known constant ranges of LHS and RHS.</p>

<p>Declaration at line 2092 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 11338 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### isKnownPredicateViaNoOverflow() {#aa79768fbd252f8de092490503bcd776a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isKnownPredicateViaNoOverflow (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to prove the condition described by "LHS Pred RHS" by ruling out integer overflow.</p>


<p>For instance, this will return true for "A s&lt; (A + C)&lt;nsw&gt;" if C is positive.</p>


<p>Declaration at line 2100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 11381 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### isKnownPredicateViaSplitting() {#a3b471480bf02920d1caddf36fc3a797e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isKnownPredicateViaSplitting (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to split Pred LHS RHS into logical conjunctions (and's) and try to prove them individually.</p>

<p>Declaration at line 2105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 11474 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### isKnownViaNonRecursiveReasoning() {#a21fd8c714c15a8ba7c329280de85922f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isKnownViaNonRecursiveReasoning (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether the condition described by Pred, LHS, and RHS is true.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> only simple non-recursive types of checks, such as range analysis etc.</p>


<p>Declaration at line 2018 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 12754 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### isSCEVExprNeverPoison() {#af42e38b421af577479ffa88c08aac1b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isSCEVExprNeverPoison (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> corresponding to <span class="doxyComputerOutput">I</span> is never poison.</p>


<p>Proving this is more complex than proving that just <span class="doxyComputerOutput">I</span> is never poison, since <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> commons expressions across control flow, and you can have cases like:</p>


<p>idx0 = a + b; ptr[idx0] = 100; if (&lt;condition&gt;) { idx1 = a +nsw b; ptr[idx1] = 200; }</p>


<p>where the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression (+ a b) is guaranteed to not be poison (and hence not sign-overflow) only if "&lt;condition&gt;" is true. Since both <span class="doxyComputerOutput">idx0</span> and <span class="doxyComputerOutput">idx1</span> will be mapped to the same <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression, (+ a b), it is not okay to annotate (+ a b) with &lt;nsw&gt; in the above example.</p>


<p>Declaration at line 2209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 7360 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### loopHasNoSideEffects() {#a392fcb7cb033043f3870a715c00aa283}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ScalarEvolution::loopHasNoSideEffects (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
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



<p>Definition at line 1697 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### matchURem() {#a82c3814bf2a8c5e8a7559d061cbdcc7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::matchURem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Expr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *&amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *&amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to match the pattern generated by getURemExpr(A, B).</p>


<p>If successful, Assign A and B to LHS and RHS, respectively.</p>


<p>Declaration at line 2275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 15275 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### proveNoSignedWrapViaInduction() {#ac77d8ec075ce875713036ca1439d25e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCEV::NoWrapFlags ScalarEvolution::proveNoSignedWrapViaInduction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * AR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to prove NSW on <span class="doxyComputerOutput">AR</span> by proving facts about conditions known on entry and backedge.</p>

<p>Declaration at line 2151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 5106 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### proveNoUnsignedWrapViaInduction() {#a7b08bbacf652ea6888acde49f097b1ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCEV::NoWrapFlags ScalarEvolution::proveNoUnsignedWrapViaInduction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * AR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to prove NUW on <span class="doxyComputerOutput">AR</span> by proving facts about conditions known on entry and backedge.</p>

<p>Declaration at line 2155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 5159 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### proveNoWrapByVaryingStart() {#a93dea5275169c80999e1f74e522a69fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ExtendOpTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::proveNoWrapByVaryingStart (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Start, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Step, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if <span class="doxyComputerOutput">ExtendOpTy</span>({<span class="doxyComputerOutput">Start</span>,+,<span class="doxyComputerOutput">Step</span>}) can be proved to be equal to {<span class="doxyComputerOutput">ExtendOpTy</span>(<span class="doxyComputerOutput">Start</span>),+,<span class="doxyComputerOutput">ExtendOpTy</span>(<span class="doxyComputerOutput">Step</span>)}.</p>


<p>This is equivalent to proving no signed (resp. unsigned) wrap in {<span class="doxyComputerOutput">Start</span>,+,<span class="doxyComputerOutput">Step</span>} if <span class="doxyComputerOutput">ExtendOpTy</span> is <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/scevsignextendexpr">SCEVSignExtendExpr</a></span> (resp. <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/scevzeroextendexpr">SCEVZeroExtendExpr</a></span>).</p>


<p>Declaration at line 2143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 1463 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### proveNoWrapViaConstantRanges() {#a7f27763749613527c7d2fa8e5cdc84a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCEV::NoWrapFlags ScalarEvolution::proveNoWrapViaConstantRanges (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * AR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to prove NSW or NUW on <span class="doxyComputerOutput">AR</span> relying on <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> manipulation.</p>

<p>Declaration at line 2147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 5062 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### setRange() {#af5b6270038fd30531c691a51b57e8a0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ConstantRange &amp; llvm::ScalarEvolution::setRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, RangeSignHint Hint, <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> CR)</td>
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

<p>Set the memoized range for the given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>.</p>

<p>Definition at line 1726 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### splitBinaryAdd() {#a617f77bccf5b0defac6741f9bac477f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::splitBinaryAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Expr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *&amp; L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *&amp; R, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> &amp; Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to match the Expr as "(L + R)&lt;Flags&gt;".</p>

<p>Declaration at line 2109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 12044 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### stripInjectiveFunctions() {#a7c9e17f21a2fe5953cb49bc19b25de46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * ScalarEvolution::stripInjectiveFunctions (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return x if <span class="doxyComputerOutput">Val</span> is f(x) where f is a 1-1 function.</p>

<p>Declaration at line 2266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 10180 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

### visitAndClearUsers() {#a47dde7c7c74e75731b103529cef47586}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScalarEvolution::visitAndClearUsers (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; Worklist, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; Visited, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; ToForget)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Iterate over instructions in <span class="doxyComputerOutput">Worklist</span> and their users.</p>


<p>Erase entries from ValueExprMap and collect <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expressions in <span class="doxyComputerOutput">ToForget</span></p>


<p>Declaration at line 2123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 8472 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AC {#a95f388a2e35d502a4d72436de42f54c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache&amp; llvm::ScalarEvolution::AC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The tracker for @llvm.assume intrinsics in this function.</p>

<p>Definition at line 1430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### BackedgeTakenCounts {#afe5b64c7528afd464f11b71b1ff4898d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Loop *, BackedgeTakenInfo&gt; llvm::ScalarEvolution::BackedgeTakenCounts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cache the backedge-taken count of the loops for this function as they are computed.</p>

<p>Definition at line 1646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### BECountUsers {#aa85d303e9315b1858a6a8b7dce6f6124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const SCEV *, SmallPtrSet&lt;PointerIntPair&lt;const Loop *, 1, bool&gt;, 4&gt; &gt; llvm::ScalarEvolution::BECountUsers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Loops whose backedge taken counts directly use this non-constant <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>.</p>

<p>Definition at line 1654 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### BlockDispositions {#a4b334bdd62bec64b325c1b85f97cbfd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt; const SCEV *, SmallVector&lt;PointerIntPair&lt;const BasicBlock *, 2, BlockDisposition&gt;, 2&gt; &gt; llvm::ScalarEvolution::BlockDispositions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Memoized computeBlockDisposition results.</p>

<p>Definition at line 1708 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### ConstantEvolutionLoopExitValue {#a1dad2853aff20ad42044247b7cd5b3b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;PHINode *, Constant *&gt; llvm::ScalarEvolution::ConstantEvolutionLoopExitValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This map contains entries for all of the PHI instructions that we attempt to compute constant evolutions for.</p>


<p>This allows us to avoid potentially expensive recomputation of these properties. An instruction maps to null if we are unable to compute its exit value.</p>


<p>Definition at line 1660 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### ConstantMultipleCache {#a9ffb674a228933a88d184ff873842b7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const SCEV *, APInt&gt; llvm::ScalarEvolution::ConstantMultipleCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Memoized values for the getConstantMultiple.</p>

<p>Definition at line 1488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### CouldNotCompute {#a70cc1e23af6aa81f94cfb9a66d7d1bd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;SCEVCouldNotCompute&gt; llvm::ScalarEvolution::CouldNotCompute</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> is used to represent unknown trip counts and things.</p>

<p>Definition at line 1439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### DL {#ac6e7a482ff8862b8bc1af7d374df2ee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; llvm::ScalarEvolution::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Data layout of the module.</p>

<p>Definition at line 1419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### DT {#a279d7f0474381dddba0711877453614b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree&amp; llvm::ScalarEvolution::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The dominator tree.</p>

<p>Definition at line 1433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### ExprValueMap {#a473dc76382b76b1a21bba57abf1177dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExprValueMapType llvm::ScalarEvolution::ExprValueMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ExprValueMap – This map records the original values from which the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expr is generated from.</p>

<p>Definition at line 1453 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### F {#a5825b2ab428f470964dce4af0cf7eb61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; llvm::ScalarEvolution::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The function we are analyzing.</p>

<p>Definition at line 1416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### FirstUnknown {#a14f654bf9a426b609db7fc834847650e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCEVUnknown* llvm::ScalarEvolution::FirstUnknown = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The head of a linked list of all <a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a> values that have been allocated.</p>


<p>This is used by releaseMemory to locate them all and call their destructors.</p>


<p>Definition at line 2315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### FoldCache {#a21970eefe17af743475eaf22846d6014}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;FoldID, const SCEV *&gt; llvm::ScalarEvolution::FoldCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is a cache for expressions that got folded to a different existing <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>.</p>

<p>Definition at line 1464 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### FoldCacheUser {#a0e52946749c2ddb1db2b4289518b43ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const SCEV *, SmallVector&lt;FoldID, 2&gt; &gt; llvm::ScalarEvolution::FoldCacheUser</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### HasGuards {#afd3634c38fc9c45c9381be285e7d85ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ScalarEvolution::HasGuards</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Does the module have any calls to the llvm.experimental.guard intrinsic at all?</p>


<p>If this is false, we avoid doing work that will only help if thare are guards present in the IR.</p>


<p>Definition at line 1424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### HasRecMap {#a4303770e6ff4a4d4e679c34c7bfc5e74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HasRecMapType llvm::ScalarEvolution::HasRecMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is a cache to record whether a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> contains any scAddRecExpr.</p>

<p>Definition at line 1445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### LI {#a1983fa914ca7e3befd135764d480bead}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo&amp; llvm::ScalarEvolution::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The loop information for the function we are currently analyzing.</p>

<p>Definition at line 1436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### LoopDispositions {#aa90ae9b03ef66ae8ceb7d6ae15f6e030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const SCEV *, SmallVector&lt;PointerIntPair&lt;const Loop *, 2, LoopDisposition&gt;, 2&gt; &gt; llvm::ScalarEvolution::LoopDispositions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Memoized computeLoopDisposition results.</p>

<p>Definition at line 1676 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### LoopPropertiesCache {#ad7305b73843117a1653883028c061718}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Loop *, LoopProperties&gt; llvm::ScalarEvolution::LoopPropertiesCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cache for <span class="doxyComputerOutput">getLoopProperties</span>.</p>

<p>Definition at line 1692 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### LoopUsers {#ab406e56dc4cb60fee23782a8163f8e06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Loop *, SmallVector&lt;const SCEVAddRecExpr *, 4&gt; &gt; llvm::ScalarEvolution::LoopUsers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This maps loops to a list of addrecs that directly use said loop.</p>

<p>Definition at line 2296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### PendingLoopPredicates {#a5abaf44364bc31d139458729eff2e408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const Value *, 6&gt; llvm::ScalarEvolution::PendingLoopPredicates</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark predicate values currently being processed by isImpliedCond.</p>

<p>Definition at line 1468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### PendingMerges {#a619e8396e50f7ef40844ea5888257a41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const PHINode *, 6&gt; llvm::ScalarEvolution::PendingMerges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1477 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### PendingPhiRanges {#a7f130d46eaff809039b9eb67dbacaff5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const PHINode *, 6&gt; llvm::ScalarEvolution::PendingPhiRanges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark <a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a> Phis currently being processed by getRangeRef.</p>

<p>Definition at line 1471 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### PendingPhiRangesIter {#a14178d96fe55717767e4e205bc0b31b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const PHINode *, 6&gt; llvm::ScalarEvolution::PendingPhiRangesIter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark <a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a> Phis currently being processed by getRangeRefIter.</p>

<p>Definition at line 1474 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### PredicatedBackedgeTakenCounts {#aea8a1b691474325789b31cf0c930e15c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Loop *, BackedgeTakenInfo&gt; llvm::ScalarEvolution::PredicatedBackedgeTakenCounts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cache the predicated backedge-taken count of the loops for this function as they are computed.</p>

<p>Definition at line 1650 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### PredicatedSCEVRewrites {#a60a0d1b47cb18b1c22b2a1d2fc2028cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;std::pair&lt;const SCEVUnknown *, const Loop *&gt;, std::pair&lt;const SCEV *, SmallVector&lt;const SCEVPredicate *, 3&gt; &gt; &gt; llvm::ScalarEvolution::PredicatedSCEVRewrites</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cache tentative mappings from UnknownSCEVs in a <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a>, to a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression they can be rewritten into under certain predicates.</p>

<p>Definition at line 2302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### ProvingSplitPredicate {#a963bcbabea12a74f365a288c01e2d74f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ScalarEvolution::ProvingSplitPredicate = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set to true by isKnownPredicateViaSplitting when we're trying to prove a predicate by splitting it into a set of independent predicates.</p>

<p>Definition at line 1485 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### SCEVAllocator {#a4e49741e6f337927533b85ffe42689fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::ScalarEvolution::SCEVAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### SCEVUsers {#ac885c764637faa8ca75f2f167cf667bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const SCEV *, SmallPtrSet&lt;const SCEV *, 8&gt; &gt; llvm::ScalarEvolution::SCEVUsers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stores all <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> that use a given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> as its direct operand.</p>

<p>Definition at line 1714 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### SignedRanges {#ab2eef82a0c6db08d9eed7c46d832bd63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const SCEV *, ConstantRange&gt; llvm::ScalarEvolution::SignedRanges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Memoized results from getRange.</p>

<p>Definition at line 1720 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### SignedWrapViaInductionTried {#ad3b95a93308cb96930df6ea207b76bea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const SCEVAddRecExpr *, 16&gt; llvm::ScalarEvolution::SignedWrapViaInductionTried</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set of AddRecs for which proving NSW via an induction has already been tried.</p>

<p>Definition at line 2310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### TLI {#ae45f925f6052bd2a76d1986b711cfd81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLibraryInfo&amp; llvm::ScalarEvolution::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The target library information for the target we are targeting.</p>

<p>Definition at line 1427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### UniquePreds {#a77a2f3086ca5d88d73a55a0418d23e6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSet&lt;SCEVPredicate&gt; llvm::ScalarEvolution::UniquePreds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### UniqueSCEVs {#aa6e27585fed67608167af32f3544d590}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSet&lt;SCEV&gt; llvm::ScalarEvolution::UniqueSCEVs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### UnsignedRanges {#af76c2ccae76bb71fb6215d44fed1ebe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const SCEV *, ConstantRange&gt; llvm::ScalarEvolution::UnsignedRanges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Memoized results from getRange.</p>

<p>Definition at line 1717 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### UnsignedWrapViaInductionTried {#aff5aa5a0e908338939e67aa37a1db92e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const SCEVAddRecExpr *, 16&gt; llvm::ScalarEvolution::UnsignedWrapViaInductionTried</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set of AddRecs for which proving NUW via an induction has already been tried.</p>

<p>Definition at line 2306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### ValueExprMap {#ab54d94b24d8f4ad8ac12cf94766d4911}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueExprMapType llvm::ScalarEvolution::ValueExprMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is a cache of the values we have analyzed so far.</p>

<p>Definition at line 1460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### ValuesAtScopes {#a6f8fe8ae570ffea98296d8d1863c8017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const SCEV *, SmallVector&lt;std::pair&lt;const Loop *, const SCEV *&gt;, 2&gt; &gt; llvm::ScalarEvolution::ValuesAtScopes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This map contains entries for all the expressions that we attempt to compute getSCEVAtScope information for, which can be expensive in extreme cases.</p>

<p>Definition at line 1666 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### ValuesAtScopesUsers {#a02da71cc634ae00e0d0fdcfaae95301e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const SCEV *, SmallVector&lt;std::pair&lt;const Loop *, const SCEV *&gt;, 2&gt; &gt; llvm::ScalarEvolution::ValuesAtScopesUsers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reverse map for invalidation purposes: Stores of which <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> and which loop this is the value-at-scope of.</p>

<p>Definition at line 1671 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### WalkingBEDominatingConds {#a76d754f47ab0bea94f4d683810f802b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ScalarEvolution::WalkingBEDominatingConds = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set to true by isLoopBackedgeGuardedByCond when we're walking the set of conditions dominating the backedge of a loop.</p>

<p>Definition at line 1481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### clearFlags() {#a7abfe35425aead3383db5d8a311c1671}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCEV::NoWrapFlags llvm::ScalarEvolution::clearFlags (<a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> OffFlags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Referenced by <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>.</p>

</div>
</div>

### hasFlags() {#a0410d63819514e3062a73eb48a5ecc82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ScalarEvolution::hasFlags (<a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> TestFlags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Reference <a href="#adfe987ba0fa56ab9ecdb606c2462b6b9">maskFlags</a>.</p>


<p>Referenced by <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#a8bcb86d8d126d95b0dc05f09e8f3df96">getMinusSCEV</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ae99f51fb7f4e120a8ebeb76e3c53cf2b">StrengthenNoWrapFlags</a>.</p>

</div>
</div>

### maskFlags() {#adfe987ba0fa56ab9ecdb606c2462b6b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCEV::NoWrapFlags llvm::ScalarEvolution::maskFlags (<a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> Flags, int Mask)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convenient NoWrapFlags manipulation that hides enum casts and is visible in the <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> name space.</p>

<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Referenced by <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#a659b27f6737fcb7eaf333b0279da1154">getAddRecExpr</a>, <a href="#a69f32678ea46cdda0318c0be9bdb1c7e">getAddRecExpr</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a359235e468f7ab6f4dccbed37c17dee1">getPreStartForExtend</a>, <a href="#a0410d63819514e3062a73eb48a5ecc82">hasFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#aa3255071e8195c43058f7e265c54677f">llvm::SCEVExpander::hoistIVInc</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/loopguards/#afc980d8379c6a1d12d091ba6b33aa05f">llvm::ScalarEvolution::LoopGuards::rewrite</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ae99f51fb7f4e120a8ebeb76e3c53cf2b">StrengthenNoWrapFlags</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#ad6315ffed3396dd69c53e1e51cfcd9f6">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::strengthenOverflowingOperation</a>.</p>

</div>
</div>

### setFlags() {#a8fed3b807739f2ff6942c12407ab00fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCEV::NoWrapFlags llvm::ScalarEvolution::setFlags (<a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> Flags, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> OnFlags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Referenced by <a href="#aef6d2bea715d1793e956f41ddeea2320">getAddExpr</a>, <a href="#a0f3039f831c483956c153ed9dee23dba">getGEPExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate/#a76a888bd97f7b7bb6b43eb4bdb9dc3bc">llvm::SCEVWrapPredicate::getImpliedFlags</a>, <a href="#ad299b0f4378f644f67168c72c763716f">getMulExpr</a>, <a href="#aa6a8e1063693697569fead19a720c43c">getStrengthenedNoWrapFlagsFromBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate/#a55e760ed817efd182374bddd96c0725d">llvm::SCEVWrapPredicate::isAlwaysTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/loopguards/#afc980d8379c6a1d12d091ba6b33aa05f">llvm::ScalarEvolution::LoopGuards::rewrite</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a5316a2763777f3670c1606452f4e99d7">llvm::SCEVAddRecExpr::setNoWrapFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ae99f51fb7f4e120a8ebeb76e3c53cf2b">StrengthenNoWrapFlags</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### isGuaranteedNotToBePoison() {#a3cc538e271abf38ff3b19e672355426a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScalarEvolution::isGuaranteedNotToBePoison (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Op)</td>
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

<p>Returns true if <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> is guaranteed to not be poison.</p>

<p>Declaration at line 2191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 7344 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
