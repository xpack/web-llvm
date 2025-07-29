---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/icmpinst
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ICmpInst` Class

<p>This instruction compares its operands according to the predicate given to the constructor. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ICmpInst { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class is the base class for the comparison instructions. <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#aca2d978237a7ee6a5118cedba2c358d1">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87273cb892a8182f137567e6b631695e">Instruction</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2472e4d5a0e2f4d6d41f2f58c8261348">ICmpInst</a> (InsertPosition InsertBefore, Predicate pred, Value *LHS, Value *RHS, const Twine &amp;NameStr="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructor with insertion semantics. <a href="#a2472e4d5a0e2f4d6d41f2f58c8261348">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf8d12a487891532df62e728d22f2c6f">ICmpInst</a> (Predicate pred, Value *LHS, Value *RHS, const Twine &amp;NameStr="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructor with no-insertion semantics. <a href="#adf8d12a487891532df62e728d22f2c6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36f67a81e2a4449854771f4e64efe60a">getCmpPredicate</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a756b791b5d2db592f79607b0776caa8c">getInverseCmpPredicate</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5661ce1d8f7e67d51e712ee12ea1e29f">getSwappedCmpPredicate</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d5f70171d811078c4d263811f13c121">getSignedPredicate</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For example, EQ-&gt;EQ, SLE-&gt;SLE, UGT-&gt;SGT, etc. <a href="#a9d5f70171d811078c4d263811f13c121">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af07a09f1cda33d984cc725dc9e856d40">getUnsignedPredicate</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For example, EQ-&gt;EQ, SLE-&gt;ULE, UGT-&gt;UGT, etc. <a href="#af07a09f1cda33d984cc725dc9e856d40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a972c176c0737e91145863040aef6cbd9">getFlippedSignednessPredicate</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For example, SLT-&gt;ULT, ULT-&gt;SLT, SLE-&gt;ULE, ULE-&gt;SLE, EQ-&gt;EQ. <a href="#a972c176c0737e91145863040aef6cbd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a236c918e82e3885748e82eddfa7debcb">setSameSign</a> (bool B=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c3d1a0d43200a0336d30721a12d981b">hasSameSign</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An icmp instruction, which can be marked as "samesign", indicating that the two operands have the same sign. <a href="#a1c3d1a0d43200a0336d30721a12d981b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaeded5d0cab77f531b294638459aca5">isEquality</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this predicate is either EQ or NE. <a href="#aaaeded5d0cab77f531b294638459aca5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43218c25980995581eeef1e8b98d6ffe">isCommutative</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae955171baab3d9254f3ffb089c082206">isRelational</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the predicate is relational (not EQ or NE). <a href="#ae955171baab3d9254f3ffb089c082206">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbc778ccd1faf4e95963c9a980acc7a5">swapOperands</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Exchange the two operands to this instruction in such a way that it does not modify the semantics of the instruction. <a href="#acbc778ccd1faf4e95963c9a980acc7a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68c6d6251c01a927f5d8c37e486ae2f1">cloneImpl</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone an identical <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a>. <a href="#a68c6d6251c01a927f5d8c37e486ae2f1">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e570d2bf2de873c881d44cbdaabb50e">AssertOK</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa871088f4c6eb5f26f7e0edc491b5676">getInverseCmpPredicate</a> (CmpPredicate Pred)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36966e3f5427e7aa08dbbf358cc4b921">getSwappedCmpPredicate</a> (CmpPredicate Pred)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e63883e17d24a441321875d07c432d7">getSignedPredicate</a> (Predicate Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the signed version of the predicate: static variant. <a href="#a0e63883e17d24a441321875d07c432d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abce1ba837e8fc4894494898dd00b8ed0">getUnsignedPredicate</a> (Predicate Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the unsigned version of the predicate: static variant. <a href="#abce1ba837e8fc4894494898dd00b8ed0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab5ed5a6c201467c29ee9de89f80314a">getFlippedSignednessPredicate</a> (Predicate Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For example, SLT-&gt;ULT, ULT-&gt;SLT, SLE-&gt;ULE, ULE-&gt;SLE, EQ-&gt;EQ. <a href="#aab5ed5a6c201467c29ee9de89f80314a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad219df451bdc04ec7842afc3eae0b569">isImpliedByMatchingCmp</a> (CmpPredicate Pred1, CmpPredicate Pred2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if Pred1 implies Pred2 is true, false, or if nothing can be inferred about the implication, when two compares have matching operands. <a href="#ad219df451bdc04ec7842afc3eae0b569">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe8988eef2e6fc2baba032cb22afedd7">isEquality</a> (Predicate P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this predicate is either EQ or NE. <a href="#abe8988eef2e6fc2baba032cb22afedd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b7e33101c99e5fe3e1ced4a8e530dea">isCommutative</a> (Predicate P)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9d1dc43ed0c167b8b4327366a70fe45">isRelational</a> (Predicate P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the predicate is relational (not EQ or NE). <a href="#ac9d1dc43ed0c167b8b4327366a70fe45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8295e869b64b0c77ba2c917eeb5f530d">isGT</a> (Predicate P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the predicate is SGT or UGT. <a href="#a8295e869b64b0c77ba2c917eeb5f530d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a5f1a2e8e2ab96bad265dfbddd41e09">isLT</a> (Predicate P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the predicate is SLT or ULT. <a href="#a5a5f1a2e8e2ab96bad265dfbddd41e09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4db9c79611d8a0a8cfad3e190b9206fc">isGE</a> (Predicate P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the predicate is SGE or UGE. <a href="#a4db9c79611d8a0a8cfad3e190b9206fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc5ae5e45df2c40564929779114e8afa">isLE</a> (Predicate P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the predicate is SLE or ULE. <a href="#afc5ae5e45df2c40564929779114e8afa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3a66e8579a590f0ea0f0bcd879e1953">predicates</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the sequence of all ICmp predicates. <a href="#ad3a66e8579a590f0ea0f0bcd879e1953">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5769f1da829d6f6400b486d8e34e317f">compare</a> (const APInt &amp;LHS, const APInt &amp;RHS, ICmpInst::Predicate Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return result of <span class="doxyComputerOutput">LHS Pred RHS</span> comparison. <a href="#a5769f1da829d6f6400b486d8e34e317f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a884b1f40d80313fe00fa303a8943015e">compare</a> (const KnownBits &amp;LHS, const KnownBits &amp;RHS, ICmpInst::Predicate Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return result of <span class="doxyComputerOutput">LHS Pred RHS</span>, if it can be determined from the <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a>. <a href="#a884b1f40d80313fe00fa303a8943015e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8494cbb2513f1f4266f9b2d152de8339">classof</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22d3e7f0cc28b70b89b06da828ff513e">classof</a> (const Value *V)</td>
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

<p>This instruction compares its operands according to the predicate given to the constructor.</p>


<p>It only operates on integers or pointers. The operands must be identical types. Represent an integer comparison operator.</p>


<p>Definition at line 1158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#aca2d978237a7ee6a5118cedba2c358d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SameSign<a id="aca2d978237a7ee6a5118cedba2c358d1a44f45e1bbafc25d64ce008432ab12b4c"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 0))</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### Instruction {#a87273cb892a8182f137567e6b631695e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a></td>
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


<p>Definition at line 1174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a68c6d6251c01a927f5d8c37e486ae2f1">cloneImpl</a>, <a href="#a2472e4d5a0e2f4d6d41f2f58c8261348">ICmpInst</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>


<p>Referenced by <a href="#a8494cbb2513f1f4266f9b2d152de8339">classof</a>, <a href="#a2472e4d5a0e2f4d6d41f2f58c8261348">ICmpInst</a>, <a href="#adf8d12a487891532df62e728d22f2c6f">ICmpInst</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ICmpInst() {#a2472e4d5a0e2f4d6d41f2f58c8261348}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ICmpInst::ICmpInst (<a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; NameStr="")</td>
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

<p>Constructor with insertion semantics.</p>

<p>Definition at line 1181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#ae65337bd76ece9e7b1d20cf665bfa742">llvm::CmpInst::CmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a0206e74dec02d952d1b620a7b63f5694">llvm::CmpInst::makeCmpResultType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenpredicate-cpp/#a0de1bf31f56b17312cc34b911d86faa4">pred</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#a68c6d6251c01a927f5d8c37e486ae2f1">cloneImpl</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

### ICmpInst() {#adf8d12a487891532df62e728d22f2c6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ICmpInst::ICmpInst (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; NameStr="")</td>
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

<p>Constructor with no-insertion semantics.</p>

<p>Definition at line 1195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#ae65337bd76ece9e7b1d20cf665bfa742">llvm::CmpInst::CmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a0206e74dec02d952d1b620a7b63f5694">llvm::CmpInst::makeCmpResultType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenpredicate-cpp/#a0de1bf31f56b17312cc34b911d86faa4">pred</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCmpPredicate() {#a36f67a81e2a4449854771f4e64efe60a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpPredicate llvm::ICmpInst::getCmpPredicate ()</td>
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
<dd><p>the predicate along with samesign information.</p></dd>
</dl>


<p>Definition at line 1208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa7414ba9f658ff1287d22a4b8fe81bcb">llvm::CmpInst::getPredicate</a> and <a href="#a1c3d1a0d43200a0336d30721a12d981b">hasSameSign</a>.</p>


<p>Referenced by <a href="#a756b791b5d2db592f79607b0776caa8c">getInverseCmpPredicate</a>, <a href="#a5661ce1d8f7e67d51e712ee12ea1e29f">getSwappedCmpPredicate</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a45bde60377059fca310bb78e5d3a3ccb">simplifyInstructionWithPHI</a>.</p>

</div>
</div>

### getFlippedSignednessPredicate() {#a972c176c0737e91145863040aef6cbd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Predicate llvm::ICmpInst::getFlippedSignednessPredicate ()</td>
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

<p>For example, SLT-&gt;ULT, ULT-&gt;SLT, SLE-&gt;ULE, ULE-&gt;SLE, EQ-&gt;EQ.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the unsigned version of the signed predicate pred or the signed version of the signed predicate pred.</p></dd>
</dl>


<p>Definition at line 1265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#aab5ed5a6c201467c29ee9de89f80314a">getFlippedSignednessPredicate</a> and <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa7414ba9f658ff1287d22a4b8fe81bcb">llvm::CmpInst::getPredicate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acff3d4c4feb8a1f71844fa1facae5670">llvm::InstCombinerImpl::foldICmpWithMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a1ca4520a4894a14c70f390091ee8d05d">llvm::ConstantRange::getEquivalentPredWithFlippedSignedness</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a741e5065c867d7dfd716eb8e16fccf12">llvm::ScalarEvolution::getLoopInvariantPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a4f30233ac0c825f0a38b55470569d7b7">isImpliedCondCommonOperandWithCR</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#ac2b8ad8da7580efe927ce83c1be4ddd5">isImpliedTrueByMatchingCmp</a>.</p>

</div>
</div>

### getInverseCmpPredicate() {#a756b791b5d2db592f79607b0776caa8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpPredicate llvm::ICmpInst::getInverseCmpPredicate ()</td>
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
<dd><p>the inverse predicate along with samesign information.</p></dd>
</dl>


<p>Definition at line 1219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a36f67a81e2a4449854771f4e64efe60a">getCmpPredicate</a> and <a href="#aa871088f4c6eb5f26f7e0edc491b5676">getInverseCmpPredicate</a>.</p>

</div>
</div>

### getSignedPredicate() {#a9d5f70171d811078c4d263811f13c121}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Predicate llvm::ICmpInst::getSignedPredicate ()</td>
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

<p>For example, EQ-&gt;EQ, SLE-&gt;SLE, UGT-&gt;SGT, etc.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the predicate that would be the result if the operand were regarded as signed. Return the signed version of the predicate.</p></dd>
</dl>


<p>Definition at line 1238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa7414ba9f658ff1287d22a4b8fe81bcb">llvm::CmpInst::getPredicate</a> and <a href="#a9d5f70171d811078c4d263811f13c121">getSignedPredicate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aec29f5580509ec9a7592200e09b7aa27">computePointerICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3cd3a3ec28036937ecebe767498ba55d">llvm::ConstantFoldCompareInstOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a6f5eb28a130d94e94dff2f9e798617ab">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa148a41463d0d36003033ac988b2c28d">llvm::InstCombinerImpl::foldICmpAddConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a672f3a3a327823cb542dcff37fb689a9">foldICmpOfCmpIntrinsicWithConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aaa96689aeea89281ebb2a702b34cd7f9">foldICmpXNegX</a>, <a href="#aab5ed5a6c201467c29ee9de89f80314a">getFlippedSignednessPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate/#a6b25351cc1e7cf7fde5d97eadffad546">llvm::CmpPredicate::getPreferredSignedPredicate</a>, <a href="#a9d5f70171d811078c4d263811f13c121">getSignedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a33c929139a72254b75f7ebb9593af9a9">llvm::InstCombinerImpl::insertRangeTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a3e8ca2c20b8c4c14c72c49d98f3801ed">simplifySwitchOfCmpIntrinsic</a>, <a href="/web-llvm/docs/api/classes/anonymous-constraintelimination-cpp-/constraintinfo/#a1445b68e785c39b17e05f17c345d46ca">anonymous{ConstraintElimination.cpp}::ConstraintInfo::transferToOtherSystem</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#abce78109fa7acac1ae7aa1b4ee1ce07f">transformToIndexedCompare</a>.</p>

</div>
</div>

### getSwappedCmpPredicate() {#a5661ce1d8f7e67d51e712ee12ea1e29f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpPredicate llvm::ICmpInst::getSwappedCmpPredicate ()</td>
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
<dd><p>the swapped predicate along with samesign information.</p></dd>
</dl>


<p>Definition at line 1230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a36f67a81e2a4449854771f4e64efe60a">getCmpPredicate</a> and <a href="#a36966e3f5427e7aa08dbbf358cc4b921">getSwappedCmpPredicate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a094d95c92490272d4b7a6bf4ab90009d">llvm::ScalarEvolution::getLoopInvariantExitCondDuringFirstIterationsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a650658d91a5b32920521b0f2120af053">isImpliedCondICmps</a> and <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a5e9fc2b9bb75a684c20ca3fa6e14b63e">llvm::ScalarEvolution::SimplifyICmpOperands</a>.</p>

</div>
</div>

### getUnsignedPredicate() {#af07a09f1cda33d984cc725dc9e856d40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Predicate llvm::ICmpInst::getUnsignedPredicate ()</td>
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

<p>For example, EQ-&gt;EQ, SLE-&gt;ULE, UGT-&gt;UGT, etc.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the predicate that would be the result if the operand were regarded as unsigned. Return the unsigned version of the predicate.</p></dd>
</dl>


<p>Definition at line 1249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa7414ba9f658ff1287d22a4b8fe81bcb">llvm::CmpInst::getPredicate</a> and <a href="#af07a09f1cda33d984cc725dc9e856d40">getUnsignedPredicate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#acccaf0eaeef2b860b1182f8985f59e94">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateIVComparison</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a6f5eb28a130d94e94dff2f9e798617ab">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateTrunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a25119a0e5bcc1f71c61c4acc02e3ff2b">foldICmpAndXX</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a04d40b2885dcf7e80feed09ba6209e54">llvm::InstCombinerImpl::foldICmpWithZextOrSext</a>, <a href="/web-llvm/docs/api/classes/anonymous-constraintelimination-cpp-/constraintinfo/#a8e787163c914dba0f28ef79e92c9768b">anonymous{ConstraintElimination.cpp}::ConstraintInfo::getConstraintForSolving</a>, <a href="#aab5ed5a6c201467c29ee9de89f80314a">getFlippedSignednessPredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc4c2b42879015c8ee1d08fa7ff90d8f">llvm::getFlippedStrictnessPredicateAndConstant</a>, <a href="#af07a09f1cda33d984cc725dc9e856d40">getUnsignedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>.</p>

</div>
</div>

### hasSameSign() {#a1c3d1a0d43200a0336d30721a12d981b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ICmpInst::hasSameSign ()</td>
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

<p>An icmp instruction, which can be marked as "samesign", indicating that the two operands have the same sign.</p>


<p>This means that we can convert "slt" to "ult" and vice versa, which enables more optimizations.</p>


<p>Definition at line 1281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/value/#a21e38886795ed32ec28d4eb5dc92b6a4">llvm::Value::SubclassOptionalData</a>.</p>


<p>Referenced by <a href="#a36f67a81e2a4449854771f4e64efe60a">getCmpPredicate</a>.</p>

</div>
</div>

### isCommutative() {#a43218c25980995581eeef1e8b98d6ffe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ICmpInst::isCommutative ()</td>
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
<dd><p>true if the predicate of this <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> is commutative Determine if this relation is commutative.</p></dd>
</dl>


<p>Definition at line 1301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa7414ba9f658ff1287d22a4b8fe81bcb">llvm::CmpInst::getPredicate</a> and <a href="#a43218c25980995581eeef1e8b98d6ffe">isCommutative</a>.</p>


<p>Referenced by <a href="#a43218c25980995581eeef1e8b98d6ffe">isCommutative</a>.</p>

</div>
</div>

### isEquality() {#aaaeded5d0cab77f531b294638459aca5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ICmpInst::isEquality ()</td>
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

<p>Return true if this predicate is either EQ or NE.</p>


<p>This also tests for commutativity.</p>


<p>Definition at line 1291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa7414ba9f658ff1287d22a4b8fe81bcb">llvm::CmpInst::getPredicate</a> and <a href="#abe8988eef2e6fc2baba032cb22afedd7">isEquality</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aec29f5580509ec9a7592200e09b7aa27">computePointerICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a419746e2bdc89fee0101b010a13ec0c7">detectShiftUntilBitTestIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a38d34fceda94c01af95b775632ba8299">llvm::CmpInst::isEquality</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39b2cbd58018001ca6c1b2d26be87b86">llvm::predicatesFoldable</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a64cb0c5ab10b63f22110e1b0183a648f">simplifyICmpWithBinOp</a>.</p>

</div>
</div>

### isRelational() {#ae955171baab3d9254f3ffb089c082206}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ICmpInst::isRelational ()</td>
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

<p>Return true if the predicate is relational (not EQ or NE).</p>

<p>Definition at line 1305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="#abe8988eef2e6fc2baba032cb22afedd7">isEquality</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aaf52bffe6dc4a6d5d5cf515aac2e4450">llvm::decomposeBitTestICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bd29d381405675f36964e4a5382dae4">llvm::InstCombinerImpl::foldSelectOpOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ac83b2f6d1a223c7b4ac9eb3783ee1465">foldSelectWithConstOpToBinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc4c2b42879015c8ee1d08fa7ff90d8f">llvm::getFlippedStrictnessPredicateAndConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a094d95c92490272d4b7a6bf4ab90009d">llvm::ScalarEvolution::getLoopInvariantExitCondDuringFirstIterationsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a1f669cc640bda295e6c2e2b3c90babb9">hoistMinMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a9ba70601e2398b462375dd8f3e9bc1b2">insertCandidatesWithPendingInjections</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a865c6ae11d94c83d4a7bcc0527f0fcef">IsKnownPredicateViaAddRecStart</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#ab8102f1d2d3e331db1f1781055e61013">isSignTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a64cb0c5ab10b63f22110e1b0183a648f">simplifyICmpWithBinOp</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcheckandadjustir-cpp/#a6e78c58ee832ea1775655021854401e6">sinkMinMaxInBB</a>.</p>

</div>
</div>

### setSameSign() {#a236c918e82e3885748e82eddfa7debcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ICmpInst::setSameSign (bool B=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 1274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a21e38886795ed32ec28d4eb5dc92b6a4">llvm::Value::SubclassOptionalData</a>.</p>

</div>
</div>

### swapOperands() {#acbc778ccd1faf4e95963c9a980acc7a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ICmpInst::swapOperands ()</td>
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

<p>Exchange the two operands to this instruction in such a way that it does not modify the semantics of the instruction.</p>


<p>The predicate value may be changed to retain the same result if the predicate is order dependent (e.g. ult). Swap operands and adjust predicate.</p>


<p>Definition at line 1348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a> and <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a126a12b67fa620ad28ec0c919ca7a3e8">llvm::CmpInst::setPredicate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### cloneImpl() {#a68c6d6251c01a927f5d8c37e486ae2f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ICmpInst * ICmpInst::cloneImpl ()</td>
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

<p>Clone an identical <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a>.</p>

<p>Declaration at line 1177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 4276 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa7414ba9f658ff1287d22a4b8fe81bcb">llvm::CmpInst::getPredicate</a> and <a href="#a2472e4d5a0e2f4d6d41f2f58c8261348">ICmpInst</a>.</p>


<p>Referenced by <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### AssertOK() {#a7e570d2bf2de873c881d44cbdaabb50e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ICmpInst::AssertOK ()</td>
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



<p>Definition at line 1159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a8494cbb2513f1f4266f9b2d152de8339}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ICmpInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 1363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>


<p>Referenced by <a href="#a22d3e7f0cc28b70b89b06da828ff513e">classof</a>.</p>

</div>
</div>

### classof() {#a22d3e7f0cc28b70b89b06da828ff513e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ICmpInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 1366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a8494cbb2513f1f4266f9b2d152de8339">classof</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### compare() {#a5769f1da829d6f6400b486d8e34e317f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ICmpInst::compare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">ICmpInst::Predicate</a> Pred)</td>
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

<p>Return result of <span class="doxyComputerOutput">LHS Pred RHS</span> comparison.</p>

<p>Declaration at line 1354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 3745 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#ad8c2100cae3093d71e65a48908158e22">llvm::CmpInst::isIntPredicate</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialconstantvaluesfloating/#a6097207906e979ba2cb03f2703ced3a0">anonymous{AttributorAttributes.cpp}::AAPotentialConstantValuesFloating::calculateICmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/icmpinst/#a69401375e6b92f361c0d71f8820b45ae">llvm::sandboxir::ICmpInst::compare</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aec29f5580509ec9a7592200e09b7aa27">computePointerICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3cd3a3ec28036937ecebe767498ba55d">llvm::ConstantFoldCompareInstOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a293a0cb64e182e693cdd406f8da7ced5">llvm::ConstantFoldCompareInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa148a41463d0d36003033ac988b2c28d">llvm::InstCombinerImpl::foldICmpAddConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a0550f165f22c1b1372bf6428191f0a9e">llvm::InstCombinerImpl::foldICmpSelectConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8de411243dcb508d9d512006edaba1ec">llvm::InstCombinerImpl::foldICmpUsingKnownBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a91d7c635d65d68f2326fd2f58e739cd3">foldICmpUSubSatOrUAddSatWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1ae915deb8e22ab5d8617a090149d0e6">llvm::SelectionDAG::FoldSetCC</a>, <a href="/web-llvm/docs/api/structs/llvm/patternmatch/icmp-pred-with-threshold/#af55122449fca3f9c21c9b0e4a94118a0">llvm::PatternMatch::icmp_pred_with_threshold::isValue</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a98f00ea8e8ca7e8ce4888da5cb138b43">llvm::CombinerHelper::matchICmpToTrueFalseKnownBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab720ac4c86a5f16a755b1e5cd0d32c80">llvm::simplifyBinaryIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a5e9fc2b9bb75a684c20ca3fa6e14b63e">llvm::ScalarEvolution::SimplifyICmpOperands</a> and <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#aee291a74c02dc725df8472084fab1377">anonymous{InlineCost.cpp}::CallAnalyzer::visitCmpInst</a>.</p>

</div>
</div>

### compare() {#a884b1f40d80313fe00fa303a8943015e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; ICmpInst::compare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">ICmpInst::Predicate</a> Pred)</td>
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

<p>Return result of <span class="doxyComputerOutput">LHS Pred RHS</span>, if it can be determined from the <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a>.</p>


<p>Otherwise return nullopt.</p>


<p>Declaration at line 1359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 3815 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a0aef6b7958c3eebec986bd226aca7325">llvm::KnownBits::eq</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a2d526cdaed505fb03e49f7bd0c96724f">llvm::KnownBits::ne</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a466e550382eee7535225b95ef91914d1">llvm::KnownBits::sge</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ad20d9f61ec3c5c2a0bd9163cb6c15335">llvm::KnownBits::sgt</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#acc61013b6ddecc5b9c8105aa961b71f2">llvm::KnownBits::sle</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a97cc47234699c26a59495f019e3fb1e3">llvm::KnownBits::slt</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ad86f53ca31fd59930678248efbfaf516">llvm::KnownBits::uge</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a92e582ead745c86654cd8d0e1228f0c5">llvm::KnownBits::ugt</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aa8a47d48d5537edfc125ee8ed5659955">llvm::KnownBits::ule</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aa0d9eb764d22c7fabfecf5164123cc18">llvm::KnownBits::ult</a>.</p>

</div>
</div>

### getFlippedSignednessPredicate() {#aab5ed5a6c201467c29ee9de89f80314a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpInst::Predicate ICmpInst::getFlippedSignednessPredicate (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> Pred)</td>
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

<p>For example, SLT-&gt;ULT, ULT-&gt;SLT, SLE-&gt;ULE, ULE-&gt;SLE, EQ-&gt;EQ.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the unsigned version of the signed predicate pred or the signed version of the signed predicate pred. Static variant.</p></dd>
</dl>


<p>Declaration at line 1260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 3844 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a9d5f70171d811078c4d263811f13c121">getSignedPredicate</a>, <a href="#af07a09f1cda33d984cc725dc9e856d40">getUnsignedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a38d34fceda94c01af95b775632ba8299">llvm::CmpInst::isEquality</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a3712279d70deeec90a93db09deb12d02">llvm::CmpInst::isSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#af206a3d6f58d9e53b074460f0d1ecb86">llvm::CmpInst::isUnsigned</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenpredicate-cpp/#a0de1bf31f56b17312cc34b911d86faa4">pred</a>.</p>


<p>Referenced by <a href="#a972c176c0737e91145863040aef6cbd9">getFlippedSignednessPredicate</a> and <a href="/web-llvm/docs/api/classes/llvm/cmppredicate/#a1c29fdc79aad7e92c7f850bbd0faa208">llvm::CmpPredicate::getMatching</a>.</p>

</div>
</div>

### getInverseCmpPredicate() {#aa871088f4c6eb5f26f7e0edc491b5676}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpPredicate llvm::ICmpInst::getInverseCmpPredicate (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the inverse predicate along with samesign information: static variant.</p></dd>
</dl>


<p>Definition at line 1214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa2a54b545d237ecfe450fd1292f7675e">llvm::CmpInst::getInversePredicate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad80020012061cb562a6f9c9f715c2cf0">llvm::ScalarEvolution::evaluatePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a4bfb461a6adf8414747571a5f94a77fc">llvm::ScalarEvolution::evaluatePredicateAt</a>, <a href="#a756b791b5d2db592f79607b0776caa8c">getInverseCmpPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a8d91ca7ede308b821f546a33f6625115">impliesPoisonOrCond</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#a237bdfe002251aaca2a9f2efd04d16de">isImpliedFalseByMatchingCmp</a>.</p>

</div>
</div>

### getSignedPredicate() {#a0e63883e17d24a441321875d07c432d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ICmpInst::Predicate ICmpInst::getSignedPredicate (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> Pred)</td>
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

<p>Return the signed version of the predicate: static variant.</p>

<p>Declaration at line 1243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 3584 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenpredicate-cpp/#a0de1bf31f56b17312cc34b911d86faa4">pred</a>.</p>

</div>
</div>

### getSwappedCmpPredicate() {#a36966e3f5427e7aa08dbbf358cc4b921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpPredicate llvm::ICmpInst::getSwappedCmpPredicate (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the swapped predicate along with samesign information: static variant.</p></dd>
</dl>


<p>Definition at line 1225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a49a2d8f483ea08a3d6ea75f90c640d76">llvm::CmpInst::getSwappedPredicate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bd29d381405675f36964e4a5382dae4">llvm::InstCombinerImpl::foldSelectOpOp</a> and <a href="#a5661ce1d8f7e67d51e712ee12ea1e29f">getSwappedCmpPredicate</a>.</p>

</div>
</div>

### getUnsignedPredicate() {#abce1ba837e8fc4894494898dd00b8ed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ICmpInst::Predicate ICmpInst::getUnsignedPredicate (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> Pred)</td>
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

<p>Return the unsigned version of the predicate: static variant.</p>

<p>Declaration at line 1254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 3597 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenpredicate-cpp/#a0de1bf31f56b17312cc34b911d86faa4">pred</a>.</p>

</div>
</div>

### isCommutative() {#a2b7e33101c99e5fe3e1ced4a8e530dea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ICmpInst::isCommutative (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> P)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the predicate is commutative Determine if this relation is commutative.</p></dd>
</dl>


<p>Definition at line 1297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#abe8988eef2e6fc2baba032cb22afedd7">isEquality</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### isEquality() {#abe8988eef2e6fc2baba032cb22afedd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ICmpInst::isEquality (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> P)</td>
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

<p>Return true if this predicate is either EQ or NE.</p>


<p>This also tests for commutativity.</p>


<p>Definition at line 1285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a6536b980547806c6fb158add5334c3ab">adjustIsPower2Test</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a8bd7da2c6b76da474423e160c63fdc68">canonicalizeCmpWithConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a293a0cb64e182e693cdd406f8da7ced5">llvm::ConstantFoldCompareInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a7098623cafc05376a44b27d202b03372">countToEliminateCompares</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a419746e2bdc89fee0101b010a13ec0c7">detectShiftUntilBitTestIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ab329d363cb73927378483de592986282">detectShiftUntilZeroIdiom</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ae046f3782a1242c97fe9fe937793fa3f">anonymous{DeadStoreElimination.cpp}::DSEState::dominatingConditionImpliesValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affd5ebabccc8fdf81ca6d2eeff2e68c1">llvm::findValuesAffectedByCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a25119a0e5bcc1f71c61c4acc02e3ff2b">foldICmpAndXX</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#afb20557855b41f2b32ebd166b4d4b10f">foldICmpOrXX</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abe15d83fb0501730bbfe840143cedc08">llvm::InstCombinerImpl::foldICmpShlConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7c9fd9f2dba79c2289639f72457fcea1">llvm::InstCombinerImpl::foldICmpUsingBoolRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a566049e9c903d4e0067b8557d49c7d62">foldICmpWithLowBitMaskedVal</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6fccc5a9bafccfbd5927bb72eb035635">llvm::InstCombinerImpl::foldICmpWithZero</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a04d40b2885dcf7e80feed09ba6209e54">llvm::InstCombinerImpl::foldICmpWithZextOrSext</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aaa96689aeea89281ebb2a702b34cd7f9">foldICmpXNegX</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a0e3285faf503c1c0ab9615ef71bc7d96">foldLogOpOfMaskedICmps</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a2e02c18bf8cc049ce1589b8f95618a0b">foldLogOpOfMaskedICmpsAsymmetric</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a5532e05d5caa4fb5e2b8512aa3095f1e">foldNegativePower2AndShiftedMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a41baeb4167dc326182b3c281d69232ae">foldReductionIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ac4102cd12659f4a5344d443b40009893">foldRoundUpIntegerWithPow2Alignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a917f93b85c9b8cfe9ad68ba6d49966ba">foldSelectBinOpIdentity</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#afcb58333497c40468d7889705a5d0b03">foldSelectICmpAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ad51f65187d4c6b69d6bf8f71e027e4de">foldSelectICmpAndBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a6918e533fa9054323684d7e5d556c787">foldSelectICmpEq</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bd29d381405675f36964e4a5382dae4">llvm::InstCombinerImpl::foldSelectOpOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a550ee33b5be6c859c443739649308721">foldSelectZeroOrMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a24dce8fa354f0f1d52209e805f0ae6a3">foldUnsignedUnderflowCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a45b557c1f3f224d01fc38c055ced3c58">llvm::AArch64TTIImpl::getCmpSelInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#a28425702df856e59142416e70fc6c43a">llvm::ValueLatticeElement::getCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#aeee622fb99bdc4c058a9ef179d0a0d09">getMaskedTypeForICmpPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a5d94ee8aaee00c42c11954aaa6022894">isAllocSiteRemovable</a>, <a href="#a2b7e33101c99e5fe3e1ced4a8e530dea">isCommutative</a>, <a href="#aaaeded5d0cab77f531b294638459aca5">isEquality</a>, <a href="#ae955171baab3d9254f3ffb089c082206">isRelational</a>, <a href="#ac9d1dc43ed0c167b8b4327366a70fe45">isRelational</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#afa0ed64c2bf09a336fb47c9488d2880b">anonymous{AArch64PreLegalizerCombiner.cpp}::matchICmpRedundantTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8274be96f16c9dfbe1d003c5797d9644">llvm::InstCombinerImpl::matchThreeWayIntCompare</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp/#a36394991a2449f5d347466a670a120e5">normalizePredicate</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstructure/#adc8650d6098e0949f6ecc6368c2ebb99">llvm::LoopStructure::parseLoopStructure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39b2cbd58018001ca6c1b2d26be87b86">llvm::predicatesFoldable</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ae739737036faaf1bcaa66a0f4a8e1e63">simplifyAndOrWithICmpEq</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a5e9fc2b9bb75a684c20ca3fa6e14b63e">llvm::ScalarEvolution::SimplifyICmpOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a64cb0c5ab10b63f22110e1b0183a648f">simplifyICmpWithBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a28e9b56583c0f73543606d22bfac472e">simplifyICmpWithBinOpOnLHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a7520bc5124cf32bdbb659ae6fc12cf9c">simplifyICmpWithConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a4355ad633eda8e7c8a6538ea41bb34f3">simplifyUnsignedRangeCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae31c50e938b95587c87aed0f133b1346">llvm::InstCombinerImpl::visitICmpInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>.</p>

</div>
</div>

### isGE() {#a4db9c79611d8a0a8cfad3e190b9206fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ICmpInst::isGE (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> P)</td>
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

<p>Return true if the predicate is SGE or UGE.</p>

<p>Definition at line 1329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aaf52bffe6dc4a6d5d5cf515aac2e4450">llvm::decomposeBitTestICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a1f669cc640bda295e6c2e2b3c90babb9">hoistMinMax</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcheckandadjustir-cpp/#a6e78c58ee832ea1775655021854401e6">sinkMinMaxInBB</a>.</p>

</div>
</div>

### isGT() {#a8295e869b64b0c77ba2c917eeb5f530d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ICmpInst::isGT (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> P)</td>
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

<p>Return true if the predicate is SGT or UGT.</p>

<p>Definition at line 1317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aaf52bffe6dc4a6d5d5cf515aac2e4450">llvm::decomposeBitTestICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a5f883a229d57832ae195c8d102445847">llvm::InstCombinerImpl::foldSelectToCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a6745cdf992554f558011c1768d4b5747">foldSelectWithExtremeEqCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a1f669cc640bda295e6c2e2b3c90babb9">hoistMinMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcheckandadjustir-cpp/#a6e78c58ee832ea1775655021854401e6">sinkMinMaxInBB</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a0a89a6b25b8a92fb896a994a36b74241">llvm::InstCombinerImpl::visitAdd</a>.</p>

</div>
</div>

### isImpliedByMatchingCmp() {#ad219df451bdc04ec7842afc3eae0b569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; ICmpInst::isImpliedByMatchingCmp (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred1, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred2)</td>
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

<p>Determine if Pred1 implies Pred2 is true, false, or if nothing can be inferred about the implication, when two compares have matching operands.</p>

<p>Declaration at line 1271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 3925 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#a237bdfe002251aaca2a9f2efd04d16de">isImpliedFalseByMatchingCmp</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#ac2b8ad8da7580efe927ce83c1be4ddd5">isImpliedTrueByMatchingCmp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/icmpinst/#a17ea3b97967596e71ddd7979c24cfdc0">llvm::sandboxir::ICmpInst::isImpliedByMatchingCmp</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a650658d91a5b32920521b0f2120af053">isImpliedCondICmps</a>.</p>

</div>
</div>

### isLE() {#afc5ae5e45df2c40564929779114e8afa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ICmpInst::isLE (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> P)</td>
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

<p>Return true if the predicate is SLE or ULE.</p>

<p>Definition at line 1335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aaf52bffe6dc4a6d5d5cf515aac2e4450">llvm::decomposeBitTestICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a1f669cc640bda295e6c2e2b3c90babb9">hoistMinMax</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcheckandadjustir-cpp/#a6e78c58ee832ea1775655021854401e6">sinkMinMaxInBB</a>.</p>

</div>
</div>

### isLT() {#a5a5f1a2e8e2ab96bad265dfbddd41e09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ICmpInst::isLT (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> P)</td>
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

<p>Return true if the predicate is SLT or ULT.</p>

<p>Definition at line 1323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a5f883a229d57832ae195c8d102445847">llvm::InstCombinerImpl::foldSelectToCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a6745cdf992554f558011c1768d4b5747">foldSelectWithExtremeEqCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a1f669cc640bda295e6c2e2b3c90babb9">hoistMinMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcheckandadjustir-cpp/#a6e78c58ee832ea1775655021854401e6">sinkMinMaxInBB</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a0a89a6b25b8a92fb896a994a36b74241">llvm::InstCombinerImpl::visitAdd</a>.</p>

</div>
</div>

### isRelational() {#ac9d1dc43ed0c167b8b4327366a70fe45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ICmpInst::isRelational (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> P)</td>
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

<p>Return true if the predicate is relational (not EQ or NE).</p>

<p>Definition at line 1311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#abe8988eef2e6fc2baba032cb22afedd7">isEquality</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### predicates() {#ad3a66e8579a590f0ea0f0bcd879e1953}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto llvm::ICmpInst::predicates ()</td>
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

<p>Returns the sequence of all ICmp predicates.</p>

<p>Definition at line 1341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2f9b3094f4be2263366d46be4a29b73e">llvm::CmpInst::ICmpPredicates</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/icmpinst/#ae64053cdb2084b078163a8fc5111c041">llvm::sandboxir::ICmpInst::predicates</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
