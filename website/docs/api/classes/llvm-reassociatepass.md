---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/reassociatepass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ReassociatePass` Class

<p>Reassociate commutative expressions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ReassociatePass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">llvm/Transforms/Scalar/Reassociate.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/passinfomixin">PassInfoMixin&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A CRTP mix-in to automatically provide informational APIs needed for passes. <a href="/web-llvm/docs/api/structs/llvm/passinfomixin/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5b48a2e37809d91383227ee1b6ee00d">OrderedSet</a> = <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &gt;, std::deque&lt; <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &gt; &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">PreservedAnalyses</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadf6b90fc920d89751c191799ff3e6ea">run</a> (Function &amp;F, FunctionAnalysisManager &amp;)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc93d0219a0afeab5e15b35a8067255e">BuildRankMap</a> (Function &amp;F, ReversePostOrderTraversal&lt; Function * &gt; &amp;RPOT)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a076814e494ababfe36ef18b41a8d68cf">getRank</a> (Value *V)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53c166d9600368986b84b8990b3e42b7">canonicalizeOperands</a> (Instruction *I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adba0e12416848bc98b63faf8a718ecd2">ReassociateExpression</a> (BinaryOperator *I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cf6842fe3f7dc9bba91755bc832be68">RewriteExprTree</a> (BinaryOperator *I, SmallVectorImpl&lt; reassociate::ValueEntry &gt; &amp;Ops, reassociate::OverflowTracking Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Now that the operands for this expression tree are linearized and optimized, emit them in-order. <a href="#a3cf6842fe3f7dc9bba91755bc832be68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ce57b1ed232be5f21ecba88a6667c39">OptimizeExpression</a> (BinaryOperator *I, SmallVectorImpl&lt; reassociate::ValueEntry &gt; &amp;Ops)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0892d06daf168d9ee5dc27620836c889">OptimizeAdd</a> (Instruction *I, SmallVectorImpl&lt; reassociate::ValueEntry &gt; &amp;Ops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimize a series of operands to an 'add' instruction. <a href="#a0892d06daf168d9ee5dc27620836c889">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbc55987101ecca02fbecec68d476dcc">OptimizeXor</a> (Instruction *I, SmallVectorImpl&lt; reassociate::ValueEntry &gt; &amp;Ops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimize a series of operands to an 'xor' instruction. <a href="#afbc55987101ecca02fbecec68d476dcc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5eed3a456f6ae037613b1bb364040ce">CombineXorOpnd</a> (BasicBlock::iterator It, reassociate::XorOpnd *Opnd1, APInt &amp;ConstOpnd, Value *&amp;Res)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4535fb3a2bbd05af66e68bd8f5f0ed1">CombineXorOpnd</a> (BasicBlock::iterator It, reassociate::XorOpnd *Opnd1, reassociate::XorOpnd *Opnd2, APInt &amp;ConstOpnd, Value *&amp;Res)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a097c387488651dfb5537182144ed8cc9">buildMinimalMultiplyDAG</a> (IRBuilderBase &amp;Builder, SmallVectorImpl&lt; reassociate::Factor &gt; &amp;Factors)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build a minimal multiplication DAG for (a^x)*(b^y)*(c^z)*... <a href="#a097c387488651dfb5537182144ed8cc9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5344b174b4e2df84347dcbbf0d60597">OptimizeMul</a> (BinaryOperator *I, SmallVectorImpl&lt; reassociate::ValueEntry &gt; &amp;Ops)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9b5580e14f4803c926b6dbb6857a3bc">RemoveFactorFromExpression</a> (Value *V, Value *Factor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If V is an expression tree that is a multiplication sequence, and if this sequence contains a multiply by <a href="/web-llvm/docs/api/structs/llvm/reassociate/factor">Factor</a>, remove <a href="/web-llvm/docs/api/structs/llvm/reassociate/factor">Factor</a> from the tree and return the new tree. <a href="#af9b5580e14f4803c926b6dbb6857a3bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a114efa96bef87ec003f5e9c6dfff4ee6">EraseInst</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Zap the given instruction, adding interesting operands to the work list. <a href="#a114efa96bef87ec003f5e9c6dfff4ee6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5c54d3ce79907a9808e68b9790d00e4">RecursivelyEraseDeadInsts</a> (Instruction *I, OrderedSet &amp;Insts)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9688f294d48107a6167b2c9fc303e9c4">OptimizeInst</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inspect and optimize the given instruction. <a href="#a9688f294d48107a6167b2c9fc303e9c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53bae3c124b8b14d2564e5a91682a99e">canonicalizeNegFPConstantsForOp</a> (Instruction *I, Instruction *Op, Value *OtherOp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an fadd/fsub with an operand that is a one-use instruction (the fadd/fsub), try to change negative floating-point constants into positive constants to increase potential for reassociation and CSE. <a href="#a53bae3c124b8b14d2564e5a91682a99e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a812a502221b5de67dc5f203bc5cc4e2c">canonicalizeNegFPConstants</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Canonicalize expressions that contain a negative floating-point constant of the following form: OtherOp + (subtree) -&gt; OtherOp {+/-} (canonical subtree) (subtree) + OtherOp -&gt; OtherOp {+/-} (canonical subtree) OtherOp - (subtree) -&gt; OtherOp {+/-} (canonical subtree) <a href="#a812a502221b5de67dc5f203bc5cc4e2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f1844f0fafd5e82562bbaff69830ca6">BuildPairMap</a> (ReversePostOrderTraversal&lt; Function * &gt; &amp;RPOT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1be14e908b4b140f912149a005a7ef6a">RankMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &gt;, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2674afb225f4837dde4417b61c1b6d1b">ValueRankMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac5b48a2e37809d91383227ee1b6ee00d">OrderedSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9df5283315bfb019e91cff4064dece8e">RedoInsts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;, <a href="/web-llvm/docs/api/structs/llvm/reassociatepass/pairmapvalue">PairMapValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd59d6b4dbc30b39c8b293549321b2d8">PairMap</a>[NumBinaryOps]</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8386718415457a800f78b990d6caee8b">MadeChange</a></td>
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

## Protected Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a703a6438daac8ecbdbe03a23ce3e471a">GlobalReassociateLimit</a> = 10</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9c3acf02682e0f6e3d9d3903348bf2b">NumBinaryOps</a> = ...</td>
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

<p>Reassociate commutative expressions.</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### OrderedSet {#ac5b48a2e37809d91383227ee1b6ee00d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ReassociatePass::OrderedSet = 
      SetVector&lt;AssertingVH&lt;Instruction&gt;, std::deque&lt;AssertingVH&lt;Instruction&gt;&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#aadf6b90fc920d89751c191799ff3e6ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses ReassociatePass::run (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>, definition at line 2547 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp">Reassociate.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#ac178f4fc4e4a0642610c374256b9fb27">llvm::SetVector&lt; T, Vector, Set, N &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a627b2f86ac433d829482d5a5a0f50668">llvm::isInstructionTriviallyDead</a>, <a href="#a8386718415457a800f78b990d6caee8b">MadeChange</a>, <a href="#acd59d6b4dbc30b39c8b293549321b2d8">PairMap</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af9880d625c506aacc716ee1c9a29ff8b">llvm::SetVector&lt; T, Vector, Set, N &gt;::pop_back_val</a>, <a href="#a1be14e908b4b140f912149a005a7ef6a">RankMap</a>, <a href="#a9df5283315bfb019e91cff4064dece8e">RedoInsts</a> and <a href="#a2674afb225f4837dde4417b61c1b6d1b">ValueRankMap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### buildMinimalMultiplyDAG() {#a097c387488651dfb5537182144ed8cc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * ReassociatePass::buildMinimalMultiplyDAG (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/reassociate/factor">reassociate::Factor</a> &gt; &amp; Factors)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build a minimal multiplication DAG for (a^x)*(b^y)*(c^z)*...</p>


<p>Given a vector of values raised to various powers, where no two values are equal and the powers are sorted in decreasing order, compute the minimal DAG of multiplies to compute the final product, and return that product value.</p>


<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>, definition at line 1805 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp">Reassociate.cpp</a>.</p>

</div>
</div>

### BuildPairMap() {#a6f1844f0fafd5e82562bbaff69830ca6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReassociatePass::BuildPairMap (<a href="/web-llvm/docs/api/classes/llvm/reversepostordertraversal">ReversePostOrderTraversal</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; &amp; RPOT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>, definition at line 2487 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp">Reassociate.cpp</a>.</p>

</div>
</div>

### BuildRankMap() {#acc93d0219a0afeab5e15b35a8067255e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReassociatePass::BuildRankMap (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/reversepostordertraversal">ReversePostOrderTraversal</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; &amp; RPOT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>, definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp">Reassociate.cpp</a>.</p>

</div>
</div>

### canonicalizeNegFPConstants() {#a812a502221b5de67dc5f203bc5cc4e2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * ReassociatePass::canonicalizeNegFPConstants (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Canonicalize expressions that contain a negative floating-point constant of the following form: OtherOp + (subtree) -&gt; OtherOp {+/-} (canonical subtree) (subtree) + OtherOp -&gt; OtherOp {+/-} (canonical subtree) OtherOp - (subtree) -&gt; OtherOp {+/-} (canonical subtree)</p>


<p>The fadd/fsub opcode may be switched to allow folding a negation into the input instruction.</p>


<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>, definition at line 2126 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp">Reassociate.cpp</a>.</p>

</div>
</div>

### canonicalizeNegFPConstantsForOp() {#a53bae3c124b8b14d2564e5a91682a99e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * ReassociatePass::canonicalizeNegFPConstantsForOp (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Op, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * OtherOp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an fadd/fsub with an operand that is a one-use instruction (the fadd/fsub), try to change negative floating-point constants into positive constants to increase potential for reassociation and CSE.</p>

<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>, definition at line 2063 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp">Reassociate.cpp</a>.</p>

</div>
</div>

### canonicalizeOperands() {#a53c166d9600368986b84b8990b3e42b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReassociatePass::canonicalizeOperands (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>, definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp">Reassociate.cpp</a>.</p>

</div>
</div>

### CombineXorOpnd() {#ad5eed3a456f6ae037613b1bb364040ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ReassociatePass::CombineXorOpnd (<a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> It, <a href="/web-llvm/docs/api/classes/llvm/reassociate/xoropnd">reassociate::XorOpnd</a> * Opnd1, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; ConstOpnd, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>, definition at line 1263 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp">Reassociate.cpp</a>.</p>

</div>
</div>

### CombineXorOpnd() {#af4535fb3a2bbd05af66e68bd8f5f0ed1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ReassociatePass::CombineXorOpnd (<a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> It, <a href="/web-llvm/docs/api/classes/llvm/reassociate/xoropnd">reassociate::XorOpnd</a> * Opnd1, <a href="/web-llvm/docs/api/classes/llvm/reassociate/xoropnd">reassociate::XorOpnd</a> * Opnd2, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; ConstOpnd, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp; Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>, definition at line 1297 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp">Reassociate.cpp</a>.</p>

</div>
</div>

### EraseInst() {#a114efa96bef87ec003f5e9c6dfff4ee6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReassociatePass::EraseInst (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Zap the given instruction, adding interesting operands to the work list.</p>

<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>, definition at line 1981 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp">Reassociate.cpp</a>.</p>

</div>
</div>

### getRank() {#a076814e494ababfe36ef18b41a8d68cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ReassociatePass::getRank (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>, definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp">Reassociate.cpp</a>.</p>

</div>
</div>

### OptimizeAdd() {#a0892d06daf168d9ee5dc27620836c889}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * ReassociatePass::OptimizeAdd (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/reassociate/valueentry">reassociate::ValueEntry</a> &gt; &amp; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Optimize a series of operands to an 'add' instruction.</p>


<p>This optimizes based on identities. If it can be reduced to a single <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, it is returned, otherwise the Ops list is mutated as necessary.</p>


<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>, definition at line 1494 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp">Reassociate.cpp</a>.</p>

</div>
</div>

### OptimizeExpression() {#a7ce57b1ed232be5f21ecba88a6667c39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * ReassociatePass::OptimizeExpression (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * I, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/reassociate/valueentry">reassociate::ValueEntry</a> &gt; &amp; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>, definition at line 1892 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp">Reassociate.cpp</a>.</p>

</div>
</div>

### OptimizeInst() {#a9688f294d48107a6167b2c9fc303e9c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReassociatePass::OptimizeInst (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Inspect and optimize the given instruction.</p>


<p>Note that erasing instructions is not allowed.</p>


<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>, definition at line 2144 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp">Reassociate.cpp</a>.</p>

</div>
</div>

### OptimizeMul() {#ad5344b174b4e2df84347dcbbf0d60597}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * ReassociatePass::OptimizeMul (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * I, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/reassociate/valueentry">reassociate::ValueEntry</a> &gt; &amp; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>, definition at line 1862 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp">Reassociate.cpp</a>.</p>

</div>
</div>

### OptimizeXor() {#afbc55987101ecca02fbecec68d476dcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * ReassociatePass::OptimizeXor (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/reassociate/valueentry">reassociate::ValueEntry</a> &gt; &amp; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Optimize a series of operands to an 'xor' instruction.</p>


<p>If it can be reduced to a single <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, it is returned, otherwise the Ops list is mutated as necessary.</p>


<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>, definition at line 1372 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp">Reassociate.cpp</a>.</p>

</div>
</div>

### ReassociateExpression() {#adba0e12416848bc98b63faf8a718ecd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReassociatePass::ReassociateExpression (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>, definition at line 2285 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp">Reassociate.cpp</a>.</p>

</div>
</div>

### RecursivelyEraseDeadInsts() {#ab5c54d3ce79907a9808e68b9790d00e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReassociatePass::RecursivelyEraseDeadInsts (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="#ac5b48a2e37809d91383227ee1b6ee00d">OrderedSet</a> &amp; Insts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>, definition at line 1965 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp">Reassociate.cpp</a>.</p>

</div>
</div>

### RemoveFactorFromExpression() {#af9b5580e14f4803c926b6dbb6857a3bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * ReassociatePass::RemoveFactorFromExpression (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Factor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If V is an expression tree that is a multiplication sequence, and if this sequence contains a multiply by <a href="/web-llvm/docs/api/structs/llvm/reassociate/factor">Factor</a>, remove <a href="/web-llvm/docs/api/structs/llvm/reassociate/factor">Factor</a> from the tree and return the new tree.</p>

<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>, definition at line 1102 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp">Reassociate.cpp</a>.</p>

</div>
</div>

### RewriteExprTree() {#a3cf6842fe3f7dc9bba91755bc832be68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ReassociatePass::RewriteExprTree (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * I, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/reassociate/valueentry">reassociate::ValueEntry</a> &gt; &amp; Ops, <a href="/web-llvm/docs/api/structs/llvm/reassociate/overflowtracking">reassociate::OverflowTracking</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Now that the operands for this expression tree are linearized and optimized, emit them in-order.</p>

<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>, definition at line 568 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp">Reassociate.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### MadeChange {#a8386718415457a800f78b990d6caee8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ReassociatePass::MadeChange</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>.</p>


<p>Referenced by <a href="#aadf6b90fc920d89751c191799ff3e6ea">run</a>.</p>

</div>
</div>

### PairMap {#acd59d6b4dbc30b39c8b293549321b2d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;std::pair&lt;Value *, Value *&gt;, PairMapValue&gt; llvm::ReassociatePass::PairMap[NumBinaryOps]</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>.</p>


<p>Referenced by <a href="#aadf6b90fc920d89751c191799ff3e6ea">run</a>.</p>

</div>
</div>

### RankMap {#a1be14e908b4b140f912149a005a7ef6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;BasicBlock *, unsigned&gt; llvm::ReassociatePass::RankMap</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>.</p>


<p>Referenced by <a href="#aadf6b90fc920d89751c191799ff3e6ea">run</a>.</p>

</div>
</div>

### RedoInsts {#a9df5283315bfb019e91cff4064dece8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OrderedSet llvm::ReassociatePass::RedoInsts</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>.</p>


<p>Referenced by <a href="#aadf6b90fc920d89751c191799ff3e6ea">run</a>.</p>

</div>
</div>

### ValueRankMap {#a2674afb225f4837dde4417b61c1b6d1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;AssertingVH&lt;Value&gt;, unsigned&gt; llvm::ReassociatePass::ValueRankMap</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>.</p>


<p>Referenced by <a href="#aadf6b90fc920d89751c191799ff3e6ea">run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Attributes

### GlobalReassociateLimit {#a703a6438daac8ecbdbe03a23ce3e471a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::ReassociatePass::GlobalReassociateLimit = 10</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>.</p>

</div>
</div>

### NumBinaryOps {#ac9c3acf02682e0f6e3d9d3903348bf2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::ReassociatePass::NumBinaryOps</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      Instruction::BinaryOpsEnd - Instruction::BinaryOpsBegin
</div>
</dd>
</dl>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reassociate-h">Reassociate.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp">Reassociate.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
