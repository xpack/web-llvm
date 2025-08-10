---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-guardwidening-cpp-/guardwideningimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GuardWideningImpl` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{GuardWidening.cpp}::GuardWideningImpl { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">WideningScore { <a href="#aa9e8beadcf5341e4ac3cdb0cfcd1e34a">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to keep track of which widening potential is more effective. <a href="#aa9e8beadcf5341e4ac3cdb0cfcd1e34a">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29f953f1a7cf473c2f1bf531711e0622">GuardWideningImpl</a> (DominatorTree &amp;DT, PostDominatorTree *PDT, LoopInfo &amp;LI, AssumptionCache &amp;AC, MemorySSAUpdater *MSSAU, DomTreeNode *Root, std::function&lt; bool(BasicBlock *)&gt; BlockFilter)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5aa5682f973c80e1570c6c788b92122">run</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The entry point for this pass. <a href="#ab5aa5682f973c80e1570c6c788b92122">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa32a9e25de2b7880d55ef07d3baea4e7">eliminateInstrViaWidening</a> (Instruction *Instr, const df_iterator&lt; DomTreeNode * &gt; &amp;DFSI, const DenseMap&lt; BasicBlock *, SmallVector&lt; Instruction *, 8 &gt; &gt; &amp;GuardsPerBlock)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to eliminate instruction <span class="doxyComputerOutput">Instr</span> by widening it into an earlier dominating guard. <a href="#aa32a9e25de2b7880d55ef07d3baea4e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">WideningScore</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd75e355f390b797c5746e1f3644ef6d">computeWideningScore</a> (Instruction *DominatedInstr, Instruction *ToWiden, BasicBlock::iterator WideningPoint, SmallVectorImpl&lt; Value * &gt; &amp;ChecksToHoist, SmallVectorImpl&lt; Value * &gt; &amp;ChecksToWiden)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the score for widening the condition in <span class="doxyComputerOutput">DominatedInstr</span> into <span class="doxyComputerOutput">WideningPoint</span>. <a href="#acd75e355f390b797c5746e1f3644ef6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e7d3e3e94a516f327ab285752e06baf">canBeHoistedTo</a> (const Value *V, BasicBlock::iterator InsertPos) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to check if <span class="doxyComputerOutput">V</span> can be hoisted to <span class="doxyComputerOutput">InsertPos</span>. <a href="#a5e7d3e3e94a516f327ab285752e06baf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33f52a08a49cef4ec90169a9c92917b4">canBeHoistedTo</a> (const Value *V, BasicBlock::iterator InsertPos, SmallPtrSetImpl&lt; const Instruction * &gt; &amp;Visited) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad3681fc6c799b4e22354afd2934307e">canBeHoistedTo</a> (const SmallVectorImpl&lt; Value * &gt; &amp;Checks, BasicBlock::iterator InsertPos) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedb908507b8175e81e5770a23d79db63">makeAvailableAt</a> (Value *V, BasicBlock::iterator InsertPos) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to hoist <span class="doxyComputerOutput">V</span> to <span class="doxyComputerOutput">InsertPos</span>. <a href="#aedb908507b8175e81e5770a23d79db63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7978e5adc354b6e3ccd8e81f2384cb2e">makeAvailableAt</a> (const SmallVectorImpl&lt; Value * &gt; &amp;Checks, BasicBlock::iterator InsertPos) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8daa08b9ec74d43126a9f5f1249bdcc">mergeChecks</a> (SmallVectorImpl&lt; Value * &gt; &amp;ChecksToHoist, SmallVectorImpl&lt; Value * &gt; &amp;ChecksToWiden, std::optional&lt; BasicBlock::iterator &gt; InsertPt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Common helper used by <span class="doxyComputerOutput">widenGuard</span> and <span class="doxyComputerOutput">isWideningCondProfitable</span>. <a href="#ae8daa08b9ec74d43126a9f5f1249bdcc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f64b83cce9feb42af542950da6586a8">hoistChecks</a> (SmallVectorImpl&lt; Value * &gt; &amp;ChecksToHoist, Value *OldCondition, BasicBlock::iterator InsertPt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate the logical AND of <span class="doxyComputerOutput">ChecksToHoist</span> and <span class="doxyComputerOutput">OldCondition</span> and make it available at InsertPt. <a href="#a8f64b83cce9feb42af542950da6586a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac88cc86c8216cc92483bfa396bfab50c">freezeAndPush</a> (Value *Orig, BasicBlock::iterator InsertPt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds freeze to Orig and push it as far as possible very aggressively. <a href="#ac88cc86c8216cc92483bfa396bfab50c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12d1e40ac3d732cbfa6cc845f3f06181">parseRangeChecks</a> (SmallVectorImpl&lt; Value * &gt; &amp;ToParse, SmallVectorImpl&lt; RangeCheck &gt; &amp;Checks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse <span class="doxyComputerOutput">ToParse</span> into a conjunction (logical-and) of range checks; and append them to <span class="doxyComputerOutput">Checks</span>. <a href="#a12d1e40ac3d732cbfa6cc845f3f06181">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b465ce04eeb7eb39b7c0bba3db2ad2d">parseRangeChecks</a> (Value *CheckCond, SmallVectorImpl&lt; RangeCheck &gt; &amp;Checks)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7958648a4ca0d02d3646dce9e49fef27">combineRangeChecks</a> (SmallVectorImpl&lt; RangeCheck &gt; &amp;Checks, SmallVectorImpl&lt; RangeCheck &gt; &amp;CombinedChecks) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine the checks in <span class="doxyComputerOutput">Checks</span> into a smaller set of checks and append them into <span class="doxyComputerOutput">CombinedChecks</span>. <a href="#a7958648a4ca0d02d3646dce9e49fef27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacf701867ea778aca724363a7f424985">isWideningCondProfitable</a> (SmallVectorImpl&lt; Value * &gt; &amp;ChecksToHoist, SmallVectorImpl&lt; Value * &gt; &amp;ChecksToWiden)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Can we compute the logical AND of <span class="doxyComputerOutput">ChecksToHoist</span> and <span class="doxyComputerOutput">ChecksToWiden</span> for the price of computing only one of the set of expressions? <a href="#aacf701867ea778aca724363a7f424985">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2a16c4e918a5c4e81014531e62e1b9a">widenGuard</a> (SmallVectorImpl&lt; Value * &gt; &amp;ChecksToHoist, SmallVectorImpl&lt; Value * &gt; &amp;ChecksToWiden, Instruction *ToWiden)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Widen <span class="doxyComputerOutput">ChecksToWiden</span> to fail if any of <span class="doxyComputerOutput">ChecksToHoist</span> is false. <a href="#ae2a16c4e918a5c4e81014531e62e1b9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29b33a1f54ea2874a2b2ac77eea68245">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cc86318b9431bdb26a0cd38079d04f0">PDT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58127f0206fe3dc3e751bdb32e3c4fac">LI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3657a1ffaec9baf8aab3b04473444db3">AC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba44956c882a8db23cac02f7df2d4cbc">MSSAU</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a58b9df85470fc4e2a8066ff6a62e5a34">DomTreeNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4899d4180f4bb2e24e98a730d94c27c1">Root</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Together, these describe the region of interest. <a href="#a4899d4180f4bb2e24e98a730d94c27c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b0b18911f40aff1bb1b87ea757a8957">BlockFilter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44a5d15694962ab0f69abf50bddf2ef5">EliminatedGuardsAndBranches</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of guards and conditional branches whose conditions have been widened into dominating guards. <a href="#a44a5d15694962ab0f69abf50bddf2ef5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f54f9f34bcac1dac8832b238a7bfd8c">WidenedGuards</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of guards which have been widened to include conditions to other guards. <a href="#a8f54f9f34bcac1dac8832b238a7bfd8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeac7cb64bc131b0235e1c63043512ca">scoreTypeToString</a> (WideningScore WS)</td>
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


<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### WideningScore {#aa9e8beadcf5341e4ac3cdb0cfcd1e34a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{GuardWidening.cpp}::GuardWideningImpl::WideningScore </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used to keep track of which widening potential is more effective.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WS_IllegalOrNegative<a id="aa9e8beadcf5341e4ac3cdb0cfcd1e34aa7185f5f623554ddd36bc3b5bdb71098b"></a></td>
<td class="doxyEnumItemDescription">Don't widen</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WS_Neutral<a id="aa9e8beadcf5341e4ac3cdb0cfcd1e34aa5f72eac0eee880047c5f9df8e6ebf8d4"></a></td>
<td class="doxyEnumItemDescription">Widening is performance neutral as far as the cycles spent in check conditions goes (but can still help, e.g., code layout, having less deopt state)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WS_Positive<a id="aa9e8beadcf5341e4ac3cdb0cfcd1e34aaa17716a08f770b2592f8128db66d3e4f"></a></td>
<td class="doxyEnumItemDescription">Widening is profitable</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WS_VeryPositive<a id="aa9e8beadcf5341e4ac3cdb0cfcd1e34aad8a157bafd0feefb20f7450bfa2413c0"></a></td>
<td class="doxyEnumItemDescription">Widening is very profitable</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GuardWideningImpl() {#a29f953f1a7cf473c2f1bf531711e0622}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{GuardWidening.cpp}::GuardWideningImpl::GuardWideningImpl (<a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> * PDT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> * MSSAU, <a href="/web-llvm/docs/api/namespaces/llvm/#a58b9df85470fc4e2a8066ff6a62e5a34">DomTreeNode</a> * Root, std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *)&gt; BlockFilter)</td>
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



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#ab5aa5682f973c80e1570c6c788b92122}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GuardWideningImpl::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The entry point for this pass.</p>

<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a4c46542f8881cacd05836ba00ab8ec">llvm::df_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad6c4441c599522e0d10c1391a460c275">llvm::df_end</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-guardwidening-cpp-/#a6d418914e8b20f42ccd313fd4f1f2585">anonymous{GuardWidening.cpp}::eliminateGuard</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-guardwidening-cpp-/#afcfd6271b1843fd8e001db13c306bac4">anonymous{GuardWidening.cpp}::getCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp/#a06f1432892d38967fd37f87b142994d5">isSupportedGuardInstruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### canBeHoistedTo() {#a5e7d3e3e94a516f327ab285752e06baf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{GuardWidening.cpp}::GuardWideningImpl::canBeHoistedTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> InsertPos)</td>
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

<p>Helper to check if <span class="doxyComputerOutput">V</span> can be hoisted to <span class="doxyComputerOutput">InsertPos</span>.</p>

<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

### canBeHoistedTo() {#a33f52a08a49cef4ec90169a9c92917b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{GuardWidening.cpp}::GuardWideningImpl::canBeHoistedTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> InsertPos, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; Visited)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

### canBeHoistedTo() {#aad3681fc6c799b4e22354afd2934307e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{GuardWidening.cpp}::GuardWideningImpl::canBeHoistedTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; Checks, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> InsertPos)</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

### combineRangeChecks() {#a7958648a4ca0d02d3646dce9e49fef27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GuardWideningImpl::combineRangeChecks (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; RangeCheck &gt; &amp; Checks, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; RangeCheck &gt; &amp; CombinedChecks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Combine the checks in <span class="doxyComputerOutput">Checks</span> into a smaller set of checks and append them into <span class="doxyComputerOutput">CombinedChecks</span>.</p>


<p>Return true on success (i.e. all of checks in <span class="doxyComputerOutput">Checks</span> were combined into <span class="doxyComputerOutput">CombinedChecks</span>). Clobbers <span class="doxyComputerOutput">Checks</span> and <span class="doxyComputerOutput">CombinedChecks</span> on success and on failure.</p>


<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

### computeWideningScore() {#acd75e355f390b797c5746e1f3644ef6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GuardWideningImpl::WideningScore GuardWideningImpl::computeWideningScore (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * DominatedInstr, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * ToWiden, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> WideningPoint, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; ChecksToHoist, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; ChecksToWiden)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the score for widening the condition in <span class="doxyComputerOutput">DominatedInstr</span> into <span class="doxyComputerOutput">WideningPoint</span>.</p>

<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

### eliminateInstrViaWidening() {#aa32a9e25de2b7880d55ef07d3baea4e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GuardWideningImpl::eliminateInstrViaWidening (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Instr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/df-iterator">df_iterator</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a58b9df85470fc4e2a8066ff6a62e5a34">DomTreeNode</a> * &gt; &amp; DFSI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 8 &gt; &gt; &amp; GuardsPerBlock)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to eliminate instruction <span class="doxyComputerOutput">Instr</span> by widening it into an earlier dominating guard.</p>


<p><span class="doxyComputerOutput">DFSI</span> is the DFS iterator on the dominator tree that is currently visiting the block containing <span class="doxyComputerOutput">Guard</span>, and <span class="doxyComputerOutput">GuardsPerBlock</span> maps BasicBlocks to the set of guards seen in that block.</p>


<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

### freezeAndPush() {#ac88cc86c8216cc92483bfa396bfab50c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * GuardWideningImpl::freezeAndPush (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Orig, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> InsertPt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds freeze to Orig and push it as far as possible very aggressively.</p>


<p>Also replaces all uses of frozen instruction with frozen version.</p>


<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

### hoistChecks() {#a8f64b83cce9feb42af542950da6586a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * GuardWideningImpl::hoistChecks (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; ChecksToHoist, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * OldCondition, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> InsertPt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate the logical AND of <span class="doxyComputerOutput">ChecksToHoist</span> and <span class="doxyComputerOutput">OldCondition</span> and make it available at InsertPt.</p>

<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

### isWideningCondProfitable() {#aacf701867ea778aca724363a7f424985}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{GuardWidening.cpp}::GuardWideningImpl::isWideningCondProfitable (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; ChecksToHoist, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; ChecksToWiden)</td>
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

<p>Can we compute the logical AND of <span class="doxyComputerOutput">ChecksToHoist</span> and <span class="doxyComputerOutput">ChecksToWiden</span> for the price of computing only one of the set of expressions?</p>

<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

### makeAvailableAt() {#aedb908507b8175e81e5770a23d79db63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{GuardWidening.cpp}::GuardWideningImpl::makeAvailableAt (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> InsertPos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper to hoist <span class="doxyComputerOutput">V</span> to <span class="doxyComputerOutput">InsertPos</span>.</p>


<p>Guaranteed to succeed if <span class="doxyComputerOutput">canBeHoistedTo</span> returned true.</p>


<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

### makeAvailableAt() {#a7978e5adc354b6e3ccd8e81f2384cb2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{GuardWidening.cpp}::GuardWideningImpl::makeAvailableAt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; Checks, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> InsertPos)</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

### mergeChecks() {#ae8daa08b9ec74d43126a9f5f1249bdcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Value * &gt; GuardWideningImpl::mergeChecks (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; ChecksToHoist, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; ChecksToWiden, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> &gt; InsertPt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Common helper used by <span class="doxyComputerOutput">widenGuard</span> and <span class="doxyComputerOutput">isWideningCondProfitable</span>.</p>


<p>Try to generate an expression computing the logical AND of <span class="doxyComputerOutput">ChecksToHoist</span> and <span class="doxyComputerOutput">ChecksToWiden</span>. Return true if the expression computing the AND is only as expensive as computing one of the set of expressions. If <span class="doxyComputerOutput">InsertPt</span> is true then actually generate the resulting expression, make it available at <span class="doxyComputerOutput">InsertPt</span> and return it in <span class="doxyComputerOutput">Result</span> (else no change to the IR is made).</p>


<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

### parseRangeChecks() {#a12d1e40ac3d732cbfa6cc845f3f06181}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{GuardWidening.cpp}::GuardWideningImpl::parseRangeChecks (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; ToParse, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; RangeCheck &gt; &amp; Checks)</td>
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

<p>Parse <span class="doxyComputerOutput">ToParse</span> into a conjunction (logical-and) of range checks; and append them to <span class="doxyComputerOutput">Checks</span>.</p>


<p>Returns true on success, may clobber <span class="doxyComputerOutput">Checks</span> on failure.</p>


<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

### parseRangeChecks() {#a8b465ce04eeb7eb39b7c0bba3db2ad2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{GuardWidening.cpp}::GuardWideningImpl::parseRangeChecks (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * CheckCond, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; RangeCheck &gt; &amp; Checks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

### widenGuard() {#ae2a16c4e918a5c4e81014531e62e1b9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{GuardWidening.cpp}::GuardWideningImpl::widenGuard (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; ChecksToHoist, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; ChecksToWiden, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * ToWiden)</td>
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

<p>Widen <span class="doxyComputerOutput">ChecksToWiden</span> to fail if any of <span class="doxyComputerOutput">ChecksToHoist</span> is false.</p>

<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AC {#a3657a1ffaec9baf8aab3b04473444db3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache&amp; anonymous{GuardWidening.cpp}::GuardWideningImpl::AC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

### BlockFilter {#a9b0b18911f40aff1bb1b87ea757a8957}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;bool(BasicBlock*)&gt; anonymous{GuardWidening.cpp}::GuardWideningImpl::BlockFilter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

### DT {#a29b33a1f54ea2874a2b2ac77eea68245}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree&amp; anonymous{GuardWidening.cpp}::GuardWideningImpl::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

### EliminatedGuardsAndBranches {#a44a5d15694962ab0f69abf50bddf2ef5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Instruction *, 16&gt; anonymous{GuardWidening.cpp}::GuardWideningImpl::EliminatedGuardsAndBranches</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of guards and conditional branches whose conditions have been widened into dominating guards.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

### LI {#a58127f0206fe3dc3e751bdb32e3c4fac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo&amp; anonymous{GuardWidening.cpp}::GuardWideningImpl::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

### MSSAU {#aba44956c882a8db23cac02f7df2d4cbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySSAUpdater* anonymous{GuardWidening.cpp}::GuardWideningImpl::MSSAU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

### PDT {#a7cc86318b9431bdb26a0cd38079d04f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PostDominatorTree* anonymous{GuardWidening.cpp}::GuardWideningImpl::PDT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

### Root {#a4899d4180f4bb2e24e98a730d94c27c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeNode* anonymous{GuardWidening.cpp}::GuardWideningImpl::Root</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Together, these describe the region of interest.</p>


<p>This might be all of the blocks within a function, or only a given loop's blocks and preheader.</p>


<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

### WidenedGuards {#a8f54f9f34bcac1dac8832b238a7bfd8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;Instruction *&gt; anonymous{GuardWidening.cpp}::GuardWideningImpl::WidenedGuards</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of guards which have been widened to include conditions to other guards.</p>

<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### scoreTypeToString() {#adeac7cb64bc131b0235e1c63043512ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef GuardWideningImpl::scoreTypeToString (WideningScore WS)</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp">GuardWidening.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
