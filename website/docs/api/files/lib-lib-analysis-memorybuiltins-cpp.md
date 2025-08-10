---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/analysis/memorybuiltins-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `MemoryBuiltins.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">llvm/Analysis/MemoryBuiltins.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">llvm/Analysis/AliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetfolder-h">llvm/Analysis/TargetFolder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">llvm/Analysis/TargetLibraryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/include/llvm/analysis/utils/local-h">llvm/Analysis/Utils/Local.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">llvm/Analysis/ValueTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">llvm/IR/Argument.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">llvm/IR/GlobalAlias.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">llvm/IR/GlobalVariable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">llvm/IR/Operator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;iterator&gt;
#include &lt;numeric&gt;
#include &lt;optional&gt;
#include &lt;utility&gt;
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/allocfnsty">AllocFnsTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/freefnsty">FreeFnsTy</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">AllocType : uint8_t { <a href="#abb725d65acc814edc5c025fb8ee6d55b">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MallocFamily { <a href="#a0efc0e8de0d1c7171d3e84ed656de113">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69f98dfddb8cacb76affe85c54a67b6a">mangledNameForMallocFamily</a> (const MallocFamily &amp;Family)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa04dbee2593fa5fbeb0552fcb8a00ee4">getCalledFunction</a> (const Value *V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/allocfnsty">AllocFnsTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c3ae5109d96640fa77e6942513269d6">getAllocationDataForFunction</a> (const Function *Callee, AllocType AllocTy, const TargetLibraryInfo *TLI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the allocation data for the given value if it's a call to a known allocation function. <a href="#a3c3ae5109d96640fa77e6942513269d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/allocfnsty">AllocFnsTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a476744838f3f9c3e23d267387bb74ca0">getAllocationData</a> (const Value *V, AllocType AllocTy, const TargetLibraryInfo *TLI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/allocfnsty">AllocFnsTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f85e7cbed6bf638fd7e984622d69458">getAllocationData</a> (const Value *V, AllocType AllocTy, function_ref&lt; const TargetLibraryInfo &amp;(Function &amp;)&gt; GetTLI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/allocfnsty">AllocFnsTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a4b1bb434f664cf880b1dd79909c61a">getAllocationSize</a> (const CallBase *CB, const TargetLibraryInfo *TLI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1">AllocFnKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f76ccb620fc227f0b307e3457cb5228">getAllocFnKind</a> (const Value *V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1">AllocFnKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad550bcacab03ad5ac659024f5f67d623">getAllocFnKind</a> (const Function *F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ffa0b23d7c3ae709c476d948f5f3d9a">checkFnAllocKind</a> (const Value *V, AllocFnKind Wanted)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfefa4c35419a38249a7215368ff7a5f">checkFnAllocKind</a> (const Function *F, AllocFnKind Wanted)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7da51e81430a2e11b0573c4b80d3911a">CheckedZextOrTrunc</a> (APInt &amp;I, unsigned IntTyBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When we're compiling N-bit code, and the user uses parameters that are greater than N bits (e.g. <a href="#a7da51e81430a2e11b0573c4b80d3911a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/freefnsty">FreeFnsTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5185b912891053821b8cb398be3a82f6">getFreeFunctionDataForFunction</a> (const Function *Callee, const LibFunc TLIFn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc4da9acea00d2b58e4d46bf97eb29c7">getSizeWithOverflow</a> (const SizeOffsetAPInt &amp;Data)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae098d8415a5682fb28d14f8716388acb">STATISTIC</a> (ObjectVisitorArgument, "Number of arguments with unsolved size and offset")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69e40d46fe01ea854b003038d8209840">STATISTIC</a> (ObjectVisitorLoad, "Number of load instructions with unsolved size and offset")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a124cd4dd0f4ea025345adf1f08f8e703">combinePossibleConstantValues</a> (std::optional&lt; APInt &gt; LHS, std::optional&lt; APInt &gt; RHS, ObjectSizeOpts::Mode EvalMode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa25c9fdb4bd7e42569e95d058d86ee4">aggregatePossibleConstantValuesImpl</a> (const Value *V, ObjectSizeOpts::Mode EvalMode, unsigned recursionDepth)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa20af95aa4e2d7198d12bf87a6a38b1e">aggregatePossibleConstantValues</a> (const Value *V, ObjectSizeOpts::Mode EvalMode)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa27b99b094b46f9e1c5bcc38d9688c28">ObjectSizeOffsetVisitorMaxVisitInstructions</a>("object-size-offset-visitor-max-visit-instructions", cl::desc("Maximum number of instructions for ObjectSizeOffsetVisitor to " "look at"), cl::init(100))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a>, <a href="/web-llvm/docs/api/structs/allocfnsty">AllocFnsTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabac84cab1d6f7ceceec3793a02b2827">AllocationFnData</a>[]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a>, <a href="/web-llvm/docs/api/structs/freefnsty">FreeFnsTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ce5bb74a97d1435a69fbe2a3d5cb6a7">FreeFnData</a>[]</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"memory-builtins"</td>
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


<div class="doxySectionDef">

## Enumerations

### AllocType {#abb725d65acc814edc5c025fb8ee6d55b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum AllocType : uint8_t</td>
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
<td class="doxyEnumItemName">OpNewLike<a id="abb725d65acc814edc5c025fb8ee6d55badcf29d9a6397809e61b52649a1d69e5a"></a></td>
<td class="doxyEnumItemDescription"> (= 1&lt;&lt;0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MallocLike<a id="abb725d65acc814edc5c025fb8ee6d55ba15cd6e2296d0d8f43508ae215591d44f"></a></td>
<td class="doxyEnumItemDescription"> (= 1&lt;&lt;1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">StrDupLike<a id="abb725d65acc814edc5c025fb8ee6d55baa9419e141a57bef2451cb5d9b800161f"></a></td>
<td class="doxyEnumItemDescription"> (= 1&lt;&lt;2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MallocOrOpNewLike<a id="abb725d65acc814edc5c025fb8ee6d55badda630c8c4139bdb211ad5c2d08c3de0"></a></td>
<td class="doxyEnumItemDescription"> (= MallocLike | OpNewLike)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllocLike<a id="abb725d65acc814edc5c025fb8ee6d55ba8f42c8985596f7dd509c1758590add72"></a></td>
<td class="doxyEnumItemDescription"> (= MallocOrOpNewLike | StrDupLike)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AnyAlloc<a id="abb725d65acc814edc5c025fb8ee6d55ba4ac405511b2f459a42890ec6f1508307"></a></td>
<td class="doxyEnumItemDescription"> (= AllocLike)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>

</div>
</div>

### MallocFamily {#a0efc0e8de0d1c7171d3e84ed656de113}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class MallocFamily </td>
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
<td class="doxyEnumItemName">Malloc<a id="a0efc0e8de0d1c7171d3e84ed656de113a1131a914388fac73e5f07b0ba0aad523"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CPPNew<a id="a0efc0e8de0d1c7171d3e84ed656de113a1dfe7f85ca63c5e3a43105ffc252ada5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CPPNewAligned<a id="a0efc0e8de0d1c7171d3e84ed656de113aaa88dc7bcdc1503eb14d99d4e19644c5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CPPNewArray<a id="a0efc0e8de0d1c7171d3e84ed656de113a9ec760dd8d933417389e65421ef9184c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CPPNewArrayAligned<a id="a0efc0e8de0d1c7171d3e84ed656de113aee546203d95ab9e7ea1a617093391edb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MSVCNew<a id="a0efc0e8de0d1c7171d3e84ed656de113aad37d019949c90bb8f9b5314ee8ca01c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MSVCArrayNew<a id="a0efc0e8de0d1c7171d3e84ed656de113a2b5594685e5078138cfa942092906510"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VecMalloc<a id="a0efc0e8de0d1c7171d3e84ed656de113ac64ec45059f08ae1cd0e664e054c1074"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">KmpcAllocShared<a id="a0efc0e8de0d1c7171d3e84ed656de113acb2090d8af4e874f510542c6735825e3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### aggregatePossibleConstantValues() {#aa20af95aa4e2d7198d12bf87a6a38b1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; APInt &gt; aggregatePossibleConstantValues (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/structs/llvm/objectsizeopts/#a77eec32ab6be9e75a4b1f7cd5c4e5b8e">ObjectSizeOpts::Mode</a> EvalMode)</td>
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



<p>Definition at line 718 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="#aaa25c9fdb4bd7e42569e95d058d86ee4">aggregatePossibleConstantValuesImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/structs/llvm/objectsizeopts/#a77eec32ab6be9e75a4b1f7cd5c4e5b8ea6a061313d22e51e0f25b7cd4dc065233">llvm::ObjectSizeOpts::Max</a> and <a href="/web-llvm/docs/api/structs/llvm/objectsizeopts/#a77eec32ab6be9e75a4b1f7cd5c4e5b8ea78d811e98514cd165dda532286610fd2">llvm::ObjectSizeOpts::Min</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor/#a3bf0370381bb5be6f2e6f4bbe28f3289">llvm::ObjectSizeOffsetVisitor::visitAllocaInst</a> and <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor/#a2cdafccac9da7d9c25309754698eb68a">llvm::ObjectSizeOffsetVisitor::visitCallBase</a>.</p>

</div>
</div>

### aggregatePossibleConstantValuesImpl() {#aaa25c9fdb4bd7e42569e95d058d86ee4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; APInt &gt; aggregatePossibleConstantValuesImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/structs/llvm/objectsizeopts/#a77eec32ab6be9e75a4b1f7cd5c4e5b8e">ObjectSizeOpts::Mode</a> EvalMode, unsigned recursionDepth)</td>
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



<p>Definition at line 685 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="#aaa25c9fdb4bd7e42569e95d058d86ee4">aggregatePossibleConstantValuesImpl</a>, <a href="#a124cd4dd0f4ea025345adf1f08f8e703">combinePossibleConstantValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#aa20af95aa4e2d7198d12bf87a6a38b1e">aggregatePossibleConstantValues</a> and <a href="#aaa25c9fdb4bd7e42569e95d058d86ee4">aggregatePossibleConstantValuesImpl</a>.</p>

</div>
</div>

### CheckedZextOrTrunc() {#a7da51e81430a2e11b0573c4b80d3911a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CheckedZextOrTrunc (<a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; I, unsigned IntTyBits)</td>
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

<p>When we're compiling N-bit code, and the user uses parameters that are greater than N bits (e.g.</p>


<p>uint64_t on a 32-bit build), we can run into trouble with <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> size issues. This function handles resizing + overflow checks for us. <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> and zext or trunc <span class="doxyComputerOutput">I</span> depending on IntTyBits and I's value.</p>


<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acdec81ddbe2a44db51de1226fa1ff5f0">llvm::getAllocSize</a>.</p>

</div>
</div>

### checkFnAllocKind() {#a5ffa0b23d7c3ae709c476d948f5f3d9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool checkFnAllocKind (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1">AllocFnKind</a> Wanted)</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="#a2f76ccb620fc227f0b307e3457cb5228">getAllocFnKind</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1a88183b946cc5f0e8c96b2e66e1c74a7e">llvm::Unknown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a291c4451c91c4aaee65308741793626a">llvm::getAllocationFamily</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9cb77a3069c227792d6bade6faff422">llvm::getFreedOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ff10451ba01dc08fc0d38983c6743b7">llvm::getReallocatedOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#accaca14b419cbac91ca6170523084a04">llvm::isAllocationFn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41502fc61f069aacb00720a5c32209e8">llvm::isAllocationFn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a56641197c50e1c7a9558446d14deadb3">llvm::isAllocLikeFn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d6c5795c1fbe672abaadd824bf08b76">llvm::isLibFreeFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9a1e36300fac11153003538cf1614659">llvm::isReallocLikeFn</a>.</p>

</div>
</div>

### checkFnAllocKind() {#acfefa4c35419a38249a7215368ff7a5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool checkFnAllocKind (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1">AllocFnKind</a> Wanted)</td>
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



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a2f76ccb620fc227f0b307e3457cb5228">getAllocFnKind</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1a88183b946cc5f0e8c96b2e66e1c74a7e">llvm::Unknown</a>.</p>

</div>
</div>

### combinePossibleConstantValues() {#a124cd4dd0f4ea025345adf1f08f8e703}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; APInt &gt; combinePossibleConstantValues (std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt; LHS, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt; RHS, <a href="/web-llvm/docs/api/structs/llvm/objectsizeopts/#a77eec32ab6be9e75a4b1f7cd5c4e5b8e">ObjectSizeOpts::Mode</a> EvalMode)</td>
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



<p>Definition at line 674 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/structs/llvm/objectsizeopts/#a77eec32ab6be9e75a4b1f7cd5c4e5b8ea6a061313d22e51e0f25b7cd4dc065233">llvm::ObjectSizeOpts::Max</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#aaa25c9fdb4bd7e42569e95d058d86ee4">aggregatePossibleConstantValuesImpl</a>.</p>

</div>
</div>

### getAllocationData() {#a476744838f3f9c3e23d267387bb74ca0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; AllocFnsTy &gt; getAllocationData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="#abb725d65acc814edc5c025fb8ee6d55b">AllocType</a> AllocTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI)</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="#a3c3ae5109d96640fa77e6942513269d6">getAllocationDataForFunction</a> and <a href="#aa04dbee2593fa5fbeb0552fcb8a00ee4">getCalledFunction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a333a0c4bc262cf38e006a6d6b8ac560e">llvm::getAllocAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a108b6e33f153eda5019d322f0ac909b0">llvm::getInitialValueOfAllocation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#accaca14b419cbac91ca6170523084a04">llvm::isAllocationFn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41502fc61f069aacb00720a5c32209e8">llvm::isAllocationFn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a56641197c50e1c7a9558446d14deadb3">llvm::isAllocLikeFn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8db6552c37faede8b3ee574d4efcc33e">llvm::isMallocOrCallocLikeFn</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adda9c09012e0e9cacf0018ab757c9044">llvm::isNewLikeFn</a>.</p>

</div>
</div>

### getAllocationData() {#a0f85e7cbed6bf638fd7e984622d69458}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; AllocFnsTy &gt; getAllocationData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="#abb725d65acc814edc5c025fb8ee6d55b">AllocType</a> AllocTy, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; GetTLI)</td>
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



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="#a3c3ae5109d96640fa77e6942513269d6">getAllocationDataForFunction</a> and <a href="#aa04dbee2593fa5fbeb0552fcb8a00ee4">getCalledFunction</a>.</p>

</div>
</div>

### getAllocationDataForFunction() {#a3c3ae5109d96640fa77e6942513269d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; AllocFnsTy &gt; getAllocationDataForFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Callee, <a href="#abb725d65acc814edc5c025fb8ee6d55b">AllocType</a> AllocTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI)</td>
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

<p>Returns the allocation data for the given value if it's a call to a known allocation function.</p>

<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="#aabac84cab1d6f7ceceec3793a02b2827">AllocationFnData</a>, <a href="/web-llvm/docs/api/structs/allocfnsty/#ad48c92a3cbc884815f1850318642173c">AllocFnsTy::AllocTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/structs/allocfnsty/#a3c9a1c0ae93034995f2b6fd895b87912">AllocFnsTy::FstParam</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#a97cfbbed8869e3582142012a071a9052">llvm::TargetLibraryInfo::getLibFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#a54699e3f128acda6003afc11d3027f6c">llvm::TargetLibraryInfo::has</a>, <a href="/web-llvm/docs/api/structs/allocfnsty/#a9303cbb27d6fa080884badf1261755f7">AllocFnsTy::NumParams</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/structs/allocfnsty/#a5fb5cb234af3f2a5d1bf7acb82f5944e">AllocFnsTy::SndParam</a>.</p>


<p>Referenced by <a href="#a476744838f3f9c3e23d267387bb74ca0">getAllocationData</a>, <a href="#a0f85e7cbed6bf638fd7e984622d69458">getAllocationData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a291c4451c91c4aaee65308741793626a">llvm::getAllocationFamily</a> and <a href="#a7a4b1bb434f664cf880b1dd79909c61a">getAllocationSize</a>.</p>

</div>
</div>

### getAllocationSize() {#a7a4b1bb434f664cf880b1dd79909c61a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; AllocFnsTy &gt; getAllocationSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI)</td>
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



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="#abb725d65acc814edc5c025fb8ee6d55ba4ac405511b2f459a42890ec6f1508307">AnyAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#adde2ea00dd2613ee41bfe91908e4e68e">llvm::CallBase::arg_size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343af2bbdf9f72c085adc4d0404e370f0f4c">llvm::Attribute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a3c3ae5109d96640fa77e6942513269d6">getAllocationDataForFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a5bac674280b8fed3e09ea688b91bb1a0">llvm::Attribute::getAllocSizeArgs</a>, <a href="#aa04dbee2593fa5fbeb0552fcb8a00ee4">getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a9e46a3a4bf99f8dcea9cb9efb4d977a3">llvm::CallBase::getFnAttr</a> and <a href="#abb725d65acc814edc5c025fb8ee6d55ba15cd6e2296d0d8f43508ae215591d44f">MallocLike</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acdec81ddbe2a44db51de1226fa1ff5f0">llvm::getAllocSize</a> and <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetevaluator/#ab0ad299c950e0e8ad155a9d78d4fa6e2">llvm::ObjectSizeOffsetEvaluator::visitCallBase</a>.</p>

</div>
</div>

### getAllocFnKind() {#a2f76ccb620fc227f0b307e3457cb5228}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocFnKind getAllocFnKind (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a1db9b109e0e28e38eb43086b679dc271">llvm::Attribute::getValueAsInt</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#adf4d22686e85732b2fef71e3c45531c6">llvm::Attribute::isValid</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1a88183b946cc5f0e8c96b2e66e1c74a7e">llvm::Unknown</a>.</p>


<p>Referenced by <a href="#acfefa4c35419a38249a7215368ff7a5f">checkFnAllocKind</a>, <a href="#a5ffa0b23d7c3ae709c476d948f5f3d9a">checkFnAllocKind</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a108b6e33f153eda5019d322f0ac909b0">llvm::getInitialValueOfAllocation</a>.</p>

</div>
</div>

### getAllocFnKind() {#ad550bcacab03ad5ac659024f5f67d623}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocFnKind getAllocFnKind (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
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



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### getCalledFunction() {#aa04dbee2593fa5fbeb0552fcb8a00ee4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function * getCalledFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/speculatequery/#ab7315fecd53d8915efb8a2ac8f908595">llvm::orc::SpeculateQuery::findCalles</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a41caa0b8eaefb07b7f8fcf19b05bb249">FindPreallocatedCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#acf512f516130aaabdd835c48140c9e5c">anonymous{SampleProfile.cpp}::SampleProfileLoader::generateMDProfMetadata</a>, <a href="#a476744838f3f9c3e23d267387bb74ca0">getAllocationData</a>, <a href="#a0f85e7cbed6bf638fd7e984622d69458">getAllocationData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a291c4451c91c4aaee65308741793626a">llvm::getAllocationFamily</a>, <a href="#a7a4b1bb434f664cf880b1dd79909c61a">getAllocationSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9cb77a3069c227792d6bade6faff422">llvm::getFreedOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#acfeb0fc40745a019c14fcfd5aadd9e70">llvm::AArch64TTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a6c22989c03e43928e4b09cfa60a804f5">llvm::ARMTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a1017f6873c8e5d75aa472aa3f06b48e3">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a978825baa870839107dcb64531311bca">llvm::RISCVTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a99733e87982c752be1218b2d87e592b9">llvm::SystemZTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyttiimpl/#acaa381079caefe69853af81f25e67928">llvm::WebAssemblyTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvice/#a8500015965ef1b86e39cd83fd2fc8dff">llvm::InlineAdvice::InlineAdvice</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp/#ac0001ca0e66f6badb71cca036c24cab0">isNoReturnDef</a>.</p>

</div>
</div>

### getFreeFunctionDataForFunction() {#a5185b912891053821b8cb398be3a82f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; FreeFnsTy &gt; getFreeFunctionDataForFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Callee, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a26a5e408fc09c5664d2bbb2d7fae154e">LibFunc</a> TLIFn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="#a8ce5bb74a97d1435a69fbe2a3d5cb6a7">FreeFnData</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a291c4451c91c4aaee65308741793626a">llvm::getAllocationFamily</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4d6c5795c1fbe672abaadd824bf08b76">llvm::isLibFreeFunction</a>.</p>

</div>
</div>

### getSizeWithOverflow() {#acc4da9acea00d2b58e4d46bf97eb29c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt getSizeWithOverflow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sizeoffsetapint">SizeOffsetAPInt</a> &amp; Data)</td>
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



<p>Definition at line 564 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a62ba0e5ee2d86f663c6de4efda6082a7">llvm::getObjectSize</a>.</p>

</div>
</div>

### mangledNameForMallocFamily() {#a69f98dfddb8cacb76affe85c54a67b6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef mangledNameForMallocFamily (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a0efc0e8de0d1c7171d3e84ed656de113">MallocFamily</a> &amp; Family)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>References <a href="#a0efc0e8de0d1c7171d3e84ed656de113a1dfe7f85ca63c5e3a43105ffc252ada5">CPPNew</a>, <a href="#a0efc0e8de0d1c7171d3e84ed656de113aaa88dc7bcdc1503eb14d99d4e19644c5">CPPNewAligned</a>, <a href="#a0efc0e8de0d1c7171d3e84ed656de113a9ec760dd8d933417389e65421ef9184c">CPPNewArray</a>, <a href="#a0efc0e8de0d1c7171d3e84ed656de113aee546203d95ab9e7ea1a617093391edb">CPPNewArrayAligned</a>, <a href="#a0efc0e8de0d1c7171d3e84ed656de113acb2090d8af4e874f510542c6735825e3">KmpcAllocShared</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a0efc0e8de0d1c7171d3e84ed656de113a1131a914388fac73e5f07b0ba0aad523">Malloc</a>, <a href="#a0efc0e8de0d1c7171d3e84ed656de113a2b5594685e5078138cfa942092906510">MSVCArrayNew</a>, <a href="#a0efc0e8de0d1c7171d3e84ed656de113aad37d019949c90bb8f9b5314ee8ca01c">MSVCNew</a> and <a href="#a0efc0e8de0d1c7171d3e84ed656de113ac64ec45059f08ae1cd0e664e054c1074">VecMalloc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a291c4451c91c4aaee65308741793626a">llvm::getAllocationFamily</a>.</p>

</div>
</div>

### STATISTIC() {#ae098d8415a5682fb28d14f8716388acb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (ObjectVisitorArgument, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a27a0ca182c45d386e77d15f3399d7cde">arguments</a> with unsolved <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and offset")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 668 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a69e40d46fe01ea854b003038d8209840}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (ObjectVisitorLoad, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumarklastscratchload-cpp/#a8a3fe89940744b94ffe5dacd6704c2be">load</a> <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a> with unsolved <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and offset")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 670 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AllocationFnData {#aabac84cab1d6f7ceceec3793a02b2827}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::pair&lt;LibFunc, AllocFnsTy&gt; AllocationFnData[]</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>Referenced by <a href="#a3c3ae5109d96640fa77e6942513269d6">getAllocationDataForFunction</a>.</p>

</div>
</div>

### FreeFnData {#a8ce5bb74a97d1435a69fbe2a3d5cb6a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::pair&lt;LibFunc, FreeFnsTy&gt; FreeFnData[]</td>
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



<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>


<p>Referenced by <a href="#a5185b912891053821b8cb398be3a82f6">getFreeFunctionDataForFunction</a>.</p>

</div>
</div>

### ObjectSizeOffsetVisitorMaxVisitInstructions {#aa27b99b094b46f9e1c5bcc38d9688c28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; ObjectSizeOffsetVisitorMaxVisitInstructions("object-size-offset-visitor-max-visit-instructions", cl::desc("Maximum number of instructions for ObjectSizeOffsetVisitor to " "look at"), cl::init(100))</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"memory-builtins"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp">MemoryBuiltins.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
