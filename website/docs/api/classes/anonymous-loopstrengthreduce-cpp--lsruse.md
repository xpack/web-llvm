---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-loopstrengthreduce-cpp-/lsruse
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LSRUse` Class

<p>This class holds the state that LSR keeps for each use in <a href="/web-llvm/docs/api/classes/llvm/ivusers">IVUsers</a>, as well as uses invented by LSR itself. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{LoopStrengthReduce.cpp}::LSRUse { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a62881e0181b4f2dc498eff32edf764">SCEVUseKindPair</a> = <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, 2, <a href="#a1ba9c6c01c92aafaeb2986bdd756dcf0">KindType</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">KindType { <a href="#a1ba9c6c01c92aafaeb2986bdd756dcf0">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An enum for a kind of use, indicating what types of scaled and immediate operands it might support. <a href="#a1ba9c6c01c92aafaeb2986bdd756dcf0">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84a56cc4bd6da1581440b16c21eef5ab">LSRUse</a> (KindType K, MemAccessTy AT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/lsrfixup">LSRFixup</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fe504663d9ae4f9f4b7d30c6d1b6d69">getNewFixup</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae24f15680876cc6aab9d451d3b7906dd">pushFixup</a> (LSRFixup &amp;f)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a389c4d3c542f309b3ad61e8966fb930a">HasFormulaWithSameRegs</a> (const Formula &amp;F) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether this use as a formula which has the same registers as the given formula. <a href="#a389c4d3c542f309b3ad61e8966fb930a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99ba1cdbe93816bffc94d88e85b97de7">getNotSelectedProbability</a> (const SCEV *Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The function returns a probability of selecting formula without Reg. <a href="#a99ba1cdbe93816bffc94d88e85b97de7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2507970e8b86d818892ad183328b450">InsertFormula</a> (const Formula &amp;F, const Loop &amp;L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the given formula has not yet been inserted, add it to the list, and return true. <a href="#ab2507970e8b86d818892ad183328b450">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc6f1cb20b27dcacac8a3ca73baf84df">DeleteFormula</a> (Formula &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the given formula from this use's list. <a href="#abc6f1cb20b27dcacac8a3ca73baf84df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5e9a6e4934a1c3f5194b6940b9b85fc">RecomputeRegs</a> (size_t LUIdx, RegUseTracker &amp;Reguses)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recompute the Regs field, and update RegUses. <a href="#ae5e9a6e4934a1c3f5194b6940b9b85fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a223ebe6602a0309788a0c3906a683175">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5eebe76701b28ce106d5ffd86fbcc27">dump</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1ba9c6c01c92aafaeb2986bdd756dcf0">KindType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af414d3b8902f3db57e9f08d3232fc17c">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/memaccessty">MemAccessTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e2278fe0c13095375e2cb49a04ebd59">AccessTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/lsrfixup">LSRFixup</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a260c70810f34f4da69f1f8fb1aeac273">Fixups</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The list of operands which are to be replaced. <a href="#a260c70810f34f4da69f1f8fb1aeac273">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate">Immediate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a445b231c7c14ab0d460f9a4d70367c8e">MinOffset</a> = <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate/#a23392dbe6d771d111f00d09560f87f0d">Immediate::getFixedMax</a>()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of the min and max offsets of the fixups. <a href="#a445b231c7c14ab0d460f9a4d70367c8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate">Immediate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb7a640470c15f82dc8df85e033d8619">MaxOffset</a> = <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate/#a691a45579958cfd41dd9dcff39646ca0">Immediate::getFixedMin</a>()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac7deb997535d3d9a445dd87bd0f2192">AllFixupsOutsideLoop</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This records whether all of the fixups using this <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> are outside of the loop, in which case some special-case heuristics may be used. <a href="#aac7deb997535d3d9a445dd87bd0f2192">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa45af5caf29ddb4040ef123166ba800a">RigidFormula</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RigidFormula is set to true to guarantee that this use will be associated with a single formula–the one that initially matched. <a href="#aa45af5caf29ddb4040ef123166ba800a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6eb6d8e22eb1da2d816c5cb38fe166d">WidestFixupType</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This records the widest use type for any fixup using this <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a>. <a href="#ac6eb6d8e22eb1da2d816c5cb38fe166d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a>, 12 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8edee80f0644aef0363b9bc0a7593182">Formulae</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A list of ways to build a value that can satisfy this user. <a href="#a8edee80f0644aef0363b9bc0a7593182">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfc1d18c4ab614170ff65151e6eb2a60">Regs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of register candidates used by all formulae in this <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a>. <a href="#acfc1d18c4ab614170ff65151e6eb2a60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, 4 &gt;, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/uniquifierdensemapinfo">UniquifierDenseMapInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e193368196c0b6192f5d23b1688718c">Uniquifier</a></td>
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

<p>This class holds the state that LSR keeps for each use in <a href="/web-llvm/docs/api/classes/llvm/ivusers">IVUsers</a>, as well as uses invented by LSR itself.</p>


<p>It includes information about what kinds of things can be folded into the user, information about the user itself, and information about how the use may be satisfied. TODO: Represent multiple users of the same expression in common?</p>


<p>Definition at line 1308 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### SCEVUseKindPair {#a4a62881e0181b4f2dc498eff32edf764}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{LoopStrengthReduce.cpp}::LSRUse::SCEVUseKindPair =  PointerIntPair&lt;const SCEV *, 2, KindType&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1322 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### KindType {#a1ba9c6c01c92aafaeb2986bdd756dcf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{LoopStrengthReduce.cpp}::LSRUse::KindType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An enum for a kind of use, indicating what types of scaled and immediate operands it might support.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Basic<a id="a1ba9c6c01c92aafaeb2986bdd756dcf0a55d63bad11e6c7c0a80a181ad353c0a4"></a></td>
<td class="doxyEnumItemDescription">A normal use, with no folding</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Special<a id="a1ba9c6c01c92aafaeb2986bdd756dcf0ab2859f05059b7bc12a24c88a418fd214"></a></td>
<td class="doxyEnumItemDescription">A special case of basic, allowing -1 scales</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Address<a id="a1ba9c6c01c92aafaeb2986bdd756dcf0a83bf7174fbbec2c33ed1a665e637fd2a"></a></td>
<td class="doxyEnumItemDescription">An address use; folding according to <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICmpZero<a id="a1ba9c6c01c92aafaeb2986bdd756dcf0aa25a0984500d71f1ab0f82f5372a4d70"></a></td>
<td class="doxyEnumItemDescription">An equality icmp with both operands folded into one</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1314 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LSRUse() {#a84a56cc4bd6da1581440b16c21eef5ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoopStrengthReduce.cpp}::LSRUse::LSRUse (<a href="#a1ba9c6c01c92aafaeb2986bdd756dcf0">KindType</a> K, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/memaccessty">MemAccessTy</a> AT)</td>
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



<p>Definition at line 1359 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="#a7e2278fe0c13095375e2cb49a04ebd59">AccessTy</a> and <a href="#af414d3b8902f3db57e9f08d3232fc17c">Kind</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### DeleteFormula() {#abc6f1cb20b27dcacac8a3ca73baf84df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRUse::DeleteFormula (<a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the given formula from this use's list.</p>

<p>Definition at line 1377 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a8edee80f0644aef0363b9bc0a7593182">Formulae</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### dump() {#af5eebe76701b28ce106d5ffd86fbcc27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void LSRUse::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1381 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf746ca1858c0e272e3a802fc27942">llvm::print</a>.</p>

</div>
</div>

### getNewFixup() {#a2fe504663d9ae4f9f4b7d30c6d1b6d69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LSRFixup &amp; anonymous{LoopStrengthReduce.cpp}::LSRUse::getNewFixup ()</td>
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



<p>Definition at line 1361 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Reference <a href="#a260c70810f34f4da69f1f8fb1aeac273">Fixups</a>.</p>

</div>
</div>

### getNotSelectedProbability() {#a99ba1cdbe93816bffc94d88e85b97de7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float LSRUse::getNotSelectedProbability (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The function returns a probability of selecting formula without Reg.</p>

<p>Definition at line 1375 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a8edee80f0644aef0363b9bc0a7593182">Formulae</a>.</p>

</div>
</div>

### HasFormulaWithSameRegs() {#a389c4d3c542f309b3ad61e8966fb930a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LSRUse::HasFormulaWithSameRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether this use as a formula which has the same registers as the given formula.</p>

<p>Definition at line 1374 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>

</div>
</div>

### InsertFormula() {#ab2507970e8b86d818892ad183328b450}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LSRUse::InsertFormula (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the given formula has not yet been inserted, add it to the list, and return true.</p>


<p>Return false otherwise. The formula must be in canonical form.</p>


<p>Definition at line 1376 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a8edee80f0644aef0363b9bc0a7593182">Formulae</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#a4541962f9c18aacceb7243520eb15e1f">llvm::SCEV::isZero</a>, <a href="#acfc1d18c4ab614170ff65151e6eb2a60">Regs</a>, <a href="#aa45af5caf29ddb4040ef123166ba800a">RigidFormula</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>

</div>
</div>

### print() {#a223ebe6602a0309788a0c3906a683175}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRUse::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1380 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="#a7e2278fe0c13095375e2cb49a04ebd59">AccessTy</a>, <a href="#a1ba9c6c01c92aafaeb2986bdd756dcf0a83bf7174fbbec2c33ed1a665e637fd2a">Address</a>, <a href="#aac7deb997535d3d9a445dd87bd0f2192">AllFixupsOutsideLoop</a>, <a href="#a1ba9c6c01c92aafaeb2986bdd756dcf0a55d63bad11e6c7c0a80a181ad353c0a4">Basic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="#a260c70810f34f4da69f1f8fb1aeac273">Fixups</a>, <a href="#a1ba9c6c01c92aafaeb2986bdd756dcf0aa25a0984500d71f1ab0f82f5372a4d70">ICmpZero</a>, <a href="#af414d3b8902f3db57e9f08d3232fc17c">Kind</a>, <a href="#a1ba9c6c01c92aafaeb2986bdd756dcf0ab2859f05059b7bc12a24c88a418fd214">Special</a> and <a href="#ac6eb6d8e22eb1da2d816c5cb38fe166d">WidestFixupType</a>.</p>

</div>
</div>

### pushFixup() {#ae24f15680876cc6aab9d451d3b7906dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopStrengthReduce.cpp}::LSRUse::pushFixup (<a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/lsrfixup">LSRFixup</a> &amp; f)</td>
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



<p>Definition at line 1366 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="#a260c70810f34f4da69f1f8fb1aeac273">Fixups</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#addaa86bfa4ca26b7f366cbdd868f99bf">llvm::details::FixedOrScalableQuantity&lt; Immediate, int64_t &gt;::isKnownGT</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a83e6442f8ebefccdb5e089732fe397ac">llvm::details::FixedOrScalableQuantity&lt; Immediate, int64_t &gt;::isKnownLT</a>, <a href="#afb7a640470c15f82dc8df85e033d8619">MaxOffset</a> and <a href="#a445b231c7c14ab0d460f9a4d70367c8e">MinOffset</a>.</p>

</div>
</div>

### RecomputeRegs() {#ae5e9a6e4934a1c3f5194b6940b9b85fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LSRUse::RecomputeRegs (size_t LUIdx, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/regusetracker">RegUseTracker</a> &amp; Reguses)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recompute the Regs field, and update RegUses.</p>

<p>Definition at line 1378 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/regusetracker/#a6a56d58ef201c3111c594b541bfef549">anonymous{LoopStrengthReduce.cpp}::RegUseTracker::dropRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a8edee80f0644aef0363b9bc0a7593182">Formulae</a> and <a href="#acfc1d18c4ab614170ff65151e6eb2a60">Regs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AccessTy {#a7e2278fe0c13095375e2cb49a04ebd59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemAccessTy anonymous{LoopStrengthReduce.cpp}::LSRUse::AccessTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1325 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Referenced by <a href="#a84a56cc4bd6da1581440b16c21eef5ab">LSRUse</a> and <a href="#a223ebe6602a0309788a0c3906a683175">print</a>.</p>

</div>
</div>

### AllFixupsOutsideLoop {#aac7deb997535d3d9a445dd87bd0f2192}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopStrengthReduce.cpp}::LSRUse::AllFixupsOutsideLoop = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This records whether all of the fixups using this <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a> are outside of the loop, in which case some special-case heuristics may be used.</p>

<p>Definition at line 1336 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Referenced by <a href="#a223ebe6602a0309788a0c3906a683175">print</a>.</p>

</div>
</div>

### Fixups {#a260c70810f34f4da69f1f8fb1aeac273}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;LSRFixup, 8&gt; anonymous{LoopStrengthReduce.cpp}::LSRUse::Fixups</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The list of operands which are to be replaced.</p>

<p>Definition at line 1328 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Referenced by <a href="#a2fe504663d9ae4f9f4b7d30c6d1b6d69">getNewFixup</a>, <a href="#a223ebe6602a0309788a0c3906a683175">print</a> and <a href="#ae24f15680876cc6aab9d451d3b7906dd">pushFixup</a>.</p>

</div>
</div>

### Formulae {#a8edee80f0644aef0363b9bc0a7593182}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Formula, 12&gt; anonymous{LoopStrengthReduce.cpp}::LSRUse::Formulae</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A list of ways to build a value that can satisfy this user.</p>


<p>After the list is populated, one of these is selected heuristically and used to formulate a replacement for OperandValToReplace in UserInst.</p>


<p>Definition at line 1354 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Referenced by <a href="#abc6f1cb20b27dcacac8a3ca73baf84df">DeleteFormula</a>, <a href="#a99ba1cdbe93816bffc94d88e85b97de7">getNotSelectedProbability</a>, <a href="#ab2507970e8b86d818892ad183328b450">InsertFormula</a> and <a href="#ae5e9a6e4934a1c3f5194b6940b9b85fc">RecomputeRegs</a>.</p>

</div>
</div>

### Kind {#af414d3b8902f3db57e9f08d3232fc17c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KindType anonymous{LoopStrengthReduce.cpp}::LSRUse::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1324 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Referenced by <a href="#a84a56cc4bd6da1581440b16c21eef5ab">LSRUse</a> and <a href="#a223ebe6602a0309788a0c3906a683175">print</a>.</p>

</div>
</div>

### MaxOffset {#afb7a640470c15f82dc8df85e033d8619}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Immediate anonymous{LoopStrengthReduce.cpp}::LSRUse::MaxOffset = <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate/#a691a45579958cfd41dd9dcff39646ca0">Immediate::getFixedMin</a>()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1332 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Referenced by <a href="#ae24f15680876cc6aab9d451d3b7906dd">pushFixup</a>.</p>

</div>
</div>

### MinOffset {#a445b231c7c14ab0d460f9a4d70367c8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Immediate anonymous{LoopStrengthReduce.cpp}::LSRUse::MinOffset = <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate/#a23392dbe6d771d111f00d09560f87f0d">Immediate::getFixedMax</a>()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of the min and max offsets of the fixups.</p>

<p>Definition at line 1331 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Referenced by <a href="#ae24f15680876cc6aab9d451d3b7906dd">pushFixup</a>.</p>

</div>
</div>

### Regs {#acfc1d18c4ab614170ff65151e6eb2a60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const SCEV *, 4&gt; anonymous{LoopStrengthReduce.cpp}::LSRUse::Regs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of register candidates used by all formulae in this <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a>.</p>

<p>Definition at line 1357 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Referenced by <a href="#ab2507970e8b86d818892ad183328b450">InsertFormula</a> and <a href="#ae5e9a6e4934a1c3f5194b6940b9b85fc">RecomputeRegs</a>.</p>

</div>
</div>

### RigidFormula {#aa45af5caf29ddb4040ef123166ba800a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopStrengthReduce.cpp}::LSRUse::RigidFormula = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>RigidFormula is set to true to guarantee that this use will be associated with a single formula–the one that initially matched.</p>


<p>Some <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expressions cannot be expanded. This allows LSR to consider the registers used by those expressions without the need to expand them later after changing the formula.</p>


<p>Definition at line 1343 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Referenced by <a href="#ab2507970e8b86d818892ad183328b450">InsertFormula</a>.</p>

</div>
</div>

### WidestFixupType {#ac6eb6d8e22eb1da2d816c5cb38fe166d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* anonymous{LoopStrengthReduce.cpp}::LSRUse::WidestFixupType = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This records the widest use type for any fixup using this <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse">LSRUse</a>.</p>


<p>FindUseWithSimilarFormula can't consider uses with different max fixup widths to be equivalent, because the narrower one may be relying on the implicit truncation to truncate away bogus bits.</p>


<p>Definition at line 1349 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Referenced by <a href="#a223ebe6602a0309788a0c3906a683175">print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Uniquifier {#a6e193368196c0b6192f5d23b1688718c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;SmallVector&lt;const SCEV *, 4&gt;, UniquifierDenseMapInfo&gt; anonymous{LoopStrengthReduce.cpp}::LSRUse::Uniquifier</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1309 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
