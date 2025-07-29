---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AssignmentTrackingLowering` Class

<p><a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering">AssignmentTrackingLowering</a> encapsulates a dataflow analysis over a function that interprets assignment tracking debug info metadata and stores in IR to create a map of variable locations. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e0b2146e9115e385d8e406b6c36e645">AssignRecord</a> = <a href="/web-llvm/docs/api/classes/llvm/pointerunion">PointerUnion</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgassignintrinsic">DbgAssignIntrinsic</a> *, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An abstraction of the assignment of a value to a variable or memory location. <a href="#a6e0b2146e9115e385d8e406b6c36e645">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecd3fbed2e4d7501952b5de23ba8aba8">AssignmentMap</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/assignment">Assignment</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afadbf47f53cfe3d4eb25a3cb1e53b19d">LocMap</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#a4012a71c02f4a13c5234aea48e772f4c">LocKind</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ff60cdc2be1ee891c876f458018fd1c">OverlapMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dcaf963c14e849c62941b7f402bf74e">UntaggedStoreAssignmentMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a>, <a href="/web-llvm/docs/api/structs/llvm/at/assignmentinfo">at::AssignmentInfo</a> &gt; &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1a71f3e9fc332d4fae9351111e97486">InstInsertMap</a> = <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a6c7f6b65820380603c12c83d4d3b620c">VarLocInsertPt</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/varlocinfo">VarLocInfo</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">LocKind { <a href="#a4012a71c02f4a13c5234aea48e772f4c">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The kind of location in use for a variable, where Mem is the stack home, Val is an SSA value or const, and None means that there is not one single kind (either because there are multiple or because there is none; it may prove useful to split this into two values in the future). <a href="#a4012a71c02f4a13c5234aea48e772f4c">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14796ed9d9b5b6770e2a62108feca587">AssignmentTrackingLowering</a> (Function &amp;Fn, const DataLayout &amp;Layout, const DenseSet&lt; DebugAggregate &gt; *VarsWithStackSlot)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9db16f6b49d380b76183877d54b42c5c">run</a> (FunctionVarLocsBuilder *FnVarLocs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run the analysis, adding variable location info to <span class="doxyComputerOutput">FnVarLocs</span>. <a href="#a9db16f6b49d380b76183877d54b42c5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a81d863ec17163a5dcedc09cb1a48aadf">emitDbgValue</a> (AssignmentTrackingLowering::LocKind Kind, const T Source, VarLocInsertPt After)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fcbe6b3e2238d2527750fb9229641cb">resetInsertionPoint</a> (Instruction &amp;After)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear the location definitions currently cached for insertion after /p After. <a href="#a0fcbe6b3e2238d2527750fb9229641cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3db1e9c5375ffd29742c0fecdc8acedc">resetInsertionPoint</a> (DbgVariableRecord &amp;After)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3ff0c30e3418026bec378dcf3094951">emitDbgValue</a> (LocKind Kind, AssignRecord Source, VarLocInsertPt After)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7c44df02806cf6f4abb1e57fac4a5774">emitDbgValue</a> (LocKind Kind, const T Source, VarLocInsertPt After)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a9ba2a4c1d82ad44e9d75af9c304fc1">getVariableID</a> (const DebugVariable &amp;Var)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0a599e9e9a2ec3e762ac2a1ff3f6801">join</a> (const BasicBlock &amp;BB, const SmallPtrSet&lt; BasicBlock *, 16 &gt; &amp;Visited)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Join the LiveOut values of preds that are contained in <span class="doxyComputerOutput">Visited</span> into LiveIn[BB]. <a href="#af0a599e9e9a2ec3e762ac2a1ff3f6801">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7a4ca3a25308251fca56b212108ab2c">process</a> (BasicBlock &amp;BB, BlockInfo *LiveSet)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> the instructions in <span class="doxyComputerOutput">BB</span> updating <span class="doxyComputerOutput">LiveSet</span> along the way. <a href="#af7a4ca3a25308251fca56b212108ab2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a932045eceb64e8070ec4058d915c79ec">setLocKind</a> (BlockInfo *LiveSet, VariableID Var, LocKind K)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the <a href="#a4012a71c02f4a13c5234aea48e772f4c">LocKind</a> for <span class="doxyComputerOutput">Var</span>. <a href="#a932045eceb64e8070ec4058d915c79ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a4012a71c02f4a13c5234aea48e772f4c">LocKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaa9406d8d3ceb2831508d9a3af47eb1">getLocKind</a> (BlockInfo *LiveSet, VariableID Var)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the live <a href="#a4012a71c02f4a13c5234aea48e772f4c">LocKind</a> for a <span class="doxyComputerOutput">Var</span>. <a href="#aaaa9406d8d3ceb2831508d9a3af47eb1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1748ba335a579a8166341235b4e07504">hasVarWithAssignment</a> (BlockInfo *LiveSet, BlockInfo::AssignmentKind Kind, VariableID Var, const Assignment &amp;AV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">Var</span> has an assignment in <span class="doxyComputerOutput">M</span> matching <span class="doxyComputerOutput">AV</span>. <a href="#a1748ba335a579a8166341235b4e07504">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add36cc320c73ceca3c4b781d2632e62d">getContainedFragments</a> (VariableID Var) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the set of VariableIDs corresponding the fragments contained fully within the variable/fragment <span class="doxyComputerOutput">Var</span>. <a href="#add36cc320c73ceca3c4b781d2632e62d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20f6564be46165cd2d8c7c931ca01f15">touchFragment</a> (VariableID Var)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark <span class="doxyComputerOutput">Var</span> as having been touched this frame. <a href="#a20f6564be46165cd2d8c7c931ca01f15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dc095d5a7ebf04bdcee6c8bbfdc0c0c">emitPromotedVarLocs</a> (FunctionVarLocsBuilder *FnVarLocs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit info for variables that are fully promoted. <a href="#a8dc095d5a7ebf04bdcee6c8bbfdc0c0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac39d04e9015d4b22203bdc7878a5b411">TrackedVariablesVectorSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The highest numbered <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a> for partially promoted variables plus 1, the values for which start at 1. <a href="#ac39d04e9015d4b22203bdc7878a5b411">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0ff60cdc2be1ee891c876f458018fd1c">OverlapMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eefa7f711d818fe8df07e5af7f9a35e">VarContains</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map a variable to the set of variables that it fully contains. <a href="#a0eefa7f711d818fe8df07e5af7f9a35e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0dcaf963c14e849c62941b7f402bf74e">UntaggedStoreAssignmentMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add6b4e5ace0120a7aa432375cd646c7f">UntaggedStoreVars</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map untagged stores to the variable fragments they assign to. <a href="#add6b4e5ace0120a7aa432375cd646c7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">InstInsertMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11aecf12030437ee0754dc89b45122d4">InsertBeforeMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace3fb6446346e99d5e1f996d6691f86c">Fn</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6dd837818886caa416388cb894e0617">Layout</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a05c5b2328f38cb1affebb8ad4ab6fe40">DebugAggregate</a> &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ce4e3e0b2e8283d365bfac025630623">VarsWithStackSlot</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/functionvarlocsbuilder">FunctionVarLocsBuilder</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03de30a67feb92759fbcbbdcd0f3e151">FnVarLocs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, BlockInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42dd67983e1e57ba55bb4547f5e0098a">LiveIn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, BlockInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030d7cd52be1827efbb975ef3b6884c4">LiveOut</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7a33f46af3ed06d248cca47b81f0b2f">VarsTouchedThisFrame</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for process methods to track variables touched each frame. <a href="#aa7a33f46af3ed06d248cca47b81f0b2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a05c5b2328f38cb1affebb8ad4ab6fe40">DebugAggregate</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93d689c2128cdf73067ce441fd3337c6">NotAlwaysStackHomed</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of variables that sometimes are not located in their stack home. <a href="#a93d689c2128cdf73067ce441fd3337c6">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab415c1f08b41ea0367bdde0bc900f2f3">mapsAreEqual</a> (const BitVector &amp;Mask, const AssignmentMap &amp;A, const AssignmentMap &amp;B)</td>
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

## joinMethods Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">BlockInfo</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e3dea86b716ecd08aec5804e14bf632">joinBlockInfo</a> (const BlockInfo &amp;A, const BlockInfo &amp;B)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a4012a71c02f4a13c5234aea48e772f4c">LocKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf5287e05f6fc042184d45a9d60a8ed6">joinKind</a> (LocKind A, LocKind B)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/assignment">Assignment</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a284bde494a758f137ae9aadc3eaf0dbf">joinAssignment</a> (const Assignment &amp;A, const Assignment &amp;B)</td>
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

## processMethods Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47f512f6497daf8ba0be6476d70b90d7">processNonDbgInstruction</a> (Instruction &amp;I, BlockInfo *LiveSet)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59bb8432b7c3837317cc521c69ff06f6">processDbgInstruction</a> (DbgInfoIntrinsic &amp;I, BlockInfo *LiveSet)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a1f2f4bbbe8a0c19a6b96343e2fe826">processTaggedInstruction</a> (Instruction &amp;I, BlockInfo *LiveSet)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <span class="doxyComputerOutput">LiveSet</span> after encountering an instruction with a <a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> attachment, <span class="doxyComputerOutput">I</span>. <a href="#a8a1f2f4bbbe8a0c19a6b96343e2fe826">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbb525e882e3f6d0bf70f9ea18565393">processUntaggedInstruction</a> (Instruction &amp;I, BlockInfo *LiveSet)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <span class="doxyComputerOutput">LiveSet</span> after encountering an instruciton without a <a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> attachment, <span class="doxyComputerOutput">I</span>. <a href="#abbb525e882e3f6d0bf70f9ea18565393">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af22058985c8fdfd518da9118f5aa1bce">processDbgAssign</a> (AssignRecord Assign, BlockInfo *LiveSet)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab04cf251f137dd30b8d6da9ef2fb6694">processDbgVariableRecord</a> (DbgVariableRecord &amp;DVR, BlockInfo *LiveSet)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2a8586109e219243dc14ea0fef3e3c0">processDbgValue</a> (PointerUnion&lt; DbgValueInst *, DbgVariableRecord * &gt; DbgValueRecord, BlockInfo *LiveSet)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7490ef214b500a29b5125bac0bdbdf8b">addMemDef</a> (BlockInfo *LiveSet, VariableID Var, const Assignment &amp;AV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an assignment to memory for the variable /p Var. <a href="#a7490ef214b500a29b5125bac0bdbdf8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cbb8139150f8f691c89fb73658f92c9">addDbgDef</a> (BlockInfo *LiveSet, VariableID Var, const Assignment &amp;AV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an assignment to the variable /p Var. <a href="#a7cbb8139150f8f691c89fb73658f92c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering">AssignmentTrackingLowering</a> encapsulates a dataflow analysis over a function that interprets assignment tracking debug info metadata and stores in IR to create a map of variable locations.</p>

<p>Definition at line 990 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### AssignmentMap {#aecd3fbed2e4d7501952b5de23ba8aba8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::AssignmentMap =  SmallVector&lt;Assignment&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1100 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### AssignRecord {#a6e0b2146e9115e385d8e406b6c36e645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::AssignRecord =  PointerUnion&lt;DbgAssignIntrinsic *, DbgVariableRecord *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An abstraction of the assignment of a value to a variable or memory location.</p>


<p>An <a href="/web-llvm/docs/api/structs/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/assignment">Assignment</a> is Known or NoneOrPhi. A Known <a href="/web-llvm/docs/api/structs/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/assignment">Assignment</a> means we have a <a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> ptr that represents it. NoneOrPhi means that we don't (or can't) know the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the last assignment that took place.</p>


<p>The <a href="/web-llvm/docs/api/structs/status">Status</a> of the <a href="/web-llvm/docs/api/structs/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/assignment">Assignment</a> (Known or NoneOrPhi) is another join-semilattice. The partial order is: NoneOrPhi &gt; Known {id_0, id_1, ...id_N}</p>


<p>i.e. for all values x and y where x != y: join(x, x) = x join(x, y) = NoneOrPhi</p>


<p>Definition at line 1031 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### LocMap {#afadbf47f53cfe3d4eb25a3cb1e53b19d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::LocMap =  SmallVector&lt;LocKind&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1101 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### OverlapMap {#a0ff60cdc2be1ee891c876f458018fd1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::OverlapMap =  DenseMap&lt;VariableID, SmallVector&lt;VariableID&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1102 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### UntaggedStoreAssignmentMap {#a0dcaf963c14e849c62941b7f402bf74e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::UntaggedStoreAssignmentMap = 
      DenseMap&lt;const Instruction *,
               SmallVector&lt;std::pair&lt;VariableID, at::AssignmentInfo&gt;&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1103 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### InstInsertMap {#ac1a71f3e9fc332d4fae9351111e97486}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::InstInsertMap =  MapVector&lt;VarLocInsertPt, SmallVector&lt;VarLocInfo&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1118 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### LocKind {#a4012a71c02f4a13c5234aea48e772f4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::LocKind </td>
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

<p>The kind of location in use for a variable, where Mem is the stack home, Val is an SSA value or const, and None means that there is not one single kind (either because there are multiple or because there is none; it may prove useful to split this into two values in the future).</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Mem<a id="a4012a71c02f4a13c5234aea48e772f4cadba5553473d129a7985fb532dc249ff4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Val<a id="a4012a71c02f4a13c5234aea48e772f4ca5988c20a047cfe063999787584b0aca7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">None<a id="a4012a71c02f4a13c5234aea48e772f4ca6adf97f83acf6453d4a6a4b1070f3754"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p><a href="#a4012a71c02f4a13c5234aea48e772f4c">LocKind</a> is a join-semilattice with the partial order: None &gt; Mem, Val</p>


<p>i.e. join(Mem, Mem) = Mem join(Val, Val) = Val join(Mem, Val) = None join(None, Mem) = None join(None, Val) = None join(None, None) = None</p>


<p>Note: the order is not <span class="doxyComputerOutput">None &gt; Val &gt; Mem</span> because we're using <a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> to name assignments and are not tracking the actual stored values. Therefore currently there's no way to ensure that Mem values and Val values are the same. This could be a future extension, though it's not clear that many additional locations would be recovered that way in practice as the likelihood of this sitation arising naturally seems incredibly low.</p>


<p>Definition at line 1015 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AssignmentTrackingLowering() {#a14796ed9d9b5b6770e2a62108feca587}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::AssignmentTrackingLowering (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; Layout, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a05c5b2328f38cb1affebb8ad4ab6fe40">DebugAggregate</a> &gt; * VarsWithStackSlot)</td>
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



<p>Definition at line 1389 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitDbgValue() {#a81d863ec17163a5dcedc09cb1a48aadf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::emitDbgValue (<a href="#a4012a71c02f4a13c5234aea48e772f4c">AssignmentTrackingLowering::LocKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T Source, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a6c7f6b65820380603c12c83d4d3b620c">VarLocInsertPt</a> After)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1535 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa7bfcadb5535fe8aad5032762b7bfe159">After</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#ab89ede590f1a89ea1b5b9cfd422d7c86">CastToDbgAssign</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#ab2fc167f75191e1d22e12e8e382605bb">llvm::DIExpression::createFragmentExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/structs/llvm/varlocinfo/#ad7e310409e444bad60535cf956972194">llvm::VarLocInfo::DL</a>, <a href="/web-llvm/docs/api/structs/llvm/varlocinfo/#a2db7bf8bbe7f16fcee0e9f21aa87fe03">llvm::VarLocInfo::Expr</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata/#a53fc78b63202142110d0e86dd1a71fbe">llvm::ValueAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a7cc5f1632a4c520497898439c17dc026">llvm::DIExpression::getFragmentInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a05eb84c8f630be406f61761013146574">getNextNode</a>, <a href="#a4012a71c02f4a13c5234aea48e772f4cadba5553473d129a7985fb532dc249ff4">Mem</a>, <a href="#a4012a71c02f4a13c5234aea48e772f4ca6adf97f83acf6453d4a6a4b1070f3754">None</a>, <a href="#a4012a71c02f4a13c5234aea48e772f4ca5988c20a047cfe063999787584b0aca7">Val</a>, <a href="/web-llvm/docs/api/structs/llvm/varlocinfo/#a95406039aa97abe00aa3b1265d846455">llvm::VarLocInfo::Values</a>, <a href="/web-llvm/docs/api/structs/llvm/varlocinfo/#af70494f348808c889f07f71f43cd28ec">llvm::VarLocInfo::VariableID</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a0b1eb53b30ddeb8ebdccc60c0837300f">walkToAllocaAndPrependOffsetDeref</a>.</p>

</div>
</div>

### run() {#a9db16f6b49d380b76183877d54b42c5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AssignmentTrackingLowering::run (<a href="/web-llvm/docs/api/classes/functionvarlocsbuilder">FunctionVarLocsBuilder</a> * FnVarLocs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run the analysis, adding variable location info to <span class="doxyComputerOutput">FnVarLocs</span>.</p>


<p>Returns true if any variable locations have been added to FnVarLocs.</p>


<p>Definition at line 1394 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a4ad92667dcad9ad33a52a2e1c505a03a">buildOverlapMapAndRecordDeclares</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/at/#a11e115c0bc63e73df009e5117821d230">llvm::at::deleteAll</a>, <a href="/web-llvm/docs/api/structs/llvm/varlocinfo/#ad7e310409e444bad60535cf956972194">llvm::VarLocInfo::DL</a>, <a href="/web-llvm/docs/api/structs/llvm/varlocinfo/#a2db7bf8bbe7f16fcee0e9f21aa87fe03">llvm::VarLocInfo::Expr</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/debugvariable/#a58e53986006a2e7d95385fe4e633fb2e">llvm::DebugVariable::getInlinedAt</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a1b59c8fe81267b338774bf6c542f90ee">llvm::DIExpression::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/debugvariable/#af2ca096ab72c055f6c2c7e3ffbe5d6bf">llvm::DebugVariable::getVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/rawlocationwrapper/#acaf135b0c3da7778910e043864bcf1ac">llvm::RawLocationWrapper::hasArgList</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#af0952d00328de72e269c7f157a015e1c">MaxNumBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eafa1fbb1e3943c2c6c560247ac8f9289780">llvm::Simple</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a3c6397a9b21812183d69e90c3dac17f9">llvm::DIExpression::startsWithDeref</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>, <a href="/web-llvm/docs/api/structs/llvm/varlocinfo/#a95406039aa97abe00aa3b1265d846455">llvm::VarLocInfo::Values</a> and <a href="/web-llvm/docs/api/structs/llvm/varlocinfo/#af70494f348808c889f07f71f43cd28ec">llvm::VarLocInfo::VariableID</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### emitDbgValue() {#af3ff0c30e3418026bec378dcf3094951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::emitDbgValue (<a href="#a4012a71c02f4a13c5234aea48e772f4c">LocKind</a> Kind, <a href="#a6e0b2146e9115e385d8e406b6c36e645">AssignRecord</a> Source, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a6c7f6b65820380603c12c83d4d3b620c">VarLocInsertPt</a> After)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1131 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### emitDbgValue() {#a7c44df02806cf6f4abb1e57fac4a5774}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::emitDbgValue (<a href="#a4012a71c02f4a13c5234aea48e772f4c">LocKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T Source, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a6c7f6b65820380603c12c83d4d3b620c">VarLocInsertPt</a> After)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1133 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### emitPromotedVarLocs() {#a8dc095d5a7ebf04bdcee6c8bbfdc0c0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AssignmentTrackingLowering::emitPromotedVarLocs (<a href="/web-llvm/docs/api/classes/functionvarlocsbuilder">FunctionVarLocsBuilder</a> * FnVarLocs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit info for variables that are fully promoted.</p>

<p>Definition at line 1386 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### getContainedFragments() {#add36cc320c73ceca3c4b781d2632e62d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; VariableID &gt; AssignmentTrackingLowering::getContainedFragments (<a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a> Var)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the set of VariableIDs corresponding the fragments contained fully within the variable/fragment <span class="doxyComputerOutput">Var</span>.</p>

<p>Definition at line 1379 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### getLocKind() {#aaaa9406d8d3ceb2831508d9a3af47eb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssignmentTrackingLowering::LocKind AssignmentTrackingLowering::getLocKind (BlockInfo * LiveSet, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a> Var)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the live <a href="#a4012a71c02f4a13c5234aea48e772f4c">LocKind</a> for a <span class="doxyComputerOutput">Var</span>.</p>


<p>Requires addMemDef or addDbgDef to have been called for <span class="doxyComputerOutput">Var</span> first.</p>


<p>Definition at line 1373 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### getVariableID() {#a6a9ba2a4c1d82ad44e9d75af9c304fc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VariableID anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::getVariableID (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> &amp; Var)</td>
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



<p>Definition at line 1309 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### hasVarWithAssignment() {#a1748ba335a579a8166341235b4e07504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AssignmentTrackingLowering::hasVarWithAssignment (BlockInfo * LiveSet, BlockInfo::AssignmentKind Kind, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a> Var, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/assignment">Assignment</a> &amp; AV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if <span class="doxyComputerOutput">Var</span> has an assignment in <span class="doxyComputerOutput">M</span> matching <span class="doxyComputerOutput">AV</span>.</p>

<p>Definition at line 1375 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### join() {#af0a599e9e9a2ec3e762ac2a1ff3f6801}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AssignmentTrackingLowering::join (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 16 &gt; &amp; Visited)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Join the LiveOut values of preds that are contained in <span class="doxyComputerOutput">Visited</span> into LiveIn[BB].</p>


<p>Return True if LiveIn[BB] has changed as a result. LiveIn[BB] values monotonically increase. See the join methods  documentation for more info.</p>


<p>Definition at line 1317 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### process() {#af7a4ca3a25308251fca56b212108ab2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssignmentTrackingLowering::process (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, BlockInfo * LiveSet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> the instructions in <span class="doxyComputerOutput">BB</span> updating <span class="doxyComputerOutput">LiveSet</span> along the way.</p>


<p><span class="doxyComputerOutput">LiveSet</span> must be initialized with the current live-in locations before calling this.</p>


<p>Definition at line 1345 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### resetInsertionPoint() {#a0fcbe6b3e2238d2527750fb9229641cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssignmentTrackingLowering::resetInsertionPoint (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; After)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clear the location definitions currently cached for insertion after /p After.</p>

<p>Definition at line 1122 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### resetInsertionPoint() {#a3db1e9c5375ffd29742c0fecdc8acedc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssignmentTrackingLowering::resetInsertionPoint (<a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> &amp; After)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1123 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### setLocKind() {#a932045eceb64e8070ec4058d915c79ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssignmentTrackingLowering::setLocKind (BlockInfo * LiveSet, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a> Var, <a href="#a4012a71c02f4a13c5234aea48e772f4c">LocKind</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the <a href="#a4012a71c02f4a13c5234aea48e772f4c">LocKind</a> for <span class="doxyComputerOutput">Var</span>.</p>

<p>Definition at line 1370 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### touchFragment() {#a20f6564be46165cd2d8c7c931ca01f15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssignmentTrackingLowering::touchFragment (<a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a> Var)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark <span class="doxyComputerOutput">Var</span> as having been touched this frame.</p>


<p>Note, this applies only to the exact fragment <span class="doxyComputerOutput">Var</span> and not to any fragments contained within.</p>


<p>Definition at line 1383 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Fn {#ace3fb6446346e99d5e1f996d6691f86c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::Fn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1296 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### FnVarLocs {#a03de30a67feb92759fbcbbdcd0f3e151}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionVarLocsBuilder* anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::FnVarLocs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1299 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### InsertBeforeMap {#a11aecf12030437ee0754dc89b45122d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstInsertMap anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::InsertBeforeMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1119 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### Layout {#ae6dd837818886caa416388cb894e0617}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::Layout</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1297 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### LiveIn {#a42dd67983e1e57ba55bb4547f5e0098a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const BasicBlock *, BlockInfo&gt; anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::LiveIn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1300 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### LiveOut {#a030d7cd52be1827efbb975ef3b6884c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const BasicBlock *, BlockInfo&gt; anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::LiveOut</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1301 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### NotAlwaysStackHomed {#a93d689c2128cdf73067ce441fd3337c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;DebugAggregate&gt; anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::NotAlwaysStackHomed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of variables that sometimes are not located in their stack home.</p>

<p>Definition at line 1307 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### TrackedVariablesVectorSize {#ac39d04e9015d4b22203bdc7878a5b411}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::TrackedVariablesVectorSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The highest numbered <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a> for partially promoted variables plus 1, the values for which start at 1.</p>

<p>Definition at line 1110 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### UntaggedStoreVars {#add6b4e5ace0120a7aa432375cd646c7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UntaggedStoreAssignmentMap anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::UntaggedStoreVars</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map untagged stores to the variable fragments they assign to.</p>


<p>Used by processUntaggedInstruction.</p>


<p>Definition at line 1115 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### VarContains {#a0eefa7f711d818fe8df07e5af7f9a35e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OverlapMap anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::VarContains</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map a variable to the set of variables that it fully contains.</p>

<p>Definition at line 1112 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### VarsTouchedThisFrame {#aa7a33f46af3ed06d248cca47b81f0b2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;VariableID&gt; anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::VarsTouchedThisFrame</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper for process methods to track variables touched each frame.</p>

<p>Definition at line 1304 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### VarsWithStackSlot {#a3ce4e3e0b2e8283d365bfac025630623}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DenseSet&lt;DebugAggregate&gt;* anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::VarsWithStackSlot</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1298 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### mapsAreEqual() {#ab415c1f08b41ea0367bdde0bc900f2f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::mapsAreEqual (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; Mask, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aecd3fbed2e4d7501952b5de23ba8aba8">AssignmentMap</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aecd3fbed2e4d7501952b5de23ba8aba8">AssignmentMap</a> &amp; B)</td>
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



<p>Definition at line 1135 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## joinMethods



<p>Functions that implement <span class="doxyComputerOutput">join</span> (the least upper bound) for the join-semilattice types used in the dataflow.</p>


<p>There is an explicit bottom value (⊥) for some types and and explicit top value (⊤) for all types. By definition:</p>



<pre><code>Join(A, B) &gt;= A &amp;&amp; Join(A, B) &gt;= B
Join(A, ⊥) = A
Join(A, ⊤) = ⊤
</code></pre>


<p>These invariants are important for monotonicity.</p>


<p>For the map-type functions, all unmapped keys in an empty map are associated with a bottom value (⊥). This represents their values being unknown. Unmapped keys in non-empty maps (joining two maps with a key only present in one) represents either a variable going out of scope or dropped debug info. It is assumed the key is associated with a top value (⊤) in this case (unknown location / assignment).</p>


### joinAssignment {#a284bde494a758f137ae9aadc3eaf0dbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssignmentTrackingLowering::Assignment AssignmentTrackingLowering::joinAssignment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/assignment">Assignment</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/assignment">Assignment</a> &amp; B)</td>
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



<p>Definition at line 1338 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### joinBlockInfo {#a9e3dea86b716ecd08aec5804e14bf632}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssignmentTrackingLowering::BlockInfo AssignmentTrackingLowering::joinBlockInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BlockInfo &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BlockInfo &amp; B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1339 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### joinKind {#adf5287e05f6fc042184d45a9d60a8ed6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssignmentTrackingLowering::LocKind AssignmentTrackingLowering::joinKind (<a href="#a4012a71c02f4a13c5234aea48e772f4c">LocKind</a> A, <a href="#a4012a71c02f4a13c5234aea48e772f4c">LocKind</a> B)</td>
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



<p>Definition at line 1337 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## processMethods



<p>Methods to process instructions in order to update the LiveSet (current location information).</p>


### addDbgDef {#a7cbb8139150f8f691c89fb73658f92c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssignmentTrackingLowering::addDbgDef (BlockInfo * LiveSet, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a> Var, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/assignment">Assignment</a> &amp; AV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an assignment to the variable /p Var.</p>

<p>Definition at line 1366 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### addMemDef {#a7490ef214b500a29b5125bac0bdbdf8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssignmentTrackingLowering::addMemDef (BlockInfo * LiveSet, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15">VariableID</a> Var, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/assignment">Assignment</a> &amp; AV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an assignment to memory for the variable /p Var.</p>

<p>Definition at line 1364 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### processDbgAssign {#af22058985c8fdfd518da9118f5aa1bce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssignmentTrackingLowering::processDbgAssign (<a href="#a6e0b2146e9115e385d8e406b6c36e645">AssignRecord</a> Assign, BlockInfo * LiveSet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1358 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### processDbgInstruction {#a59bb8432b7c3837317cc521c69ff06f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssignmentTrackingLowering::processDbgInstruction (<a href="/web-llvm/docs/api/classes/llvm/dbginfointrinsic">DbgInfoIntrinsic</a> &amp; I, BlockInfo * LiveSet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1351 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### processDbgValue {#ac2a8586109e219243dc14ea0fef3e3c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssignmentTrackingLowering::processDbgValue (<a href="/web-llvm/docs/api/classes/llvm/pointerunion">PointerUnion</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgvalueinst">DbgValueInst</a> *, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> * &gt; DbgValueRecord, BlockInfo * LiveSet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1360 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### processDbgVariableRecord {#ab04cf251f137dd30b8d6da9ef2fb6694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssignmentTrackingLowering::processDbgVariableRecord (<a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> &amp; DVR, BlockInfo * LiveSet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1359 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### processNonDbgInstruction {#a47f512f6497daf8ba0be6476d70b90d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssignmentTrackingLowering::processNonDbgInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, BlockInfo * LiveSet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1350 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### processTaggedInstruction {#a8a1f2f4bbbe8a0c19a6b96343e2fe826}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssignmentTrackingLowering::processTaggedInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, BlockInfo * LiveSet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update <span class="doxyComputerOutput">LiveSet</span> after encountering an instruction with a <a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> attachment, <span class="doxyComputerOutput">I</span>.</p>

<p>Definition at line 1354 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

### processUntaggedInstruction {#abbb525e882e3f6d0bf70f9ea18565393}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AssignmentTrackingLowering::processUntaggedInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, BlockInfo * LiveSet)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update <span class="doxyComputerOutput">LiveSet</span> after encountering an instruciton without a <a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> attachment, <span class="doxyComputerOutput">I</span>.</p>

<p>Definition at line 1357 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp">AssignmentTrackingAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
