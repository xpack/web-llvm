---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/interleavedaccessinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InterleavedAccessInfo` Class Reference

<p>Drive the analysis of interleaved memory accesses in the loop. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::InterleavedAccessInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">llvm/Analysis/VectorUtils.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af45c4b68a5963e501df3b38c609cb5c5">StrideEntry</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, StrideDescriptor &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A type for holding instructions and their stride descriptors. <a href="#af45c4b68a5963e501df3b38c609cb5c5">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdb6529eb70fb9aed0036ebc1a864c49">InterleavedAccessInfo</a> (PredicatedScalarEvolution &amp;PSE, Loop *L, DominatorTree *DT, LoopInfo *LI, const LoopAccessInfo *LAI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbe177a202a10b44c23c97acb07a1992">~InterleavedAccessInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af587d7218fa15a456103c3d2125a1fc8">analyzeInterleaving</a> (bool EnableMaskedInterleavedGroup)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze the interleaved accesses and collect them in interleave groups. <a href="#af587d7218fa15a456103c3d2125a1fc8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d9b6620a692f452f5080cb0c20e41e3">invalidateGroups</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Invalidate groups, e.g., in case all blocks in loop will be predicated contrary to original assumption. <a href="#a9d9b6620a692f452f5080cb0c20e41e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7697f9f41ff04e918857f5af7c36fc2a">isInterleaved</a> (Instruction *Instr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">Instr</span> belongs to any interleave group. <a href="#a7697f9f41ff04e918857f5af7c36fc2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/interleavegroup">InterleaveGroup</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a345ad7b4c4d40bffb6ee8c77cac21244">getInterleaveGroup</a> (const Instruction *Instr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the interleave group that <span class="doxyComputerOutput">Instr</span> belongs to. <a href="#a345ad7b4c4d40bffb6ee8c77cac21244">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallptrsetiterator">SmallPtrSetIterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/interleavegroup">llvm::InterleaveGroup</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &gt; * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad12b635916525291058062992dc87d2d">getInterleaveGroups</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34ed64ff27fabc002da4047589142b02">requiresScalarEpilogue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if an interleaved group that may access memory out-of-bounds requires a scalar epilogue iteration for correctness. <a href="#a34ed64ff27fabc002da4047589142b02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afad01409b57e77467d7cafa03ffe3d3f">invalidateGroupsRequiringScalarEpilogue</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Invalidate groups that require a scalar epilogue (due to gaps). <a href="#afad01409b57e77467d7cafa03ffe3d3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7643f0a04959b7febe7e6873dbf403fe">hasGroups</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if we have any interleave groups. <a href="#a7643f0a04959b7febe7e6873dbf403fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/interleavegroup">InterleaveGroup</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc6d6ba3532247ad1661326a18835fb7">createInterleaveGroup</a> (Instruction *Instr, int Stride, Align Alignment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new interleave group with the given instruction <span class="doxyComputerOutput">Instr</span>, stride <span class="doxyComputerOutput">Stride</span> and alignment <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></span>. <a href="#afc6d6ba3532247ad1661326a18835fb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d4a5c3e268a2fcfdeaeb753674448a5">releaseGroup</a> (InterleaveGroup&lt; Instruction &gt; *Group)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Release the group and remove all the relationships. <a href="#a2d4a5c3e268a2fcfdeaeb753674448a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a049538b0e31540cb80bd419e4d1a23b4">releaseGroupWithoutRemovingFromSet</a> (InterleaveGroup&lt; Instruction &gt; *Group)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do everything necessary to release the group, apart from removing it from the InterleaveGroups set. <a href="#a049538b0e31540cb80bd419e4d1a23b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77f96a6a49f4ba74eaf83ab2fd079207">collectConstStrideAccesses</a> (MapVector&lt; Instruction *, StrideDescriptor &gt; &amp;AccessStrideInfo, const DenseMap&lt; Value *, const SCEV * &gt; &amp;Strides)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect all the accesses with a constant stride in program order. <a href="#a77f96a6a49f4ba74eaf83ab2fd079207">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89a2e68f7609dc30954122683bef61d1">isPredicated</a> (BasicBlock *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">BB</span> is a predicated block. <a href="#a89a2e68f7609dc30954122683bef61d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15e835f12423ec4c9298eb7f633510ad">areDependencesValid</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo">LoopAccessInfo</a> can be used for dependence queries. <a href="#a15e835f12423ec4c9298eb7f633510ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a316b31ae4ba73371a530ebeb27320d1e">canReorderMemAccessesForInterleavedGroups</a> (StrideEntry *A, StrideEntry *B) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if memory accesses <span class="doxyComputerOutput">A</span> and <span class="doxyComputerOutput">B</span> can be reordered, if necessary, when constructing interleaved groups. <a href="#a316b31ae4ba73371a530ebeb27320d1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee49da5c2001a7914482802f2a466f15">collectDependences</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect the dependences from <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo">LoopAccessInfo</a>. <a href="#aee49da5c2001a7914482802f2a466f15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab20bd3c889d45067d7e71c9d64782bbf">PSE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A wrapper around <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a>, used to add runtime <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> checks. <a href="#ab20bd3c889d45067d7e71c9d64782bbf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c82be1e536a9c79e9364ac25a0b9ffc">TheLoop</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca5d802fb3ad1400d89dbaeb55ede0b0">DT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad87741c9904cd9d49e715cd452c7bcd0">LI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo">LoopAccessInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33d63df20b45f9afaba5b9199cacea1d">LAI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4eba7f1755d63c3de0671131f0349ea0">RequiresScalarEpilogue</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the loop may contain non-reversed interleaved groups with out-of-bounds accesses. <a href="#a4eba7f1755d63c3de0671131f0349ea0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/interleavegroup">InterleaveGroup</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &gt; * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed1d45a470215dea75c861c97680568a">InterleaveGroupMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds the relationships between the members and the interleave group. <a href="#aed1d45a470215dea75c861c97680568a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/interleavegroup">InterleaveGroup</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &gt; *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9765c3f807019766048a312337a47cd2">InterleaveGroups</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 2 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a896df5ed084aa0f0328f25e692ee216d">Dependences</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds dependences among the memory accesses in the loop. <a href="#a896df5ed084aa0f0328f25e692ee216d">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad75b69605939ae6e5059c3a88656d2ca">isStrided</a> (int Stride)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">Stride</span> is allowed in an interleaved group. <a href="#ad75b69605939ae6e5059c3a88656d2ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Drive the analysis of interleaved memory accesses in the loop.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> this class to analyze interleaved accesses only when we can vectorize a loop. Otherwise it's meaningless to do analysis as the vectorization on interleaved accesses is unsafe.</p>


<p>The analysis collects interleave groups and records the relationships between the member and the group in a map.</p>


<p>Definition at line 630 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### StrideEntry {#af45c4b68a5963e501df3b38c609cb5c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InterleavedAccessInfo::StrideEntry =  std::pair&lt;Instruction *, StrideDescriptor&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A type for holding instructions and their stride descriptors.</p>

<p>Definition at line 743 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InterleavedAccessInfo() {#afdb6529eb70fb9aed0036ebc1a864c49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InterleavedAccessInfo::InterleavedAccessInfo (<a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp; PSE, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo">LoopAccessInfo</a> * LAI)</td>
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



<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~InterleavedAccessInfo() {#afbe177a202a10b44c23c97acb07a1992}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InterleavedAccessInfo::~InterleavedAccessInfo ()</td>
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



<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>


<p>Reference <a href="#a9d9b6620a692f452f5080cb0c20e41e3">invalidateGroups</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### analyzeInterleaving() {#af587d7218fa15a456103c3d2125a1fc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InterleavedAccessInfo::analyzeInterleaving (bool EnableMaskedInterleavedGroup)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyze the interleaved accesses and collect them in interleave groups.</p>


<p>Substitute symbolic strides using <span class="doxyComputerOutput">Strides</span>. Consider also predicated loads/stores in the analysis if <span class="doxyComputerOutput">EnableMaskedInterleavedGroup</span> is true.</p>


<p>Declaration at line 643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>, definition at line 1303 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/vectorutils-cpp">VectorUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#afebe38e4f4ade382a8e857b27cd990a2">llvm::SetVector&lt; T, Vector, Set, N &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#af74676a3c7447be34bd2c1da76ec0c48">llvm::SmallPtrSetImpl&lt; PtrType &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a8da97c44f514ad1ae9ccf4518b0f88aa">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a6b0c3e15c351ba9682837c29b0a141b6">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/scevconstant/#a6caf7f3a0a4303e4c0bc06ed8e205126">llvm::SCEVConstant::getAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/interleavegroup/#a46f3b431a3121fdf53608a283bf4efec">llvm::InterleaveGroup&lt; InstTy &gt;::getFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/interleavegroup/#a5bb08a7480808cec4d5b9e1d0a3012c6">llvm::InterleaveGroup&lt; InstTy &gt;::getIndex</a>, <a href="#a345ad7b4c4d40bffb6ee8c77cac21244">getInterleaveGroup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d97f0780a320d53641729a2d8371b74">llvm::getLoadStoreAddressSpace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2922c0c507ccec5bea4642aff9e2e328">llvm::getLoadStorePointerOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12126a4bea94833696dc67e0431e829">llvm::getLoadStoreType</a>, <a href="/web-llvm/docs/api/classes/llvm/interleavegroup/#a5085afe1fa721f3ef5bf09ca7fc7537c">llvm::InterleaveGroup&lt; InstTy &gt;::getMember</a>, <a href="/web-llvm/docs/api/classes/llvm/interleavegroup/#af81c826ee51addc3321e4ef1c1934696">llvm::InterleaveGroup&lt; InstTy &gt;::getNumMembers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8021a49018596bcbea563e6d5cac9a70">llvm::getPtrStride</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af2daa0ee117afefed4c82eee55bf97b7">llvm::APInt::getSExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/interleavegroup/#ad2398638cf12a8318566a3fc6cc0e771">llvm::InterleaveGroup&lt; InstTy &gt;::insertMember</a>, <a href="#a7697f9f41ff04e918857f5af7c36fc2a">isInterleaved</a>, <a href="/web-llvm/docs/api/classes/llvm/interleavegroup/#a776b9e4e25dda6aff28a94e69a7533e6">llvm::InterleaveGroup&lt; InstTy &gt;::isReverse</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#afa84f2e649eac2b43ff8e4a5e3d866e8">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::rbegin</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a0ddd27a8bb9aa02671ef487de0c6f5ca">llvm::SetVector&lt; T, Vector, Set, N &gt;::remove</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a290c99a05ce4f33c242f41f0a1d59b84">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::rend</a> and <a href="/web-llvm/docs/api/classes/llvm/interleavegroup/#a722a0e30a844c1f562b38ca7e06d6213">llvm::InterleaveGroup&lt; InstTy &gt;::setInsertPos</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

### getInterleaveGroup() {#a345ad7b4c4d40bffb6ee8c77cac21244}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InterleaveGroup&lt; Instruction &gt; * llvm::InterleavedAccessInfo::getInterleaveGroup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Instr)</td>
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

<p>Get the interleave group that <span class="doxyComputerOutput">Instr</span> belongs to.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>nullptr if doesn't have such group.</p></dd>
</dl>


<p>Definition at line 675 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>


<p>Referenced by <a href="#af587d7218fa15a456103c3d2125a1fc8">analyzeInterleaving</a>.</p>

</div>
</div>

### getInterleaveGroups() {#ad12b635916525291058062992dc87d2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; SmallPtrSetIterator&lt; llvm::InterleaveGroup&lt; Instruction &gt; * &gt; &gt; llvm::InterleavedAccessInfo::getInterleaveGroups ()</td>
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



<p>Definition at line 680 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### hasGroups() {#a7643f0a04959b7febe7e6873dbf403fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InterleavedAccessInfo::hasGroups ()</td>
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

<p>Returns true if we have any interleave groups.</p>

<p>Definition at line 694 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#ab68c7ba7bd95784715357a3fbf5235a7">llvm::AArch64TTIImpl::preferPredicateOverEpilogue</a>.</p>

</div>
</div>

### invalidateGroups() {#a9d9b6620a692f452f5080cb0c20e41e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InterleavedAccessInfo::invalidateGroups ()</td>
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

<p>Invalidate groups, e.g., in case all blocks in loop will be predicated contrary to original assumption.</p>


<p>Although we currently prevent group formation for predicated accesses, we may be able to relax this limitation in the future once we handle more complicated blocks. Returns true if any groups were invalidated.</p>


<p>Definition at line 650 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="#afbe177a202a10b44c23c97acb07a1992">~InterleavedAccessInfo</a>.</p>

</div>
</div>

### invalidateGroupsRequiringScalarEpilogue() {#afad01409b57e77467d7cafa03ffe3d3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InterleavedAccessInfo::invalidateGroupsRequiringScalarEpilogue ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Invalidate groups that require a scalar epilogue (due to gaps).</p>


<p>This can happen when optimizing for size forbids a scalar epilogue, and the gap cannot be filtered by masking the load/store.</p>


<p>Declaration at line 691 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>, definition at line 1606 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/vectorutils-cpp">VectorUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a4323c151516742793df95050739d72ab">llvm::SmallPtrSetImpl&lt; PtrType &gt;::remove_if</a> and <a href="#a34ed64ff27fabc002da4047589142b02">requiresScalarEpilogue</a>.</p>

</div>
</div>

### isInterleaved() {#a7697f9f41ff04e918857f5af7c36fc2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InterleavedAccessInfo::isInterleaved (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Instr)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">Instr</span> belongs to any interleave group.</p>

<p>Definition at line 667 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>


<p>Referenced by <a href="#af587d7218fa15a456103c3d2125a1fc8">analyzeInterleaving</a>.</p>

</div>
</div>

### requiresScalarEpilogue() {#a34ed64ff27fabc002da4047589142b02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InterleavedAccessInfo::requiresScalarEpilogue ()</td>
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

<p>Returns true if an interleaved group that may access memory out-of-bounds requires a scalar epilogue iteration for correctness.</p>

<p>Definition at line 686 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>


<p>Referenced by <a href="#afad01409b57e77467d7cafa03ffe3d3f">invalidateGroupsRequiringScalarEpilogue</a> and <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### areDependencesValid() {#a15e835f12423ec4c9298eb7f633510ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InterleavedAccessInfo::areDependencesValid ()</td>
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

<p>Returns true if <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo">LoopAccessInfo</a> can be used for dependence queries.</p>

<p>Definition at line 789 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>

</div>
</div>

### canReorderMemAccessesForInterleavedGroups() {#a316b31ae4ba73371a530ebeb27320d1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InterleavedAccessInfo::canReorderMemAccessesForInterleavedGroups (StrideEntry * A, StrideEntry * B)</td>
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

<p>Returns true if memory accesses <span class="doxyComputerOutput">A</span> and <span class="doxyComputerOutput">B</span> can be reordered, if necessary, when constructing interleaved groups.</p>


<p><span class="doxyComputerOutput">A</span> must precede <span class="doxyComputerOutput">B</span> in program order. We return false if reordering is not necessary or is prevented because <span class="doxyComputerOutput">A</span> and <span class="doxyComputerOutput">B</span> may be dependent.</p>


<p>Definition at line 798 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>

</div>
</div>

### collectConstStrideAccesses() {#a77f96a6a49f4ba74eaf83ab2fd079207}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InterleavedAccessInfo::collectConstStrideAccesses (<a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, StrideDescriptor &gt; &amp; AccessStrideInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; Strides)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect all the accesses with a constant stride in program order.</p>

<p>Declaration at line 776 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>, definition at line 1224 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/vectorutils-cpp">VectorUtils.cpp</a>.</p>

</div>
</div>

### collectDependences() {#aee49da5c2001a7914482802f2a466f15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InterleavedAccessInfo::collectDependences ()</td>
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

<p>Collect the dependences from <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo">LoopAccessInfo</a>.</p>


<p>We process the dependences once during the interleaved access analysis to enable constant-time dependence queries.</p>


<p>Definition at line 845 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>

</div>
</div>

### createInterleaveGroup() {#afc6d6ba3532247ad1661326a18835fb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InterleaveGroup&lt; Instruction &gt; * llvm::InterleavedAccessInfo::createInterleaveGroup (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Instr, int Stride, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
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

<p>Create a new interleave group with the given instruction <span class="doxyComputerOutput">Instr</span>, stride <span class="doxyComputerOutput">Stride</span> and alignment <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the newly created interleave group.</p></dd>
</dl>


<p>Definition at line 750 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>

</div>
</div>

### isPredicated() {#a89a2e68f7609dc30954122683bef61d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InterleavedAccessInfo::isPredicated (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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

<p>Returns true if <span class="doxyComputerOutput">BB</span> is a predicated block.</p>

<p>Definition at line 784 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>

</div>
</div>

### releaseGroup() {#a2d4a5c3e268a2fcfdeaeb753674448a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InterleavedAccessInfo::releaseGroup (<a href="/web-llvm/docs/api/classes/llvm/interleavegroup">InterleaveGroup</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &gt; * Group)</td>
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

<p>Release the group and remove all the relationships.</p>

<p>Definition at line 760 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>

</div>
</div>

### releaseGroupWithoutRemovingFromSet() {#a049538b0e31540cb80bd419e4d1a23b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InterleavedAccessInfo::releaseGroupWithoutRemovingFromSet (<a href="/web-llvm/docs/api/classes/llvm/interleavegroup">InterleaveGroup</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &gt; * Group)</td>
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

<p>Do everything necessary to release the group, apart from removing it from the InterleaveGroups set.</p>

<p>Definition at line 767 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Dependences {#a896df5ed084aa0f0328f25e692ee216d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Instruction *, SmallPtrSet&lt;Instruction *, 2&gt; &gt; llvm::InterleavedAccessInfo::Dependences</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds dependences among the memory accesses in the loop.</p>


<p>It maps a source access to a set of dependent sink accesses.</p>


<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>

</div>
</div>

### DT {#aca5d802fb3ad1400d89dbaeb55ede0b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* llvm::InterleavedAccessInfo::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 704 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>

</div>
</div>

### InterleaveGroupMap {#aed1d45a470215dea75c861c97680568a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Instruction *, InterleaveGroup&lt;Instruction&gt; *&gt; llvm::InterleavedAccessInfo::InterleaveGroupMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds the relationships between the members and the interleave group.</p>

<p>Definition at line 714 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>

</div>
</div>

### InterleaveGroups {#a9765c3f807019766048a312337a47cd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;InterleaveGroup&lt;Instruction&gt; *, 4&gt; llvm::InterleavedAccessInfo::InterleaveGroups</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 716 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>

</div>
</div>

### LAI {#a33d63df20b45f9afaba5b9199cacea1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LoopAccessInfo* llvm::InterleavedAccessInfo::LAI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 706 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>

</div>
</div>

### LI {#ad87741c9904cd9d49e715cd452c7bcd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* llvm::InterleavedAccessInfo::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 705 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>

</div>
</div>

### PSE {#ab20bd3c889d45067d7e71c9d64782bbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PredicatedScalarEvolution&amp; llvm::InterleavedAccessInfo::PSE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A wrapper around <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a>, used to add runtime <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> checks.</p>


<p>Simplifies <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expressions in the context of existing <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> assumptions. The interleaved access analysis can also add new predicates (for example by versioning strides of pointers).</p>


<p>Definition at line 701 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>

</div>
</div>

### RequiresScalarEpilogue {#a4eba7f1755d63c3de0671131f0349ea0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InterleavedAccessInfo::RequiresScalarEpilogue = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the loop may contain non-reversed interleaved groups with out-of-bounds accesses.</p>


<p>We ensure we don't speculatively access memory out-of-bounds by executing at least one scalar epilogue iteration.</p>


<p>Definition at line 711 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>

</div>
</div>

### TheLoop {#a1c82be1e536a9c79e9364ac25a0b9ffc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* llvm::InterleavedAccessInfo::TheLoop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 703 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### isStrided() {#ad75b69605939ae6e5059c3a88656d2ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InterleavedAccessInfo::isStrided (int Stride)</td>
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

<p>Returns true if <span class="doxyComputerOutput">Stride</span> is allowed in an interleaved group.</p>

<p>Declaration at line 781 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a>, definition at line 1219 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/vectorutils-cpp">VectorUtils.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">VectorUtils.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/vectorutils-cpp">VectorUtils.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
