---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/cmpinst
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CmpInst` Class

<p>This class is the base class for the comparison instructions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::CmpInst { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">llvm/IR/InstrTypes.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a></td>
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fcmpinst">FCmpInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This instruction compares its operands according to the predicate given to the constructor. <a href="/web-llvm/docs/api/classes/llvm/fcmpinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This instruction compares its operands according to the predicate given to the constructor. <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b207a01ccf956060f77e6153e79a123">PredicateField</a> = <a href="/web-llvm/docs/api/structs/llvm/bitfield/element">Bitfield::Element</a>&lt; <a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a>, 0, 6, <a href="#a2be3583dac92a031fa1458d4d992c78baa5c6e466e2df2c472e487f84531421fc">LAST_ICMP_PREDICATE</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">Predicate : unsigned { <a href="#a2be3583dac92a031fa1458d4d992c78b">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This enumeration lists the possible predicates for <a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> subclasses. <a href="#a2be3583dac92a031fa1458d4d992c78b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae65337bd76ece9e7b1d20cf665bfa742">CmpInst</a> (Type *ty, Instruction::OtherOps op, Predicate pred, Value *LHS, Value *RHS, const Twine &amp;Name="", InsertPosition InsertBefore=nullptr, Instruction *FlagsSource=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a6e5851e9acbdc5e6053ebe4d680876">operator new</a> (size_t S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61b3f1b8b370c0e821fab91410d76405">operator delete</a> (void *Ptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction/#a92db6d5865b9492ef8eeedad41235d0a">OtherOps</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4abe8e5b55577f35032131a6264fe4f">getOpcode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the opcode casted to the right type. <a href="#af4abe8e5b55577f35032131a6264fe4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7414ba9f658ff1287d22a4b8fe81bcb">getPredicate</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the predicate for this instruction. <a href="#aa7414ba9f658ff1287d22a4b8fe81bcb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a126a12b67fa620ad28ec0c919ca7a3e8">setPredicate</a> (Predicate P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the predicate for this instruction to the specified value. <a href="#a126a12b67fa620ad28ec0c919ca7a3e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bd850492d35a34f0fe419e5555997a9">isFPPredicate</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad73f009e1b3b060bcdf6c2c1dd86600e">isIntPredicate</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2a54b545d237ecfe450fd1292f7675e">getInversePredicate</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For example, EQ -&gt; NE, UGT -&gt; ULE, SLT -&gt; SGE, OEQ -&gt; UNE, UGT -&gt; OLE, OLT -&gt; UGE, etc. <a href="#aa2a54b545d237ecfe450fd1292f7675e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a661fa29fe8d4acd9640aefa3a067f942">getOrderedPredicate</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad91baf1a1f08eefbccce132916ff24c5">getUnorderedPredicate</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49a2d8f483ea08a3d6ea75f90c640d76">getSwappedPredicate</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For example, EQ-&gt;EQ, SLE-&gt;SGE, ULT-&gt;UGT, OEQ-&gt;OEQ, ULE-&gt;UGE, OLT-&gt;OGT, etc. <a href="#a49a2d8f483ea08a3d6ea75f90c640d76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaabe18310fb8c24218fc883d7866ca58">isStrictPredicate</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75c72a7b8f5248ed6702dc166847cde9">isNonStrictPredicate</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0578679c169c9ca4cc731185ffddb431">getStrictPredicate</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For example, SGE -&gt; SGT, SLE -&gt; SLT, ULE -&gt; ULT, UGE -&gt; UGT. <a href="#a0578679c169c9ca4cc731185ffddb431">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b13f2e75444202b854672a5fbf85e2e">getNonStrictPredicate</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For example, SGT -&gt; SGE, SLT -&gt; SLE, ULT -&gt; ULE, UGT -&gt; UGE. <a href="#a6b13f2e75444202b854672a5fbf85e2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafc99bbdcf56632d353043ae3e2bca21">getFlippedStrictnessPredicate</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For predicate of kind "is X or equal to 0" returns the predicate "is X". <a href="#aafc99bbdcf56632d353043ae3e2bca21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeae55881876c4b52ccfe8ea36d12f59">DECLARE_TRANSPARENT_OPERAND_ACCESSORS</a> (Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide more efficient getOperand methods. <a href="#abeae55881876c4b52ccfe8ea36d12f59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b39b8cdcb092d69083a4fefe98bb083">swapOperands</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is just a convenience that dispatches to the subclasses. <a href="#a8b39b8cdcb092d69083a4fefe98bb083">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9380fd13783f0a859e3942aa12d1091">isCommutative</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is just a convenience that dispatches to the subclasses. <a href="#af9380fd13783f0a859e3942aa12d1091">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c27987ab3db5ef2125fd178e0ff21b2">isEquality</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if this is an equals/not equals predicate. <a href="#a0c27987ab3db5ef2125fd178e0ff21b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a340e06a462ce241e992ce74943f82a97">isEquivalence</a> (bool Invert=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if one operand of this compare can always be replaced by the other operand, ignoring provenance considerations. <a href="#a340e06a462ce241e992ce74943f82a97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9751cf77753dd8d3bb39c0bb7a281e1">isRelational</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the predicate is relational (not EQ or NE). <a href="#af9751cf77753dd8d3bb39c0bb7a281e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3712279d70deeec90a93db09deb12d02">isSigned</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af206a3d6f58d9e53b074460f0d1ecb86">isUnsigned</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ba8484cef2818d14b85640a903b2598">isTrueWhenEqual</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is just a convenience. <a href="#a5ba8484cef2818d14b85640a903b2598">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e32582702cf5b9d4484c0ce346b2f57">isFalseWhenEqual</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is just a convenience. <a href="#a1e32582702cf5b9d4484c0ce346b2f57">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36f1e936c4996e83debb47a573d73c10">setValueSubclassData</a> (unsigned short D)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49a78eafc7ac1f2afbfce2a88022bc28">FCmpPredicates</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the sequence of all FCmp predicates. <a href="#a49a78eafc7ac1f2afbfce2a88022bc28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f9b3094f4be2263366d46be4a29b73e">ICmpPredicates</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the sequence of all ICmp predicates. <a href="#a2f9b3094f4be2263366d46be4a29b73e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62e2cf3675b93f0e6c07a4a00852f7cd">Create</a> (OtherOps Op, Predicate Pred, Value *S1, Value *S2, const Twine &amp;Name="", InsertPosition InsertBefore=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a compare instruction, given the opcode, the predicate and the two operands. <a href="#a62e2cf3675b93f0e6c07a4a00852f7cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d0ee639690d0fa59e6c9e0af5adc5c2">CreateWithCopiedFlags</a> (OtherOps Op, Predicate Pred, Value *S1, Value *S2, const Instruction *FlagsSource, const Twine &amp;Name="", InsertPosition InsertBefore=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a compare instruction, given the opcode, the predicate, the two operands and the instruction to copy the flags from. <a href="#a6d0ee639690d0fa59e6c9e0af5adc5c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66c10680694a0184d50e7a8c0d1ea874">isFPPredicate</a> (Predicate P)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8c2100cae3093d71e65a48908158e22">isIntPredicate</a> (Predicate P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa68a2d2c06a10b1e5a5bc778a107c0ba">getPredicateName</a> (Predicate P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab95f6ee8398d4632b27c25783f3339ec">getOrderedPredicate</a> (Predicate Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the ordered variant of a floating point compare. <a href="#ab95f6ee8398d4632b27c25783f3339ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af43d73db8b352514cd05bad535e44746">getUnorderedPredicate</a> (Predicate Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the unordered variant of a floating point compare. <a href="#af43d73db8b352514cd05bad535e44746">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa11e04e8ea07654a3a172d1169fb4ca8">getInversePredicate</a> (Predicate pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For example, EQ -&gt; NE, UGT -&gt; ULE, SLT -&gt; SGE, OEQ -&gt; UNE, UGT -&gt; OLE, OLT -&gt; UGE, etc. <a href="#aa11e04e8ea07654a3a172d1169fb4ca8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9a9ca11399cf7101e5102589f043cf4">getSwappedPredicate</a> (Predicate pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a static version that you can use without an instruction available. <a href="#af9a9ca11399cf7101e5102589f043cf4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d82fa77fd3d80b33e0beabb65ad8b93">isStrictPredicate</a> (Predicate predicate)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a static version that you can use without an instruction available. <a href="#a7d82fa77fd3d80b33e0beabb65ad8b93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cf49613e9993b859e165996ca5655d7">isNonStrictPredicate</a> (Predicate predicate)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a static version that you can use without an instruction available. <a href="#a9cf49613e9993b859e165996ca5655d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a820c0ce2716bbd66df04f397054c980d">getStrictPredicate</a> (Predicate pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a static version that you can use without an instruction available. <a href="#a820c0ce2716bbd66df04f397054c980d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae548c5f1dacf3f055b391daba9e7a659">getNonStrictPredicate</a> (Predicate pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a static version that you can use without an instruction available. <a href="#ae548c5f1dacf3f055b391daba9e7a659">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23665a6553110e9303fff3ea76c21de1">getFlippedStrictnessPredicate</a> (Predicate pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a static version that you can use without an instruction available. <a href="#a23665a6553110e9303fff3ea76c21de1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38d34fceda94c01af95b775632ba8299">isEquality</a> (Predicate pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if this is an equals/not equals predicate. <a href="#a38d34fceda94c01af95b775632ba8299">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98ecd87b7ee2e36f02e7ea0b366fd92c">isRelational</a> (Predicate P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the predicate is relational (not EQ or NE). <a href="#a98ecd87b7ee2e36f02e7ea0b366fd92c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae69bfc8f4b26dbeaa4dd06d73117e330">isUnsigned</a> (Predicate predicate)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad69ad0984324da2e7e1d6830228a3ade">isSigned</a> (Predicate predicate)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad91c80980a394e9c81f04e8988261224">isOrdered</a> (Predicate predicate)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the predicate is an ordered operation. <a href="#ad91c80980a394e9c81f04e8988261224">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae55ea42185b7528c0c149625b998968">isUnordered</a> (Predicate predicate)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the predicate is an unordered operation. <a href="#aae55ea42185b7528c0c149625b998968">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ec811146e53bcf7e6c87b60ddef2827">isTrueWhenEqual</a> (Predicate predicate)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the predicate is true when comparing a value with itself. <a href="#a7ec811146e53bcf7e6c87b60ddef2827">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1e20f6a8ec09b49fbe4d574b2757379">isFalseWhenEqual</a> (Predicate predicate)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the predicate is false when comparing a value with itself. <a href="#ac1e20f6a8ec09b49fbe4d574b2757379">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24a5f30f3d82fa2f32115ef1df689c07">classof</a> (const Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for support type inquiry through isa, cast, and dyn_cast: <a href="#a24a5f30f3d82fa2f32115ef1df689c07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea968ce5b75b8e4c71a9f527a3028d6d">classof</a> (const Value *V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0206e74dec02d952d1b620a7b63f5694">makeCmpResultType</a> (Type *opnd_type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a result type for fcmp/icmp. <a href="#a0206e74dec02d952d1b620a7b63f5694">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/user/intrusiveoperandsallocmarker">IntrusiveOperandsAllocMarker</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd882fc4196ed612177491e85e512a8a">AllocMarker</a> {2}</td>
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

<p>This class is the base class for the comparison instructions.</p>


<p>Abstract base class of comparison instructions.</p>


<p>Definition at line 661 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### PredicateField {#a5b207a01ccf956060f77e6153e79a123}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CmpInst::PredicateField = 
      Bitfield::Element&lt;Predicate, 0, 6, LAST_ICMP_PREDICATE&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 708 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### Predicate {#a2be3583dac92a031fa1458d4d992c78b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::CmpInst::Predicate : unsigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This enumeration lists the possible predicates for <a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> subclasses.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMP_FALSE<a id="a2be3583dac92a031fa1458d4d992c78bae9c013750fff3023001d7e3af8df2d6d"></a></td>
<td class="doxyEnumItemDescription">0 0 0 0 Always false (always folded) (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMP_OEQ<a id="a2be3583dac92a031fa1458d4d992c78ba024db78a5ed74f64666f3ca4955e6eca"></a></td>
<td class="doxyEnumItemDescription">0 0 0 1 True if ordered and equal (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMP_OGT<a id="a2be3583dac92a031fa1458d4d992c78ba4c399f525bbcf03d72af4b303e6eeca8"></a></td>
<td class="doxyEnumItemDescription">0 0 1 0 True if ordered and greater than (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMP_OGE<a id="a2be3583dac92a031fa1458d4d992c78ba541533f34077bbbcfb703a90f6d2da9b"></a></td>
<td class="doxyEnumItemDescription">0 0 1 1 True if ordered and greater than or equal (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMP_OLT<a id="a2be3583dac92a031fa1458d4d992c78ba326bee0a4a424cef21c1cf8adb8b8dd8"></a></td>
<td class="doxyEnumItemDescription">0 1 0 0 True if ordered and less than (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMP_OLE<a id="a2be3583dac92a031fa1458d4d992c78ba9835cfe02fb5027680bd7203b024f77a"></a></td>
<td class="doxyEnumItemDescription">0 1 0 1 True if ordered and less than or equal (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMP_ONE<a id="a2be3583dac92a031fa1458d4d992c78ba8a80b27ca29fe2076b9bbdee02c65464"></a></td>
<td class="doxyEnumItemDescription">0 1 1 0 True if ordered and operands are unequal (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMP_ORD<a id="a2be3583dac92a031fa1458d4d992c78baa3213b645e029aba8bb1b85213607d5e"></a></td>
<td class="doxyEnumItemDescription">0 1 1 1 True if ordered (no nans) (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMP_UNO<a id="a2be3583dac92a031fa1458d4d992c78baf0159e4005258dc54f20b6fc227d19ed"></a></td>
<td class="doxyEnumItemDescription">1 0 0 0 True if unordered: isnan(X) | isnan(Y) (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMP_UEQ<a id="a2be3583dac92a031fa1458d4d992c78ba919643b83ce3c9af2e4296ed5e413a1f"></a></td>
<td class="doxyEnumItemDescription">1 0 0 1 True if unordered or equal (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMP_UGT<a id="a2be3583dac92a031fa1458d4d992c78ba959268ceeae23abe5c9ad9e895669d0c"></a></td>
<td class="doxyEnumItemDescription">1 0 1 0 True if unordered or greater than (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMP_UGE<a id="a2be3583dac92a031fa1458d4d992c78bae51609fc6a425f849d37c28cb9bc0344"></a></td>
<td class="doxyEnumItemDescription">1 0 1 1 True if unordered, greater than, or equal (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMP_ULT<a id="a2be3583dac92a031fa1458d4d992c78ba75016d5872d90adf89cc1cbf5763f474"></a></td>
<td class="doxyEnumItemDescription">1 1 0 0 True if unordered or less than (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMP_ULE<a id="a2be3583dac92a031fa1458d4d992c78ba396dda2571cd3c575f1d9cb44dc2cc09"></a></td>
<td class="doxyEnumItemDescription">1 1 0 1 True if unordered, less than, or equal (= 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMP_UNE<a id="a2be3583dac92a031fa1458d4d992c78bad601460c9371d0f0ada5ae006bdba2bd"></a></td>
<td class="doxyEnumItemDescription">1 1 1 0 True if unordered or not equal (= 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FCMP_TRUE<a id="a2be3583dac92a031fa1458d4d992c78ba0a33c71e3c5e8f128ca47539a85962f5"></a></td>
<td class="doxyEnumItemDescription">1 1 1 1 Always true (always folded) (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_FCMP_PREDICATE<a id="a2be3583dac92a031fa1458d4d992c78ba392f2cfc83c62daa024d96b8a13872f8"></a></td>
<td class="doxyEnumItemDescription"> (= FCMP_FALSE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LAST_FCMP_PREDICATE<a id="a2be3583dac92a031fa1458d4d992c78bab10f753354ede9597f74448afbb0762c"></a></td>
<td class="doxyEnumItemDescription"> (= FCMP_TRUE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BAD_FCMP_PREDICATE<a id="a2be3583dac92a031fa1458d4d992c78bad99425e1c7df18b4be5edbffbf896e55"></a></td>
<td class="doxyEnumItemDescription"> (= FCMP_TRUE + 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICMP_EQ<a id="a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218"></a></td>
<td class="doxyEnumItemDescription">equal (= 32)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICMP_NE<a id="a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a"></a></td>
<td class="doxyEnumItemDescription">not equal (= 33)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICMP_UGT<a id="a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad"></a></td>
<td class="doxyEnumItemDescription">unsigned greater than (= 34)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICMP_UGE<a id="a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8"></a></td>
<td class="doxyEnumItemDescription">unsigned greater or equal (= 35)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICMP_ULT<a id="a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e"></a></td>
<td class="doxyEnumItemDescription">unsigned less than (= 36)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICMP_ULE<a id="a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5"></a></td>
<td class="doxyEnumItemDescription">unsigned less or equal (= 37)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICMP_SGT<a id="a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a"></a></td>
<td class="doxyEnumItemDescription">signed greater than (= 38)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICMP_SGE<a id="a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc"></a></td>
<td class="doxyEnumItemDescription">signed greater or equal (= 39)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICMP_SLT<a id="a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c"></a></td>
<td class="doxyEnumItemDescription">signed less than (= 40)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICMP_SLE<a id="a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246"></a></td>
<td class="doxyEnumItemDescription">signed less or equal (= 41)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_ICMP_PREDICATE<a id="a2be3583dac92a031fa1458d4d992c78ba1d680986286d79b2eb671750e9c78dbe"></a></td>
<td class="doxyEnumItemDescription"> (= ICMP_EQ)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LAST_ICMP_PREDICATE<a id="a2be3583dac92a031fa1458d4d992c78baa5c6e466e2df2c472e487f84531421fc"></a></td>
<td class="doxyEnumItemDescription"> (= ICMP_SLE)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BAD_ICMP_PREDICATE<a id="a2be3583dac92a031fa1458d4d992c78ba07aee43ffb66908a25c55c77ce4c0d05"></a></td>
<td class="doxyEnumItemDescription"> (= ICMP_SLE + 1)</td>
</tr>

</table>
</dd>
</dl>


<p>Values in the range 0-31 are reserved for <a href="/web-llvm/docs/api/classes/llvm/fcmpinst">FCmpInst</a>, while values in the range 32-64 are reserved for <a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a>. This is necessary to ensure the predicate values are not overlapping between the classes.</p>


<p>Some passes (e.g. InstCombine) depend on the bit-wise characteristics of FCMP_* values. Changing the bit patterns requires a potential change to those passes.</p>


<p>Definition at line 673 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### CmpInst() {#ae65337bd76ece9e7b1d20cf665bfa742}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpInst::CmpInst (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ty, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a92db6d5865b9492ef8eeedad41235d0a">Instruction::OtherOps</a> op, <a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * FlagsSource=nullptr)</td>
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



<p>Declaration at line 726 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3422 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instruction/#a3e6d2896c39a84cfa6c47f34cdc584ff">llvm::Instruction::copyIRFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae70f02adcd410ca9c8429fa8d7711965">llvm::Instruction::Instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a> and <a href="#a126a12b67fa620ad28ec0c919ca7a3e8">setPredicate</a>.</p>


<p>Referenced by <a href="#a62e2cf3675b93f0e6c07a4a00852f7cd">Create</a>, <a href="#a6d0ee639690d0fa59e6c9e0af5adc5c2">CreateWithCopiedFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/fcmpinst/#adcf5270fa9a80077dc604114f66fafaa">llvm::FCmpInst::FCmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/fcmpinst/#a254cb3886750473f69d9a9f8b0cbbdab">llvm::FCmpInst::FCmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a2472e4d5a0e2f4d6d41f2f58c8261348">llvm::ICmpInst::ICmpInst</a> and <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#adf8d12a487891532df62e728d22f2c6f">llvm::ICmpInst::ICmpInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator delete() {#a61b3f1b8b370c0e821fab91410d76405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CmpInst::operator delete (void * Ptr)</td>
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



<p>Definition at line 734 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### operator new() {#a2a6e5851e9acbdc5e6053ebe4d680876}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::CmpInst::operator new (size_t S)</td>
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



<p>Definition at line 733 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### DECLARE\_TRANSPARENT\_OPERAND\_ACCESSORS() {#abeae55881876c4b52ccfe8ea36d12f59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CmpInst::DECLARE_TRANSPARENT_OPERAND_ACCESSORS (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Provide more efficient getOperand methods.</p>

<p>Definition at line 896 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenpredicate-cpp/#a0de1bf31f56b17312cc34b911d86faa4">pred</a>.</p>

</div>
</div>

### getFlippedStrictnessPredicate() {#aafc99bbdcf56632d353043ae3e2bca21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Predicate llvm::CmpInst::getFlippedStrictnessPredicate ()</td>
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

<p>For predicate of kind "is X or equal to 0" returns the predicate "is X".</p>


<p>For predicate of kind "is X" returns the predicate "is X or equal to 0". does not support other kind of predicates.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the predicate that does not contains is equal to zero if it had and vice versa. Return the flipped strictness of predicate</p></dd>
</dl>


<p>Definition at line 891 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#aafc99bbdcf56632d353043ae3e2bca21">getFlippedStrictnessPredicate</a> and <a href="#aa7414ba9f658ff1287d22a4b8fe81bcb">getPredicate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loop/loopbounds/#acfa250dd5ec97448681f9833e22d50cf">llvm::Loop::LoopBounds::getCanonicalPredicate</a>, <a href="#aafc99bbdcf56632d353043ae3e2bca21">getFlippedStrictnessPredicate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acc4c2b42879015c8ee1d08fa7ff90d8f">llvm::getFlippedStrictnessPredicateAndConstant</a>.</p>

</div>
</div>

### getInversePredicate() {#aa2a54b545d237ecfe450fd1292f7675e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Predicate llvm::CmpInst::getInversePredicate ()</td>
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

<p>For example, EQ -&gt; NE, UGT -&gt; ULE, SLT -&gt; SGE, OEQ -&gt; UNE, UGT -&gt; OLE, OLT -&gt; UGE, etc.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the inverse predicate for the instruction's current predicate. Return the inverse of the instruction's predicate.</p></dd>
</dl>


<p>Definition at line 787 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#aa2a54b545d237ecfe450fd1292f7675e">getInversePredicate</a> and <a href="#aa7414ba9f658ff1287d22a4b8fe81bcb">getPredicate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a321f2dfbd709348cfd0e1ab66cf0b62c">llvm::CombinerHelper::applyNotCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a94bc2ff14a27583461b207499f426ee2">canonicalizeForInvariantConditionInjection</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6f392d7a34855ef605496d0afcb913cd">llvm::InstCombinerImpl::canonicalizeICmpPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a3c4424f4bbcee5f3dd484c2822221812">canonicalizeSaturatedAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a65c587ebfe84f7c55b3d2266ff0500f9">canonicalizeSaturatedSubtract</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64giselutils/#ab7a7906ef883e6d0a588e63caf3315cf">llvm::AArch64GISelUtils::changeVectorFCMPPredToAArch64CC</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a4bbe548f3095c981a34533d7910a909d">checkCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#ab230432af09554d7dd357c77b0ec3cde">checkOrAndOpImpliedByOther</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a7098623cafc05376a44b27d202b03372">countToEliminateCompares</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a741f7bb1cc23d5c9d8917e1c7970c732">createInvariantCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a8160c4d5a8fc34f6085af951980dbaa6">createReplacement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaf52bffe6dc4a6d5d5cf515aac2e4450">llvm::decomposeBitTestICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a419746e2bdc89fee0101b010a13ec0c7">detectShiftUntilBitTestIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ab329d363cb73927378483de592986282">detectShiftUntilZeroIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a72c491cdf8cf0283d87008831431f917">llvm::InnerLoopVectorizer::emitIterationCountCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#ab9d2c872efeb61279eb6cbe774b117d4">llvm::SCEVExpander::expandComparePredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a5a46b94b8be40eba6d85169820f2a3a4">foldBitCeil</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acb575761ffbc75842def91257cc5168d">llvm::InstCombinerImpl::foldICmpEquality</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a47a83bda096455c177d40a2fbae13de1">llvm::InstCombinerImpl::foldICmpShlConstConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af57017eaefdf5b514ffd801e9923bbca">llvm::InstCombinerImpl::foldICmpShrConstConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8de411243dcb508d9d512006edaba1ec">llvm::InstCombinerImpl::foldICmpUsingKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af24dc3f2a89de0b400a681002927217d">llvm::InstCombinerImpl::foldICmpWithDominatingICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acff3d4c4feb8a1f71844fa1facae5670">llvm::InstCombinerImpl::foldICmpWithMinMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a0e3285faf503c1c0ab9615ef71bc7d96">foldLogOpOfMaskedICmps</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ac83b2f6d1a223c7b4ac9eb3783ee1465">foldSelectWithConstOpToBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a81425fa662eac9cc9cd5d21f1c66695e">generateKeySubkey</a>, <a href="/web-llvm/docs/api/structs/llvm/loop/loopbounds/#acfa250dd5ec97448681f9833e22d50cf">llvm::Loop::LoopBounds::getCanonicalPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#a28425702df856e59142416e70fc6c43a">llvm::ValueLatticeElement::getCompare</a>, <a href="/web-llvm/docs/api/classes/llvm/predicatebase/#a8202c612fc1a6d435b8cf02fea6dde38">llvm::PredicateBase::getConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a1ca4520a4894a14c70f390091ee8d05d">llvm::ConstantRange::getEquivalentPredWithFlippedSignedness</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp/#aa52ac704c30d37ea926b7e186f4fac83">getHashValueImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#aa871088f4c6eb5f26f7e0edc491b5676">llvm::ICmpInst::getInverseCmpPredicate</a>, <a href="#aa2a54b545d237ecfe450fd1292f7675e">getInversePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a741e5065c867d7dfd716eb8e16fccf12">llvm::ScalarEvolution::getLoopInvariantPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ac4cfc0065b09dbea4311561f67c2e3ea">getPredicateResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#a587440f5e057e5ec16ccb30c878cb554">getRangeViaSLT</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a1f669cc640bda295e6c2e2b3c90babb9">hoistMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a70cdc32fcfc8ba3feaf026f4959e2c2a">llvm::InvertBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp/#aa60423084fe7d27af0ffbba889cbdf1a">isEqualImpl</a>, <a href="#a340e06a462ce241e992ce74943f82a97">isEquivalence</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a4f30233ac0c825f0a38b55470569d7b7">isImpliedCondCommonOperandWithCR</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aeba9a285bd71d537ea9284c8c21aa9ba">isImpliedToBeAPowerOfTwoFromCond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9298a379e311818b5244bcb6b386953b">llvm::isKnownInversion</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a08c9c2fedd8f175884c88275c7987e03">isKnownNonNullFromDominatingCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ab9019ef5668e5a3c97fe9ee61a3a9336">isSafeToRemoveBitCeilSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvinstructionselector-cpp/#ae5a410638118950b68cdb71cd984122b">legalizeFCmpPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a6fbc74ae7d3a1a1423c26b9ce948f34c">llvm::ConstantRange::makeSatisfyingICmpRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a4aa6c86468a25ae6ef47ec9b300990e0">matchFastFloatClamp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#acda14ede9da471244980c7fada91a4aa">negateICmpIfUsedByBranchOrSelectOnly</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a93f2e165baf61dd8295c9aececed9985">simplifyCmpSelOfMaxMin</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a4f8adcab536e4c9f42e148d7eb218e6a">simplifyICmpWithMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa4100f52d21246ec944e97fe1b64b124">llvm::InstCombinerImpl::simplifyRangeCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a75fa36408fed5acf91329505b3419196">simplifySelectWithFCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a002b7ea3a854166ae7ffe9d0e3e994d7">simplifySwitchOnSelectUsingRanges</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aea9ba5a362fb88bd97349a302133dd03">llvm::InstCombinerImpl::visitBranchInst</a>.</p>

</div>
</div>

### getNonStrictPredicate() {#a6b13f2e75444202b854672a5fbf85e2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Predicate llvm::CmpInst::getNonStrictPredicate ()</td>
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

<p>For example, SGT -&gt; SGE, SLT -&gt; SLE, ULT -&gt; ULE, UGT -&gt; UGE.</p>


<p>Returns the non-strict version of strict comparisons.</p>


<p>Definition at line 869 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a6b13f2e75444202b854672a5fbf85e2e">getNonStrictPredicate</a> and <a href="#aa7414ba9f658ff1287d22a4b8fe81bcb">getPredicate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a761596303fee8f03f896c70d36a18303">checkAndReplaceMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acff3d4c4feb8a1f71844fa1facae5670">llvm::InstCombinerImpl::foldICmpWithMinMax</a>, <a href="#a23665a6553110e9303fff3ea76c21de1">getFlippedStrictnessPredicate</a>, <a href="#a6b13f2e75444202b854672a5fbf85e2e">getNonStrictPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a9ba70601e2398b462375dd8f3e9bc1b2">insertCandidatesWithPendingInjections</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aefc772d1808d513abc142b59844cfe45">llvm::ScalarEvolution::isBasicBlockEntryGuardedByCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a6d4d9e7eb49fd2f51ffcb0596b37c596">processMinMaxIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab720ac4c86a5f16a755b1e5cd0d32c80">llvm::simplifyBinaryIntrinsic</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### getOpcode() {#af4abe8e5b55577f35032131a6264fe4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OtherOps llvm::CmpInst::getOpcode ()</td>
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

<p>Get the opcode casted to the right type.</p>

<p>Definition at line 758 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7a3e32edb65b5b1c216d4454f14df21c">llvm::InstCombinerImpl::foldPHIArgOpIntoPHI</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a71ef354bd1ea9e02d70146d7218a7d39">llvm::InstCombinerImpl::visitExtractElementInst</a>.</p>

</div>
</div>

### getOrderedPredicate() {#a661fa29fe8d4acd9640aefa3a067f942}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Predicate llvm::CmpInst::getOrderedPredicate ()</td>
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



<p>Definition at line 798 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a661fa29fe8d4acd9640aefa3a067f942">getOrderedPredicate</a> and <a href="#aa7414ba9f658ff1287d22a4b8fe81bcb">getPredicate</a>.</p>


<p>Referenced by <a href="#a661fa29fe8d4acd9640aefa3a067f942">getOrderedPredicate</a>.</p>

</div>
</div>

### getPredicate() {#aa7414ba9f658ff1287d22a4b8fe81bcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Predicate llvm::CmpInst::getPredicate ()</td>
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

<p>Return the predicate for this instruction.</p>

<p>Definition at line 763 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instruction/#a041694a1ea45996587ef9712d9a2bb1f">llvm::Instruction::getSubclassData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a28797a7ad88ceb957e31f0bc5802395f">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::calculateCmpInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialconstantvaluesfloating/#a6097207906e979ba2cb03f2703ced3a0">anonymous{AttributorAttributes.cpp}::AAPotentialConstantValuesFloating::calculateICmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/hardwareloops-cpp/#adb6fcf2b6da127679d3169f4474e6912">CanGenerateTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a65c587ebfe84f7c55b3d2266ff0500f9">canonicalizeSaturatedSubtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#ab230432af09554d7dd357c77b0ec3cde">checkOrAndOpImpliedByOther</a>, <a href="/web-llvm/docs/api/classes/llvm/fcmpinst/#ab4bb1ceaf28449be1f1785b8f25971d5">llvm::FCmpInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a68c6d6251c01a927f5d8c37e486ae2f1">llvm::ICmpInst::cloneImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp/#ade155905429b0a259a1030f418c04ad9">computeUnlikelySuccessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a8160c4d5a8fc34f6085af951980dbaa6">createReplacement</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#acccaf0eaeef2b860b1182f8985f59e94">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateIVComparison</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a866883cec7ed781fcf1e9cda18b24f5b">llvm::InstCombinerImpl::foldCmpLoadFromIndexedGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a1f580ab00002a65787ab52ef2aa9a439">foldFCmpToFPClassTest</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9ab27a13577b53506529f28d41aa0672">llvm::InstCombinerImpl::foldICmpWithCastOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7caf9cd5dff4734b8af500d6f0f07437">llvm::InstCombinerImpl::foldICmpWithTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a04d40b2885dcf7e80feed09ba6209e54">llvm::InstCombinerImpl::foldICmpWithZextOrSext</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a22b32bcfbb9aec8a8fcb9826f40a3955">foldIsPowerOf2</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7a3e32edb65b5b1c216d4454f14df21c">llvm::InstCombinerImpl::foldPHIArgOpIntoPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ad51f65187d4c6b69d6bf8f71e027e4de">foldSelectICmpAndBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a6918e533fa9054323684d7e5d556c787">foldSelectICmpEq</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ad76042aae559769f4dc50ee2f9548789">foldSelectICmpLshrAshr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad2480247c6d76207d0f6c5a617534ab4">llvm::InstCombinerImpl::foldSelectInstWithICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a1f569ebf4402ad560d7c147f688ac05a">foldSignedTruncationCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#af0e4d9315f1815020f42edec6a27ad1f">getBranchCondString</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad3e63520dcd2b8f8aa1b2e66e734a575">getBranchWeights</a>, <a href="/web-llvm/docs/api/structs/llvm/loop/loopbounds/#acfa250dd5ec97448681f9833e22d50cf">llvm::Loop::LoopBounds::getCanonicalPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a36f67a81e2a4449854771f4e64efe60a">llvm::ICmpInst::getCmpPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a972c176c0737e91145863040aef6cbd9">llvm::ICmpInst::getFlippedSignednessPredicate</a>, <a href="#aafc99bbdcf56632d353043ae3e2bca21">getFlippedStrictnessPredicate</a>, <a href="#aa2a54b545d237ecfe450fd1292f7675e">getInversePredicate</a>, <a href="#a6b13f2e75444202b854672a5fbf85e2e">getNonStrictPredicate</a>, <a href="#a661fa29fe8d4acd9640aefa3a067f942">getOrderedPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a7b323f2153ac64cdbab7e81c15575c0d">getSalvageOpsForIcmpOp</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a9d5f70171d811078c4d263811f13c121">llvm::ICmpInst::getSignedPredicate</a>, <a href="#a0578679c169c9ca4cc731185ffddb431">getStrictPredicate</a>, <a href="#a49a2d8f483ea08a3d6ea75f90c640d76">getSwappedPredicate</a>, <a href="#ad91baf1a1f08eefbccce132916ff24c5">getUnorderedPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#af07a09f1cda33d984cc725dc9e856d40">llvm::ICmpInst::getUnsignedPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#a6ac9067dc7c125cd83855df3e480e04c">handleBrSelExpect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a807bb3d2ecc2999993a91d499bd26543">isCmpSameOrSwapped</a>, <a href="/web-llvm/docs/api/classes/llvm/fcmpinst/#a28aeb9345482725e92290f9d58b86626">llvm::FCmpInst::isCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a43218c25980995581eeef1e8b98d6ffe">llvm::ICmpInst::isCommutative</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp/#aa60423084fe7d27af0ffbba889cbdf1a">isEqualImpl</a>, <a href="#a0c27987ab3db5ef2125fd178e0ff21b2">isEquality</a>, <a href="/web-llvm/docs/api/classes/llvm/fcmpinst/#a25c8383fa246274a3e19d16c00f32ab1">llvm::FCmpInst::isEquality</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#aaaeded5d0cab77f531b294638459aca5">llvm::ICmpInst::isEquality</a>, <a href="#a340e06a462ce241e992ce74943f82a97">isEquivalence</a>, <a href="#a1e32582702cf5b9d4484c0ce346b2f57">isFalseWhenEqual</a>, <a href="#a7bd850492d35a34f0fe419e5555997a9">isFPPredicate</a>, <a href="#ad73f009e1b3b060bcdf6c2c1dd86600e">isIntPredicate</a>, <a href="#a75c72a7b8f5248ed6702dc166847cde9">isNonStrictPredicate</a>, <a href="#a3712279d70deeec90a93db09deb12d02">isSigned</a>, <a href="#aaabe18310fb8c24218fc883d7866ca58">isStrictPredicate</a>, <a href="#a5ba8484cef2818d14b85640a903b2598">isTrueWhenEqual</a>, <a href="#af206a3d6f58d9e53b074460f0d1ecb86">isUnsigned</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a304f0837129322608c9e0384d193a0ba">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::makeIVComparisonInvariant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf62ca503c047621e9b9047c548f231f">llvm::matchDecomposedSelectPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#acda14ede9da471244980c7fada91a4aa">negateICmpIfUsedByBranchOrSelectOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#aa26a7d0b19ce017fda518be95485fb8e">llvm::FastISel::optimizeCmpPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstructure/#adc8650d6098e0949f6ecc6368c2ebb99">llvm::LoopStructure::parseLoopStructure</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata/#aa7aa1c92fb184b145e4841fc114e790b">llvm::IRSimilarity::IRInstructionData::predicateForConsistency</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af37433fe005d86f4551e44915bd97e0b">llvm::InstCombinerImpl::replacedSelectWithOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad75372cc26ff6f641159aed90d5fc11e">reuseTableCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ae5781faa80a27cf51fa316feaa2ad363">simplifyAndOrOfICmpsWithConstants</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa4100f52d21246ec944e97fe1b64b124">llvm::InstCombinerImpl::simplifyRangeCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcheckandadjustir-cpp/#a6e78c58ee832ea1775655021854401e6">sinkMinMaxInBB</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ae4ca9bfe94c6cc3d952413c7907db47f">llvm::JumpThreadingPass::tryToUnfoldSelect</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#aaa39273101436002f3e3bd16293327be">anonymous{MergeICmps.cpp}::visitICmp</a>.</p>

</div>
</div>

### getStrictPredicate() {#a0578679c169c9ca4cc731185ffddb431}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Predicate llvm::CmpInst::getStrictPredicate ()</td>
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

<p>For example, SGE -&gt; SGT, SLE -&gt; SLT, ULE -&gt; ULT, UGE -&gt; UGT.</p>


<p>Returns the strict version of non-strict comparisons.</p>


<p>Definition at line 856 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#aa7414ba9f658ff1287d22a4b8fe81bcb">getPredicate</a> and <a href="#a0578679c169c9ca4cc731185ffddb431">getStrictPredicate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aaf52bffe6dc4a6d5d5cf515aac2e4450">llvm::decomposeBitTestICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acff3d4c4feb8a1f71844fa1facae5670">llvm::InstCombinerImpl::foldICmpWithMinMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a65be905e09162574d5634bcfcef7c4af">foldICmpXorXX</a>, <a href="#a23665a6553110e9303fff3ea76c21de1">getFlippedStrictnessPredicate</a>, <a href="#a0578679c169c9ca4cc731185ffddb431">getStrictPredicate</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a93f2e165baf61dd8295c9aececed9985">simplifyCmpSelOfMaxMin</a>.</p>

</div>
</div>

### getSwappedPredicate() {#a49a2d8f483ea08a3d6ea75f90c640d76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Predicate llvm::CmpInst::getSwappedPredicate ()</td>
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

<p>For example, EQ-&gt;EQ, SLE-&gt;SGE, ULT-&gt;UGT, OEQ-&gt;OEQ, ULE-&gt;UGE, OLT-&gt;OGT, etc.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the predicate that would be the result of exchanging the two operands of the <a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> instruction without changing the result produced. Return the predicate as if the operands were swapped</p></dd>
</dl>


<p>Definition at line 825 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#aa7414ba9f658ff1287d22a4b8fe81bcb">getPredicate</a> and <a href="#a49a2d8f483ea08a3d6ea75f90c640d76">getSwappedPredicate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/state/#a77dccdccff30d1cf89c684cf37cd85d8">anonymous{ConstraintElimination.cpp}::State::addInfoForInductions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeacc9805af138ccb1d72bc3000ec5013">llvm::analyzeICmp</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a682303631f076977e40a54643727e8a4">anonymous{AArch64PostLegalizerLowering.cpp}::applySwapICmpOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a94bc2ff14a27583461b207499f426ee2">canonicalizeForInvariantConditionInjection</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a3c4424f4bbcee5f3dd484c2822221812">canonicalizeSaturatedAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a65c587ebfe84f7c55b3d2266ff0500f9">canonicalizeSaturatedSubtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#af5d61d0124d62ee38726acc83dcdc037">compareCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3cd3a3ec28036937ecebe767498ba55d">llvm::ConstantFoldCompareInstOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a293a0cb64e182e693cdd406f8da7ced5">llvm::ConstantFoldCompareInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a7098623cafc05376a44b27d202b03372">countToEliminateCompares</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#acccaf0eaeef2b860b1182f8985f59e94">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateIVComparison</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a6f5eb28a130d94e94dff2f9e798617ab">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateTrunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfold-cpp/#aefdc5e2a3d0696ee5c5bf0b467e5f0c5">evaluateICmpRelation</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ad38d439eec395362c9cfce6c92751677">extractEquivalentCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a8be066fc4335931ee772b1e903beeca2">foldAbsDiff</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a25119a0e5bcc1f71c61c4acc02e3ff2b">foldICmpAndXX</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a78688f28e25e6d68d3f06ddf6e7aac0f">llvm::InstCombinerImpl::foldICmpCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8efbb860a56c4deccffeca4d2963fb70">llvm::InstCombinerImpl::foldICmpDivConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa270db889638f96fa18c715cdce379e0">llvm::InstCombinerImpl::foldICmpMulConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#afb20557855b41f2b32ebd166b4d4b10f">foldICmpOrXX</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a98c59bcf49cb7343886e8f425d6d877b">foldICmpWithDominatingICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aaa96689aeea89281ebb2a702b34cd7f9">foldICmpXNegX</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a65be905e09162574d5634bcfcef7c4af">foldICmpXorXX</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a5f883a229d57832ae195c8d102445847">llvm::InstCombinerImpl::foldSelectToCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#afdc0c60200d744fe53a7f48e3f7e4bb0">foldSelectWithFCmpToFabs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a81425fa662eac9cc9cd5d21f1c66695e">generateKeySubkey</a>, <a href="/web-llvm/docs/api/structs/llvm/loop/loopbounds/#acfa250dd5ec97448681f9833e22d50cf">llvm::Loop::LoopBounds::getCanonicalPredicate</a>, <a href="/web-llvm/docs/api/classes/anonymous-constraintelimination-cpp-/constraintinfo/#a085e72b5a3ed050deb15aa57090c54ba">anonymous{ConstraintElimination.cpp}::ConstraintInfo::getConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a741e5065c867d7dfd716eb8e16fccf12">llvm::ScalarEvolution::getLoopInvariantPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aa92b3e6375805368f9a24cf69ce73797">llvm::ScalarEvolution::getMonotonicPredicateType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvinstructionselector-cpp/#aeb9fd2e90366c6aeb6ceb89a21022894">getOperandsForBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfo/#a3296ab5af4e3c77a57810f97ab19e088">llvm::LazyValueInfo::getPredicateAt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#acb2c6a8dafac1cdf8927e67b28baab1c">getSameOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate/#ad155f02dd1653e10da9e766a5c0a90c7">llvm::CmpPredicate::getSwapped</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a36966e3f5427e7aa08dbbf358cc4b921">llvm::ICmpInst::getSwappedCmpPredicate</a>, <a href="#a49a2d8f483ea08a3d6ea75f90c640d76">getSwappedPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a66f8120f59f3970d1c0a554a8f7c3e2e">hoistAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a1f669cc640bda295e6c2e2b3c90babb9">hoistMinMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#aabf61131f4fe5c83b4f3dccf4adb5e96">hoistSub</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#afb636ad432c97f9178ff3f966e93d819">isAlternateInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a807bb3d2ecc2999993a91d499bd26543">isCmpSameOrSwapped</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a3e2c41b46422f8392e87d92a2f8e9d3c">isSameCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvinstructionselector-cpp/#ae5a410638118950b68cdb71cd984122b">legalizeFCmpPredicate</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a304f0837129322608c9e0384d193a0ba">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::makeIVComparisonInvariant</a>, <a href="/web-llvm/docs/api/structs/llvm/mipatternmatch/compareop-match/#afdb133294564dd07699c439079f2c1ee">llvm::MIPatternMatch::CompareOp_match&lt; Pred_P, LHS_P, RHS_P, Opcode, Commutable &gt;::match</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a7c6878dbda903ec9201f83db42d93fdc">llvm::CombinerHelper::matchCanonicalizeFCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ae7e76e88a680a8f2de889a6f6928fcc0">llvm::CombinerHelper::matchCanonicalizeICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aae4b3f95626af4abcad7012a51272475">matchClamp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a77bc4c2ac5bdfea178b15627e282cc8c">matchMinMaxOfMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a9098323777f98b3dd53bef412554961c">llvm::CombinerHelper::matchSelectIMinMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a59d23c7a219bf242360a0b2ef67bc3c8">matchSelectPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp/#ac766ad35d48500bdcc7df68b14f17b04">matchSelectWithOptionalNotCond</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8274be96f16c9dfbe1d003c5797d9644">llvm::InstCombinerImpl::matchThreeWayIntCompare</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstructure/#adc8650d6098e0949f6ecc6368c2ebb99">llvm::LoopStructure::parseLoopStructure</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata/#aa7aa1c92fb184b145e4841fc114e790b">llvm::IRSimilarity::IRInstructionData::predicateForConsistency</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a93f2e165baf61dd8295c9aececed9985">simplifyCmpSelOfMaxMin</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a110a350e37f3cc2ed2c603c3efde0a30">simplifyFCmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a64cb0c5ab10b63f22110e1b0183a648f">simplifyICmpWithBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a4f8adcab536e4c9f42e148d7eb218e6a">simplifyICmpWithMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa4100f52d21246ec944e97fe1b64b124">llvm::InstCombinerImpl::simplifyRangeCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a4355ad633eda8e7c8a6538ea41bb34f3">simplifyUnsignedRangeCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcheckandadjustir-cpp/#a6e78c58ee832ea1775655021854401e6">sinkMinMaxInBB</a>, <a href="/web-llvm/docs/api/classes/llvm/fcmpinst/#ad3be45a337f5541511a869dd2dcd7a38">llvm::FCmpInst::swapOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#acbc778ccd1faf4e95963c9a980acc7a5">llvm::ICmpInst::swapOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a1ec7a76fbddf5983969def6e47c0f177">threadCmpOverPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aa6faca61824779a7d72a2c1e08b9e7a0">threadCmpOverSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a86b0437dceb8e39c8185dc7def325011">llvm::InstCombinerImpl::visitFCmpInst</a>.</p>

</div>
</div>

### getUnorderedPredicate() {#ad91baf1a1f08eefbccce132916ff24c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Predicate llvm::CmpInst::getUnorderedPredicate ()</td>
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



<p>Definition at line 809 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#aa7414ba9f658ff1287d22a4b8fe81bcb">getPredicate</a> and <a href="#ad91baf1a1f08eefbccce132916ff24c5">getUnorderedPredicate</a>.</p>


<p>Referenced by <a href="#ad91baf1a1f08eefbccce132916ff24c5">getUnorderedPredicate</a>.</p>

</div>
</div>

### isCommutative() {#af9380fd13783f0a859e3942aa12d1091}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CmpInst::isCommutative ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is just a convenience that dispatches to the subclasses.</p>


<p>Determine if this <a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> is commutative.</p>


<p>Declaration at line 905 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3470 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>

</div>
</div>

### isEquality() {#a0c27987ab3db5ef2125fd178e0ff21b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CmpInst::isEquality ()</td>
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

<p>Determine if this is an equals/not equals predicate.</p>

<p>Definition at line 913 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#aa7414ba9f658ff1287d22a4b8fe81bcb">getPredicate</a> and <a href="#a0c27987ab3db5ef2125fd178e0ff21b2">isEquality</a>.</p>


<p>Referenced by <a href="#a0c27987ab3db5ef2125fd178e0ff21b2">isEquality</a>, <a href="#af9751cf77753dd8d3bb39c0bb7a281e1">isRelational</a>, <a href="#a98ecd87b7ee2e36f02e7ea0b366fd92c">isRelational</a> and <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aaf88f3025beeaebb5bd345ebe277711c">llvm::CombinerHelper::matchRedundantBinOpInEquality</a>.</p>

</div>
</div>

### isEquivalence() {#a340e06a462ce241e992ce74943f82a97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CmpInst::isEquivalence (bool Invert=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if one operand of this compare can always be replaced by the other operand, ignoring provenance considerations.</p>


<p>If <span class="doxyComputerOutput">Invert</span>, check for equivalence with the inverse predicate.</p>


<p>Declaration at line 918 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3499 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a2be3583dac92a031fa1458d4d992c78ba024db78a5ed74f64666f3ca4955e6eca">FCMP_OEQ</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba919643b83ce3c9af2e4296ed5e413a1f">FCMP_UEQ</a>, <a href="#aa2a54b545d237ecfe450fd1292f7675e">getInversePredicate</a>, <a href="#aa7414ba9f658ff1287d22a4b8fe81bcb">getPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a0d4bb13ba43d71cfe58184ab1bb4abd1">llvm::Instruction::hasNoNaNs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#a74f943f2404f6ec3f48ad5671b947b2c">hasNonZeroFPOperands</a> and <a href="#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">ICMP_EQ</a>.</p>

</div>
</div>

### isFalseWhenEqual() {#a1e32582702cf5b9d4484c0ce346b2f57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CmpInst::isFalseWhenEqual ()</td>
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

<p>This is just a convenience.</p>


<p>Determine if this is false when both operands are the same.</p>


<p>Definition at line 946 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#aa7414ba9f658ff1287d22a4b8fe81bcb">getPredicate</a> and <a href="#a1e32582702cf5b9d4484c0ce346b2f57">isFalseWhenEqual</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aec29f5580509ec9a7592200e09b7aa27">computePointerICmp</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a9dfa7d879ffc886a8014f1c9714ec166">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleCmp</a>, <a href="#a1e32582702cf5b9d4484c0ce346b2f57">isFalseWhenEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a110a350e37f3cc2ed2c603c3efde0a30">simplifyFCmpInst</a> and <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a5e9fc2b9bb75a684c20ca3fa6e14b63e">llvm::ScalarEvolution::SimplifyICmpOperands</a>.</p>

</div>
</div>

### isFPPredicate() {#a7bd850492d35a34f0fe419e5555997a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CmpInst::isFPPredicate ()</td>
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



<p>Definition at line 780 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#aa7414ba9f658ff1287d22a4b8fe81bcb">getPredicate</a> and <a href="#a7bd850492d35a34f0fe419e5555997a9">isFPPredicate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a6dacb1328b30771530a48be17307efb0">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a843d43d070f0b1c6a133403edce488ef">llvm::IRBuilderBase::CreateCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a> and <a href="#a7bd850492d35a34f0fe419e5555997a9">isFPPredicate</a>.</p>

</div>
</div>

### isIntPredicate() {#ad73f009e1b3b060bcdf6c2c1dd86600e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CmpInst::isIntPredicate ()</td>
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



<p>Definition at line 781 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#aa7414ba9f658ff1287d22a4b8fe81bcb">getPredicate</a> and <a href="#ad73f009e1b3b060bcdf6c2c1dd86600e">isIntPredicate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a6dacb1328b30771530a48be17307efb0">llvm::MachineIRBuilder::buildInstr</a>, <a href="#ad73f009e1b3b060bcdf6c2c1dd86600e">isIntPredicate</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76123bb0e0b41f5dbae594726160db22">llvm::MachineOperand::print</a>.</p>

</div>
</div>

### isNonStrictPredicate() {#a75c72a7b8f5248ed6702dc166847cde9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CmpInst::isNonStrictPredicate ()</td>
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
<dd><p>true if the comparison predicate is non-strict, false otherwise. Determine if this instruction is using an non-strict comparison predicate.</p></dd>
</dl>


<p>Definition at line 850 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#aa7414ba9f658ff1287d22a4b8fe81bcb">getPredicate</a> and <a href="#a75c72a7b8f5248ed6702dc166847cde9">isNonStrictPredicate</a>.</p>


<p>Referenced by <a href="#a23665a6553110e9303fff3ea76c21de1">getFlippedStrictnessPredicate</a> and <a href="#a75c72a7b8f5248ed6702dc166847cde9">isNonStrictPredicate</a>.</p>

</div>
</div>

### isRelational() {#af9751cf77753dd8d3bb39c0bb7a281e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CmpInst::isRelational ()</td>
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

<p>Definition at line 924 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a0c27987ab3db5ef2125fd178e0ff21b2">isEquality</a>.</p>

</div>
</div>

### isSigned() {#a3712279d70deeec90a93db09deb12d02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CmpInst::isSigned ()</td>
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
<dd><p>true if the comparison is signed, false otherwise. Determine if this instruction is using a signed comparison.</p></dd>
</dl>


<p>Definition at line 928 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#aa7414ba9f658ff1287d22a4b8fe81bcb">getPredicate</a> and <a href="#a3712279d70deeec90a93db09deb12d02">isSigned</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a2cf59a15a8b7603c5d66d8fdb117ecec">AllUsesOfValueWillTrapIfNull</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad3c7760a82783f7d9aea9166ad4b0fcb">llvm::calculateUpperBound</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3cd3a3ec28036937ecebe767498ba55d">llvm::ConstantFoldCompareInstOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaf52bffe6dc4a6d5d5cf515aac2e4450">llvm::decomposeBitTestICmp</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#acccaf0eaeef2b860b1182f8985f59e94">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateIVComparison</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a6f5eb28a130d94e94dff2f9e798617ab">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a25119a0e5bcc1f71c61c4acc02e3ff2b">foldICmpAndXX</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7df35aaa0732f4b23e5458034a2c29d1">llvm::InstCombinerImpl::foldICmpIntrinsicWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa270db889638f96fa18c715cdce379e0">llvm::InstCombinerImpl::foldICmpMulConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a566049e9c903d4e0067b8557d49c7d62">foldICmpWithLowBitMaskedVal</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acff3d4c4feb8a1f71844fa1facae5670">llvm::InstCombinerImpl::foldICmpWithMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a04d40b2885dcf7e80feed09ba6209e54">llvm::InstCombinerImpl::foldICmpWithZextOrSext</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aaa96689aeea89281ebb2a702b34cd7f9">foldICmpXNegX</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a5f883a229d57832ae195c8d102445847">llvm::InstCombinerImpl::foldSelectToCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a6745cdf992554f558011c1768d4b5747">foldSelectWithExtremeEqCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a7ea4fb4d6b0198f2b6eac325a8d93031">generateReproducer</a>, <a href="/web-llvm/docs/api/classes/anonymous-constraintelimination-cpp-/constraintinfo/#a085e72b5a3ed050deb15aa57090c54ba">anonymous{ConstraintElimination.cpp}::ConstraintInfo::getConstraint</a>, <a href="/web-llvm/docs/api/classes/anonymous-constraintelimination-cpp-/constraintinfo/#a8e787163c914dba0f28ef79e92c9768b">anonymous{ConstraintElimination.cpp}::ConstraintInfo::getConstraintForSolving</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#aab5ed5a6c201467c29ee9de89f80314a">llvm::ICmpInst::getFlippedSignednessPredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc4c2b42879015c8ee1d08fa7ff90d8f">llvm::getFlippedStrictnessPredicateAndConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a094d95c92490272d4b7a6bf4ab90009d">llvm::ScalarEvolution::getLoopInvariantExitCondDuringFirstIterationsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a7b323f2153ac64cdbab7e81c15575c0d">getSalvageOpsForIcmpOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a2f46552f3c07dc30e7acc64cdab53056">hoistAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a1f669cc640bda295e6c2e2b3c90babb9">hoistMinMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#aabf61131f4fe5c83b4f3dccf4adb5e96">hoistSub</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a650658d91a5b32920521b0f2120af053">isImpliedCondICmps</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#ac2b8ad8da7580efe927ce83c1be4ddd5">isImpliedTrueByMatchingCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a865c6ae11d94c83d4a7bcc0527f0fcef">IsKnownPredicateViaAddRecStart</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#ac8cf3aa27282d640f5acbc3a676e03c5">isSafeDecreasingBound</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#adbc17f3ace73f701522eefe28104c06c">isSafeIncreasingBound</a>, <a href="#a3712279d70deeec90a93db09deb12d02">isSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/minmaxintrinsic/#aacefcdc949f3458e46206861e2d7716d">llvm::MinMaxIntrinsic::isSigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#ab8102f1d2d3e331db1f1781055e61013">isSignTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a88b0909bfe0684c1c286237dd9985ce9">lookThroughCastConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a6ffcf0878851c4e84a8c11a68b07e9e7">lowerICMPIntrinsic</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstructure/#adc8650d6098e0949f6ecc6368c2ebb99">llvm::LoopStructure::parseLoopStructure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39b2cbd58018001ca6c1b2d26be87b86">llvm::predicatesFoldable</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a64cb0c5ab10b63f22110e1b0183a648f">simplifyICmpWithBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a7520bc5124cf32bdbb659ae6fc12cf9c">simplifyICmpWithConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcheckandadjustir-cpp/#a6e78c58ee832ea1775655021854401e6">sinkMinMaxInBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a0a89a6b25b8a92fb896a994a36b74241">llvm::InstCombinerImpl::visitAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aacc36b9bbb74a3cdb987aa8f28b269e3">llvm::LegalizerHelper::widenScalar</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#acd093283d4e8d1301859f0a98a157680">anonymous{SimplifyIndVar.cpp}::WidenIV::widenWithVariantUse</a>.</p>

</div>
</div>

### isStrictPredicate() {#aaabe18310fb8c24218fc883d7866ca58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CmpInst::isStrictPredicate ()</td>
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
<dd><p>true if the comparison predicate is strict, false otherwise. Determine if this instruction is using an strict comparison predicate.</p></dd>
</dl>


<p>Definition at line 841 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#aa7414ba9f658ff1287d22a4b8fe81bcb">getPredicate</a> and <a href="#aaabe18310fb8c24218fc883d7866ca58">isStrictPredicate</a>.</p>


<p>Referenced by <a href="#a23665a6553110e9303fff3ea76c21de1">getFlippedStrictnessPredicate</a> and <a href="#aaabe18310fb8c24218fc883d7866ca58">isStrictPredicate</a>.</p>

</div>
</div>

### isTrueWhenEqual() {#a5ba8484cef2818d14b85640a903b2598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CmpInst::isTrueWhenEqual ()</td>
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

<p>This is just a convenience.</p>


<p>Determine if this is true when both operands are the same.</p>


<p>Definition at line 940 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#aa7414ba9f658ff1287d22a4b8fe81bcb">getPredicate</a> and <a href="#a5ba8484cef2818d14b85640a903b2598">isTrueWhenEqual</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aec29f5580509ec9a7592200e09b7aa27">computePointerICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a293a0cb64e182e693cdd406f8da7ced5">llvm::ConstantFoldCompareInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a9dfa7d879ffc886a8014f1c9714ec166">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a050b9d439487145d988a49cf9a6132fe">isTruePredicate</a>, <a href="#a5ba8484cef2818d14b85640a903b2598">isTrueWhenEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a110a350e37f3cc2ed2c603c3efde0a30">simplifyFCmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a> and <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a5e9fc2b9bb75a684c20ca3fa6e14b63e">llvm::ScalarEvolution::SimplifyICmpOperands</a>.</p>

</div>
</div>

### isUnsigned() {#af206a3d6f58d9e53b074460f0d1ecb86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CmpInst::isUnsigned ()</td>
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
<dd><p>true if the comparison is unsigned, false otherwise. Determine if this instruction is using an unsigned comparison.</p></dd>
</dl>


<p>Definition at line 934 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#aa7414ba9f658ff1287d22a4b8fe81bcb">getPredicate</a> and <a href="#af206a3d6f58d9e53b074460f0d1ecb86">isUnsigned</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a65c587ebfe84f7c55b3d2266ff0500f9">canonicalizeSaturatedSubtract</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a6f5eb28a130d94e94dff2f9e798617ab">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affd5ebabccc8fdf81ca6d2eeff2e68c1">llvm::findValuesAffectedByCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa148a41463d0d36003033ac988b2c28d">llvm::InstCombinerImpl::foldICmpAddConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a78688f28e25e6d68d3f06ddf6e7aac0f">llvm::InstCombinerImpl::foldICmpCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa270db889638f96fa18c715cdce379e0">llvm::InstCombinerImpl::foldICmpMulConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a9a6d718332f56fad5b1dcb6c6c103057">foldICmpPow2Test</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acff3d4c4feb8a1f71844fa1facae5670">llvm::InstCombinerImpl::foldICmpWithMinMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aaa96689aeea89281ebb2a702b34cd7f9">foldICmpXNegX</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#aab5ed5a6c201467c29ee9de89f80314a">llvm::ICmpInst::getFlippedSignednessPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aa8f270ce4d001ee9e7839aa11c607931">injectPendingInvariantConditions</a>, <a href="#af206a3d6f58d9e53b074460f0d1ecb86">isUnsigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a88b0909bfe0684c1c286237dd9985ce9">lookThroughCastConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a64cb0c5ab10b63f22110e1b0183a648f">simplifyICmpWithBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a4355ad633eda8e7c8a6538ea41bb34f3">simplifyUnsignedRangeCheck</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#acd093283d4e8d1301859f0a98a157680">anonymous{SimplifyIndVar.cpp}::WidenIV::widenWithVariantUse</a>.</p>

</div>
</div>

### setPredicate() {#a126a12b67fa620ad28ec0c919ca7a3e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CmpInst::setPredicate (<a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> P)</td>
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

<p>Set the predicate for this instruction to the specified value.</p>

<p>Definition at line 766 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#afbb5877d4ac72148b232c8fedb08bba5">llvm::Instruction::setSubclassData</a>.</p>


<p>Referenced by <a href="#ae65337bd76ece9e7b1d20cf665bfa742">CmpInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#acccaf0eaeef2b860b1182f8985f59e94">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateIVComparison</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a2f46552f3c07dc30e7acc64cdab53056">hoistAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#aabf61131f4fe5c83b4f3dccf4adb5e96">hoistSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a70cdc32fcfc8ba3feaf026f4959e2c2a">llvm::InvertBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a304f0837129322608c9e0384d193a0ba">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::makeIVComparisonInvariant</a>, <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#acda14ede9da471244980c7fada91a4aa">negateICmpIfUsedByBranchOrSelectOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/fcmpinst/#ad3be45a337f5541511a869dd2dcd7a38">llvm::FCmpInst::swapOperands</a> and <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#acbc778ccd1faf4e95963c9a980acc7a5">llvm::ICmpInst::swapOperands</a>.</p>

</div>
</div>

### swapOperands() {#a8b39b8cdcb092d69083a4fefe98bb083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CmpInst::swapOperands ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is just a convenience that dispatches to the subclasses.</p>


<p>Swap the operands and adjust predicate accordingly to retain the same comparison.</p>


<p>Declaration at line 901 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3463 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="#a8b39b8cdcb092d69083a4fefe98bb083">swapOperands</a>.</p>


<p>Referenced by <a href="#a8b39b8cdcb092d69083a4fefe98bb083">swapOperands</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### setValueSubclassData() {#a36f1e936c4996e83debb47a573d73c10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CmpInst::setValueSubclassData (unsigned short D)</td>
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



<p>Definition at line 991 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a24a5f30f3d82fa2f32115ef1df689c07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CmpInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Methods for support type inquiry through isa, cast, and dyn_cast:</p>

<p>Definition at line 971 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae70f02adcd410ca9c8429fa8d7711965">llvm::Instruction::Instruction</a>.</p>


<p>Referenced by <a href="#aea968ce5b75b8e4c71a9f527a3028d6d">classof</a>.</p>

</div>
</div>

### classof() {#aea968ce5b75b8e4c71a9f527a3028d6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CmpInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 975 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a24a5f30f3d82fa2f32115ef1df689c07">classof</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### Create() {#a62e2cf3675b93f0e6c07a4a00852f7cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpInst * CmpInst::Create (<a href="/web-llvm/docs/api/classes/llvm/instruction/#a92db6d5865b9492ef8eeedad41235d0a">OtherOps</a> Op, <a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * S1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * S2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
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

<p>Construct a compare instruction, given the opcode, the predicate and the two operands.</p>


<p>Optionally (if InstBefore is specified) insert the instruction into a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> right before the specified instruction. The specified <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> is allowed to be a dereferenced end iterator. Create a <a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a></p>


<p>Declaration at line 741 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3434 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#ae65337bd76ece9e7b1d20cf665bfa742">CmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/insertposition/#a004805cdcc4314519ac66a4977ab408c">llvm::InsertPosition::isValid</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#a16144b1e0f0bc86c81b262b2f82c44df">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::buildCustomStateMachine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a646829664451eb913bfa2f92920478ea">calcPredicateUsingInteger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a545034b7da895280ed2c457c835d98f2">llvm::fuzzerop::cmpOpDescriptor</a>, <a href="#a6d0ee639690d0fa59e6c9e0af5adc5c2">CreateWithCopiedFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7df35aaa0732f4b23e5458034a2c29d1">llvm::InstCombinerImpl::foldICmpIntrinsicWithConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a3c60326c7cc5b93cc7ee840435e1600d">foldICmpInvariantGroup</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7c9fd9f2dba79c2289639f72457fcea1">llvm::InstCombinerImpl::foldICmpUsingBoolRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a84f21a080a9d5fddbdcee787d3f295e0">foldICmpWithHighBitMask</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acff3d4c4feb8a1f71844fa1facae5670">llvm::InstCombinerImpl::foldICmpWithMinMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aaa96689aeea89281ebb2a702b34cd7f9">foldICmpXNegX</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a90148636c6d38a9475471b8b43e93b04">llvm::InstCombinerImpl::foldIRemByPowerOfTwoToBitTest</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4df124d92129ffa8748086388a420b73">llvm::InstCombinerImpl::foldPHIArgBinOpIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7a3e32edb65b5b1c216d4454f14df21c">llvm::InstCombinerImpl::foldPHIArgOpIntoPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a41baeb4167dc326182b3c281d69232ae">foldReductionIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1f737dab05d29dca38561bc99b9ef5b5">llvm::InstCombinerImpl::foldSignBitTest</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#aaffd2ef85a5bde3351bbc659c18c1ebe">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::forceSingleThreadPerWorkgroupHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aa8f270ce4d001ee9e7839aa11c607931">injectPendingInvariantConditions</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a24a3e4aad4cb2fdde7ce294a531cd52a">sinkCmpExpression</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae31c50e938b95587c87aed0f133b1346">llvm::InstCombinerImpl::visitICmpInst</a>.</p>

</div>
</div>

### CreateWithCopiedFlags() {#a6d0ee639690d0fa59e6c9e0af5adc5c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpInst * CmpInst::CreateWithCopiedFlags (<a href="/web-llvm/docs/api/classes/llvm/instruction/#a92db6d5865b9492ef8eeedad41235d0a">OtherOps</a> Op, <a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * S1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * S2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * FlagsSource, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
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

<p>Construct a compare instruction, given the opcode, the predicate, the two operands and the instruction to copy the flags from.</p>


<p>Optionally (if InstBefore is specified) insert the instruction into a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> right before the specified instruction. The specified <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> is allowed to be a dereferenced end iterator. Create a <a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a></p>


<p>Declaration at line 751 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3453 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#ae65337bd76ece9e7b1d20cf665bfa742">CmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a3e6d2896c39a84cfa6c47f34cdc584ff">llvm::Instruction::copyIRFlags</a>, <a href="#a62e2cf3675b93f0e6c07a4a00852f7cd">Create</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae70f02adcd410ca9c8429fa8d7711965">llvm::Instruction::Instruction</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a71ef354bd1ea9e02d70146d7218a7d39">llvm::InstCombinerImpl::visitExtractElementInst</a>.</p>

</div>
</div>

### FCmpPredicates() {#a49a78eafc7ac1f2afbfce2a88022bc28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto llvm::CmpInst::FCmpPredicates ()</td>
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

<p>Returns the sequence of all FCmp predicates.</p>

<p>Definition at line 712 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1007cb97b7cec9a75cfa17e031c62432">llvm::enum_seq_inclusive</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba392f2cfc83c62daa024d96b8a13872f8">FIRST_FCMP_PREDICATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b5e6b876da6b3f05f152988e2837b4c">llvm::force_iteration_on_noniterable_enum</a> and <a href="#a2be3583dac92a031fa1458d4d992c78bab10f753354ede9597f74448afbb0762c">LAST_FCMP_PREDICATE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fcmpinst/#ab0d798d86d3a8b6d99a49cf81328e52b">llvm::FCmpInst::predicates</a>.</p>

</div>
</div>

### getFlippedStrictnessPredicate() {#a23665a6553110e9303fff3ea76c21de1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpInst::Predicate CmpInst::getFlippedStrictnessPredicate (<a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> pred)</td>
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

<p>This is a static version that you can use without an instruction available.</p>


<p>Return the flipped strictness of predicate</p>


<p>Declaration at line 883 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3718 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6b13f2e75444202b854672a5fbf85e2e">getNonStrictPredicate</a>, <a href="#a0578679c169c9ca4cc731185ffddb431">getStrictPredicate</a>, <a href="#a75c72a7b8f5248ed6702dc166847cde9">isNonStrictPredicate</a>, <a href="#a98ecd87b7ee2e36f02e7ea0b366fd92c">isRelational</a>, <a href="#aaabe18310fb8c24218fc883d7866ca58">isStrictPredicate</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenpredicate-cpp/#a0de1bf31f56b17312cc34b911d86faa4">pred</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a25119a0e5bcc1f71c61c4acc02e3ff2b">foldICmpAndXX</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1140591a375ac3efde57977192880eb0">llvm::InstCombinerImpl::foldICmpOrConstant</a>.</p>

</div>
</div>

### getInversePredicate() {#aa11e04e8ea07654a3a172d1169fb4ca8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpInst::Predicate CmpInst::getInversePredicate (<a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> pred)</td>
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

<p>For example, EQ -&gt; NE, UGT -&gt; ULE, SLT -&gt; SGE, OEQ -&gt; UNE, UGT -&gt; OLE, OLT -&gt; UGE, etc.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the inverse predicate for predicate provided in <span class="doxyComputerOutput">pred</span>. Return the inverse of a given predicate</p></dd>
</dl>


<p>Declaration at line 817 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3514 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a2be3583dac92a031fa1458d4d992c78bae9c013750fff3023001d7e3af8df2d6d">FCMP_FALSE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba024db78a5ed74f64666f3ca4955e6eca">FCMP_OEQ</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba541533f34077bbbcfb703a90f6d2da9b">FCMP_OGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba4c399f525bbcf03d72af4b303e6eeca8">FCMP_OGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba9835cfe02fb5027680bd7203b024f77a">FCMP_OLE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba326bee0a4a424cef21c1cf8adb8b8dd8">FCMP_OLT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba8a80b27ca29fe2076b9bbdee02c65464">FCMP_ONE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78baa3213b645e029aba8bb1b85213607d5e">FCMP_ORD</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba0a33c71e3c5e8f128ca47539a85962f5">FCMP_TRUE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba919643b83ce3c9af2e4296ed5e413a1f">FCMP_UEQ</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bae51609fc6a425f849d37c28cb9bc0344">FCMP_UGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba959268ceeae23abe5c9ad9e895669d0c">FCMP_UGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba396dda2571cd3c575f1d9cb44dc2cc09">FCMP_ULE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba75016d5872d90adf89cc1cbf5763f474">FCMP_ULT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bad601460c9371d0f0ada5ae006bdba2bd">FCMP_UNE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78baf0159e4005258dc54f20b6fc227d19ed">FCMP_UNO</a>, <a href="#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">ICMP_EQ</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">ICMP_NE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">ICMP_SGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">ICMP_SGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">ICMP_SLE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">ICMP_SLT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">ICMP_UGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">ICMP_UGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">ICMP_ULE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">ICMP_ULT</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenpredicate-cpp/#a0de1bf31f56b17312cc34b911d86faa4">pred</a>.</p>

</div>
</div>

### getNonStrictPredicate() {#ae548c5f1dacf3f055b391daba9e7a659}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpInst::Predicate CmpInst::getNonStrictPredicate (<a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> pred)</td>
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

<p>This is a static version that you can use without an instruction available.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the non-strict version of comparison provided in <span class="doxyComputerOutput">pred</span>. If <span class="doxyComputerOutput">pred</span> is not a strict comparison predicate, returns <span class="doxyComputerOutput">pred</span>. Returns the non-strict version of strict comparisons.</p></dd>
</dl>


<p>Declaration at line 878 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3695 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a2be3583dac92a031fa1458d4d992c78ba541533f34077bbbcfb703a90f6d2da9b">FCMP_OGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba4c399f525bbcf03d72af4b303e6eeca8">FCMP_OGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba9835cfe02fb5027680bd7203b024f77a">FCMP_OLE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba326bee0a4a424cef21c1cf8adb8b8dd8">FCMP_OLT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bae51609fc6a425f849d37c28cb9bc0344">FCMP_UGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba959268ceeae23abe5c9ad9e895669d0c">FCMP_UGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba396dda2571cd3c575f1d9cb44dc2cc09">FCMP_ULE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba75016d5872d90adf89cc1cbf5763f474">FCMP_ULT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">ICMP_SGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">ICMP_SGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">ICMP_SLE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">ICMP_SLT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">ICMP_UGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">ICMP_UGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">ICMP_ULE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">ICMP_ULT</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenpredicate-cpp/#a0de1bf31f56b17312cc34b911d86faa4">pred</a>.</p>

</div>
</div>

### getOrderedPredicate() {#ab95f6ee8398d4632b27c25783f3339ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Predicate llvm::CmpInst::getOrderedPredicate (<a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> Pred)</td>
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

<p>Returns the ordered variant of a floating point compare.</p>


<p>For example, UEQ -&gt; OEQ, ULT -&gt; OLT, OEQ -&gt; OEQ</p>


<p>Definition at line 794 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a2be3583dac92a031fa1458d4d992c78baa3213b645e029aba8bb1b85213607d5e">FCMP_ORD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a5946d75decfd106d2b75af6d59009f34">matchIsFiniteTest</a>.</p>

</div>
</div>

### getPredicateName() {#aa68a2d2c06a10b1e5a5bc778a107c0ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef CmpInst::getPredicateName (<a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> P)</td>
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



<p>Declaration at line 778 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3547 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a2be3583dac92a031fa1458d4d992c78bae9c013750fff3023001d7e3af8df2d6d">FCMP_FALSE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba024db78a5ed74f64666f3ca4955e6eca">FCMP_OEQ</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba541533f34077bbbcfb703a90f6d2da9b">FCMP_OGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba4c399f525bbcf03d72af4b303e6eeca8">FCMP_OGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba9835cfe02fb5027680bd7203b024f77a">FCMP_OLE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba326bee0a4a424cef21c1cf8adb8b8dd8">FCMP_OLT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba8a80b27ca29fe2076b9bbdee02c65464">FCMP_ONE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78baa3213b645e029aba8bb1b85213607d5e">FCMP_ORD</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba0a33c71e3c5e8f128ca47539a85962f5">FCMP_TRUE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba919643b83ce3c9af2e4296ed5e413a1f">FCMP_UEQ</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bae51609fc6a425f849d37c28cb9bc0344">FCMP_UGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba959268ceeae23abe5c9ad9e895669d0c">FCMP_UGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba396dda2571cd3c575f1d9cb44dc2cc09">FCMP_ULE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba75016d5872d90adf89cc1cbf5763f474">FCMP_ULT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bad601460c9371d0f0ada5ae006bdba2bd">FCMP_UNE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78baf0159e4005258dc54f20b6fc227d19ed">FCMP_UNO</a>, <a href="#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">ICMP_EQ</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">ICMP_NE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">ICMP_SGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">ICMP_SGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">ICMP_SLE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">ICMP_SLT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">ICMP_UGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">ICMP_UGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">ICMP_ULE</a> and <a href="#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">ICMP_ULT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#afbf9fd3d3729664031c88766bcefcdf0">anonymous{CloneFunction.cpp}::PruningFunctionCloner::cloneInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a43f7a62f184069bc5077ddc9181d2ab2">llvm::operator&lt;&lt;</a> and <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#ae6a91bbf1cfed2d6ba572ca974c94161">llvm::VPRecipeWithIRFlags::printFlags</a>.</p>

</div>
</div>

### getStrictPredicate() {#a820c0ce2716bbd66df04f397054c980d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpInst::Predicate CmpInst::getStrictPredicate (<a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> pred)</td>
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

<p>This is a static version that you can use without an instruction available.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the strict version of comparison provided in <span class="doxyComputerOutput">pred</span>. If <span class="doxyComputerOutput">pred</span> is not a strict comparison predicate, returns <span class="doxyComputerOutput">pred</span>. Returns the strict version of non-strict comparisons.</p></dd>
</dl>


<p>Declaration at line 865 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3672 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a2be3583dac92a031fa1458d4d992c78ba541533f34077bbbcfb703a90f6d2da9b">FCMP_OGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba4c399f525bbcf03d72af4b303e6eeca8">FCMP_OGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba9835cfe02fb5027680bd7203b024f77a">FCMP_OLE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba326bee0a4a424cef21c1cf8adb8b8dd8">FCMP_OLT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bae51609fc6a425f849d37c28cb9bc0344">FCMP_UGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba959268ceeae23abe5c9ad9e895669d0c">FCMP_UGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba396dda2571cd3c575f1d9cb44dc2cc09">FCMP_ULE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba75016d5872d90adf89cc1cbf5763f474">FCMP_ULT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">ICMP_SGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">ICMP_SGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">ICMP_SLE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">ICMP_SLT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">ICMP_UGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">ICMP_UGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">ICMP_ULE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">ICMP_ULT</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenpredicate-cpp/#a0de1bf31f56b17312cc34b911d86faa4">pred</a>.</p>

</div>
</div>

### getSwappedPredicate() {#af9a9ca11399cf7101e5102589f043cf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpInst::Predicate CmpInst::getSwappedPredicate (<a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> pred)</td>
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

<p>This is a static version that you can use without an instruction available.</p>


<p>Return the predicate as if the operands were swapped.</p>


<p>Declaration at line 832 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3610 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a2be3583dac92a031fa1458d4d992c78bae9c013750fff3023001d7e3af8df2d6d">FCMP_FALSE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba024db78a5ed74f64666f3ca4955e6eca">FCMP_OEQ</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba541533f34077bbbcfb703a90f6d2da9b">FCMP_OGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba4c399f525bbcf03d72af4b303e6eeca8">FCMP_OGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba9835cfe02fb5027680bd7203b024f77a">FCMP_OLE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba326bee0a4a424cef21c1cf8adb8b8dd8">FCMP_OLT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba8a80b27ca29fe2076b9bbdee02c65464">FCMP_ONE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78baa3213b645e029aba8bb1b85213607d5e">FCMP_ORD</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba0a33c71e3c5e8f128ca47539a85962f5">FCMP_TRUE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba919643b83ce3c9af2e4296ed5e413a1f">FCMP_UEQ</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bae51609fc6a425f849d37c28cb9bc0344">FCMP_UGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba959268ceeae23abe5c9ad9e895669d0c">FCMP_UGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba396dda2571cd3c575f1d9cb44dc2cc09">FCMP_ULE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba75016d5872d90adf89cc1cbf5763f474">FCMP_ULT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bad601460c9371d0f0ada5ae006bdba2bd">FCMP_UNE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78baf0159e4005258dc54f20b6fc227d19ed">FCMP_UNO</a>, <a href="#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">ICMP_EQ</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">ICMP_NE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">ICMP_SGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">ICMP_SGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">ICMP_SLE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">ICMP_SLT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">ICMP_UGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">ICMP_UGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">ICMP_ULE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">ICMP_ULT</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenpredicate-cpp/#a0de1bf31f56b17312cc34b911d86faa4">pred</a>.</p>

</div>
</div>

### getUnorderedPredicate() {#af43d73db8b352514cd05bad535e44746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Predicate llvm::CmpInst::getUnorderedPredicate (<a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> Pred)</td>
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

<p>Returns the unordered variant of a floating point compare.</p>


<p>For example, OEQ -&gt; UEQ, OLT -&gt; ULT, OEQ -&gt; UEQ</p>


<p>Definition at line 805 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a2be3583dac92a031fa1458d4d992c78baf0159e4005258dc54f20b6fc227d19ed">FCMP_UNO</a>.</p>

</div>
</div>

### ICmpPredicates() {#a2f9b3094f4be2263366d46be4a29b73e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto llvm::CmpInst::ICmpPredicates ()</td>
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

<p>Definition at line 719 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1007cb97b7cec9a75cfa17e031c62432">llvm::enum_seq_inclusive</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba1d680986286d79b2eb671750e9c78dbe">FIRST_ICMP_PREDICATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b5e6b876da6b3f05f152988e2837b4c">llvm::force_iteration_on_noniterable_enum</a> and <a href="#a2be3583dac92a031fa1458d4d992c78baa5c6e466e2df2c472e487f84531421fc">LAST_ICMP_PREDICATE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#ad3a66e8579a590f0ea0f0bcd879e1953">llvm::ICmpInst::predicates</a>.</p>

</div>
</div>

### isEquality() {#a38d34fceda94c01af95b775632ba8299}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CmpInst::isEquality (<a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> pred)</td>
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

<p>Determine if this is an equals/not equals predicate.</p>


<p>This is a static version that you can use without an instruction available.</p>


<p>Declaration at line 910 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3476 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/fcmpinst/#a25c8383fa246274a3e19d16c00f32ab1">llvm::FCmpInst::isEquality</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#aaaeded5d0cab77f531b294638459aca5">llvm::ICmpInst::isEquality</a>, <a href="#a66c10680694a0184d50e7a8c0d1ea874">isFPPredicate</a>, <a href="#ad8c2100cae3093d71e65a48908158e22">isIntPredicate</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-constraintelimination-cpp-/constraintinfo/#a5b2900a4d0eed6238bc169af9e528863">anonymous{ConstraintElimination.cpp}::ConstraintInfo::addFact</a>, <a href="/web-llvm/docs/api/classes/anonymous-constraintelimination-cpp-/constraintinfo/#a085e72b5a3ed050deb15aa57090c54ba">anonymous{ConstraintElimination.cpp}::ConstraintInfo::getConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#aab5ed5a6c201467c29ee9de89f80314a">llvm::ICmpInst::getFlippedSignednessPredicate</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a9dfa7d879ffc886a8014f1c9714ec166">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64giselutils/#aecef689b4ba2a5bf1d3609151f448180">llvm::AArch64GISelUtils::isCMN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf62ca503c047621e9b9047c548f231f">llvm::matchDecomposedSelectPattern</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a79ff9815398a2c3331b42832035f21c6">llvm::CombinerHelper::matchICmpToLHSKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a9098323777f98b3dd53bef412554961c">llvm::CombinerHelper::matchSelectIMinMax</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a752efe4724ac3a97d07ee81d5f779c92">llvm::InstCombinerImpl::visitPHINode</a>.</p>

</div>
</div>

### isFalseWhenEqual() {#ac1e20f6a8ec09b49fbe4d574b2757379}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CmpInst::isFalseWhenEqual (<a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> predicate)</td>
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

<p>Determine if the predicate is false when comparing a value with itself.</p>

<p>Declaration at line 968 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3881 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a2be3583dac92a031fa1458d4d992c78bae9c013750fff3023001d7e3af8df2d6d">FCMP_FALSE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba4c399f525bbcf03d72af4b303e6eeca8">FCMP_OGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba326bee0a4a424cef21c1cf8adb8b8dd8">FCMP_OLT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba8a80b27ca29fe2076b9bbdee02c65464">FCMP_ONE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">ICMP_NE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">ICMP_SGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">ICMP_SLT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">ICMP_UGT</a> and <a href="#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">ICMP_ULT</a>.</p>

</div>
</div>

### isFPPredicate() {#a66c10680694a0184d50e7a8c0d1ea874}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CmpInst::isFPPredicate (<a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> P)</td>
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



<p>Definition at line 768 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a2be3583dac92a031fa1458d4d992c78ba392f2cfc83c62daa024d96b8a13872f8">FIRST_FCMP_PREDICATE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bab10f753354ede9597f74448afbb0762c">LAST_FCMP_PREDICATE</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a3cd3a3ec28036937ecebe767498ba55d">llvm::ConstantFoldCompareInstOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a917f93b85c9b8cfe9ad68ba6d49966ba">foldSelectBinOpIdentity</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1baed59fc0a242d63e6eac45f50f37dd">llvm::RISCVTTIImpl::getCmpSelInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate/#a1c29fdc79aad7e92c7f850bbd0faa208">llvm::CmpPredicate::getMatching</a>, <a href="#a38d34fceda94c01af95b775632ba8299">isEquality</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ad02dfd40a37e1c0fc6365a700c4263dc">lowerFCMPIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a7c6878dbda903ec9201f83db42d93fdc">llvm::CombinerHelper::matchCanonicalizeFCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a59d23c7a219bf242360a0b2ef67bc3c8">matchSelectPattern</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a4590f4e05f484028f3b4bf3387955427">anonymous{MIParser.cpp}::MIParser::parsePredicateOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a110a350e37f3cc2ed2c603c3efde0a30">simplifyFCmpInst</a>.</p>

</div>
</div>

### isIntPredicate() {#ad8c2100cae3093d71e65a48908158e22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CmpInst::isIntPredicate (<a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> P)</td>
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



<p>Definition at line 774 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a2be3583dac92a031fa1458d4d992c78ba1d680986286d79b2eb671750e9c78dbe">FIRST_ICMP_PREDICATE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78baa5c6e466e2df2c472e487f84531421fc">LAST_ICMP_PREDICATE</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a8bd7da2c6b76da474423e160c63fdc68">canonicalizeCmpWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate/#a73f832a07263966ceb3958de221d25a0">llvm::CmpPredicate::CmpPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a5769f1da829d6f6400b486d8e34e317f">llvm::ICmpInst::compare</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a293a0cb64e182e693cdd406f8da7ced5">llvm::ConstantFoldCompareInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a45b557c1f3f224d01fc38c055ced3c58">llvm::AArch64TTIImpl::getCmpSelInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1baed59fc0a242d63e6eac45f50f37dd">llvm::RISCVTTIImpl::getCmpSelInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a1ca4520a4894a14c70f390091ee8d05d">llvm::ConstantRange::getEquivalentPredWithFlippedSignedness</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc4c2b42879015c8ee1d08fa7ff90d8f">llvm::getFlippedStrictnessPredicateAndConstant</a>, <a href="#a38d34fceda94c01af95b775632ba8299">isEquality</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a2aeed55e4456de4086b3592eb92dc2e2">llvm::ARMLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a6ffcf0878851c4e84a8c11a68b07e9e7">lowerICMPIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ae7e76e88a680a8f2de889a6f6928fcc0">llvm::CombinerHelper::matchCanonicalizeICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a77bc4c2ac5bdfea178b15627e282cc8c">matchMinMaxOfMinMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a59d23c7a219bf242360a0b2ef67bc3c8">matchSelectPattern</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a4590f4e05f484028f3b4bf3387955427">anonymous{MIParser.cpp}::MIParser::parsePredicateOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a5a5e32c5d5b01554c4d171562427a2de">simplifyCmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a62e2ba967b974d6e68931532ab1aa4e8">llvm::InstCombinerImpl::visitSelectInst</a>.</p>

</div>
</div>

### isNonStrictPredicate() {#a9cf49613e9993b859e165996ca5655d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CmpInst::isNonStrictPredicate (<a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> predicate)</td>
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

<p>This is a static version that you can use without an instruction available.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the comparison predicate is non-strict, false otherwise.</p></dd>
</dl>


<p>Declaration at line 846 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3640 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a2be3583dac92a031fa1458d4d992c78ba541533f34077bbbcfb703a90f6d2da9b">FCMP_OGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba9835cfe02fb5027680bd7203b024f77a">FCMP_OLE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bae51609fc6a425f849d37c28cb9bc0344">FCMP_UGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba396dda2571cd3c575f1d9cb44dc2cc09">FCMP_ULE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">ICMP_SGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">ICMP_SLE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">ICMP_UGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">ICMP_ULE</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenpredicate-cpp/#a0de1bf31f56b17312cc34b911d86faa4">pred</a>.</p>

</div>
</div>

### isOrdered() {#ad91c80980a394e9c81f04e8988261224}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CmpInst::isOrdered (<a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> predicate)</td>
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

<p>Determine if the predicate is an ordered operation.</p>

<p>Declaration at line 959 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3855 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a2be3583dac92a031fa1458d4d992c78ba024db78a5ed74f64666f3ca4955e6eca">FCMP_OEQ</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba541533f34077bbbcfb703a90f6d2da9b">FCMP_OGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba4c399f525bbcf03d72af4b303e6eeca8">FCMP_OGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba9835cfe02fb5027680bd7203b024f77a">FCMP_OLE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba326bee0a4a424cef21c1cf8adb8b8dd8">FCMP_OLT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba8a80b27ca29fe2076b9bbdee02c65464">FCMP_ONE</a> and <a href="#a2be3583dac92a031fa1458d4d992c78baa3213b645e029aba8bb1b85213607d5e">FCMP_ORD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1539ae3ac4221909b26a57b4664e426a">llvm::fcmpImpliesClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#afdc0c60200d744fe53a7f48e3f7e4bb0">foldSelectWithFCmpToFabs</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a84ec432d02febd1b518e9453b1a0eba9">llvm::ConstantFPRange::makeAllowedFCmpRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a4c7a26e0bf4a7880f0ba8c3aa2d74a89">llvm::ConstantFPRange::makeSatisfyingFCmpRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a59d23c7a219bf242360a0b2ef67bc3c8">matchSelectPattern</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#acb8e54b9f6be2fdb87b369c2218db1cc">simplifyAndOrOfFCmps</a>.</p>

</div>
</div>

### isRelational() {#a98ecd87b7ee2e36f02e7ea0b366fd92c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CmpInst::isRelational (<a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> P)</td>
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

<p>Definition at line 921 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a0c27987ab3db5ef2125fd178e0ff21b2">isEquality</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#aadd274cfa4ae19782aa85d9f162925c6">foldSelectIntoAddConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a1ca4520a4894a14c70f390091ee8d05d">llvm::ConstantRange::getEquivalentPredWithFlippedSignedness</a> and <a href="#a23665a6553110e9303fff3ea76c21de1">getFlippedStrictnessPredicate</a>.</p>

</div>
</div>

### isSigned() {#ad69ad0984324da2e7e1d6830228a3ade}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CmpInst::isSigned (<a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> predicate)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the predicate is signed, false otherwise. Determine if the predicate is an signed operation.</p></dd>
</dl>


<p>Declaration at line 956 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3737 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">ICMP_SGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">ICMP_SGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">ICMP_SLE</a> and <a href="#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">ICMP_SLT</a>.</p>

</div>
</div>

### isStrictPredicate() {#a7d82fa77fd3d80b33e0beabb65ad8b93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CmpInst::isStrictPredicate (<a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> predicate)</td>
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

<p>This is a static version that you can use without an instruction available.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the comparison predicate is strict, false otherwise.</p></dd>
</dl>


<p>Declaration at line 837 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3656 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a2be3583dac92a031fa1458d4d992c78ba4c399f525bbcf03d72af4b303e6eeca8">FCMP_OGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba326bee0a4a424cef21c1cf8adb8b8dd8">FCMP_OLT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba959268ceeae23abe5c9ad9e895669d0c">FCMP_UGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba75016d5872d90adf89cc1cbf5763f474">FCMP_ULT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">ICMP_SGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">ICMP_SLT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">ICMP_UGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">ICMP_ULT</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenpredicate-cpp/#a0de1bf31f56b17312cc34b911d86faa4">pred</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abe15d83fb0501730bbfe840143cedc08">llvm::InstCombinerImpl::foldICmpShlConstant</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a9ba70601e2398b462375dd8f3e9bc1b2">insertCandidatesWithPendingInjections</a>.</p>

</div>
</div>

### isTrueWhenEqual() {#a7ec811146e53bcf7e6c87b60ddef2827}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CmpInst::isTrueWhenEqual (<a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> predicate)</td>
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

<p>Determine if the predicate is true when comparing a value with itself.</p>

<p>Declaration at line 965 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3873 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a2be3583dac92a031fa1458d4d992c78ba0a33c71e3c5e8f128ca47539a85962f5">FCMP_TRUE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba919643b83ce3c9af2e4296ed5e413a1f">FCMP_UEQ</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bae51609fc6a425f849d37c28cb9bc0344">FCMP_UGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba396dda2571cd3c575f1d9cb44dc2cc09">FCMP_ULE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">ICMP_EQ</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">ICMP_SGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">ICMP_SLE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">ICMP_UGE</a> and <a href="#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">ICMP_ULE</a>.</p>

</div>
</div>

### isUnordered() {#aae55ea42185b7528c0c149625b998968}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CmpInst::isUnordered (<a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> predicate)</td>
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

<p>Determine if the predicate is an unordered operation.</p>

<p>Declaration at line 962 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3864 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a2be3583dac92a031fa1458d4d992c78ba919643b83ce3c9af2e4296ed5e413a1f">FCMP_UEQ</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bae51609fc6a425f849d37c28cb9bc0344">FCMP_UGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba959268ceeae23abe5c9ad9e895669d0c">FCMP_UGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba396dda2571cd3c575f1d9cb44dc2cc09">FCMP_ULE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba75016d5872d90adf89cc1cbf5763f474">FCMP_ULT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bad601460c9371d0f0ada5ae006bdba2bd">FCMP_UNE</a> and <a href="#a2be3583dac92a031fa1458d4d992c78baf0159e4005258dc54f20b6fc227d19ed">FCMP_UNO</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a293a0cb64e182e693cdd406f8da7ced5">llvm::ConstantFoldCompareInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa56f37cb4a3ca6ae2017ac7c5e5b5d13">llvm::fcmpImpliesClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1539ae3ac4221909b26a57b4664e426a">llvm::fcmpImpliesClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#afdc0c60200d744fe53a7f48e3f7e4bb0">foldSelectWithFCmpToFabs</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a84ec432d02febd1b518e9453b1a0eba9">llvm::ConstantFPRange::makeAllowedFCmpRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#a4c7a26e0bf4a7880f0ba8c3aa2d74a89">llvm::ConstantFPRange::makeSatisfyingFCmpRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a9977c80be67ea7e51bb37ee242d1cc4c">matchUnorderedInfCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfprange-cpp/#affe0a2d80588accff7111123a015df68">setNaNField</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#acb8e54b9f6be2fdb87b369c2218db1cc">simplifyAndOrOfFCmps</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a110a350e37f3cc2ed2c603c3efde0a30">simplifyFCmpInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a62e2ba967b974d6e68931532ab1aa4e8">llvm::InstCombinerImpl::visitSelectInst</a>.</p>

</div>
</div>

### isUnsigned() {#ae69bfc8f4b26dbeaa4dd06d73117e330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CmpInst::isUnsigned (<a href="#a2be3583dac92a031fa1458d4d992c78b">Predicate</a> predicate)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the predicate is unsigned, false otherwise. Determine if the predicate is an unsigned operation.</p></dd>
</dl>


<p>Declaration at line 952 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 3729 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">ICMP_UGE</a>, <a href="#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">ICMP_UGT</a>, <a href="#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">ICMP_ULE</a> and <a href="#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">ICMP_ULT</a>.</p>

</div>
</div>

### makeCmpResultType() {#a0206e74dec02d952d1b620a7b63f5694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::CmpInst::makeCmpResultType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * opnd_type)</td>
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

<p>Create a result type for fcmp/icmp.</p>

<p>Definition at line 980 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#add6cb3c2274e68181ab8a1b4be472b90">checkAndReplaceCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp/#a6cb2ac452d4ebd9583a901b052037d24">costAndCollectOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/fcmpinst/#adcf5270fa9a80077dc604114f66fafaa">llvm::FCmpInst::FCmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/fcmpinst/#a254cb3886750473f69d9a9f8b0cbbdab">llvm::FCmpInst::FCmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#ae83866ca1a903e74fd6b66c1fec0d528">llvm::ARMTTIImpl::getCmpSelInstrCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#abee3cf86c05d2369d387f07f7055b9dc">getCompareTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a071d237c0318d336cc84124ec3a8d037">llvm::getPredForFCmpCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff210c52130b5778e2ef75dd74778afb">llvm::getPredForICmpCode</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfo/#a3296ab5af4e3c77a57810f97ab19e088">llvm::LazyValueInfo::getPredicateAt</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfo/#ad10df0e6ccca0fc951b845e3a007e385">llvm::LazyValueInfo::getPredicateAt</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ac4cfc0065b09dbea4311561f67c2e3ea">getPredicateResult</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a2c1b9368972e15e3602d4279f9988584">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getTreeReductionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#a2472e4d5a0e2f4d6d41f2f58c8261348">llvm::ICmpInst::ICmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/icmpinst/#adf8d12a487891532df62e728d22f2c6f">llvm::ICmpInst::ICmpInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a01ed915fb2acf9fd660ca752edeec0db">llvm::InstCombinerImpl::visitMul</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### AllocMarker {#acd882fc4196ed612177491e85e512a8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntrusiveOperandsAllocMarker llvm::CmpInst::AllocMarker {2}</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 662 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
