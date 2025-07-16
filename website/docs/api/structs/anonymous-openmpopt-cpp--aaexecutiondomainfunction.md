---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AAExecutionDomainFunction` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain">AAExecutionDomain</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">Direction { <a href="#a1ea0e0885759b6aefd8d04866cdac079">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc69e1157f94e0127e9940b8d5bb72b5">AAExecutionDomainFunction</a> (const IRPosition &amp;IRP, Attributor &amp;A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a831f6cd2fcfc1b0e4f29527031a05e38">~AAExecutionDomainFunction</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a434c328cc87725efcfb56d78ca310e56">initialize</a> (Attributor &amp;A) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the state with the information in the Attributor <span class="doxyComputerOutput">A</span>. <a href="#a434c328cc87725efcfb56d78ca310e56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9008361b1d158d70137eff54eded9483">getAsStr</a> (Attributor *) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function should return the "summarized" assumed state as string. <a href="#a9008361b1d158d70137eff54eded9483">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a668f4f3df1dbf8b253e8e036570cb384">trackStatistics</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#add85e4d78cefc67429904d7492aff9a4">AbstractAttribute::trackStatistics()</a>. <a href="#a668f4f3df1dbf8b253e8e036570cb384">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a665e880cc41e9fd97416741590e2e0d0">manifest</a> (Attributor &amp;A) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Hook for the Attributor to trigger the manifestation of the information represented by the abstract attribute in the LLVM-IR. <a href="#a665e880cc41e9fd97416741590e2e0d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ce53128a1643e2b6d4260d7abb1084c">isNoOpFence</a> (const FenceInst &amp;FI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to determine if <span class="doxyComputerOutput">FI</span> is a no-op given the information about its execution from <span class="doxyComputerOutput">ExecDomainAA</span>. <a href="#a0ce53128a1643e2b6d4260d7abb1084c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab408d969789cd06b4bde506160b80d1e">mergeInPredecessorBarriersAndAssumptions</a> (Attributor &amp;A, ExecutionDomainTy &amp;ED, const ExecutionDomainTy &amp;PredED)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge barrier and assumption information from <span class="doxyComputerOutput">PredED</span> into the successor <span class="doxyComputerOutput">ED</span>. <a href="#ab408d969789cd06b4bde506160b80d1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d1d88ed623962b62576733b8f474655">mergeInPredecessor</a> (Attributor &amp;A, ExecutionDomainTy &amp;ED, const ExecutionDomainTy &amp;PredED, bool InitialEdgeOnly=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge all information from <span class="doxyComputerOutput">PredED</span> into the successor <span class="doxyComputerOutput">ED</span>. <a href="#a6d1d88ed623962b62576733b8f474655">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad567ae138977391ddcc0d292749aecc8">handleCallees</a> (Attributor &amp;A, ExecutionDomainTy &amp;EntryBBED)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Accumulate information for the entry block in <span class="doxyComputerOutput">EntryBBED</span>. <a href="#ad567ae138977391ddcc0d292749aecc8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53429c521770c95bf0380a74711dd451">updateImpl</a> (Attributor &amp;A) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#adae4d3d2e4be96b506c572fcc4a8738a">AbstractAttribute::updateImpl</a>. <a href="#a53429c521770c95bf0380a74711dd451">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fdc6cad0c749330f186d0415048e2cd">isExecutedByInitialThreadOnly</a> (const BasicBlock &amp;BB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Query interface, see AAExecutionDomain {. <a href="#a0fdc6cad0c749330f186d0415048e2cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d53d8df2e0ea40eee8a7349563a9df7">isExecutedInAlignedRegion</a> (Attributor &amp;A, const Instruction &amp;I) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if the instruction <span class="doxyComputerOutput">I</span> is executed in an aligned region, that is, the synchronizing effects before and after <span class="doxyComputerOutput">I</span> are both aligned barriers. <a href="#a6d53d8df2e0ea40eee8a7349563a9df7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty">ExecutionDomainTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af36820c70ded6b35f465c9a34a5ddcce">getExecutionDomain</a> (const BasicBlock &amp;BB) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty">ExecutionDomainTy</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty">ExecutionDomainTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4af4803ab147e760b5206be86d02190d">getExecutionDomain</a> (const CallBase &amp;CB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the execution domain with which the call <span class="doxyComputerOutput">CB</span> is entered and the one with which it is left. <a href="#a4af4803ab147e760b5206be86d02190d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty">ExecutionDomainTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70fcabdd1145367166fe7bb3082e103c">getFunctionExecutionDomain</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty">ExecutionDomainTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae24a07850f18b8f5cd2a1fac4c32ee89">InterProceduralED</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping containing information about the function for other AAs. <a href="#ae24a07850f18b8f5cd2a1fac4c32ee89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty">ExecutionDomainTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c6820fc3cc855f918ad44ea0313a55d">BEDMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping containing information per block. <a href="#a0c6820fc3cc855f918ad44ea0313a55d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> *, 1, <a href="#a1ea0e0885759b6aefd8d04866cdac079">Direction</a> &gt;, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty">ExecutionDomainTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abff319bf95fffb0090cc73102910a113">CEDMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c512db8bd7fc2cc5bc7e4a7537510c7">AlignedBarriers</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/reversepostordertraversal">ReversePostOrderTraversal</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4000d003c03a1e65038b96814219aea4">RPOT</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fenceinst">FenceInst</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaae60780e4bc055679061d9ad2ca66f">NonNoOpFences</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collection of fences known to be non-no-opt. <a href="#afaae60780e4bc055679061d9ad2ca66f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e8065095902b6763ce9c78e1178816d">isInitialThreadOnlyEdge</a> (Attributor &amp;A, BranchInst *Edge, BasicBlock &amp;SuccessorBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#a2e8065095902b6763ce9c78e1178816d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c1be90f92103a73227a6e8a8fba3a99">setAndRecord</a> (bool &amp;R, bool V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set <span class="doxyComputerOutput">R</span> to \V and report true if that changed <span class="doxyComputerOutput">R</span>. <a href="#a6c1be90f92103a73227a6e8a8fba3a99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 2692 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Direction {#a1ea0e0885759b6aefd8d04866cdac079}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::Direction </td>
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
<td class="doxyEnumItemName">PRE<a id="a1ea0e0885759b6aefd8d04866cdac079a124fa7a00a55fdc530e1c73613d5664c"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">POST<a id="a1ea0e0885759b6aefd8d04866cdac079acf64c0a2f18300906a12b59966c52497"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 2968 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AAExecutionDomainFunction() {#abc69e1157f94e0127e9940b8d5bb72b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::AAExecutionDomainFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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



<p>Definition at line 2693 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/#acfdbd3ac33d408567173a5108d6fa8e1">llvm::AAExecutionDomain::AAExecutionDomain</a> and <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AAExecutionDomainFunction() {#a831f6cd2fcfc1b0e4f29527031a05e38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::~AAExecutionDomainFunction ()</td>
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



<p>Definition at line 2696 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Reference <a href="#a4000d003c03a1e65038b96814219aea4">RPOT</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAsStr() {#a9008361b1d158d70137eff54eded9483}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::getAsStr (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> * A)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function should return the "summarized" assumed state as string.</p>

<p>Definition at line 2704 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a> and <a href="#a0c6820fc3cc855f918ad44ea0313a55d">BEDMap</a>.</p>

</div>
</div>

### getExecutionDomain() {#af36820c70ded6b35f465c9a34a5ddcce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionDomainTy anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::getExecutionDomain (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2900 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0c6820fc3cc855f918ad44ea0313a55d">BEDMap</a> and <a href="/web-llvm/docs/api/structs/llvm/integerstatebase/#a160d75d0c1abdc58fe6a377f6f8ddd4f">llvm::IntegerStateBase&lt; bool, true, false &gt;::isValidState</a>.</p>

</div>
</div>

### getExecutionDomain() {#a4af4803ab147e760b5206be86d02190d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; ExecutionDomainTy, ExecutionDomainTy &gt; anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::getExecutionDomain (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the execution domain with which the call <span class="doxyComputerOutput">CB</span> is entered and the one with which it is left.</p>

<p>Definition at line 2906 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#abff319bf95fffb0090cc73102910a113">CEDMap</a>, <a href="/web-llvm/docs/api/structs/llvm/integerstatebase/#a160d75d0c1abdc58fe6a377f6f8ddd4f">llvm::IntegerStateBase&lt; bool, true, false &gt;::isValidState</a> and <a href="#a1ea0e0885759b6aefd8d04866cdac079a124fa7a00a55fdc530e1c73613d5664c">PRE</a>.</p>

</div>
</div>

### getFunctionExecutionDomain() {#a70fcabdd1145367166fe7bb3082e103c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionDomainTy anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::getFunctionExecutionDomain ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2911 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae24a07850f18b8f5cd2a1fac4c32ee89">InterProceduralED</a> and <a href="/web-llvm/docs/api/structs/llvm/integerstatebase/#a160d75d0c1abdc58fe6a377f6f8ddd4f">llvm::IntegerStateBase&lt; bool, true, false &gt;::isValidState</a>.</p>

</div>
</div>

### handleCallees() {#ad567ae138977391ddcc0d292749aecc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::handleCallees (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty">ExecutionDomainTy</a> &amp; EntryBBED)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Accumulate information for the entry block in <span class="doxyComputerOutput">EntryBBED</span>.</p>

<p>Definition at line 2821 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/#acfdbd3ac33d408567173a5108d6fa8e1">llvm::AAExecutionDomain::AAExecutionDomain</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>, <a href="#a0c6820fc3cc855f918ad44ea0313a55d">BEDMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty/#a296785357f6b429d8b0adf6be1068d83">llvm::AAExecutionDomain::ExecutionDomainTy::EncounteredNonLocalSideEffect</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a8936a7eb7c9151c46513b192053afb2e">llvm::IRPosition::function</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#afa339f4513a2704e8e2dadb6a92faab3">llvm::IRPosition::getAnchorScope</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty/#a00322b7e10aa3ab5ff88da464dcdd87d">llvm::AAExecutionDomain::ExecutionDomainTy::IsExecutedByInitialThreadOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#adbaec5588449adc75116f4cad3997a03">llvm::omp::isOpenMPKernel</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty/#a67e0a6ee379bd5b1b474c11641de68c4">llvm::AAExecutionDomain::ExecutionDomainTy::IsReachedFromAlignedBarrierOnly</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty/#ab8f2d578675f69c7f53f7dc822d5aa8e">llvm::AAExecutionDomain::ExecutionDomainTy::IsReachingAlignedBarrierOnly</a>, <a href="#a6d1d88ed623962b62576733b8f474655">mergeInPredecessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1a7951811e4b085cf68ed3dc3191f36405">llvm::OPTIONAL</a> and <a href="#a6c1be90f92103a73227a6e8a8fba3a99">setAndRecord</a>.</p>


<p>Referenced by <a href="#a53429c521770c95bf0380a74711dd451">updateImpl</a>.</p>

</div>
</div>

### initialize() {#a434c328cc87725efcfb56d78ca310e56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::initialize (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize the state with the information in the Attributor <span class="doxyComputerOutput">A</span>.</p>


<p>This function is called by the Attributor once all abstract attributes have been identified. It can and shall be used for task like:</p>


<ul class="doxyList ">
<li>identify existing knowledge in the IR and use it for the "known state"</li>
<li>perform any work that is not going to change over time, e.g., determine a subset of the IR, or attributes in-flight, that have to be looked at in the <span class="doxyComputerOutput">updateImpl</span> method.</li>
</ul>

<p>Definition at line 2698 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#afa339f4513a2704e8e2dadb6a92faab3">llvm::IRPosition::getAnchorScope</a> and <a href="#a4000d003c03a1e65038b96814219aea4">RPOT</a>.</p>

</div>
</div>

### isExecutedByInitialThreadOnly() {#a0fdc6cad0c749330f186d0415048e2cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::isExecutedByInitialThreadOnly (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Query interface, see AAExecutionDomain {.</p>

<p>Definition at line 2828 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0c6820fc3cc855f918ad44ea0313a55d">BEDMap</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#afa339f4513a2704e8e2dadb6a92faab3">llvm::IRPosition::getAnchorScope</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a> and <a href="/web-llvm/docs/api/structs/llvm/integerstatebase/#a160d75d0c1abdc58fe6a377f6f8ddd4f">llvm::IntegerStateBase&lt; bool, true, false &gt;::isValidState</a>.</p>


<p>Referenced by <a href="#a665e880cc41e9fd97416741590e2e0d0">manifest</a>.</p>

</div>
</div>

### isExecutedInAlignedRegion() {#a6d53d8df2e0ea40eee8a7349563a9df7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::isExecutedInAlignedRegion (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if the instruction <span class="doxyComputerOutput">I</span> is executed in an aligned region, that is, the synchronizing effects before and after <span class="doxyComputerOutput">I</span> are both aligned barriers.</p>


<p>This effectively means all threads execute <span class="doxyComputerOutput">I</span> together.</p>


<p>Definition at line 2835 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a5c512db8bd7fc2cc5bc7e4a7537510c7">AlignedBarriers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>, <a href="#a0c6820fc3cc855f918ad44ea0313a55d">BEDMap</a>, <a href="#abff319bf95fffb0090cc73102910a113">CEDMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#afa339f4513a2704e8e2dadb6a92faab3">llvm::IRPosition::getAnchorScope</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a169f0c26ef46161741fdd120a806f853">llvm::Function::getEntryBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a91bd28adea418a08cec78b72413d9d45">llvm::Instruction::getNextNonDebugInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a512494b857b0644c1f722531e3ee5495">llvm::Instruction::getPrevNonDebugInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/integerstatebase/#a160d75d0c1abdc58fe6a377f6f8ddd4f">llvm::IntegerStateBase&lt; bool, true, false &gt;::isValidState</a>, <a href="#a1ea0e0885759b6aefd8d04866cdac079acf64c0a2f18300906a12b59966c52497">POST</a>, <a href="#a1ea0e0885759b6aefd8d04866cdac079a124fa7a00a55fdc530e1c73613d5664c">PRE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>.</p>

</div>
</div>

### isNoOpFence() {#a0ce53128a1643e2b6d4260d7abb1084c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::isNoOpFence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/fenceinst">FenceInst</a> &amp; FI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function to determine if <span class="doxyComputerOutput">FI</span> is a no-op given the information about its execution from <span class="doxyComputerOutput">ExecDomainAA</span>.</p>

<p>Definition at line 2803 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/statewrapper/#aa83a3107fcf157e652c6be8fa548b893">llvm::StateWrapper&lt; BooleanState, AbstractAttribute &gt;::getState</a> and <a href="#afaae60780e4bc055679061d9ad2ca66f">NonNoOpFences</a>.</p>

</div>
</div>

### manifest() {#a665e880cc41e9fd97416741590e2e0d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::manifest (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Hook for the Attributor to trigger the manifestation of the information represented by the abstract attribute in the LLVM-IR.</p>


<p>\Return CHANGED if the IR was altered, otherwise UNCHANGED.</p>


<p>Definition at line 2723 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a5c512db8bd7fc2cc5bc7e4a7537510c7">AlignedBarriers</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty/#a04c0486cfcad87099745acf241d1ac60">llvm::AAExecutionDomain::ExecutionDomainTy::AlignedBarriers</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>, <a href="#a0c6820fc3cc855f918ad44ea0313a55d">BEDMap</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#abf73a826b5d6f739eb4af48ddf14c5b4">llvm::SmallPtrSetImpl&lt; PtrType &gt;::begin</a>, <a href="#abff319bf95fffb0090cc73102910a113">CEDMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3ae6b94e58bfd13b21bc786578d9f8ba4a">llvm::CHANGED</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp/#acfb84264e46f9a54287bee817f04e362">DisableOpenMPOptBarrierElimination</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#af8a50544090e81ac83601aff8f4b0142">llvm::SmallPtrSetImplBase::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty/#ad0b1dcaed2f92d7a201ea636e49a3d61">llvm::AAExecutionDomain::ExecutionDomainTy::EncounteredAssumes</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty/#a296785357f6b429d8b0adf6be1068d83">llvm::AAExecutionDomain::ExecutionDomainTy::EncounteredNonLocalSideEffect</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a7004354fbee1c8cd74ed9001915e1db5">llvm::SmallPtrSetImpl&lt; PtrType &gt;::end</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#afa339f4513a2704e8e2dadb6a92faab3">llvm::IRPosition::getAnchorScope</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6a66ebb3aa12757479a3c88de77d78f8">llvm::Instruction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-openmpopt-cpp-/#a87ab0eadf8a08e2fcd3e07d9529b6635">anonymous{OpenMPOpt.cpp}::hasFunctionEndAsUniqueSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="#a0fdc6cad0c749330f186d0415048e2cd">isExecutedByInitialThreadOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#adbaec5588449adc75116f4cad3997a03">llvm::omp::isOpenMPKernel</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty/#a67e0a6ee379bd5b1b474c11641de68c4">llvm::AAExecutionDomain::ExecutionDomainTy::IsReachedFromAlignedBarrierOnly</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="#a1ea0e0885759b6aefd8d04866cdac079a124fa7a00a55fdc530e1c73613d5664c">PRE</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp/#a01dcc1d7b3fe71c031ab52a3ee7e02f0">TAG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3a46335765005ff44b1fe1e38e5d2ddfcc">llvm::UNCHANGED</a>.</p>

</div>
</div>

### mergeInPredecessor() {#a6d1d88ed623962b62576733b8f474655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::mergeInPredecessor (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty">ExecutionDomainTy</a> &amp; ED, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty">ExecutionDomainTy</a> &amp; PredED, bool InitialEdgeOnly=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge all information from <span class="doxyComputerOutput">PredED</span> into the successor <span class="doxyComputerOutput">ED</span>.</p>


<p>If <span class="doxyComputerOutput">InitialEdgeOnly</span> is set, only the initial edge will enter the block represented by <span class="doxyComputerOutput">ED</span> from this predecessor.</p>


<p>Definition at line 2816 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty/#a5be8d3e5802f922f7755bfc3cb998164">llvm::AAExecutionDomain::ExecutionDomainTy::clearAssumeInstAndAlignedBarriers</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty/#a296785357f6b429d8b0adf6be1068d83">llvm::AAExecutionDomain::ExecutionDomainTy::EncounteredNonLocalSideEffect</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty/#a00322b7e10aa3ab5ff88da464dcdd87d">llvm::AAExecutionDomain::ExecutionDomainTy::IsExecutedByInitialThreadOnly</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty/#a67e0a6ee379bd5b1b474c11641de68c4">llvm::AAExecutionDomain::ExecutionDomainTy::IsReachedFromAlignedBarrierOnly</a>, <a href="#ab408d969789cd06b4bde506160b80d1e">mergeInPredecessorBarriersAndAssumptions</a> and <a href="#a6c1be90f92103a73227a6e8a8fba3a99">setAndRecord</a>.</p>


<p>Referenced by <a href="#ad567ae138977391ddcc0d292749aecc8">handleCallees</a> and <a href="#a53429c521770c95bf0380a74711dd451">updateImpl</a>.</p>

</div>
</div>

### mergeInPredecessorBarriersAndAssumptions() {#ab408d969789cd06b4bde506160b80d1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::mergeInPredecessorBarriersAndAssumptions (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty">ExecutionDomainTy</a> &amp; ED, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty">ExecutionDomainTy</a> &amp; PredED)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge barrier and assumption information from <span class="doxyComputerOutput">PredED</span> into the successor <span class="doxyComputerOutput">ED</span>.</p>

<p>Definition at line 2810 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty/#a2bc35214963d6a6cc5ec91c3316b4b24">llvm::AAExecutionDomain::ExecutionDomainTy::addAlignedBarrier</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty/#a0a5b953f4df64571686a601a932abd6d">llvm::AAExecutionDomain::ExecutionDomainTy::addAssumeInst</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty/#a04c0486cfcad87099745acf241d1ac60">llvm::AAExecutionDomain::ExecutionDomainTy::AlignedBarriers</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a> and <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty/#ad0b1dcaed2f92d7a201ea636e49a3d61">llvm::AAExecutionDomain::ExecutionDomainTy::EncounteredAssumes</a>.</p>


<p>Referenced by <a href="#a6d1d88ed623962b62576733b8f474655">mergeInPredecessor</a> and <a href="#a53429c521770c95bf0380a74711dd451">updateImpl</a>.</p>

</div>
</div>

### trackStatistics() {#a668f4f3df1dbf8b253e8e036570cb384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::trackStatistics ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#add85e4d78cefc67429904d7492aff9a4">AbstractAttribute::trackStatistics()</a>.</p>

<p>Definition at line 2721 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>

</div>
</div>

### updateImpl() {#a53429c521770c95bf0380a74711dd451}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::updateImpl (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#adae4d3d2e4be96b506c572fcc4a8738a">AbstractAttribute::updateImpl</a>.</p>

<p>Definition at line 2824 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/#acfdbd3ac33d408567173a5108d6fa8e1">llvm::AAExecutionDomain::AAExecutionDomain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a993ca650a85e8e69b8f7eaa4809c4862">llvm::Acquire</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a960fbd067612ca87e16d5dfdb12fe40a">llvm::AcquireRelease</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty/#a0a5b953f4df64571686a601a932abd6d">llvm::AAExecutionDomain::ExecutionDomainTy::addAssumeInst</a>, <a href="#a5c512db8bd7fc2cc5bc7e4a7537510c7">AlignedBarriers</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a85955f71af20254ae831687849a1a737a0e7b3ae5911d61bd79225d9bda18f625">llvm::AAMemoryLocation::ALL_LOCATIONS</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>, <a href="#a0c6820fc3cc855f918ad44ea0313a55d">BEDMap</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#aeef35bb007616add7418161b0313b56b">llvm::IRPosition::callsite_function</a>, <a href="#abff319bf95fffb0090cc73102910a113">CEDMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3ae6b94e58bfd13b21bc786578d9f8ba4a">llvm::CHANGED</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2d989cf6c0da10e436e1e95e380e0e09">llvm::CallBase::doesNotAccessMemory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty/#a296785357f6b429d8b0adf6be1068d83">llvm::AAExecutionDomain::ExecutionDomainTy::EncounteredNonLocalSideEffect</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a8936a7eb7c9151c46513b192053afb2e">llvm::IRPosition::function</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#afa339f4513a2704e8e2dadb6a92faab3">llvm::IRPosition::getAnchorScope</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#af5135f33d24ea71544db77941dab1e38">llvm::AbstractAttribute::getIRPosition</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a3287172f2d13af086e6d66364e8c6de3">llvm::Instruction::getNumSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#a1dfdcf6998ec28bfd2f8d2cdebc984a9">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getPrevNode</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="#ad567ae138977391ddcc0d292749aecc8">handleCallees</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="#ae24a07850f18b8f5cd2a1fac4c32ee89">InterProceduralED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/aanosync/#a79dea56e8e62d80d48cddd4319a55380">llvm::AANoSync::isAlignedBarrier</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty/#a00322b7e10aa3ab5ff88da464dcdd87d">llvm::AAExecutionDomain::ExecutionDomainTy::IsExecutedByInitialThreadOnly</a>, <a href="#a2e8065095902b6763ce9c78e1178816d">isInitialThreadOnlyEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#add4df090e923f2fe0dceeb0c60e5f74b">llvm::AA::isNoSyncInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#adbaec5588449adc75116f4cad3997a03">llvm::omp::isOpenMPKernel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#a9b9d4b530f90e36eede3c575ad1948ee">llvm::AA::isPotentiallyAffectedByBarrier</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty/#a67e0a6ee379bd5b1b474c11641de68c4">llvm::AAExecutionDomain::ExecutionDomainTy::IsReachedFromAlignedBarrierOnly</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/executiondomainty/#ab8f2d578675f69c7f53f7dc822d5aa8e">llvm::AAExecutionDomain::ExecutionDomainTy::IsReachingAlignedBarrierOnly</a>, <a href="#a6d1d88ed623962b62576733b8f474655">mergeInPredecessor</a>, <a href="#ab408d969789cd06b4bde506160b80d1e">mergeInPredecessorBarriersAndAssumptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a14194d0b2e6c6680067975517cd58eac">llvm::Monotonic</a>, <a href="#afaae60780e4bc055679061d9ad2ca66f">NonNoOpFences</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">llvm::NotAtomic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1a7951811e4b085cf68ed3dc3191f36405">llvm::OPTIONAL</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="#a1ea0e0885759b6aefd8d04866cdac079acf64c0a2f18300906a12b59966c52497">POST</a>, <a href="#a1ea0e0885759b6aefd8d04866cdac079a124fa7a00a55fdc530e1c73613d5664c">PRE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ab8e7b465df7c5979dc731d06e84ce2cf">llvm::Release</a>, <a href="#a4000d003c03a1e65038b96814219aea4">RPOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ae3b0fa849dbd758b450f98fcfde936a2">llvm::SequentiallyConsistent</a>, <a href="#a6c1be90f92103a73227a6e8a8fba3a99">setAndRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3a46335765005ff44b1fe1e38e5d2ddfcc">llvm::UNCHANGED</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a288d468c5e0969f26a310773eda65603">llvm::Unordered</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AlignedBarriers {#a5c512db8bd7fc2cc5bc7e4a7537510c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSetVector&lt;CallBase *, 16&gt; anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::AlignedBarriers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2973 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="#a6d53d8df2e0ea40eee8a7349563a9df7">isExecutedInAlignedRegion</a>, <a href="#a665e880cc41e9fd97416741590e2e0d0">manifest</a> and <a href="#a53429c521770c95bf0380a74711dd451">updateImpl</a>.</p>

</div>
</div>

### BEDMap {#a0c6820fc3cc855f918ad44ea0313a55d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const BasicBlock *, ExecutionDomainTy&gt; anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::BEDMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mapping containing information per block.</p>

<p>Definition at line 2970 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="#a9008361b1d158d70137eff54eded9483">getAsStr</a>, <a href="#af36820c70ded6b35f465c9a34a5ddcce">getExecutionDomain</a>, <a href="#ad567ae138977391ddcc0d292749aecc8">handleCallees</a>, <a href="#a0fdc6cad0c749330f186d0415048e2cd">isExecutedByInitialThreadOnly</a>, <a href="#a6d53d8df2e0ea40eee8a7349563a9df7">isExecutedInAlignedRegion</a>, <a href="#a665e880cc41e9fd97416741590e2e0d0">manifest</a> and <a href="#a53429c521770c95bf0380a74711dd451">updateImpl</a>.</p>

</div>
</div>

### CEDMap {#abff319bf95fffb0090cc73102910a113}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;PointerIntPair&lt;const CallBase *, 1, Direction&gt;, ExecutionDomainTy&gt; anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::CEDMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2972 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="#a4af4803ab147e760b5206be86d02190d">getExecutionDomain</a>, <a href="#a6d53d8df2e0ea40eee8a7349563a9df7">isExecutedInAlignedRegion</a>, <a href="#a665e880cc41e9fd97416741590e2e0d0">manifest</a> and <a href="#a53429c521770c95bf0380a74711dd451">updateImpl</a>.</p>

</div>
</div>

### InterProceduralED {#ae24a07850f18b8f5cd2a1fac4c32ee89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionDomainTy anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::InterProceduralED</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mapping containing information about the function for other AAs.</p>

<p>Definition at line 2966 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="#a70fcabdd1145367166fe7bb3082e103c">getFunctionExecutionDomain</a> and <a href="#a53429c521770c95bf0380a74711dd451">updateImpl</a>.</p>

</div>
</div>

### NonNoOpFences {#afaae60780e4bc055679061d9ad2ca66f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const FenceInst *, 8&gt; anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::NonNoOpFences</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collection of fences known to be non-no-opt.</p>


<p>All fences not in this set can be assumed no-opt.</p>


<p>Definition at line 2986 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="#a0ce53128a1643e2b6d4260d7abb1084c">isNoOpFence</a> and <a href="#a53429c521770c95bf0380a74711dd451">updateImpl</a>.</p>

</div>
</div>

### RPOT {#a4000d003c03a1e65038b96814219aea4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReversePostOrderTraversal&lt;Function *&gt;* anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::RPOT = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2975 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="#a434c328cc87725efcfb56d78ca310e56">initialize</a>, <a href="#a53429c521770c95bf0380a74711dd451">updateImpl</a> and <a href="#a831f6cd2fcfc1b0e4f29527031a05e38">~AAExecutionDomainFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isInitialThreadOnlyEdge() {#a2e8065095902b6763ce9c78e1178816d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::isInitialThreadOnlyEdge (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> * Edge, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; SuccessorBB)</td>
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

<p>}</p>

<p>Definition at line 2920 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/openmpopt/#a652b7ff39d88ac67e35d0955ac906292">anonymous{OpenMPOpt.cpp}::OpenMPOpt::getCallIfRegularCall</a>, <a href="/web-llvm/docs/api/namespaces/kernelinfo/#afc35ca85aef2e06a527c9edfe484eb56">KernelInfo::getKernelEnvironementFromKernelInitCB</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa8f4be0661aa64f5b1f20b15e93bb403">llvm::ConstantInt::getSExtValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="/web-llvm/docs/api/namespaces/llvm/omp/#aa0c0d79dafb0d22308ce48808689f430afa583a38ff705195c9bce9dec0c5eff8">llvm::omp::OMP_TGT_EXEC_MODE_GENERIC</a>.</p>


<p>Referenced by <a href="#a53429c521770c95bf0380a74711dd451">updateImpl</a>.</p>

</div>
</div>

### setAndRecord() {#a6c1be90f92103a73227a6e8a8fba3a99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::setAndRecord (bool &amp; R, bool V)</td>
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

<p>Set <span class="doxyComputerOutput">R</span> to \V and report true if that changed <span class="doxyComputerOutput">R</span>.</p>

<p>Definition at line 2978 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a>.</p>


<p>Referenced by <a href="#ad567ae138977391ddcc0d292749aecc8">handleCallees</a>, <a href="#a6d1d88ed623962b62576733b8f474655">mergeInPredecessor</a> and <a href="#a53429c521770c95bf0380a74711dd451">updateImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/openmpopt-cpp">OpenMPOpt.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
