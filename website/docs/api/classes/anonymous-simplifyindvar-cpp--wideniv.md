---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-simplifyindvar-cpp-/wideniv
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `WidenIV` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{SimplifyIndVar.cpp}::WidenIV { ... }
</div>

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a692ebb057bf10c9bf99b2354d10d5402">WidenedRecTy</a> = std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> *, ExtendKind &gt;</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4350c00b12ae9e7d192915fbc035e55">DefUserPair</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &gt;, <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ExtendKind { <a href="#af9031d27ec727b81c90170fe12359834">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba677aadf1abee0a03e3e5744b9724cd">WidenIV</a> (const WideIVInfo &amp;WI, LoopInfo *LInfo, ScalarEvolution *SEv, DominatorTree *DTree, SmallVectorImpl&lt; WeakTrackingVH &gt; &amp;DI, bool HasGuards, bool UsePostIncrementRanges=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5586ec5eac8a93b87b095f949ea8daf3">createWideIV</a> (SCEVExpander &amp;Rewriter)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> a single induction variable. <a href="#a5586ec5eac8a93b87b095f949ea8daf3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e00ac6fdaee0e1f14f90a12abd10dc7">getNumElimExt</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20a835d33fbb0807cef6a8fb519b4ad5">getNumWidened</a> ()</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d6b9e4d1f5157d53f36e8c37f218233">createExtendInst</a> (Value *NarrowOper, Type *WideType, bool IsSigned, Instruction *Use)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee5e663199f460b53a80855073e21bd">cloneIVUser</a> (NarrowIVDefUse DU, const SCEVAddRecExpr *WideAR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instantiate a wide operation to replace a narrow operation. <a href="#a7ee5e663199f460b53a80855073e21bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee57a451f8dea6781fa17e7728ee78b5">cloneArithmeticIVUser</a> (NarrowIVDefUse DU, const SCEVAddRecExpr *WideAR)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5441d4cfeb857eb3f3afad58fd88c08">cloneBitwiseIVUser</a> (NarrowIVDefUse DU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">ExtendKind</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49e339292d507be61d9087d9aa664595">getExtendKind</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a692ebb057bf10c9bf99b2354d10d5402">WidenedRecTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c90afd148f896bab791bdcad6b41dd0">getWideRecurrence</a> (NarrowIVDefUse DU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this instruction potentially interesting for further simplification after widening it's type? <a href="#a2c90afd148f896bab791bdcad6b41dd0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a692ebb057bf10c9bf99b2354d10d5402">WidenedRecTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5acadc27f8741ff017a264df16bb8885">getExtendedOperandRecurrence</a> (NarrowIVDefUse DU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>No-wrap operations can transfer sign extension of their result to their operands. <a href="#a5acadc27f8741ff017a264df16bb8885">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a181037cb6974efc0dfabf5f48ebf8238">getSCEVByOpCode</a> (const SCEV *LHS, const SCEV *RHS, unsigned OpCode) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39eadf98e4773739cd4e7b4befee6fb5">widenIVUse</a> (NarrowIVDefUse DU, SCEVExpander &amp;Rewriter, PHINode *OrigPhi, PHINode *WidePhi)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether an individual user of the narrow IV can be widened. <a href="#a39eadf98e4773739cd4e7b4befee6fb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a821be8169bc31b8413a69cd7f22ff9ab">truncateIVUse</a> (NarrowIVDefUse DU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This IV user cannot be widened. <a href="#a821be8169bc31b8413a69cd7f22ff9ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9eefc297d0b2b8097701f80c06ba19d">widenLoopCompare</a> (NarrowIVDefUse DU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the narrow use is a compare instruction, then widen the compare. <a href="#aa9eefc297d0b2b8097701f80c06ba19d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd093283d4e8d1301859f0a98a157680">widenWithVariantUse</a> (NarrowIVDefUse DU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac65b91bafca4f727e589bdfbfb79edc1">pushNarrowIVUsers</a> (Instruction *NarrowDef, Instruction *WideDef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add eligible users of NarrowDef to NarrowIVUsers. <a href="#ac65b91bafca4f727e589bdfbfb79edc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09c74d0333c5b464874620ff82509ee5">getPostIncRangeInfo</a> (Value *Def, Instruction *UseI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96b6f154a803f416230af36ee105fdfb">calculatePostIncRanges</a> (PHINode *OrigPhi)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculates PostIncRangeInfos map for the given IV. <a href="#a96b6f154a803f416230af36ee105fdfb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1d340b2763a5cd51755392bda73fb58">calculatePostIncRange</a> (Instruction *NarrowDef, Instruction *NarrowUser)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculates control-dependent range for the given def at the given context by looking at dominating conditions inside of the loop. <a href="#af1d340b2763a5cd51755392bda73fb58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24883075d4b1888ec7b6a9b2edf534fd">updatePostIncRangeInfo</a> (Value *Def, Instruction *UseI, ConstantRange R)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7dbf745a1fb27852ecefc3e81dcd84b">OrigPhi</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa226486a01f1ea7a562378f55390a96">WideType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa4272e7ee9f4b64ff3b942e34934830">LI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab36e2e0481879d3689798fab6438d88a">L</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38fec9a65503557fcacb40214a5ac38c">SE</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af81ff6ec7a5fed4a19ae9ba3e7071b0a">DT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0205e12edb7d13d9434167d769a0c65">HasGuards</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a267a25d7293342a1309b7e1b0e701a58">UsePostIncrementRanges</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31aa3df8bf2492200162056aab585ed3">NumElimExt</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98183179e67700da421742b06d7c4aeb">NumWidened</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7382ac5510c7c1e452eb892834c3d241">WidePhi</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f1aed837cdc8cdb4a2887adf7a8885">WideInc</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54be9eaa7bdda1ad45caf3d2af93eab8">WideIncExpr</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1322314677c37fe42a11a2c1479c2963">DeadInsts</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ba15d8fbb802e1305bc9a3bbd099db4">Widened</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &gt;, ExtendKind &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c1af6f36f37bcb2b3e7e87a83ce1a07">ExtendKindMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; DefUserPair, <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3138895d5494b5365a1bc75de30e6363">PostIncRangeInfos</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse">NarrowIVDefUse</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44aa6a4505788a1622a09a9901412bab">NarrowIVUsers</a></td>
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


<p>Definition at line 1047 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### WidenedRecTy {#a692ebb057bf10c9bf99b2354d10d5402}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{SimplifyIndVar.cpp}::WidenIV::WidenedRecTy =  std::pair&lt;const SCEVAddRecExpr *, ExtendKind&gt;</td>
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



<p>Definition at line 1151 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### DefUserPair {#ac4350c00b12ae9e7d192915fbc035e55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{SimplifyIndVar.cpp}::WidenIV::DefUserPair =  std::pair&lt;AssertingVH&lt;Value&gt;, AssertingVH&lt;Instruction&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1084 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### ExtendKind {#af9031d27ec727b81c90170fe12359834}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{SimplifyIndVar.cpp}::WidenIV::ExtendKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Zero<a id="af9031d27ec727b81c90170fe12359834ad7ed4ee1df437474d005188535f74875"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sign<a id="af9031d27ec727b81c90170fe12359834a31c6b3fdfaaa80dba2dbf92a4600524c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Unknown<a id="af9031d27ec727b81c90170fe12359834a88183b946cc5f0e8c96b2e66e1c74a7e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1076 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### WidenIV() {#aba677aadf1abee0a03e3e5744b9724cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WidenIV::WidenIV (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wideivinfo">WideIVInfo</a> &amp; WI, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LInfo, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SEv, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DTree, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a> &gt; &amp; DI, bool HasGuards, bool UsePostIncrementRanges=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1131 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a> and <a href="/web-llvm/docs/api/structs/llvm/wideivinfo/#a45b4503c5e229503d60cc68c034286ab">llvm::WideIVInfo::IsSigned</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createWideIV() {#a5586ec5eac8a93b87b095f949ea8daf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHINode * WidenIV::createWideIV (<a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a> &amp; Rewriter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> a single induction variable.</p>


<p>First use the <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a> to create a wide induction variable that evaluates to the same recurrence as the original narrow IV. Then use a worklist to forward traverse the narrow IV's def-use chain. After widenIVUse has processed all interesting IV users, the narrow IV will be isolated for removal by DeleteDeadPHIs.</p>


<p>It would be simpler to delete uses as they are processed, but we must avoid invalidating <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expressions.</p>


<p>Definition at line 1135 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#aad8311debca961aeee16791414f9efa1">llvm::SCEVExpander::canReuseFlagsFromOriginalIVInc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a49e339292d507be61d9087d9aa664595">getExtendKind</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a99ab4a82c6d7373e2e367986b9527bf0">llvm::SCEVAddRecExpr::getLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a19c13fe96d59c787e900b7bbf7173263">llvm::SCEVAddRecExpr::getStart</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a4049f7040a4628b15f182c3c9aaf802a">llvm::SCEVAddRecExpr::getStepRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a7c779ce2ba55bc94f52014fc25f3d520">llvm::Value::hasNUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a5e016da67d6b8bbf10f63bb125d25e11">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NarrowDef</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a7d5e94a7ebb4f2950eec1132228f6556">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NarrowUse</a>, <a href="#ac65b91bafca4f727e589bdfbfb79edc1">pushNarrowIVUsers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9784a018b2dd6a85ee8a70f5f5ab3d02">llvm::replaceAllDbgUsesWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/virtregmap-cpp/#a1ad52109a2ff430460c8776286b97b2e">Rewriter</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a> and <a href="#a39eadf98e4773739cd4e7b4befee6fb5">widenIVUse</a>.</p>

</div>
</div>

### getNumElimExt() {#a6e00ac6fdaee0e1f14f90a12abd10dc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SimplifyIndVar.cpp}::WidenIV::getNumElimExt ()</td>
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



<p>Definition at line 1137 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### getNumWidened() {#a20a835d33fbb0807cef6a8fb519b4ad5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SimplifyIndVar.cpp}::WidenIV::getNumWidened ()</td>
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



<p>Definition at line 1138 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### cloneArithmeticIVUser() {#aee57a451f8dea6781fa17e7728ee78b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * WidenIV::cloneArithmeticIVUser (<a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse">NarrowIVDefUse</a> DU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * WideAR)</td>
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



<p>Definition at line 1145 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a8f385eda0f71b4e8199b296fbc8e0da9">llvm::BinaryOperator::Create</a>, <a href="#a0d6b9e4d1f5157d53f36e8c37f218233">createExtendInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a49e339292d507be61d9087d9aa664595">getExtendKind</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="#a181037cb6974efc0dfabf5f48ebf8238">getSCEVByOpCode</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8ef25defccf4817608a13e7a9db4000d">llvm::IRBuilderBase::Insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a5e016da67d6b8bbf10f63bb125d25e11">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NarrowDef</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a7d5e94a7ebb4f2950eec1132228f6556">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NarrowUse</a> and <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a41ae7e1b14cb78ee141c769563f59a7c">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::WideDef</a>.</p>


<p>Referenced by <a href="#a7ee5e663199f460b53a80855073e21bd">cloneIVUser</a>.</p>

</div>
</div>

### cloneBitwiseIVUser() {#ae5441d4cfeb857eb3f3afad58fd88c08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * WidenIV::cloneBitwiseIVUser (<a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse">NarrowIVDefUse</a> DU)</td>
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



<p>Definition at line 1147 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a8f385eda0f71b4e8199b296fbc8e0da9">llvm::BinaryOperator::Create</a>, <a href="#a0d6b9e4d1f5157d53f36e8c37f218233">createExtendInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a49e339292d507be61d9087d9aa664595">getExtendKind</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8ef25defccf4817608a13e7a9db4000d">llvm::IRBuilderBase::Insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a5e016da67d6b8bbf10f63bb125d25e11">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NarrowDef</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a7d5e94a7ebb4f2950eec1132228f6556">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NarrowUse</a> and <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a41ae7e1b14cb78ee141c769563f59a7c">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::WideDef</a>.</p>


<p>Referenced by <a href="#a7ee5e663199f460b53a80855073e21bd">cloneIVUser</a>.</p>

</div>
</div>

### cloneIVUser() {#a7ee5e663199f460b53a80855073e21bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * WidenIV::cloneIVUser (<a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse">NarrowIVDefUse</a> DU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * WideAR)</td>
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

<p>Instantiate a wide operation to replace a narrow operation.</p>


<p>This only needs to handle operations that can evaluation to SCEVAddRec. It can safely return 0 for any operation we decide not to clone.</p>


<p>Definition at line 1144 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="#aee57a451f8dea6781fa17e7728ee78b5">cloneArithmeticIVUser</a>, <a href="#ae5441d4cfeb857eb3f3afad58fd88c08">cloneBitwiseIVUser</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a> and <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a7d5e94a7ebb4f2950eec1132228f6556">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NarrowUse</a>.</p>


<p>Referenced by <a href="#a39eadf98e4773739cd4e7b4befee6fb5">widenIVUse</a>.</p>

</div>
</div>

### createExtendInst() {#a0d6b9e4d1f5157d53f36e8c37f218233}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * WidenIV::createExtendInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NarrowOper, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * WideType, bool IsSigned, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Use)</td>
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



<p>Definition at line 1141 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ac3280e7f76f955403fe17eacf126b90d">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopPreheader</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>.</p>


<p>Referenced by <a href="#aee57a451f8dea6781fa17e7728ee78b5">cloneArithmeticIVUser</a>, <a href="#ae5441d4cfeb857eb3f3afad58fd88c08">cloneBitwiseIVUser</a>, <a href="#aa9eefc297d0b2b8097701f80c06ba19d">widenLoopCompare</a> and <a href="#acd093283d4e8d1301859f0a98a157680">widenWithVariantUse</a>.</p>

</div>
</div>

### getExtendedOperandRecurrence() {#a5acadc27f8741ff017a264df16bb8885}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WidenIV::WidenedRecTy WidenIV::getExtendedOperandRecurrence (<a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse">NarrowIVDefUse</a> DU)</td>
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

<p>No-wrap operations can transfer sign extension of their result to their operands.</p>


<p>Generate the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> value for the widened operation without actually modifying the IR yet. If the expression after extending the operands is an AddRec for this loop, return the AddRec and the kind of extension used.</p>


<p>Definition at line 1155 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a49e339292d507be61d9087d9aa664595">getExtendKind</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a99ab4a82c6d7373e2e367986b9527bf0">llvm::SCEVAddRecExpr::getLoop</a>, <a href="#a181037cb6974efc0dfabf5f48ebf8238">getSCEVByOpCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp/#aae7060f1dababae7ea60ae22eb9e9c6b">matchBinaryOp</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a5e016da67d6b8bbf10f63bb125d25e11">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NarrowDef</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a7d5e94a7ebb4f2950eec1132228f6556">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NarrowUse</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#aeef9f24cc8914e50d2296cdd85b87fdc">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NeverNegative</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a> and <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a41ae7e1b14cb78ee141c769563f59a7c">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::WideDef</a>.</p>


<p>Referenced by <a href="#a39eadf98e4773739cd4e7b4befee6fb5">widenIVUse</a>.</p>

</div>
</div>

### getExtendKind() {#a49e339292d507be61d9087d9aa664595}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WidenIV::ExtendKind WidenIV::getExtendKind (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 1149 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#aee57a451f8dea6781fa17e7728ee78b5">cloneArithmeticIVUser</a>, <a href="#ae5441d4cfeb857eb3f3afad58fd88c08">cloneBitwiseIVUser</a>, <a href="#a5586ec5eac8a93b87b095f949ea8daf3">createWideIV</a>, <a href="#a5acadc27f8741ff017a264df16bb8885">getExtendedOperandRecurrence</a>, <a href="#a2c90afd148f896bab791bdcad6b41dd0">getWideRecurrence</a>, <a href="#a821be8169bc31b8413a69cd7f22ff9ab">truncateIVUse</a>, <a href="#a39eadf98e4773739cd4e7b4befee6fb5">widenIVUse</a>, <a href="#aa9eefc297d0b2b8097701f80c06ba19d">widenLoopCompare</a> and <a href="#acd093283d4e8d1301859f0a98a157680">widenWithVariantUse</a>.</p>

</div>
</div>

### getSCEVByOpCode() {#a181037cb6974efc0dfabf5f48ebf8238}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * WidenIV::getSCEVByOpCode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * RHS, unsigned OpCode)</td>
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



<p>Definition at line 1157 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#aee57a451f8dea6781fa17e7728ee78b5">cloneArithmeticIVUser</a> and <a href="#a5acadc27f8741ff017a264df16bb8885">getExtendedOperandRecurrence</a>.</p>

</div>
</div>

### getWideRecurrence() {#a2c90afd148f896bab791bdcad6b41dd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WidenIV::WidenedRecTy WidenIV::getWideRecurrence (<a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse">NarrowIVDefUse</a> DU)</td>
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

<p>Is this instruction potentially interesting for further simplification after widening it's type?</p>


<p>In other words, can the extend be safely hoisted out of the loop with <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> reducing the value to a recurrence on the same loop. If so, return the extended recurrence and the kind of extension used. Otherwise return {nullptr, ExtendKind::Unknown}.</p>


<p>Definition at line 1153 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a49e339292d507be61d9087d9aa664595">getExtendKind</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a99ab4a82c6d7373e2e367986b9527bf0">llvm::SCEVAddRecExpr::getLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a5e016da67d6b8bbf10f63bb125d25e11">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NarrowDef</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a7d5e94a7ebb4f2950eec1132228f6556">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NarrowUse</a> and <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#aeef9f24cc8914e50d2296cdd85b87fdc">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NeverNegative</a>.</p>


<p>Referenced by <a href="#a39eadf98e4773739cd4e7b4befee6fb5">widenIVUse</a>.</p>

</div>
</div>

### pushNarrowIVUsers() {#ac65b91bafca4f727e589bdfbfb79edc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WidenIV::pushNarrowIVUsers (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * NarrowDef, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * WideDef)</td>
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

<p>Add eligible users of NarrowDef to NarrowIVUsers.</p>

<p>Definition at line 1167 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>


<p>Referenced by <a href="#a5586ec5eac8a93b87b095f949ea8daf3">createWideIV</a>.</p>

</div>
</div>

### truncateIVUse() {#a821be8169bc31b8413a69cd7f22ff9ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WidenIV::truncateIVUse (<a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse">NarrowIVDefUse</a> DU)</td>
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

<p>This IV user cannot be widened.</p>


<p>Replace this use of the original narrow IV with a truncation of the new wide IV to isolate and eliminate the narrow IV.</p>


<p>Definition at line 1162 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a49e339292d507be61d9087d9aa664595">getExtendKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp/#a995c9f54308d436b9046a8741b149671">getInsertPointForUses</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a5e016da67d6b8bbf10f63bb125d25e11">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NarrowDef</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a7d5e94a7ebb4f2950eec1132228f6556">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NarrowUse</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#aeef9f24cc8914e50d2296cdd85b87fdc">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NeverNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a1600c7959045cb6b6a5f5a1d427ec67e">llvm::User::replaceUsesOfWith</a> and <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a41ae7e1b14cb78ee141c769563f59a7c">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::WideDef</a>.</p>


<p>Referenced by <a href="#a39eadf98e4773739cd4e7b4befee6fb5">widenIVUse</a>.</p>

</div>
</div>

### widenIVUse() {#a39eadf98e4773739cd4e7b4befee6fb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * WidenIV::widenIVUse (<a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse">NarrowIVDefUse</a> DU, <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a> &amp; Rewriter, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * OrigPhi, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * WidePhi)</td>
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

<p>Determine whether an individual user of the narrow IV can be widened.</p>


<p>If so, return the wide clone of the user.</p>


<p>Definition at line 1160 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#aad8311debca961aeee16791414f9efa1">llvm::SCEVExpander::canReuseFlagsFromOriginalIVInc</a>, <a href="#a7ee5e663199f460b53a80855073e21bd">cloneIVUser</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#af4aba918a76ca15bde1be3e14572e475">llvm::PHINode::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5acadc27f8741ff017a264df16bb8885">getExtendedOperandRecurrence</a>, <a href="#a49e339292d507be61d9087d9aa664595">getExtendKind</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a161fd4e9fa5367f64c2a4c9e921c3ad3">llvm::BasicBlock::getFirstInsertionPt</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a2c90afd148f896bab791bdcad6b41dd0">getWideRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a350f4fdc01c770b5cf6a8be2624ae3e5">llvm::Instruction::hasNoSignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a100c666f9253331dd1d166a863248326">llvm::Instruction::hasNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a9ffe83e2db4b833b819ee721595c04dc">llvm::PatternMatch::m_SExtLike</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a5e016da67d6b8bbf10f63bb125d25e11">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NarrowDef</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a7d5e94a7ebb4f2950eec1132228f6556">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NarrowUse</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#aeef9f24cc8914e50d2296cdd85b87fdc">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NeverNegative</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9784a018b2dd6a85ee8a70f5f5ab3d02">llvm::replaceAllDbgUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a1600c7959045cb6b6a5f5a1d427ec67e">llvm::User::replaceUsesOfWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/virtregmap-cpp/#a1ad52109a2ff430460c8776286b97b2e">Rewriter</a>, <a href="#a821be8169bc31b8413a69cd7f22ff9ab">truncateIVUse</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a41ae7e1b14cb78ee141c769563f59a7c">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::WideDef</a>, <a href="#aa9eefc297d0b2b8097701f80c06ba19d">widenLoopCompare</a> and <a href="#acd093283d4e8d1301859f0a98a157680">widenWithVariantUse</a>.</p>


<p>Referenced by <a href="#a5586ec5eac8a93b87b095f949ea8daf3">createWideIV</a>.</p>

</div>
</div>

### widenLoopCompare() {#aa9eefc297d0b2b8097701f80c06ba19d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WidenIV::widenLoopCompare (<a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse">NarrowIVDefUse</a> DU)</td>
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

<p>If the narrow use is a compare instruction, then widen the compare.</p>

<p>Definition at line 1164 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0d6b9e4d1f5157d53f36e8c37f218233">createExtendInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a49e339292d507be61d9087d9aa664595">getExtendKind</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a5e016da67d6b8bbf10f63bb125d25e11">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NarrowDef</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a7d5e94a7ebb4f2950eec1132228f6556">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NarrowUse</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#aeef9f24cc8914e50d2296cdd85b87fdc">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NeverNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a1600c7959045cb6b6a5f5a1d427ec67e">llvm::User::replaceUsesOfWith</a> and <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a41ae7e1b14cb78ee141c769563f59a7c">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::WideDef</a>.</p>


<p>Referenced by <a href="#a39eadf98e4773739cd4e7b4befee6fb5">widenIVUse</a>.</p>

</div>
</div>

### widenWithVariantUse() {#acd093283d4e8d1301859f0a98a157680}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WidenIV::widenWithVariantUse (<a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse">NarrowIVDefUse</a> DU)</td>
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



<p>Definition at line 1165 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a8f385eda0f71b4e8199b296fbc8e0da9">llvm::BinaryOperator::Create</a>, <a href="#a0d6b9e4d1f5157d53f36e8c37f218233">createExtendInst</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae0bd6c2fab2d18443038a8f3a2b64856">llvm::IRBuilderBase::CreateICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a876fb556ecea804faa2cd8ad1e498ec3">llvm::IRBuilderBase::CreatePHI</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab5b4acb0f45af3f2308cad1468804f1e">llvm::IRBuilderBase::CreateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp/#a61b5cb822ee8e25eee3418a520337962">findCommonDominator</a>, <a href="#a49e339292d507be61d9087d9aa664595">getExtendKind</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a99ab4a82c6d7373e2e367986b9527bf0">llvm::SCEVAddRecExpr::getLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/overflowingbinaryoperator/#a7876c618729b8764493aa340b53b574f">llvm::OverflowingBinaryOperator::hasNoSignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/overflowingbinaryoperator/#a95474ea140862464db7ea0580f01eae9">llvm::OverflowingBinaryOperator::hasNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8ef25defccf4817608a13e7a9db4000d">llvm::IRBuilderBase::Insert</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a3712279d70deeec90a93db09deb12d02">llvm::CmpInst::isSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#af206a3d6f58d9e53b074460f0d1ecb86">llvm::CmpInst::isUnsigned</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a5e016da67d6b8bbf10f63bb125d25e11">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NarrowDef</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a7d5e94a7ebb4f2950eec1132228f6556">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::NarrowUse</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#abf855b7cd63a0cd7f73759e396f280c9">llvm::Value::uses</a> and <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/wideniv/narrowivdefuse/#a41ae7e1b14cb78ee141c769563f59a7c">anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVDefUse::WideDef</a>.</p>


<p>Referenced by <a href="#a39eadf98e4773739cd4e7b4befee6fb5">widenIVUse</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### calculatePostIncRange() {#af1d340b2763a5cd51755392bda73fb58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WidenIV::calculatePostIncRange (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * NarrowDef, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * NarrowUser)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculates control-dependent range for the given def at the given context by looking at dominating conditions inside of the loop.</p>

<p>Definition at line 1102 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### calculatePostIncRanges() {#a96b6f154a803f416230af36ee105fdfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WidenIV::calculatePostIncRanges (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * OrigPhi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculates PostIncRangeInfos map for the given IV.</p>

<p>Definition at line 1101 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### getPostIncRangeInfo() {#a09c74d0333c5b464874620ff82509ee5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ConstantRange &gt; anonymous{SimplifyIndVar.cpp}::WidenIV::getPostIncRangeInfo (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Def, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * UseI)</td>
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



<p>Definition at line 1092 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### updatePostIncRangeInfo() {#a24883075d4b1888ec7b6a9b2edf534fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SimplifyIndVar.cpp}::WidenIV::updatePostIncRangeInfo (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Def, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * UseI, <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> R)</td>
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



<p>Definition at line 1104 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DeadInsts {#a1322314677c37fe42a11a2c1479c2963}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt;WeakTrackingVH&gt;&amp; anonymous{SimplifyIndVar.cpp}::WidenIV::DeadInsts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1072 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### DT {#af81ff6ec7a5fed4a19ae9ba3e7071b0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* anonymous{SimplifyIndVar.cpp}::WidenIV::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1056 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### ExtendKindMap {#a1c1af6f36f37bcb2b3e7e87a83ce1a07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;AssertingVH&lt;Instruction&gt;, ExtendKind&gt; anonymous{SimplifyIndVar.cpp}::WidenIV::ExtendKindMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1082 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### HasGuards {#ab0205e12edb7d13d9434167d769a0c65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SimplifyIndVar.cpp}::WidenIV::HasGuards</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1060 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### L {#ab36e2e0481879d3689798fab6438d88a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* anonymous{SimplifyIndVar.cpp}::WidenIV::L</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1054 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### LI {#aaa4272e7ee9f4b64ff3b942e34934830}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* anonymous{SimplifyIndVar.cpp}::WidenIV::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1053 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### NarrowIVUsers {#a44aa6a4505788a1622a09a9901412bab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;NarrowIVDefUse, 8&gt; anonymous{SimplifyIndVar.cpp}::WidenIV::NarrowIVUsers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1170 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### NumElimExt {#a31aa3df8bf2492200162056aab585ed3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SimplifyIndVar.cpp}::WidenIV::NumElimExt = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1065 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### NumWidened {#a98183179e67700da421742b06d7c4aeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SimplifyIndVar.cpp}::WidenIV::NumWidened = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1066 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### OrigPhi {#aa7dbf745a1fb27852ecefc3e81dcd84b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHINode* anonymous{SimplifyIndVar.cpp}::WidenIV::OrigPhi</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1049 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### PostIncRangeInfos {#a3138895d5494b5365a1bc75de30e6363}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;DefUserPair, ConstantRange&gt; anonymous{SimplifyIndVar.cpp}::WidenIV::PostIncRangeInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1090 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### SE {#a38fec9a65503557fcacb40214a5ac38c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution* anonymous{SimplifyIndVar.cpp}::WidenIV::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1055 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### UsePostIncrementRanges {#a267a25d7293342a1309b7e1b0e701a58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SimplifyIndVar.cpp}::WidenIV::UsePostIncrementRanges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1062 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### WideInc {#a39f1aed837cdc8cdb4a2887adf7a8885}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* anonymous{SimplifyIndVar.cpp}::WidenIV::WideInc = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1070 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### WideIncExpr {#a54be9eaa7bdda1ad45caf3d2af93eab8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV* anonymous{SimplifyIndVar.cpp}::WidenIV::WideIncExpr = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1071 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### Widened {#a5ba15d8fbb802e1305bc9a3bbd099db4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Instruction *,16&gt; anonymous{SimplifyIndVar.cpp}::WidenIV::Widened</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1074 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### WidePhi {#a7382ac5510c7c1e452eb892834c3d241}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHINode* anonymous{SimplifyIndVar.cpp}::WidenIV::WidePhi = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1069 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

### WideType {#aaa226486a01f1ea7a562378f55390a96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* anonymous{SimplifyIndVar.cpp}::WidenIV::WideType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1050 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp">SimplifyIndVar.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
