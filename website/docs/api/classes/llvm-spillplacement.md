---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/spillplacement
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SpillPlacement` Class



## Declaration

<div class="doxyDeclaration">
class llvm::SpillPlacement { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">llvm/CodeGen/SpillPlacement.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">BorderConstraint { <a href="#ab09623fee8a653165a7cc624b8eaaa8c">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#ab09623fee8a653165a7cc624b8eaaa8c">BorderConstraint</a> - A basic block has separate constraints for entry and exit. <a href="#ab09623fee8a653165a7cc624b8eaaa8c">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31742950e758d7113228d8e8d90bb9b1">SpillPlacementWrapperLegacy</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7147088054bc8460d429c62d88efbcad">SpillPlacementAnalysis</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad30b36db615c8d126002e0f42b5d0fa2">SpillPlacement</a> (SpillPlacement &amp;&amp;)</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ffbf6440c5de2ff821dc751ea3b2da0">SpillPlacement</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0c5451db0d7741582cb9314fa61398c">~SpillPlacement</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a329177b9cd260516a4aca8f55c199020">prepare</a> (BitVector &amp;RegBundles)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>prepare - Reset state and prepare for a new spill placement computation. <a href="#a329177b9cd260516a4aca8f55c199020">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d46b9b2cb2caf78e65bbd56644fc0f2">addConstraints</a> (ArrayRef&lt; BlockConstraint &gt; LiveBlocks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addConstraints - Add constraints and biases. <a href="#a0d46b9b2cb2caf78e65bbd56644fc0f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bd552babf3d34952ed159b653515b5e">addPrefSpill</a> (ArrayRef&lt; unsigned &gt; Blocks, bool Strong)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addPrefSpill - Add PrefSpill constraints to all blocks listed. <a href="#a2bd552babf3d34952ed159b653515b5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80ed1a6b4e8e7a1eb342ac71a24e842b">addLinks</a> (ArrayRef&lt; unsigned &gt; Links)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addLinks - Add transparent blocks with the given numbers. <a href="#a80ed1a6b4e8e7a1eb342ac71a24e842b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a435b043e417bb3f4fc9ac0f6e0c6ebc8">scanActiveBundles</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>scanActiveBundles - Perform an initial scan of all bundles activated by addConstraints and addLinks, updating their state. <a href="#a435b043e417bb3f4fc9ac0f6e0c6ebc8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d70270c78d36ddb40a8b782e141b63a">iterate</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>iterate - Update the network iteratively until convergence, or new bundles are found. <a href="#a8d70270c78d36ddb40a8b782e141b63a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcc18d97175ebe3c6c276562482302fb">getRecentPositive</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getRecentPositive - Return an array of bundles that became positive during the previous call to scanActiveBundles or iterate. <a href="#adcc18d97175ebe3c6c276562482302fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2310373a95001e3677c0f0534cdfc0e1">finish</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>finish - Compute the optimal spill code placement given the constraints. <a href="#a2310373a95001e3677c0f0534cdfc0e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2b2fc73ca35a622fa5eaf62a048d508">getBlockFrequency</a> (unsigned Number) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getBlockFrequency - Return the estimated block execution frequency per function invocation. <a href="#ae2b2fc73ca35a622fa5eaf62a048d508">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64ebfd5ad1ddae5f9cd92ea10af28610">invalidate</a> (MachineFunction &amp;MF, const PreservedAnalyses &amp;PA, MachineFunctionAnalysisManager::Invalidator &amp;Inv)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bc9d45e0612246a18a97ce8c7ae5030">releaseMemory</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac13f3ac9142ff481f349bc1d3a87c9ae">run</a> (MachineFunction &amp;MF, EdgeBundles *Bundles, MachineBlockFrequencyInfo *MBFI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fed96ef608fce30b2185bb261c63f40">activate</a> (unsigned n)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>activate - mark node n as active if it wasn't already. <a href="#a2fed96ef608fce30b2185bb261c63f40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4bec3bd2bfc454d43e55f1271834fa5">setThreshold</a> (BlockFrequency Entry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the threshold for a given entry frequency. <a href="#ac4bec3bd2bfc454d43e55f1271834fa5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac44259880dccee6128593bd4f33ed5be">update</a> (unsigned n)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a1ab4faa395ddf304481ff5b12cb22b">MF</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/edgebundles">EdgeBundles</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bf87d8f6fed2199a29cd977c8ffb66b">bundles</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f65f0fa0864b1c2b8ff3f826d832e63">MBFI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/spillplacement/node">Node</a>[]&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19bb9b2be0c8eca40fab3854d3dbbab0">nodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63b7a67bdefb26dd2e35bc4129cdda9a">ActiveNodes</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dfe781a7d2a0f1b385c80e2bb8c88fd">Linked</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0134275129dd5e53c7e395ef82cdbbe2">RecentPositive</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a869ac1241668f7a460ef875e0af9c076">BlockFrequencies</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f1c4633962082678ab1602f0e6d8a6a">Threshold</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decision threshold. <a href="#a2f1c4633962082678ab1602f0e6d8a6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5511d6b4e3b32b5e7fa6f6cd9d8b8482">TodoList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of nodes that need to be updated in <a href="#a8d70270c78d36ddb40a8b782e141b63a">iterate</a>. <a href="#a5511d6b4e3b32b5e7fa6f6cd9d8b8482">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### BorderConstraint {#ab09623fee8a653165a7cc624b8eaaa8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::SpillPlacement::BorderConstraint </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#ab09623fee8a653165a7cc624b8eaaa8c">BorderConstraint</a> - A basic block has separate constraints for entry and exit.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DontCare<a id="ab09623fee8a653165a7cc624b8eaaa8ca49b6f21cf41c5b608cb5645bc70d36b8"></a></td>
<td class="doxyEnumItemDescription">Block doesn't care / variable not live</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PrefReg<a id="ab09623fee8a653165a7cc624b8eaaa8caca6da2dad218232636b80854d81a6e1c"></a></td>
<td class="doxyEnumItemDescription">Block entry/exit prefers a register</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PrefSpill<a id="ab09623fee8a653165a7cc624b8eaaa8caf5efe10871d66719c8668d09d768e740"></a></td>
<td class="doxyEnumItemDescription">Block entry/exit prefers a stack slot</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PrefBoth<a id="ab09623fee8a653165a7cc624b8eaaa8ca821efd84662975133aa7c60d1a84fa42"></a></td>
<td class="doxyEnumItemDescription">Block entry prefers both register and stack</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MustSpill<a id="ab09623fee8a653165a7cc624b8eaaa8ca043a091e52f465df92623f5f17477837"></a></td>
<td class="doxyEnumItemDescription">A register is impossible, variable must be spilled</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### SpillPlacementAnalysis {#a7147088054bc8460d429c62d88efbcad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/spillplacementanalysis">SpillPlacementAnalysis</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>.</p>


<p>Reference <a href="#a7147088054bc8460d429c62d88efbcad">SpillPlacementAnalysis</a>.</p>


<p>Referenced by <a href="#a64ebfd5ad1ddae5f9cd92ea10af28610">invalidate</a> and <a href="#a7147088054bc8460d429c62d88efbcad">SpillPlacementAnalysis</a>.</p>

</div>
</div>

### SpillPlacementWrapperLegacy {#a31742950e758d7113228d8e8d90bb9b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/spillplacementwrapperlegacy">SpillPlacementWrapperLegacy</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>.</p>


<p>Reference <a href="#a31742950e758d7113228d8e8d90bb9b1">SpillPlacementWrapperLegacy</a>.</p>


<p>Referenced by <a href="#a31742950e758d7113228d8e8d90bb9b1">SpillPlacementWrapperLegacy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SpillPlacement() {#ad30b36db615c8d126002e0f42b5d0fa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpillPlacement::SpillPlacement (<a href="/web-llvm/docs/api/classes/llvm/spillplacement">SpillPlacement</a> &amp;&amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>.</p>


<p>Reference <a href="#ad30b36db615c8d126002e0f42b5d0fa2">SpillPlacement</a>.</p>


<p>Referenced by <a href="#ad30b36db615c8d126002e0f42b5d0fa2">SpillPlacement</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### SpillPlacement() {#a1ffbf6440c5de2ff821dc751ea3b2da0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpillPlacement::SpillPlacement ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SpillPlacement() {#ab0c5451db0d7741582cb9314fa61398c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpillPlacement::~SpillPlacement ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addConstraints() {#a0d46b9b2cb2caf78e65bbd56644fc0f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SpillPlacement::addConstraints (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/spillplacement/blockconstraint">BlockConstraint</a> &gt; LiveBlocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addConstraints - Add constraints and biases.</p>


<p>addConstraints - Compute node biases and weights from a set of constraints.</p>


<p>This method may be called more than once to accumulate constraints.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">LiveBlocks</td>
<td class="doxyParamItemDescription"><p>Constraints for blocks that have the variable live in or live out.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Set a bit in NodeMask for each active node.</p>


<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>, definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>


<p>Reference <a href="#ab09623fee8a653165a7cc624b8eaaa8ca49b6f21cf41c5b608cb5645bc70d36b8">DontCare</a>.</p>

</div>
</div>

### addLinks() {#a80ed1a6b4e8e7a1eb342ac71a24e842b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SpillPlacement::addLinks (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Links)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addLinks - Add transparent blocks with the given numbers.</p>

<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>, definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#af83da56920f4f1059b02e07966f9fccfab2ee912b91d69b435159c7c3f6df7f5f">llvm::Number</a>.</p>

</div>
</div>

### addPrefSpill() {#a2bd552babf3d34952ed159b653515b5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SpillPlacement::addPrefSpill (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Blocks, bool Strong)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addPrefSpill - Add PrefSpill constraints to all blocks listed.</p>


<p>addPrefSpill - Same as addConstraints(PrefSpill)</p>


<p>This is equivalent to calling addConstraint with identical BlockConstraints with Entry = Exit = PrefSpill, and ChangesValue = false.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Blocks</td>
<td class="doxyParamItemDescription"><p>Array of block numbers that prefer to spill in and out.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Strong</td>
<td class="doxyParamItemDescription"><p>When true, double the negative bias for these blocks.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>, definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#ab09623fee8a653165a7cc624b8eaaa8caf5efe10871d66719c8668d09d768e740">PrefSpill</a>.</p>

</div>
</div>

### finish() {#a2310373a95001e3677c0f0534cdfc0e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SpillPlacement::finish ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>finish - Compute the optimal spill code placement given the constraints.</p>


<p>No MustSpill constraints will be violated, and the smallest possible number of PrefX constraints will be violated, weighted by expected execution frequencies. The selected bundles are returned in the bitvector passed to <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#acc01b07763ec8c4b7acd6ffaa69b1c0c">prepare()</a>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if a perfect solution was found, allowing the variable to be in a register through all relevant bundles.</p></dd>
</dl>


<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>, definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getBlockFrequency() {#ae2b2fc73ca35a622fa5eaf62a048d508}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency llvm::SpillPlacement::getBlockFrequency (unsigned Number)</td>
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

<p>getBlockFrequency - Return the estimated block execution frequency per function invocation.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#af83da56920f4f1059b02e07966f9fccfab2ee912b91d69b435159c7c3f6df7f5f">llvm::Number</a>.</p>

</div>
</div>

### getRecentPositive() {#adcc18d97175ebe3c6c276562482302fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; unsigned &gt; llvm::SpillPlacement::getRecentPositive ()</td>
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

<p>getRecentPositive - Return an array of bundles that became positive during the previous call to scanActiveBundles or iterate.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>.</p>

</div>
</div>

### invalidate() {#a64ebfd5ad1ddae5f9cd92ea10af28610}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SpillPlacementAnalysis::Result::invalidate (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp; PA, MachineFunctionAnalysisManager::Invalidator &amp; Inv)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>, definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>


<p>Reference <a href="#a7147088054bc8460d429c62d88efbcad">SpillPlacementAnalysis</a>.</p>

</div>
</div>

### iterate() {#a8d70270c78d36ddb40a8b782e141b63a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SpillPlacement::iterate ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>iterate - Update the network iteratively until convergence, or new bundles are found.</p>


<p>iterate - Repeatedly update the Hopfield nodes until stability or the maximum number of iterations is reached.</p>


<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>, definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>

</div>
</div>

### prepare() {#a329177b9cd260516a4aca8f55c199020}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SpillPlacement::prepare (<a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; RegBundles)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>prepare - Reset state and prepare for a new spill placement computation.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">RegBundles</td>
<td class="doxyParamItemDescription"><p>Bit vector to receive the edge bundles where the variable should be kept in a register. Each bit corresponds to an edge bundle, a set bit means the variable should be kept in a register through the bundle. A clear bit means the variable should be spilled. This vector is retained.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>, definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a35bbc237e4a675c5332103ac6e7dcce1">llvm::BitVector::clear</a>.</p>

</div>
</div>

### scanActiveBundles() {#a435b043e417bb3f4fc9ac0f6e0c6ebc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SpillPlacement::scanActiveBundles ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>scanActiveBundles - Perform an initial scan of all bundles activated by addConstraints and addLinks, updating their state.</p>


<p>Add all the bundles that now prefer a register to RecentPositive. Prepare internal data structures for iterate. Return true is there are any positive nodes.</p>


<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>, definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### activate() {#a2fed96ef608fce30b2185bb261c63f40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SpillPlacement::activate (unsigned n)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>activate - mark node n as active if it wasn't already.</p>

<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>, definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>

</div>
</div>

### releaseMemory() {#a2bc9d45e0612246a18a97ce8c7ae5030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SpillPlacement::releaseMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>, definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>

</div>
</div>

### run() {#ac13f3ac9142ff481f349bc1d3a87c9ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SpillPlacement::run (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/edgebundles">EdgeBundles</a> * Bundles, <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a> * MBFI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>, definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>

</div>
</div>

### setThreshold() {#ac4bec3bd2bfc454d43e55f1271834fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SpillPlacement::setThreshold (<a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> Entry)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the threshold for a given entry frequency.</p>


<p>Set the threshold relative to <span class="doxyComputerOutput">Entry</span>. Since the threshold is used as a bound on the open interval (-Threshold;Threshold), 1 is the minimum threshold.</p>


<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>, definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>

</div>
</div>

### update() {#ac44259880dccee6128593bd4f33ed5be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SpillPlacement::update (unsigned n)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>, definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ActiveNodes {#a63b7a67bdefb26dd2e35bc4129cdda9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector* llvm::SpillPlacement::ActiveNodes = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>.</p>

</div>
</div>

### BlockFrequencies {#a869ac1241668f7a460ef875e0af9c076}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;BlockFrequency, 8&gt; llvm::SpillPlacement::BlockFrequencies</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>.</p>

</div>
</div>

### bundles {#a7bf87d8f6fed2199a29cd977c8ffb66b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EdgeBundles* llvm::SpillPlacement::bundles = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>.</p>

</div>
</div>

### Linked {#a9dfe781a7d2a0f1b385c80e2bb8c88fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;unsigned, 8&gt; llvm::SpillPlacement::Linked</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>.</p>

</div>
</div>

### MBFI {#a3f65f0fa0864b1c2b8ff3f826d832e63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBlockFrequencyInfo* llvm::SpillPlacement::MBFI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>.</p>

</div>
</div>

### MF {#a8a1ab4faa395ddf304481ff5b12cb22b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineFunction* llvm::SpillPlacement::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>.</p>

</div>
</div>

### nodes {#a19bb9b2be0c8eca40fab3854d3dbbab0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Node[]&gt; llvm::SpillPlacement::nodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>.</p>

</div>
</div>

### RecentPositive {#a0134275129dd5e53c7e395ef82cdbbe2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;unsigned, 8&gt; llvm::SpillPlacement::RecentPositive</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>.</p>

</div>
</div>

### Threshold {#a2f1c4633962082678ab1602f0e6d8a6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency llvm::SpillPlacement::Threshold</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Decision threshold.</p>


<p>A node gets the output value 0 if the weighted sum of its inputs falls in the open interval (-Threshold;Threshold).</p>


<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>.</p>

</div>
</div>

### TodoList {#a5511d6b4e3b32b5e7fa6f6cd9d8b8482}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SparseSet&lt;unsigned&gt; llvm::SpillPlacement::TodoList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of nodes that need to be updated in <a href="#a8d70270c78d36ddb40a8b782e141b63a">iterate</a>.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
