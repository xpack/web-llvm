---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/openmpirbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `OpenMPIRBuilder` Class Reference

<p>An interface to create LLVM-IR for OpenMP directives. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::OpenMPIRBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">llvm/Frontend/OpenMP/OMPIRBuilder.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> = <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt;::InsertPoint</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> used throughout for insertion points. <a href="#aafc1886793b898052f87edd7e9fdbaa3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> used to represent an insertion point or an error value. <a href="#af24d1c61cec57095ced3b08a6dd99ee8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c571620ff53fdb78e7404f5261dbd23">FinalizeCallbackTy</a> = std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>(<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback type for variable finalization (think destructors). <a href="#a0c571620ff53fdb78e7404f5261dbd23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>(<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback type for body (=inner region) code generation. <a href="#a49e35e3ee470add16efcde1ab5d5556b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a761a2c853c1d16b33e4e8c565ce0ca45">StorableBodyGenCallbackTy</a> = std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>(<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a296d2e28bddf1051d614f48b61005899">LoopBodyGenCallbackTy</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>(<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *IndVar)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback type for loop body code generation. <a href="#a296d2e28bddf1051d614f48b61005899">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71b5ba020f68829f5a1fd99f48b63d42">PrivatizeCallbackTy</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a>( <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp;Original, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp;Inner, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *&amp;ReplVal)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback type for variable privatization (think copy &amp; default constructor). <a href="#a71b5ba020f68829f5a1fd99f48b63d42">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1a990c96a3ebf58698901d09c5b4378">OpenMPIRBuilder</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder">OpenMPIRBuilder</a> operating on the given module <span class="doxyComputerOutput">M</span>. <a href="#ae1a990c96a3ebf58698901d09c5b4378">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad66949e2e846451e61d9c8f34014ea31">~OpenMPIRBuilder</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1af99f6f33b0db83a3e941fcb819fa29">initialize</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the internal state, this will put structures types and potentially other helpers into the underlying module. <a href="#a1af99f6f33b0db83a3e941fcb819fa29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cf3a832c89fb823f696ce21ecf37b9b">setConfig</a> (OpenMPIRBuilderConfig C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a784adc2347b72f745ff1239aef3a3c26">finalize</a> (Function *Fn=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize the underlying module, e.g., by outlining regions. <a href="#a784adc2347b72f745ff1239aef3a3c26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50c6490cf353f064946c4e32673ac098">addAttributes</a> (omp::RuntimeFunction FnID, Function &amp;Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add attributes known for <span class="doxyComputerOutput">FnID</span> to <span class="doxyComputerOutput">Fn</span>. <a href="#a50c6490cf353f064946c4e32673ac098">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a488c861f8a68e5f78ceca8b57acd8be5">createPlatformSpecificName</a> (ArrayRef&lt; StringRef &gt; Parts) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the create a name using the platform specific separators. <a href="#a488c861f8a68e5f78ceca8b57acd8be5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a977f2477d245a9d554642492fedd049a">pushFinalizationCB</a> (const FinalizationInfo &amp;FI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Push a finalization callback on the finalization stack. <a href="#a977f2477d245a9d554642492fedd049a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2e7210874149ecbd52c8ce44ca4f416">popFinalizationCB</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pop the last finalization callback from the finalization stack. <a href="#af2e7210874149ecbd52c8ce44ca4f416">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abca6530c9099bd1b1c3e0a5c32381f07">createBarrier</a> (const LocationDescription &amp;Loc, omp::Directive Kind, bool ForceSimpleCall=false, bool CheckCancelFlag=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emitter methods for OpenMP directives. <a href="#abca6530c9099bd1b1c3e0a5c32381f07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04285415a321e48322c08f3b9185540e">createCancel</a> (const LocationDescription &amp;Loc, Value *IfCondition, omp::Directive CanceledDirective)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> cancel'. <a href="#a04285415a321e48322c08f3b9185540e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f81b9940e1869e146636dc533455929">createParallel</a> (const LocationDescription &amp;Loc, InsertPointTy AllocaIP, BodyGenCallbackTy BodyGenCB, PrivatizeCallbackTy PrivCB, FinalizeCallbackTy FiniCB, Value *IfCondition, Value *NumThreads, omp::ProcBindKind ProcBind, bool IsCancellable)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> parallel'. <a href="#a4f81b9940e1869e146636dc533455929">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0287686a5ffe03bc264972c862726ea">createCanonicalLoop</a> (const LocationDescription &amp;Loc, LoopBodyGenCallbackTy BodyGenCB, Value *TripCount, const Twine &amp;Name="loop")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for the control flow structure of an OpenMP canonical loop. <a href="#ae0287686a5ffe03bc264972c862726ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac669acbd0f638c6ef32977575362052e">createCanonicalLoop</a> (const LocationDescription &amp;Loc, LoopBodyGenCallbackTy BodyGenCB, Value *Start, Value *Stop, Value *Step, bool IsSigned, bool InclusiveStop, InsertPointTy ComputeIP={}, const Twine &amp;Name="loop")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for the control flow structure of an OpenMP canonical loop. <a href="#ac669acbd0f638c6ef32977575362052e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08610118e213de1b759470f0eafb9b18">collapseLoops</a> (DebugLoc DL, ArrayRef&lt; CanonicalLoopInfo * &gt; Loops, InsertPointTy ComputeIP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collapse a loop nest into a single loop. <a href="#a08610118e213de1b759470f0eafb9b18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdc1b8675a946ce055c64607ba75af3a">getAddrOfDeclareTargetVar</a> (OffloadEntriesInfoManager::OMPTargetGlobalVarEntryKind CaptureClause, OffloadEntriesInfoManager::OMPTargetDeviceClauseKind DeviceClause, bool IsDeclaration, bool IsExternallyVisible, TargetRegionEntryInfo EntryInfo, StringRef MangledName, std::vector&lt; GlobalVariable * &gt; &amp;GeneratedRefs, bool OpenMPSIMD, std::vector&lt; Triple &gt; TargetTriple, Type *LlvmPtrTy, std::function&lt; Constant *()&gt; GlobalInitializer, std::function&lt; GlobalValue::LinkageTypes()&gt; VariableLinkage)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve (or create if non-existent) the address of a declare target variable, used in conjunction with registerTargetGlobalVariable to create declare target global variables. <a href="#afdc1b8675a946ce055c64607ba75af3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae327be8503a76bd4dccfff4713a38553">registerTargetGlobalVariable</a> (OffloadEntriesInfoManager::OMPTargetGlobalVarEntryKind CaptureClause, OffloadEntriesInfoManager::OMPTargetDeviceClauseKind DeviceClause, bool IsDeclaration, bool IsExternallyVisible, TargetRegionEntryInfo EntryInfo, StringRef MangledName, std::vector&lt; GlobalVariable * &gt; &amp;GeneratedRefs, bool OpenMPSIMD, std::vector&lt; Triple &gt; TargetTriple, std::function&lt; Constant *()&gt; GlobalInitializer, std::function&lt; GlobalValue::LinkageTypes()&gt; VariableLinkage, Type *LlvmPtrTy, Constant *Addr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Registers a target variable for device or host. <a href="#ae327be8503a76bd4dccfff4713a38553">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac86b562509588cbc00fbdc441c615bd3">getFlagMemberOffset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the offset of the OMP_MAP_MEMBER_OF field. <a href="#ac86b562509588cbc00fbdc441c615bd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/omp/#a02d7a52c47f2d71a111aef9d4fb70ecb">omp::OpenMPOffloadMappingFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f82182a8cc23f854efdbd453f685086">getMemberOfFlag</a> (unsigned Position)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get OMP_MAP_MEMBER_OF flag with extra bits reserved based on the position given. <a href="#a4f82182a8cc23f854efdbd453f685086">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeea5a3df7d0266470cd04bb721db70e">setCorrectMemberOfFlag</a> (omp::OpenMPOffloadMappingFlags &amp;Flags, omp::OpenMPOffloadMappingFlags MemberOfFlag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an initial flag set, this function modifies it to contain the passed in MemberOfFlag generated from the getMemberOfFlag function. <a href="#abeea5a3df7d0266470cd04bb721db70e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaa14806d128ad33bdc48d2bfc46870c">applyWorkshareLoop</a> (DebugLoc DL, CanonicalLoopInfo *CLI, InsertPointTy AllocaIP, bool NeedsBarrier, llvm::omp::ScheduleKind SchedKind=llvm::omp::OMP_SCHEDULE_Default, Value *ChunkSize=nullptr, bool HasSimdModifier=false, bool HasMonotonicModifier=false, bool HasNonmonotonicModifier=false, bool HasOrderedClause=false, omp::WorksharingLoopType LoopType=omp::WorksharingLoopType::ForStaticLoop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Modifies the canonical loop to be a workshare loop. <a href="#adaa14806d128ad33bdc48d2bfc46870c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76e12ec076e7af4be7b8b77a5d53d3fc">tileLoops</a> (DebugLoc DL, ArrayRef&lt; CanonicalLoopInfo * &gt; Loops, ArrayRef&lt; Value * &gt; TileSizes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tile a loop nest. <a href="#a76e12ec076e7af4be7b8b77a5d53d3fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28a2a9806d828609fe107f766d2dd569">unrollLoopFull</a> (DebugLoc DL, CanonicalLoopInfo *Loop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fully unroll a loop. <a href="#a28a2a9806d828609fe107f766d2dd569">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ca0068cb6a50615c74ecdb8f23839e0">unrollLoopHeuristic</a> (DebugLoc DL, CanonicalLoopInfo *Loop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fully or partially unroll a loop. <a href="#a4ca0068cb6a50615c74ecdb8f23839e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e2b7ac5f48193117a340aa15b085719">unrollLoopPartial</a> (DebugLoc DL, CanonicalLoopInfo *Loop, int32_t Factor, CanonicalLoopInfo **UnrolledCLI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Partially unroll a loop. <a href="#a5e2b7ac5f48193117a340aa15b085719">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd1fbb2df257f945afda92919be322f3">applySimd</a> (CanonicalLoopInfo *Loop, MapVector&lt; Value *, Value * &gt; AlignedVars, Value *IfCond, omp::OrderKind Order, ConstantInt *Simdlen, ConstantInt *Safelen)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add metadata to simd-ize a loop. <a href="#acd1fbb2df257f945afda92919be322f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc2cc623eda981e1b3fbb61a44e80ef8">createFlush</a> (const LocationDescription &amp;Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> flush'. <a href="#afc2cc623eda981e1b3fbb61a44e80ef8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a419ffad9e4d59275e299ce1ad3c73cd4">createTaskwait</a> (const LocationDescription &amp;Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> taskwait'. <a href="#a419ffad9e4d59275e299ce1ad3c73cd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b0ed7f600549e4239bf10b5b85de66c">createTaskyield</a> (const LocationDescription &amp;Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> taskyield'. <a href="#a0b0ed7f600549e4239bf10b5b85de66c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae75c4b44f208011259ee93497c2cb411">createAtomicUpdate</a> (const LocationDescription &amp;Loc, InsertPointTy AllocaIP, AtomicOpValue &amp;X, Value *Expr, AtomicOrdering AO, AtomicRMWInst::BinOp RMWOp, AtomicUpdateCallbackTy &amp;UpdateOp, bool IsXBinopExpr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for <span class="doxyComputerOutput">#omp task</span> <a href="#ae75c4b44f208011259ee93497c2cb411">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cc340cf5dc46cf45eb6f784577cadbd">createAtomicCapture</a> (const LocationDescription &amp;Loc, InsertPointTy AllocaIP, AtomicOpValue &amp;X, AtomicOpValue &amp;V, Value *Expr, AtomicOrdering AO, AtomicRMWInst::BinOp RMWOp, AtomicUpdateCallbackTy &amp;UpdateOp, bool UpdateExpr, bool IsPostfixUpdate, bool IsXBinopExpr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit atomic update for constructs: — Only Scalar data types V = X; X = X BinOp Expr , X = X BinOp Expr; V = X, V = X; X = Expr BinOp X, X = Expr BinOp X; V = X, V = X; X = UpdateOp(X), X = UpdateOp(X); V = X,. <a href="#a6cc340cf5dc46cf45eb6f784577cadbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c4eeba23c6f192892487de272e8ce72">createAtomicCompare</a> (const LocationDescription &amp;Loc, AtomicOpValue &amp;X, AtomicOpValue &amp;V, AtomicOpValue &amp;R, Value *E, Value *D, AtomicOrdering AO, omp::OMPAtomicCompareOp Op, bool IsXBinopExpr, bool IsPostfixUpdate, bool IsFailOnly)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit atomic compare for constructs: — Only scalar data types cond-expr-stmt: x = x ordop expr ? <a href="#a6c4eeba23c6f192892487de272e8ce72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab84af206a9a08b9bf97eaadc87874c6c">createAtomicCompare</a> (const LocationDescription &amp;Loc, AtomicOpValue &amp;X, AtomicOpValue &amp;V, AtomicOpValue &amp;R, Value *E, Value *D, AtomicOrdering AO, omp::OMPAtomicCompareOp Op, bool IsXBinopExpr, bool IsPostfixUpdate, bool IsFailOnly, AtomicOrdering Failure)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a445fa52d77040bccb16bfea111234a2e">createLoopSkeleton</a> (DebugLoc DL, Value *TripCount, Function *F, BasicBlock *PreInsertBefore, BasicBlock *PostInsertBefore, const Twine &amp;Name={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the control flow structure of a canonical OpenMP loop. <a href="#a445fa52d77040bccb16bfea111234a2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2242b144e54fa6203dae5c5b27fff17c">loadOffloadInfoMetadata</a> (Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loads all the offload entries information from the host IR metadata. <a href="#a2242b144e54fa6203dae5c5b27fff17c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6293b7ea84a4deac85481dd10dad437">loadOffloadInfoMetadata</a> (StringRef HostFilePath)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loads all the offload entries information from the host IR metadata read from the file passed in as the HostFilePath argument. <a href="#ac6293b7ea84a4deac85481dd10dad437">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5ef00e5a7487cc6c5bfed0f301fa1cc">getOrCreateInternalVariable</a> (Type *Ty, const StringRef &amp;Name, unsigned AddressSpace=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets (if variable with the given name already exist) or creates internal global variable with the specified Name. <a href="#aa5ef00e5a7487cc6c5bfed0f301fa1cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3614ae5b7da8dfc1d3b6e74e3b114ae8">applyWorkshareLoopTarget</a> (DebugLoc DL, CanonicalLoopInfo *CLI, InsertPointTy AllocaIP, omp::WorksharingLoopType LoopType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Modifies the canonical loop to be a statically-scheduled workshare loop which is executed on the device. <a href="#a3614ae5b7da8dfc1d3b6e74e3b114ae8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4844b18964505b7687f7261c6eccde30">applyStaticWorkshareLoop</a> (DebugLoc DL, CanonicalLoopInfo *CLI, InsertPointTy AllocaIP, bool NeedsBarrier)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Modifies the canonical loop to be a statically-scheduled workshare loop. <a href="#a4844b18964505b7687f7261c6eccde30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5ac7c7120c51e85a0a9b107b278773f">applyStaticChunkedWorkshareLoop</a> (DebugLoc DL, CanonicalLoopInfo *CLI, InsertPointTy AllocaIP, bool NeedsBarrier, Value *ChunkSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Modifies the canonical loop a statically-scheduled workshare loop with a user-specified chunk size. <a href="#ae5ac7c7120c51e85a0a9b107b278773f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a040fad70b742c2d5fb4df1006b8e2fe4">applyDynamicWorkshareLoop</a> (DebugLoc DL, CanonicalLoopInfo *CLI, InsertPointTy AllocaIP, omp::OMPScheduleType SchedType, bool NeedsBarrier, Value *Chunk=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Modifies the canonical loop to be a dynamically-scheduled workshare loop. <a href="#a040fad70b742c2d5fb4df1006b8e2fe4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af94ce0ccebe00cffe61b5a50ba679eb8">createIfVersion</a> (CanonicalLoopInfo *Loop, Value *IfCond, ValueToValueMapTy &amp;VMap, const Twine &amp;NamePrefix="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create alternative version of the loop to support if clause. <a href="#af94ce0ccebe00cffe61b5a50ba679eb8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefadc356da16598ff8c210dafbf4a2b7">ompOffloadInfoName</a> = "omp_offload.info"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OMP Offload Info <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> name string. <a href="#aefadc356da16598ff8c210dafbf4a2b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5b407054e7727d04053af9c3f1a5568">getOpenMPDefaultSimdAlign</a> (const Triple &amp;TargetTriple, const StringMap&lt; bool &gt; &amp;Features)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the default alignment value for given target. <a href="#ac5b407054e7727d04053af9c3f1a5568">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>An interface to create LLVM-IR for OpenMP directives.</p>


<p>Each OpenMP directive has a corresponding public generator method.</p>


<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BodyGenCallbackTy {#a49e35e3ee470add16efcde1ab5d5556b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::BodyGenCallbackTy = 
      function_ref&lt;Error(InsertPointTy AllocaIP, InsertPointTy CodeGenIP)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback type for body (=inner region) code generation.</p>


<p>The callback takes code locations as arguments, each describing a location where additional instructions can be inserted.</p>


<p>The CodeGenIP may be in the middle of a basic block or point to the end of it. The basic block may have a terminator or be degenerate. The callback function may just insert instructions at that position, but also split the block (without the Before argument of <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a52c990590792c91dd20b6d45acebe359">BasicBlock::splitBasicBlock</a> such that the identify of the split predecessor block is preserved) and insert additional control flow, including branches that do not lead back to what follows the CodeGenIP. Note that since the callback is allowed to split the block, callers must assume that InsertPoints to positions in the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> after CodeGenIP including CodeGenIP itself are invalidated. If such InsertPoints need to be preserved, it can split the block itself before calling the callback.</p>


<p>AllocaIP and CodeGenIP must not point to the same position.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>is the insertion point at which new alloca instructions should be placed. The <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> it is pointing to must not be split.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CodeGenIP</td>
<td class="doxyParamItemDescription"><p>is the insertion point at which the body code should be placed.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an error, if any were triggered during execution.</p></dd>
</dl>


<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### FinalizeCallbackTy {#a0c571620ff53fdb78e7404f5261dbd23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::FinalizeCallbackTy =  std::function&lt;Error(InsertPointTy CodeGenIP)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback type for variable finalization (think destructors).</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CodeGenIP</td>
<td class="doxyParamItemDescription"><p>is the insertion point at which the finalization code should be placed.</p></td>
</tr>
</table>
</dd>
</dl>

<p>A finalize callback knows about all objects that need finalization, e.g. destruction, when the scope of the currently generated construct is left at the time, and location, the callback is invoked.</p>


<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### InsertPointOrErrorTy {#af24d1c61cec57095ced3b08a6dd99ee8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::InsertPointOrErrorTy =  Expected&lt;InsertPointTy&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> used to represent an insertion point or an error value.</p>

<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### InsertPointTy {#aafc1886793b898052f87edd7e9fdbaa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::InsertPointTy =  IRBuilder&lt;&gt;::InsertPoint</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> used throughout for insertion points.</p>

<p>Definition at line 520 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### LoopBodyGenCallbackTy {#a296d2e28bddf1051d614f48b61005899}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::LoopBodyGenCallbackTy = 
      function_ref&lt;Error(InsertPointTy CodeGenIP, Value *IndVar)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback type for loop body code generation.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CodeGenIP</td>
<td class="doxyParamItemDescription"><p>is the insertion point where the loop's body code must be placed. This will be a dedicated <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> with a conditional branch from the loop condition check and terminated with an unconditional branch to the loop latch.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IndVar</td>
<td class="doxyParamItemDescription"><p>is the induction variable usable at the insertion point.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an error, if any were triggered during execution.</p></dd>
</dl>


<p>Definition at line 618 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### PrivatizeCallbackTy {#a71b5ba020f68829f5a1fd99f48b63d42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::PrivatizeCallbackTy =  function_ref&lt;InsertPointOrErrorTy(
      InsertPointTy AllocaIP, InsertPointTy CodeGenIP, Value &amp;Original,
      Value &amp;Inner, Value *&amp;ReplVal)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback type for variable privatization (think copy &amp; default constructor).</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>is the insertion point at which new alloca instructions should be placed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CodeGenIP</td>
<td class="doxyParamItemDescription"><p>is the insertion point at which the privatization code should be placed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Original</td>
<td class="doxyParamItemDescription"><p>The value being copied/created, should not be used in the generated IR.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Inner</td>
<td class="doxyParamItemDescription"><p>The equivalent of <span class="doxyComputerOutput">Original</span> that should be used in the generated IR; this is equal to <span class="doxyComputerOutput">Original</span> if the value is a pointer and can thus be passed directly, otherwise it is an equivalent but different value.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReplVal</td>
<td class="doxyParamItemDescription"><p>The replacement value, thus a copy or new created version of <span class="doxyComputerOutput">Inner</span>.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The new insertion point where code generation continues and <span class="doxyComputerOutput">ReplVal</span> the replacement value.</p></dd>
</dl>


<p>Definition at line 639 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### StorableBodyGenCallbackTy {#a761a2c853c1d16b33e4e8c565ce0ca45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::OpenMPIRBuilder::StorableBodyGenCallbackTy = 
      std::function&lt;Error(InsertPointTy AllocaIP, InsertPointTy CodeGenIP)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an error, if any were triggered during execution.</p></dd>
</dl>


<p>Definition at line 605 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### OpenMPIRBuilder() {#ae1a990c96a3ebf58698901d09c5b4378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OpenMPIRBuilder::OpenMPIRBuilder (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>Create a new <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder">OpenMPIRBuilder</a> operating on the given module <span class="doxyComputerOutput">M</span>.</p>


<p>This will not have an effect on <span class="doxyComputerOutput">M</span> (see initialize)</p>


<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~OpenMPIRBuilder() {#ad66949e2e846451e61d9c8f34014ea31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::~OpenMPIRBuilder ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 845 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAttributes() {#a50c6490cf353f064946c4e32673ac098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::addAttributes (<a href="/web-llvm/docs/api/namespaces/llvm/omp/#a4c503140c7f851151906d85b515330e9">omp::RuntimeFunction</a> FnID, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add attributes known for <span class="doxyComputerOutput">FnID</span> to <span class="doxyComputerOutput">Fn</span>.</p>

<p>Declaration at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attributeset/#af2b9418751d1f1f1b99e5b05d0ed7efa">llvm::AttributeSet::addAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a46f189c4026ace551d70a16566e641b1">llvm::AttributeSet::addAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#ac6baa801e4aea800984e760d5460662f">llvm::Function::arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a7477aafbbe989ad35b96fac186d8e9fd">llvm::Function::getAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### applySimd() {#acd1fbb2df257f945afda92919be322f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::applySimd (<a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * Loop, <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; AlignedVars, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * IfCond, omp::OrderKind Order, <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * Simdlen, <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * Safelen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add metadata to simd-ize a loop.</p>


<p>If IfCond is not nullptr, the loop is cloned. The metadata which prevents vectorization is added to to the cloned loop. The cloned loop is executed when ifCond is evaluated to false.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/loop"&gt;Loop&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The loop to simd-ize.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AlignedVars</td>
<td class="doxyParamItemDescription"><p>The map which containts pairs of the pointer and its corresponding alignment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IfCond</td>
<td class="doxyParamItemDescription"><p>The value which corresponds to the if clause condition.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Order</td>
<td class="doxyParamItemDescription"><p>The enum to map order clause.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Simdlen</td>
<td class="doxyParamItemDescription"><p>The Simdlen length to apply to the simd loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Safelen</td>
<td class="doxyParamItemDescription"><p>The Safelen length to apply to the simd loop.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 5342 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#ac36177cea684b1e36fdbc92d692f69d0">addBasicBlockMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#adf813540e363817b85e9eecef51269b5">addLoopMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a545cc7eb4f94d0957ba9960a69b10a90">addSimdMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a480959ce9fb41e0ac0ce2cd7907d7ace">llvm::IRBuilderBase::CreateAlignmentAssumption</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>, <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#acb5b5b136597312e0d5df6b746a7e6db">llvm::CanonicalLoopInfo::getCond</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa2ed385be8984b4306762990278eb13d">llvm::IRBuilderBase::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a21a975fd58c287a6ca3f1c89c048e7d3">llvm::MDNode::getDistinct</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a9592feb460b27d417f42a41aabfe253a">llvm::CanonicalLoopInfo::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a01c4471afa921c4962d7138cfcef4942">llvm::CanonicalLoopInfo::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#ac37a6cf77f6f82b6bb28af4d9c8626d0">llvm::CanonicalLoopInfo::getLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#a62ee7ece4986606d41363bc1f70d5ab2">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getNextNode</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/valuemap/#a15f92579a5fc316dab8cd1fad51015ef">llvm::ValueMap&lt; KeyT, ValueT, Config &gt;::lookup</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac8778dcbd35e8ae5902050117feb57a0">llvm::IRBuilderBase::restoreIP</a>, <a href="/web-llvm/docs/api/classes/llvm/loopanalysis/#aea38b668f2d98b7e9f64b8b3c2e524dc">llvm::LoopAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a79479229269c1abc7dba0840d19b97cf">llvm::IRBuilderBase::saveIP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a> and <a href="/web-llvm/docs/api/classes/llvm/mapvector/#acf4c09e1f30cdd4e0b5b1b8a236ead34">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::size</a>.</p>

</div>
</div>

### applyWorkshareLoop() {#adaa14806d128ad33bdc48d2bfc46870c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::applyWorkshareLoop (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * CLI, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, bool NeedsBarrier, llvm::omp::ScheduleKind SchedKind=llvm::omp::OMP_SCHEDULE_Default, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ChunkSize=nullptr, bool HasSimdModifier=false, bool HasMonotonicModifier=false, bool HasNonmonotonicModifier=false, bool HasOrderedClause=false, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#ab6fb146c332fd3f3d677ee65081fe669">omp::WorksharingLoopType</a> LoopType=<a href="/web-llvm/docs/api/namespaces/llvm/omp/#ab6fb146c332fd3f3d677ee65081fe669a45663d75b039e00b6412fb82fed8c306">omp::WorksharingLoopType::ForStaticLoop</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Modifies the canonical loop to be a workshare loop.</p>


<p>This takes a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a></span> representing a canonical loop, such as the one created by <span class="doxyComputerOutput">createCanonicalLoop</span> and emits additional instructions to turn it into a workshare loop. In particular, it calls to an OpenMP runtime function in the preheader to obtain the loop bounds to be used in the current thread, updates the relevant instructions in the canonical loop and calls to an OpenMP runtime finalization function after the loop.</p>


<p>The concrete transformation is done by applyStaticWorkshareLoop, applyStaticChunkedWorkshareLoop, or applyDynamicWorkshareLoop, depending on the value of <span class="doxyComputerOutput">SchedKind</span> and <span class="doxyComputerOutput">ChunkSize</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug location for instructions added for the workshare-loop construct itself.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CLI</td>
<td class="doxyParamItemDescription"><p>A descriptor of the canonical loop to workshare.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>An insertion point for Alloca instructions usable in the preheader of the loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NeedsBarrier</td>
<td class="doxyParamItemDescription"><p>Indicates whether a barrier must be insterted after the loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SchedKind</td>
<td class="doxyParamItemDescription"><p>Scheduling algorithm to use.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ChunkSize</td>
<td class="doxyParamItemDescription"><p>The chunk size for the inner loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HasSimdModifier</td>
<td class="doxyParamItemDescription"><p>Whether the simd modifier is present in the schedule clause.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HasMonotonicModifier</td>
<td class="doxyParamItemDescription"><p>Whether the monotonic modifier is present in the schedule clause.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HasNonmonotonicModifier</td>
<td class="doxyParamItemDescription"><p>Whether the nonmonotonic modifier is present in the schedule clause.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HasOrderedClause</td>
<td class="doxyParamItemDescription"><p>Whether the (parameterless) ordered clause is present.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LoopType</td>
<td class="doxyParamItemDescription"><p>Information about type of loop worksharing. It corresponds to type of loop workshare OpenMP pragma.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Point where to insert code after the workshare construct.</p></dd>
</dl>


<p>Declaration at line 1107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 4621 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a554000c782275642b783964853720bee">computeOpenMPScheduleType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### collapseLoops() {#a08610118e213de1b759470f0eafb9b18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CanonicalLoopInfo * OpenMPIRBuilder::collapseLoops (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * &gt; Loops, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> ComputeIP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collapse a loop nest into a single loop.</p>


<p>Merges loops of a loop nest into a single CanonicalLoopNest representation that has the same number of innermost loop iterations as the origin loop nest. The induction variables of the input loops are derived from the collapsed loop's induction variable. This is intended to be used to implement OpenMP's collapse clause. Before applying a directive, collapseLoops normalizes a loop nest to contain only a single loop and the directive's implementation does not need to handle multiple loops itself. This does not remove the need to handle all loop nest handling by directives, such as the ordered(&lt;n&gt;) clause or the simd schedule-clause modifier of the worksharing-loop directive.</p>


<p>Example:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = 0; i &lt; 7; ++i) </span><span class="doxyHighlightComment">// Canonical loop "i"</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> j = 0; <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea363b122c528f54df4a0446b6bab05515">j</a> &lt; 9; ++<a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea363b122c528f54df4a0446b6bab05515">j</a>) </span><span class="doxyHighlightComment">// Canonical loop "j"</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    body(i, j);</span></span></div>

</div>


<p>After collapsing with Loops={i,j}, the loop is changed to</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ij = 0; ij &lt; 63; ++ij) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = ij / 9;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea363b122c528f54df4a0446b6bab05515">j</a> = ij % 9;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  body(i, j);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>In the current implementation, the following limitations apply:</p>


<ul class="doxyList ">
<li>All input loops have an induction variable of the same type.</li>
<li>The collapsed loop will have the same trip count integer type as the input loops. Therefore it is possible that the collapsed loop cannot represent all iterations of the input loops. For instance, assuming a 32 bit integer type, and two input loops both iterating 2^16 times, the theoretical trip count of the collapsed loop would be 2^32 iteration, which cannot be represented in an 32-bit integer. Behavior is undefined in this case.</li>
<li>The trip counts of every input loop must be available at <span class="doxyComputerOutput">ComputeIP</span>. Non-rectangular loops are not yet supported.</li>
<li>At each nest level, code between a surrounding loop and its nested loop is hoisted into the loop body, and such code will be executed more often than before collapsing (or not at all if any inner loop iteration has a trip count of 0). This is permitted by the OpenMP specification.</li>
</ul>

<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug location for instructions added for collapsing, such as instructions to compute/derive the input loop's induction variables.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Loops</td>
<td class="doxyParamItemDescription"><p>Loops in the loop nest to collapse. Loops are specified from outermost-to-innermost and every control flow of a loop's body must pass through its directly nested loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ComputeIP</td>
<td class="doxyParamItemDescription"><p>Where additional instruction that compute the collapsed trip count. If not set, defaults to before the generated loop.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> object representing the collapsed loop.</p></dd>
</dl>


<p>Declaration at line 842 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 4887 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a445fa52d77040bccb16bfea111234a2e">createLoopSkeleton</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aecd40f9a16dc0ef1e0bc416599f89277">llvm::IRBuilderBase::CreateMul</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6b68047eda0d6d6eec5dd564ed1a22b8">llvm::IRBuilderBase::CreateUDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae884a856c5f31ab8fcf64f81db130dcd">llvm::IRBuilderBase::CreateURem</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a92d8bce979891dc43b6573e8cca2e58c">llvm::CanonicalLoopInfo::getAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a47521ec347ef7b522745bf89e2e2d19a">llvm::CanonicalLoopInfo::getBody</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#ac37a6cf77f6f82b6bb28af4d9c8626d0">llvm::CanonicalLoopInfo::getLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#a62ee7ece4986606d41363bc1f70d5ab2">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getNextNode</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a1b4bf7c97cdc8159fd73d48063f0b250">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#ad50eb30e70ff2a9ea7f220547e2b6f6d">llvm::CanonicalLoopInfo::getPreheader</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#ac72ebc430ef7dcf1791c66080ddedd9d">llvm::CanonicalLoopInfo::getPreheaderIP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/insertpoint/#a85b9635b21610f18b51007437bcc26cf">llvm::IRBuilderBase::InsertPoint::isSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp/#ada7c1594a393ede3ce32602d64d7ddb2">Loops</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#abdcdbfc178873f5055fbcf98bad92f53">redirectAllPredecessorsTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3057c2b7e1e25de160497b1ef3985c2a">redirectTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#af0ce60c4a958016f62ce78f1eda423af">removeUnusedBlocksFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac8778dcbd35e8ae5902050117feb57a0">llvm::IRBuilderBase::restoreIP</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a63fc74646456a3bed261512f21efe29c">llvm::IRBuilderBase::SetCurrentDebugLocation</a>.</p>

</div>
</div>

### createAtomicCapture() {#a6cc340cf5dc46cf45eb6f784577cadbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::createAtomicCapture (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, AtomicOpValue &amp; X, AtomicOpValue &amp; V, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Expr, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> AO, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615">AtomicRMWInst::BinOp</a> RMWOp, AtomicUpdateCallbackTy &amp; UpdateOp, bool UpdateExpr, bool IsPostfixUpdate, bool IsXBinopExpr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit atomic update for constructs: — Only Scalar data types V = X; X = X BinOp Expr , X = X BinOp Expr; V = X, V = X; X = Expr BinOp X, X = Expr BinOp X; V = X, V = X; X = UpdateOp(X), X = UpdateOp(X); V = X,.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>The insertion point to be used for alloca instructions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">X</td>
<td class="doxyParamItemDescription"><p>The target atomic pointer to be updated</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">V</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> address where to store captured value</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Expr</td>
<td class="doxyParamItemDescription"><p>The value to update X with.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AO</td>
<td class="doxyParamItemDescription"><p>Atomic ordering of the generated atomic instructions</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RMWOp</td>
<td class="doxyParamItemDescription"><p>The binary operation used for update. If operation is not supported by atomicRMW, or belong to {FADD, FSUB, BAD_BINOP}. Then a cmpExch based atomic will be generated.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UpdateOp</td>
<td class="doxyParamItemDescription"><p>Code generator for complex expressions that cannot be expressed through atomicrmw instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UpdateExpr</td>
<td class="doxyParamItemDescription"><p>true if X is an in place update of the form X = X BinOp Expr or X = Expr BinOp X</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsXBinopExpr</td>
<td class="doxyParamItemDescription"><p>true if X is Left H.S. in Right H.S. part of the update expression, false otherwise. (e.g. true for X = X BinOp Expr)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsPostfixUpdate</td>
<td class="doxyParamItemDescription"><p>true if original value of 'x' must be stored in 'v', not an updated one.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Insertion point after generated atomic capture IR.</p></dd>
</dl>


<p>Declaration at line 3299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 8793 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a91b7eb2a05d10c788413bec7977f3474">emitImplicitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aac5759c83abd6a4af236401a7cfe7a0f">llvm::Type::isFloatingPointTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615aa1184a7e35e94d162a2d40f2b11beeb2">llvm::AtomicRMWInst::Max</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a39edb6e51c1ad37244e8b32a2af4077d">llvm::AtomicRMWInst::Min</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a79479229269c1abc7dba0840d19b97cf">llvm::IRBuilderBase::saveIP</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615afc870a548088c5b7a93a34f648889d77">llvm::AtomicRMWInst::Xchg</a>.</p>

</div>
</div>

### createAtomicCompare() {#a6c4eeba23c6f192892487de272e8ce72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointTy OpenMPIRBuilder::createAtomicCompare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, AtomicOpValue &amp; X, AtomicOpValue &amp; V, AtomicOpValue &amp; R, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * E, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * D, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> AO, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#acb593a387130148478f3c30af0d322df">omp::OMPAtomicCompareOp</a> Op, bool IsXBinopExpr, bool IsPostfixUpdate, bool IsFailOnly)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit atomic compare for constructs: — Only scalar data types cond-expr-stmt: x = x ordop expr ?</p>


<p>expr : x; x = expr ordop x ? expr : x; x = x == e ? d : x; x = e == x ? d : x; (this one is not in the spec) cond-update-stmt: if (x ordop expr) { x = expr; } if (expr ordop x) { x = expr; } if (x == e) { x = d; } if (e == x) { x = d; } (this one is not in the spec) conditional-update-capture-atomic: v = x; cond-update-stmt; (IsPostfixUpdate=true, IsFailOnly=false) cond-update-stmt; v = x; (IsPostfixUpdate=false, IsFailOnly=false) if (x == e) { x = d; } else { v = x; } (IsPostfixUpdate=false, IsFailOnly=true) r = x == e; if (r) { x = d; } (IsPostfixUpdate=false, IsFailOnly=false) r = x == e; if (r) { x = d; } else { v = x; } (IsPostfixUpdate=false, IsFailOnly=true)</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">X</td>
<td class="doxyParamItemDescription"><p>The target atomic pointer to be updated.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">V</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> address where to store captured value (for compare capture only).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">R</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> address where to store comparison result (for compare capture with '==' only).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">E</td>
<td class="doxyParamItemDescription"><p>The expected value ('e') for forms that use an equality comparison or an expression ('expr') for forms that use 'ordop' (logically an atomic maximum or minimum).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">D</td>
<td class="doxyParamItemDescription"><p>The desired value for forms that use an equality comparison. If forms that use 'ordop', it should be <span class="doxyComputerOutput">nullptr</span>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AO</td>
<td class="doxyParamItemDescription"><p>Atomic ordering of the generated atomic instructions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6"&gt;Op&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>Atomic compare operation. It can only be ==, &lt;, or &gt;.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsXBinopExpr</td>
<td class="doxyParamItemDescription"><p>True if the conditional statement is in the form where x is on LHS. It only matters for &lt; or &gt;.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsPostfixUpdate</td>
<td class="doxyParamItemDescription"><p>True if original value of 'x' must be stored in 'v', not an updated one (for compare capture only).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsFailOnly</td>
<td class="doxyParamItemDescription"><p>True if the original value of 'x' is stored to 'v' only when the comparison fails. This is only valid for the case the comparison is '=='.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Insertion point after generated atomic capture IR.</p></dd>
</dl>


<p>Declaration at line 3351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 8831 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#a6c4eeba23c6f192892487de272e8ce72">createAtomicCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#a7ce03ab5b2a6006ebcdfe804e4c8f1a1">llvm::AtomicCmpXchgInst::getStrongestFailureOrdering</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#a6c4eeba23c6f192892487de272e8ce72">createAtomicCompare</a>.</p>

</div>
</div>

### createAtomicCompare() {#ab84af206a9a08b9bf97eaadc87874c6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointTy OpenMPIRBuilder::createAtomicCompare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, AtomicOpValue &amp; X, AtomicOpValue &amp; V, AtomicOpValue &amp; R, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * E, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * D, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> AO, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#acb593a387130148478f3c30af0d322df">omp::OMPAtomicCompareOp</a> Op, bool IsXBinopExpr, bool IsPostfixUpdate, bool IsFailOnly, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Failure)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 3355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 8842 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a199f6765de1f6b1a242aac556528f3b3">llvm::IRBuilderBase::CreateAtomicCmpXchg</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab2a2c89b21cf14b2c729a898006cb438">llvm::IRBuilderBase::CreateAtomicRMW</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#abab736a0141f903dc32a6f48828ad908">llvm::IRBuilderBase::CreateBr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a843d43d070f0b1c6a133403edce488ef">llvm::IRBuilderBase::CreateCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a972c30f044db799668bdcace5544edeb">llvm::IRBuilderBase::CreateCondBr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a41cf66866b0b0e5a10038bfb77477419">llvm::IRBuilderBase::CreateExtractValue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a49b228f797f9b3563256da446100c3ac">llvm::IRBuilderBase::CreateSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a39acc29443d48968a798fb22a76fa4c0">llvm::IRBuilderBase::CreateUnreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba4c399f525bbcf03d72af4b303e6eeca8">llvm::CmpInst::FCMP_OGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba326bee0a4a424cef21c1cf8adb8b8dd8">llvm::CmpInst::FCMP_OLT</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615acce124326ba87b0127b36c412bf555fd">llvm::AtomicRMWInst::FMax</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615abd5e733a10a36f3572105b1a67538e18">llvm::AtomicRMWInst::FMin</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a60a6d6c205f483fa96597a960f3c093b">llvm::IRBuilderBase::GetInsertBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aef9e9fcf4c5dfce90276ca16d91b8e46">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615aa1184a7e35e94d162a2d40f2b11beeb2">llvm::AtomicRMWInst::Max</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a39edb6e51c1ad37244e8b32a2af4077d">llvm::AtomicRMWInst::Min</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a79479229269c1abc7dba0840d19b97cf">llvm::IRBuilderBase::saveIP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a52c990590792c91dd20b6d45acebe359">llvm::BasicBlock::splitBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615abe171d96ba8de66fb30e08c00211591e">llvm::AtomicRMWInst::UMax</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615aa53854e09143f57d2ff2ad6ac89dc55d">llvm::AtomicRMWInst::UMin</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### createAtomicUpdate() {#ae75c4b44f208011259ee93497c2cb411}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::createAtomicUpdate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, AtomicOpValue &amp; X, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Expr, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> AO, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615">AtomicRMWInst::BinOp</a> RMWOp, AtomicUpdateCallbackTy &amp; UpdateOp, bool IsXBinopExpr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for <span class="doxyComputerOutput">#omp task</span></p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location where the task construct was encountered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>The insertion point to be used for alloca instructions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the region code.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Tied</td>
<td class="doxyParamItemDescription"><p>True if the task is tied, false if the task is untied.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Final</td>
<td class="doxyParamItemDescription"><p>i1 value which is <span class="doxyComputerOutput">true</span> if the task is final, <span class="doxyComputerOutput">false</span> if the task is not final.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IfCondition</td>
<td class="doxyParamItemDescription"><p>i1 value. If it evaluates to <span class="doxyComputerOutput">false</span>, an undeferred task is generated, and the encountering thread must suspend the current task region, for which execution cannot be resumed until execution of the structured block that is associated with the generated task is completed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EventHandle</td>
<td class="doxyParamItemDescription"><p>If present, signifies the event handle as part of the detach clause</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Mergeable</td>
<td class="doxyParamItemDescription"><p>If the given task is <span class="doxyComputerOutput">mergeable</span></p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">priority</td>
<td class="doxyParamItemDescription"><p>‘priority-value` specifies the execution order of the / tasks that is generated by the construct <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a> createTask(const <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp;<a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a>, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a> BodyGenCB, bool Tied = true, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *Final = nullptr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *IfCondition = nullptr, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;DependData&gt;</a> Dependencies = {}, bool Mergeable = false, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *EventHandle = nullptr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *Priority = nullptr);</p></td>
</tr>
</table>
</dd>
</dl>

<p>/ Generator for the taskgroup construct / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location where the taskgroup construct was encountered. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>The insertion point to be used for alloca instructions. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the region code. <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a> createTaskgroup(const LocationDescription &amp;Loc,
                                       InsertPointTy AllocaIP,
                                       BodyGenCallbackTy BodyGenCB);</p></td>
</tr>
</table>
</dd>
</dl>

<p>using FileIdentifierInfoCallbackTy = std::function&lt;std::tuple&lt;std::string, uint64_t&gt;()&gt;;</p>


<p>/ Creates a unique info for a target entry when provided a filename and / line number from. / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CallBack</td>
<td class="doxyParamItemDescription"><p>A callback function which should return filename the entry / resides in as well as the line number for the target entry /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ParentName</td>
<td class="doxyParamItemDescription"><p>The name of the parent the target entry resides in, if / any. static <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo">TargetRegionEntryInfo</a> getTargetEntryUniqueInfo(FileIdentifierInfoCallbackTy CallBack, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ParentName = "");</p></td>
</tr>
</table>
</dd>
</dl>

<p>/ Enum class for the RedctionGen CallBack type to be used. enum class ReductionGenCBKind { Clang, MLIR };</p>


<p>/ ReductionGen CallBack for Clang / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CodeGenIP</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/irbuilder">InsertPoint</a> for CodeGen. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Index</td>
<td class="doxyParamItemDescription"><p>Index of the ReductionInfo to generate code for. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LHSPtr</td>
<td class="doxyParamItemDescription"><p>Optionally used by Clang to return the LHSPtr it used for / codegen, used for fixup later. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RHSPtr</td>
<td class="doxyParamItemDescription"><p>Optionally used by Clang to / return the RHSPtr it used for codegen, used for fixup later. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CurFn</td>
<td class="doxyParamItemDescription"><p>Optionally used by Clang to pass in the Current <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> as / Clang context may be old. using ReductionGenClangCBTy = std::function&lt;<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy(InsertPointTy CodeGenIP, unsigned Index,
                                  Value **LHS, Value **RHS, Function *CurFn)</a>&gt;;</p></td>
</tr>
</table>
</dd>
</dl>

<p>/ ReductionGen CallBack for MLIR / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CodeGenIP</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/irbuilder">InsertPoint</a> for CodeGen. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LHS</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> in the LHS <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to be used for CodeGen. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RHS</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> in the RHS <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to be used for CodeGen. using ReductionGenCBTy = std::function&lt;<a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy(
      InsertPointTy CodeGenIP, Value *LHS, Value *RHS, Value *&amp;Res)</a>&gt;;</p></td>
</tr>
</table>
</dd>
</dl>

<p>/ Functions used to generate atomic reductions. Such functions take two / Values representing pointers to LHS and RHS of the reduction, as well as / the element type of these pointers. They are expected to atomically / update the LHS to the reduced value. using ReductionGenAtomicCBTy = std::function&lt;<a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy(
      InsertPointTy, Type *, Value *, Value *)</a>&gt;;</p>


<p>/ Enum class for reduction evaluation types scalar, complex and aggregate. enum class EvalKind { Scalar, Complex, Aggregate };</p>


<p>/ Information about an OpenMP reduction. struct ReductionInfo { ReductionInfo(Type *ElementType, Value *Variable, Value *PrivateVariable,
                  EvalKind EvaluationKind, ReductionGenCBTy ReductionGen,
                  ReductionGenClangCBTy ReductionGenClang,
                  ReductionGenAtomicCBTy AtomicReductionGen) : ElementType(ElementType), Variable(Variable), PrivateVariable(PrivateVariable), EvaluationKind(EvaluationKind), ReductionGen(ReductionGen), ReductionGenClang(ReductionGenClang), AtomicReductionGen(AtomicReductionGen) {} ReductionInfo(Value *PrivateVariable) : ElementType(nullptr), Variable(nullptr), PrivateVariable(PrivateVariable), EvaluationKind(EvalKind::Scalar), ReductionGen(), ReductionGenClang(), AtomicReductionGen() {}</p>


<p>/ Reduction element type, must match pointee type of variable. <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *ElementType;</p>


<p>/ Reduction variable of pointer type. <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *Variable;</p>


<p>/ Thread-private partial reduction variable. <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *PrivateVariable;</p>


<p>/ Reduction evaluation kind - scalar, complex or aggregate. EvalKind EvaluationKind;</p>


<p>/ Callback for generating the reduction body. The IR produced by this will / be used to combine two values in a thread-safe context, e.g., under / lock or within the same thread, and therefore need not be atomic. ReductionGenCBTy ReductionGen;</p>


<p>/ Clang callback for generating the reduction body. The IR produced by / this will be used to combine two values in a thread-safe context, e.g., / under lock or within the same thread, and therefore need not be atomic. ReductionGenClangCBTy ReductionGenClang;</p>


<p>/ Callback for generating the atomic reduction body, may be null. The IR / produced by this will be used to atomically combine two values during / reduction. If null, the implementation will use the non-atomic version / along with the appropriate synchronization mechanisms. ReductionGenAtomicCBTy AtomicReductionGen; };</p>


<p>enum class CopyAction : unsigned { RemoteLaneToThread: Copy over a Reduce list from a remote lane in the warp using shuffle instructions. RemoteLaneToThread, ThreadCopy: Make a copy of a Reduce list on the thread's stack. ThreadCopy, };</p>


<p>struct CopyOptionsTy { <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *RemoteLaneOffset = nullptr; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *ScratchpadIndex = nullptr; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *ScratchpadWidth = nullptr; };</p>


<p>/ Supporting functions for Reductions CodeGen. private: / Get the id of the current thread on the GPU. <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *getGPUThreadID();</p>


<p>/ Get the GPU warp size. <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *getGPUWarpSize();</p>


<p>/ Get the id of the warp in the block. / We assume that the warp size is 32, which is always the case / on the <a href="/web-llvm/docs/api/namespaces/llvm/nvptx">NVPTX</a> device, to generate more efficient code. <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *getNVPTXWarpID();</p>


<p>/ Get the id of the current lane in the Warp. / We assume that the warp size is 32, which is always the case / on the <a href="/web-llvm/docs/api/namespaces/llvm/nvptx">NVPTX</a> device, to generate more efficient code. <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *getNVPTXLaneID();</p>


<p>/ Cast value to the specified type. <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *castValueToType(<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *From, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *ToType);</p>


<p>/ This function creates calls to one of two shuffle functions to copy / variables between lanes in a warp. <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *createRuntimeShuffleFunction(<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *Element, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *ElementType, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *Offset);</p>


<p>/ <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> to shuffle over the value from the remote lane. void shuffleAndStore(InsertPointTy AllocaIP, Value *SrcAddr, Value *DstAddr,
                       Type *ElementType, Value *Offset,
                       Type *ReductionArrayTy);</p>


<p>/ Emit instructions to copy a Reduce list, which contains partially / aggregated values, in the specified direction. void emitReductionListCopy( <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, CopyAction Action, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *ReductionArrayTy, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef&lt;ReductionInfo&gt;</a> ReductionInfos, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *SrcBase, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *DestBase, CopyOptionsTy CopyOptions = {nullptr, nullptr, nullptr});</p>


<p>/ Emit a helper that reduces data across two OpenMP threads (lanes) / in the same warp. It uses shuffle instructions to copy over data from / a remote lane's stack. The reduction algorithm performed is specified / by the fourth parameter. / / Algorithm Versions. / Full Warp Reduce (argument value 0): / This algorithm assumes that all 32 lanes are active and gathers / data from these 32 lanes, producing a single resultant value. / Contiguous Partial Warp Reduce (argument value 1): / This algorithm assumes that only a <em>contiguous</em> subset of lanes / are active. This happens for the last warp in a parallel region / when the user specified num_threads is not an integer multiple of / 32. This contiguous subset always starts with the zeroth lane. / Partial Warp Reduce (argument value 2): / This algorithm gathers data from any number of lanes at any position. / All reduced values are stored in the lowest possible lane. The set / of problems every algorithm addresses is a super set of those / addressable by algorithms with a lower version number. Overhead / increases as algorithm version increases. / / Terminology / Reduce element: / Reduce element refers to the individual data field with primitive / data types to be combined and reduced across threads. / Reduce list: / Reduce list refers to a collection of local, thread-private / reduce elements. / Remote Reduce list: / Remote Reduce list refers to a collection of remote (relative to / the current thread) reduce elements. / / We distinguish between three states of threads that are important to / the implementation of this function. / Alive threads: / Threads in a warp executing the SIMT instruction, as distinguished from / threads that are inactive due to divergent control flow. / Active threads: / The minimal set of threads that has to be alive upon entry to this / function. The computation is correct iff active threads are alive. / Some threads are alive but they are not active because they do not / contribute to the computation in any useful manner. Turning them off / may introduce control flow overheads without any tangible benefits. / Effective threads: / In order to comply with the argument requirements of the shuffle / function, we must keep all lanes holding data alive. But at most / half of them perform value aggregation; we refer to this half of / threads as effective. The other half is simply handing off their / data. / / Procedure / <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> shuffle: / In this step active threads transfer data from higher lane positions / in the warp to lower lane positions, creating Remote Reduce list. / <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> aggregation: / In this step, effective threads combine their thread local Reduce list / with Remote Reduce list and store the result in the thread local / Reduce list. / <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> copy: / In this step, we deal with the assumption made by algorithm 2 / (i.e. contiguity assumption). When we have an odd number of lanes / active, say 2k+1, only k threads will be effective and therefore k / new values will be produced. However, the Reduce list owned by the / (2k+1)th thread is ignored in the value aggregation. Therefore / we copy the Reduce list from the (2k+1)th lane to (k+1)th lane so / that the contiguity assumption still holds. / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionInfos</td>
<td class="doxyParamItemDescription"><p>Array type containing the ReductionOps. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReduceFn</td>
<td class="doxyParamItemDescription"><p>The reduction function. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FuncAttrs</td>
<td class="doxyParamItemDescription"><p>Optional param to specify any function attributes that / need to be copied to the new function. / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The ShuffleAndReduce function. <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *emitShuffleAndReduceFunction( <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef&lt;OpenMPIRBuilder::ReductionInfo&gt;</a> ReductionInfos, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *ReduceFn, AttributeList FuncAttrs);</p></dd>
</dl>


<p>/ This function emits a helper that gathers Reduce lists from the first / lane of every active warp to lanes in the first warp. / / void inter_warp_copy_func(void* reduce_data, num_warps) / shared smem[warp_size]; / For all data entries D in reduce_data: / sync / If (I am the first lane in each warp) / Copy my local D to smem[warp_id] / sync / if (I am the first warp) / Copy smem[thread_id] to my local D / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionInfos</td>
<td class="doxyParamItemDescription"><p>Array type containing the ReductionOps. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FuncAttrs</td>
<td class="doxyParamItemDescription"><p>Optional param to specify any function attributes that / need to be copied to the new function. / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>The InterWarpCopy function. <a href="/web-llvm/docs/api/classes/llvm/expected">Expected&lt;Function *&gt;</a> emitInterWarpCopyFunction(const LocationDescription &amp;Loc,
                            ArrayRef&lt;ReductionInfo&gt; ReductionInfos,
                            AttributeList FuncAttrs);</p>
</dd>
</dl>


<p>/ This function emits a helper that copies all the reduction variables from / the team into the provided global buffer for the reduction variables. / / void list_to_global_copy_func(void *buffer, int Idx, void *reduce_data) / For all data entries D in reduce_data: / Copy local D to buffer.D[Idx] / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionInfos</td>
<td class="doxyParamItemDescription"><p>Array type containing the ReductionOps. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionsBufferTy</td>
<td class="doxyParamItemDescription"><p>The StructTy for the reductions buffer. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FuncAttrs</td>
<td class="doxyParamItemDescription"><p>Optional param to specify any function attributes that / need to be copied to the new function. / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The ListToGlobalCopy function. <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *emitListToGlobalCopyFunction(<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef&lt;ReductionInfo&gt;</a> ReductionInfos, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *ReductionsBufferTy, AttributeList FuncAttrs);</p></dd>
</dl>


<p>/ This function emits a helper that copies all the reduction variables from / the team into the provided global buffer for the reduction variables. / / void list_to_global_copy_func(void *buffer, int Idx, void *reduce_data) / For all data entries D in reduce_data: / Copy buffer.D[Idx] to local D; / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionInfos</td>
<td class="doxyParamItemDescription"><p>Array type containing the ReductionOps. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionsBufferTy</td>
<td class="doxyParamItemDescription"><p>The StructTy for the reductions buffer. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FuncAttrs</td>
<td class="doxyParamItemDescription"><p>Optional param to specify any function attributes that / need to be copied to the new function. / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The GlobalToList function. <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *emitGlobalToListCopyFunction(<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef&lt;ReductionInfo&gt;</a> ReductionInfos, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *ReductionsBufferTy, AttributeList FuncAttrs);</p></dd>
</dl>


<p>/ This function emits a helper that reduces all the reduction variables from / the team into the provided global buffer for the reduction variables. / / void list_to_global_reduce_func(void &lt;em&gt;buffer, int Idx, void *reduce_data) / void *GlobPtrs[]; / GlobPtrs[0] = (void)&amp;buffer.D0[Idx]; / ... / GlobPtrs[N] = (void*)&amp;buffer.DN[Idx]; / reduce_function(GlobPtrs, reduce_data); / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionInfos</td>
<td class="doxyParamItemDescription"><p>Array type containing the ReductionOps. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReduceFn</td>
<td class="doxyParamItemDescription"><p>The reduction function. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionsBufferTy</td>
<td class="doxyParamItemDescription"><p>The StructTy for the reductions buffer. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FuncAttrs</td>
<td class="doxyParamItemDescription"><p>Optional param to specify any function attributes that / need to be copied to the new function. / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>The ListToGlobalReduce function. <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * emitListToGlobalReduceFunction(ArrayRef&lt;ReductionInfo&gt; ReductionInfos,
                                 Function *ReduceFn, Type *ReductionsBufferTy,
                                 AttributeList FuncAttrs);</p>
</dd>
</dl>


<p>/ This function emits a helper that reduces all the reduction variables from / the team into the provided global buffer for the reduction variables. / / void global_to_list_reduce_func(void &lt;em&gt;buffer, int Idx, void *reduce_data) / void *GlobPtrs[]; / GlobPtrs[0] = (void)&amp;buffer.D0[Idx]; / ... / GlobPtrs[N] = (void*)&amp;buffer.DN[Idx]; / reduce_function(reduce_data, GlobPtrs); / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionInfos</td>
<td class="doxyParamItemDescription"><p>Array type containing the ReductionOps. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReduceFn</td>
<td class="doxyParamItemDescription"><p>The reduction function. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionsBufferTy</td>
<td class="doxyParamItemDescription"><p>The StructTy for the reductions buffer. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FuncAttrs</td>
<td class="doxyParamItemDescription"><p>Optional param to specify any function attributes that / need to be copied to the new function. / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>The GlobalToListReduce function. <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * emitGlobalToListReduceFunction(ArrayRef&lt;ReductionInfo&gt; ReductionInfos,
                                 Function *ReduceFn, Type *ReductionsBufferTy,
                                 AttributeList FuncAttrs);</p>
</dd>
</dl>


<p>/ Get the function name of a reduction function. std::string getReductionFuncName(StringRef Name) const;</p>


<p>/ Emits reduction function. /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReducerName</td>
<td class="doxyParamItemDescription"><p>Name of the function calling the reduction. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionInfos</td>
<td class="doxyParamItemDescription"><p>Array type containing the ReductionOps. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionGenCBKind</td>
<td class="doxyParamItemDescription"><p>Optional param to specify Clang or MLIR / CodeGenCB kind. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FuncAttrs</td>
<td class="doxyParamItemDescription"><p>Optional param to specify any function attributes that / need to be copied to the new function. / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The reduction function. <a href="/web-llvm/docs/api/classes/llvm/expected">Expected&lt;Function *&gt;</a> createReductionFunction( <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ReducerName, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef&lt;ReductionInfo&gt;</a> ReductionInfos, ReductionGenCBKind ReductionGenCBKind = ReductionGenCBKind::MLIR, AttributeList FuncAttrs = {});</p></dd>
</dl>


<p>public: / / Design of OpenMP reductions on the GPU / / Consider a typical OpenMP program with one or more reduction / clauses: / / float foo; / double bar; / #pragma omp target teams distribute parallel for \ / reduction(+:foo) <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/straightlinestrengthreduce-cpp/#a7b51b9df5e7db582597e8556087c71ce">reduction(*:bar)</a> / for (int i = 0; i &lt; N; i++) { / foo += A[i]; bar *= B[i]; / } / / where 'foo' and 'bar' are reduced across all OpenMP threads in / all teams. In our OpenMP implementation on the <a href="/web-llvm/docs/api/namespaces/llvm/nvptx">NVPTX</a> device an / OpenMP team is mapped to a CUDA threadblock and OpenMP threads / within a team are mapped to CUDA threads within a threadblock. / Our goal is to efficiently aggregate values across all OpenMP / threads such that: / / - the compiler and runtime are logically concise, and / - the reduction is performed efficiently in a hierarchical / manner as follows: within OpenMP threads in the same warp, / across warps in a threadblock, and finally across teams on / the <a href="/web-llvm/docs/api/namespaces/llvm/nvptx">NVPTX</a> device. / / Introduction to Decoupling / / We would like to decouple the compiler and the runtime so that the / latter is ignorant of the reduction variables (number, data types) / and the reduction operators. This allows a simpler interface / and implementation while still attaining good performance. / / Pseudocode for the aforementioned OpenMP program generated by the / compiler is as follows: / / 1. Create private copies of reduction variables on each OpenMP / thread: 'foo_private', 'bar_private' / 2. Each OpenMP thread reduces the chunk of 'A' and 'B' assigned / to it and writes the result in 'foo_private' and 'bar_private' / respectively. / 3. Call the OpenMP runtime on the GPU to reduce within a team / and store the result on the team master: / / __kmpc_nvptx_parallel_reduce_nowait_v2(..., / reduceData, shuffleReduceFn, interWarpCpyFn) / / where: / struct ReduceData { / double *foo; / double *bar; / } reduceData / reduceData.foo = &amp;foo_private / reduceData.bar = &amp;bar_private / / 'shuffleReduceFn' and 'interWarpCpyFn' are pointers to two / auxiliary functions generated by the compiler that operate on / variables of type 'ReduceData'. They aid the runtime perform / algorithmic steps in a data agnostic manner. / / 'shuffleReduceFn' is a pointer to a function that reduces data / of type 'ReduceData' across two OpenMP threads (lanes) in the / same warp. It takes the following arguments as input: / / a. variable of type 'ReduceData' on the calling lane, / b. its lane_id, / c. an offset relative to the current lane_id to generate a / remote_lane_id. The remote lane contains the second / variable of type 'ReduceData' that is to be reduced. / d. an algorithm version parameter determining which reduction / algorithm to use. / / 'shuffleReduceFn' retrieves data from the remote lane using / efficient GPU shuffle intrinsics and reduces, using the / algorithm specified by the 4th parameter, the two operands / element-wise. The result is written to the first operand. / / Different reduction algorithms are implemented in different / runtime functions, all calling 'shuffleReduceFn' to perform / the essential reduction step. Therefore, based on the 4th / parameter, this function behaves slightly differently to / cooperate with the runtime to ensure correctness under / different circumstances. / / 'InterWarpCpyFn' is a pointer to a function that transfers / reduced variables across warps. It tunnels, through CUDA / shared memory, the thread-private data of type 'ReduceData' / from lane 0 of each warp to a lane in the first warp. / 4. Call the OpenMP runtime on the GPU to reduce across teams. / The last team writes the global reduced value to memory. / / ret = __kmpc_nvptx_teams_reduce_nowait(..., / reduceData, shuffleReduceFn, interWarpCpyFn, / scratchpadCopyFn, loadAndReduceFn) / / 'scratchpadCopyFn' is a helper that stores reduced / data from the team master to a scratchpad array in / global memory. / / 'loadAndReduceFn' is a helper that loads data from / the scratchpad array and reduces it with the input / operand. / / These compiler generated functions hide address / calculation and alignment information from the runtime. / 5. if ret == 1: / The team master of the last team stores the reduced / result to the globals in memory. / foo += reduceData.foo; bar *= reduceData.bar / / / Warp Reduction Algorithms / / On the warp level, we have three algorithms implemented in the / OpenMP runtime depending on the number of active lanes: / / Full Warp Reduction / / The reduce algorithm within a warp where all lanes are active / is implemented in the runtime as follows: / / full_warp_reduce(void *reduce_data, / kmp_ShuffleReductFctPtr ShuffleReduceFn) { / for (int offset = WARPSIZE/2; offset &gt; 0; offset /= 2) / ShuffleReduceFn(reduce_data, 0, offset, 0); / } / / The algorithm completes in log(2, WARPSIZE) steps. / / 'ShuffleReduceFn' is used here with lane_id set to 0 because it is / not used therefore we save instructions by not retrieving lane_id / from the corresponding special registers. The 4th parameter, which / represents the version of the algorithm being used, is set to 0 to / signify full warp reduction. / / In this version, 'ShuffleReduceFn' behaves, per element, as follows: / / #reduce_elem refers to an element in the local lane's data structure / #remote_elem is retrieved from a remote lane / remote_elem = shuffle_down(reduce_elem, offset, WARPSIZE); / reduce_elem = reduce_elem REDUCE_OP remote_elem; / / Contiguous Partial Warp Reduction / / This reduce algorithm is used within a warp where only the first / 'n' (n &lt;= WARPSIZE) lanes are active. It is typically used when the / number of OpenMP threads in a parallel region is not a multiple of / WARPSIZE. The algorithm is implemented in the runtime as follows: / / void / contiguous_partial_reduce(void *reduce_data, / kmp_ShuffleReductFctPtr ShuffleReduceFn, / int size, int lane_id) { / int curr_size; / int offset; / curr_size = size; / mask = curr_size/2; / while (offset&gt;0) { / ShuffleReduceFn(reduce_data, lane_id, offset, 1); / curr_size = (curr_size+1)/2; / offset = curr_size/2; / } / } / / In this version, 'ShuffleReduceFn' behaves, per element, as follows: / / remote_elem = shuffle_down(reduce_elem, offset, WARPSIZE); / if (lane_id &lt; offset) / reduce_elem = reduce_elem REDUCE_OP remote_elem / else / reduce_elem = remote_elem / / This algorithm assumes that the data to be reduced are located in a / contiguous subset of lanes starting from the first. When there is / an odd number of active lanes, the data in the last lane is not / aggregated with any other lane's dat but is instead copied over. / / Dispersed Partial Warp Reduction / / This algorithm is used within a warp when any discontiguous subset of / lanes are active. It is used to implement the reduction operation / across lanes in an OpenMP simd region or in a nested parallel region. / / void / dispersed_partial_reduce(void *reduce_data, / kmp_ShuffleReductFctPtr ShuffleReduceFn) { / int size, remote_id; / int logical_lane_id = number_of_active_lanes_before_me() * 2; / do { / remote_id = next_active_lane_id_right_after_me(); / # the above function returns 0 of no active lane / # is present right after the current lane. / size = number_of_active_lanes_in_this_warp(); / logical_lane_id /= 2; / ShuffleReduceFn(reduce_data, logical_lane_id, / remote_id-1-threadIdx.x, 2); / } while (logical_lane_id % 2 == 0 &amp;&amp; size &gt; 1); / } / / There is no assumption made about the initial state of the reduction. / <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> number of lanes (&gt;=1) could be active at any position. The reduction / result is returned in the first active lane. / / In this version, 'ShuffleReduceFn' behaves, per element, as follows: / / remote_elem = shuffle_down(reduce_elem, offset, WARPSIZE); / if (lane_id % 2 == 0 &amp;&amp; offset &gt; 0) / reduce_elem = reduce_elem REDUCE_OP remote_elem / else / reduce_elem = remote_elem / / / Intra-Team Reduction / / This function, as implemented in the runtime call / '__kmpc_nvptx_parallel_reduce_nowait_v2', aggregates data across OpenMP / threads in a team. It first reduces within a warp using the / aforementioned algorithms. We then proceed to gather all such / reduced values at the first warp. / / The runtime makes use of the function 'InterWarpCpyFn', which copies / data from each of the "warp master" (zeroth lane of each warp, where / warp-reduced data is held) to the zeroth warp. This step reduces (in / a mathematical sense) the problem of reduction across warp masters in / a block to the problem of warp reduction. / / / Inter-Team Reduction / / Once a team has reduced its data to a single value, it is stored in / a global scratchpad array. Since each team has a distinct slot, this / can be done without locking. / / The last team to write to the scratchpad array proceeds to reduce the / scratchpad array. One or more workers in the last team use the helper / 'loadAndReduceDataFn' to load and reduce values from the array, i.e., / the k'th worker reduces every k'th element. / / Finally, a call is made to '__kmpc_nvptx_parallel_reduce_nowait_v2' to / reduce across workers and compute a globally reduced value. / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location where the reduction was / encountered. Must be within the associate / directive and after the last local access to the / reduction variables. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>An insertion point suitable for allocas usable / in reductions. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CodeGenIP</td>
<td class="doxyParamItemDescription"><p>An insertion point suitable for code / generation.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionInfos</td>
<td class="doxyParamItemDescription"><p>A list of info on each reduction / variable.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsNoWait</td>
<td class="doxyParamItemDescription"><p>Optional flag set if the reduction is / marked as / nowait. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsTeamsReduction</td>
<td class="doxyParamItemDescription"><p>Optional flag set if it is a teams / reduction. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HasDistribute</td>
<td class="doxyParamItemDescription"><p>Optional flag set if it is a / distribute reduction. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GridValue</td>
<td class="doxyParamItemDescription"><p>Optional GPU grid value. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionBufNum</td>
<td class="doxyParamItemDescription"><p>Optional OpenMPCUDAReductionBufNumValue to be / used for teams reduction. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SrcLocInfo</td>
<td class="doxyParamItemDescription"><p>Source location information global. <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a> createReductionsGPU( const <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp;<a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a>, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef&lt;ReductionInfo&gt;</a> ReductionInfos, bool IsNoWait = false, bool IsTeamsReduction = false, bool HasDistribute = false, ReductionGenCBKind ReductionGenCBKind = ReductionGenCBKind::MLIR, std::optional&lt;omp::GV&gt; GridValue = {}, unsigned ReductionBufNum = 1024, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *SrcLocInfo = nullptr);</p></td>
</tr>
</table>
</dd>
</dl>

<p>TODO: provide atomic and non-atomic reduction generators for reduction operators defined by the OpenMP specification.</p>


<p>/ Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> reduction'. / / Emits the IR instructing the runtime to perform the specific kind of / reductions. Expects reduction variables to have been privatized and / initialized to reduction-neutral values separately. Emits the calls to / runtime functions as well as the reduction function and the basic blocks / performing the reduction atomically and non-atomically. / / The code emitted for the following: / /</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///   type var_1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///   type var_2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///   #pragma omp &lt;directive&gt; reduction(reduction-op:var_1,var_2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///   /* body */;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/// </span></span></div>

</div>


<p>/ / corresponds to the following sketch. / /</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/// void _outlined_par() {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///   // N is the number of different reductions.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///   void *red_array[] = {privatized_var_1, privatized_var_2, ...};</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///   switch(__kmpc_reduce(..., N, /*size of data in red array*/, red_array,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///                        _omp_reduction_func,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///                        _gomp_critical_user.reduction.var)) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///   case 1: {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///     var_1 = var_1 &lt;reduction-op&gt; privatized_var_1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///     var_2 = var_2 &lt;reduction-op&gt; privatized_var_2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///     // ...</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///    __kmpc_end_reduce(...);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///     break;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///   case 2: {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///     _Atomic&lt;ReductionOp&gt;(var_1, privatized_var_1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///     _Atomic&lt;ReductionOp&gt;(var_2, privatized_var_2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///     // ...</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///     break;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///   default: break;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/// }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/// void _omp_reduction_func(void **lhs, void **rhs) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///   *(type *)lhs[0] = *(type *)lhs[0] &lt;reduction-op&gt; *(type *)rhs[0];</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///   *(type *)lhs[1] = *(type *)lhs[1] &lt;reduction-op&gt; *(type *)rhs[1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///   // ...</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/// }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/// </span></span></div>

</div>


<p>/ /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location where the reduction was / encountered. Must be within the associate / directive and after the last local access to the / reduction variables. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>An insertion point suitable for allocas usable / in reductions. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReductionInfos</td>
<td class="doxyParamItemDescription"><p>A list of info on each reduction variable. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsNoWait</td>
<td class="doxyParamItemDescription"><p>A flag set if the reduction is marked as nowait. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsByRef</td>
<td class="doxyParamItemDescription"><p>A flag set if the reduction is using reference / or direct value. <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a> createReductions(const <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp;<a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a>, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef&lt;ReductionInfo&gt;</a> ReductionInfos, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef&lt;bool&gt;</a> IsByRef, bool IsNoWait = false);</p></td>
</tr>
</table>
</dd>
</dl>

<p>/}</p>


<p>/ Return the insertion point used by the underlying <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>. <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> getInsertionPoint() { return Builder.saveIP(); }</p>


<p>/ Update the internal location to <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span>. bool updateToLocation(const LocationDescription &amp;Loc) { Builder.restoreIP(Loc.IP); Builder.SetCurrentDebugLocation(Loc.DL); return Loc.IP.getBlock() != nullptr; }</p>


<p>/ Return the function declaration for the runtime function with <span class="doxyComputerOutput">FnID</span>. <a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a> getOrCreateRuntimeFunction(Module &amp;M,
                                            omp::RuntimeFunction FnID);</p>


<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *getOrCreateRuntimeFunctionPtr(<a href="/web-llvm/docs/api/namespaces/llvm/omp/#a4c503140c7f851151906d85b515330e9">omp::RuntimeFunction</a> FnID);</p>


<p>/ Return the (LLVM-IR) string describing the source location <span class="doxyComputerOutput">LocStr</span>. <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *getOrCreateSrcLocStr(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> LocStr, uint32_t &amp;SrcLocStrSize);</p>


<p>/ Return the (LLVM-IR) string describing the default source location. <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *getOrCreateDefaultSrcLocStr(uint32_t &amp;SrcLocStrSize);</p>


<p>/ Return the (LLVM-IR) string describing the source location identified by / the arguments. <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *getOrCreateSrcLocStr(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FunctionName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileName, unsigned Line, unsigned Column, uint32_t &amp;SrcLocStrSize);</p>


<p>/ Return the (LLVM-IR) string describing the <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> <span class="doxyComputerOutput">DL</span>. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <span class="doxyComputerOutput">F</span> as / fallback if <span class="doxyComputerOutput">DL</span> does not specify the function name. <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *getOrCreateSrcLocStr(<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, uint32_t &amp;SrcLocStrSize, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *F = nullptr);</p>


<p>/ Return the (LLVM-IR) string describing the source location <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span>. <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *getOrCreateSrcLocStr(const <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp;<a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a>, uint32_t &amp;SrcLocStrSize);</p>


<p>/ Return an ident_t* encoding the source location <span class="doxyComputerOutput">SrcLocStr</span> and <span class="doxyComputerOutput">Flags</span>. / TODO: Create a enum class for the Reserve2Flags <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *getOrCreateIdent(<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *SrcLocStr, uint32_t SrcLocStrSize, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a0e821d8251c97d66ca185efe2f8ffde2">omp::IdentFlag</a> Flags = <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a0e821d8251c97d66ca185efe2f8ffde2">omp::IdentFlag(0)</a>, unsigned Reserve2Flags = 0);</p>


<p>/ Create a hidden global flag <span class="doxyComputerOutput">Name</span> in the module with initial value <span class="doxyComputerOutput">/</span> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *createGlobalFlag(unsigned <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name);</p>


<p>/ Emit the llvm.used metadata. void emitUsed(StringRef Name, ArrayRef&lt;llvm::WeakTrackingVH&gt; List);</p>


<p>/ Emit the kernel execution mode. <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *emitKernelExecutionMode(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> KernelName, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#aa0c0d79dafb0d22308ce48808689f430">omp::OMPTgtExecModeFlags</a> Mode);</p>


<p>/ Generate control flow and cleanup for cancellation. / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CancelFlag</td>
<td class="doxyParamItemDescription"><p>Flag indicating if the cancellation is performed. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CanceledDirective</td>
<td class="doxyParamItemDescription"><p>The kind of directive that is cancled. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ExitCB</td>
<td class="doxyParamItemDescription"><p>Extra code to be generated in the exit block. / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an error, if any were triggered during execution. <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> emitCancelationCheckImpl(<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *CancelFlag, omp::Directive CanceledDirective, <a href="#a0c571620ff53fdb78e7404f5261dbd23">FinalizeCallbackTy</a> ExitCB = {});</p></dd>
</dl>


<p>/ Generate a target region entry call. / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location at which the request originated and is fulfilled. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>The insertion point to be used for alloca instructions. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Return</td>
<td class="doxyParamItemDescription"><p>Return value of the created function returned by reference. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DeviceID</td>
<td class="doxyParamItemDescription"><p>Identifier for the device via the 'device' clause. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumTeams</td>
<td class="doxyParamItemDescription"><p>Numer of teams for the region via the 'num_teams' clause / or 0 if unspecified and -1 if there is no 'teams' clause. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumThreads</td>
<td class="doxyParamItemDescription"><p>Number of threads via the 'thread_limit' clause. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HostPtr</td>
<td class="doxyParamItemDescription"><p>Pointer to the host-side pointer of the target kernel. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">KernelArgs</td>
<td class="doxyParamItemDescription"><p>Array of arguments to the kernel. <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> emitTargetKernel(const LocationDescription &amp;Loc,
                                 InsertPointTy AllocaIP, Value *&amp;Return,
                                 Value *Ident, Value *DeviceID, Value *NumTeams,
                                 Value *NumThreads, Value *HostPtr,
                                 ArrayRef&lt;Value *&gt; KernelArgs);</p></td>
</tr>
</table>
</dd>
</dl>

<p>/ Generate a flush runtime call. / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location at which the request originated and is fulfilled. void emitFlush(const LocationDescription &amp;Loc);</p></td>
</tr>
</table>
</dd>
</dl>

<p>/ The finalization stack made up of finalize callbacks currently in-flight, / wrapped into <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/finalizationinfo">FinalizationInfo</a> objects that reference also the finalization / target block and the kind of cancellable directive. <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;FinalizationInfo, 8&gt;</a> FinalizationStack;</p>


<p>/ Return true if the last entry in the finalization stack is of kind <span class="doxyComputerOutput">DK</span> / and cancellable. bool isLastFinalizationInfoCancellable(omp::Directive DK) { return !FinalizationStack.empty() &amp;&amp; FinalizationStack.back().IsCancellable &amp;&amp; FinalizationStack.back().DK == DK; }</p>


<p>/ Generate a taskwait runtime call. / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location at which the request originated and is fulfilled. void emitTaskwaitImpl(const LocationDescription &amp;Loc);</p></td>
</tr>
</table>
</dd>
</dl>

<p>/ Generate a taskyield runtime call. / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location at which the request originated and is fulfilled. void emitTaskyieldImpl(const LocationDescription &amp;Loc);</p></td>
</tr>
</table>
</dd>
</dl>

<p>/ Return the current thread <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ident</td>
<td class="doxyParamItemDescription"><p>The ident (ident_t*) describing the query origin. <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *getOrCreateThreadID(<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *Ident);</p></td>
</tr>
</table>
</dd>
</dl>

<p>/ The <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder">OpenMPIRBuilder</a> Configuration <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilderconfig">OpenMPIRBuilderConfig</a> Config;</p>


<p>/ The underlying LLVM-IR module <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;M;</p>


<p>/ The LLVM-IR Builder used to create IR. <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder&lt;&gt;</a> Builder;</p>


<p>/ Map to remember source location strings <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap&lt;Constant *&gt;</a> SrcLocStrMap;</p>


<p>/ Map to remember existing ident_t*. <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt;std::pair&lt;Constant *, uint64_t&gt;, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *&gt; IdentMap;</p>


<p>/ Info manager to keep track of target regions. <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager">OffloadEntriesInfoManager</a> OffloadInfoManager;</p>


<p>/ The target triple of the underlying module. const <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> T;</p>


<p>/ Helper that contains information about regions we need to outline / during finalization. struct OutlineInfo { using PostOutlineCBTy = std::function&lt;void(Function &amp;)&gt;; PostOutlineCBTy PostOutlineCB; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *EntryBB, *ExitBB, *OuterAllocaBB; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;Value *, 2&gt;</a> ExcludeArgsFromAggregate;</p>


<p>/ Collect all blocks in between EntryBB and ExitBB in both the given / vector and set. void collectBlocks(SmallPtrSetImpl&lt;BasicBlock *&gt; &amp;BlockSet,
                       SmallVectorImpl&lt;BasicBlock *&gt; &amp;BlockVector);</p>


<p>/ Return the function that contains the region to be outlined. <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *getFunction() const { return EntryBB-&gt;<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent()</a>; } };</p>


<p>/ Collection of regions that need to be outlined during finalization. <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;OutlineInfo, 16&gt;</a> OutlineInfos;</p>


<p>/ A collection of candidate target functions that's constant allocas will / attempt to be raised on a call of finalize after all currently enqueued / outline info's have been processed. <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;llvm::Function *, 16&gt;</a> ConstantAllocaRaiseCandidates;</p>


<p>/ Collection of owned canonical loop objects that eventually need to be / free'd. std::forward_list&lt;CanonicalLoopInfo&gt; LoopInfos;</p>


<p>/ Add a new region that will be outlined later. void addOutlineInfo(OutlineInfo &amp;&amp;OI) { OutlineInfos.emplace_back(OI); }</p>


<p>/ An ordered map of auto-generated variables to their unique names. / It stores variables with the following names: 1) ".gomp_critical_user_" + / &lt;critical_section_name&gt; + ".var" for "omp critical" directives; 2) / &lt;mangled_name_for_global_var&gt; + ".cache." for cache for threadprivate / variables. <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap&lt;GlobalVariable *, BumpPtrAllocator&gt;</a> InternalVars;</p>


<p>/ Computes the size of type in bytes. <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *getSizeInBytes(<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *BasePtr);</p>


<p>Emit a branch from the current block to the <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> block only if the current block has a terminator. void emitBranch(BasicBlock *Target);</p>


<p>If BB has no use then delete it and return. Else place BB after the current block, if possible, or else at the end of the function. Also add a branch from current block to BB if current block does not have a terminator. void emitBlock(<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *BB, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *CurFn, bool IsFinished = false);</p>


<p>/ Emits code for OpenMP 'if' clause using specified <em><a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a></em> / Here is the logic: / if (Cond) { / ThenGen(); / } else { / ElseGen(); / } / /</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an error, if any were triggered during execution. <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> emitIfClause(<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *Cond, <a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a> ThenGen, <a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a> ElseGen, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP = {});</p></dd>
</dl>


<p>/ Create the global variable holding the offload mappings information. <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *createOffloadMaptypes(<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;uint64_t&gt;</a> &amp;Mappings, std::string VarName);</p>


<p>/ Create the global variable holding the offload names information. <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * createOffloadMapnames(SmallVectorImpl&lt;llvm::Constant *&gt; &amp;Names,
                        std::string VarName);</p>


<p>struct MapperAllocas { <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *ArgsBase = nullptr; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *Args = nullptr; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *ArgSizes = nullptr; };</p>


<p>/ Create the allocas instruction used in call to mapper functions. void createMapperAllocas(const LocationDescription &amp;Loc,
                           InsertPointTy AllocaIP, unsigned NumOperands,
                           struct MapperAllocas &amp;MapperAllocas);</p>


<p>/ Create the call for the target mapper function. /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The source location description. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MapperFunc</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> to be called. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SrcLocInfo</td>
<td class="doxyParamItemDescription"><p>Source location information global. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MaptypesArg</td>
<td class="doxyParamItemDescription"><p>The argument types. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MapnamesArg</td>
<td class="doxyParamItemDescription"><p>The argument names. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MapperAllocas</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> used for the call. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DeviceID</td>
<td class="doxyParamItemDescription"><p>Device <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the call. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumOperands</td>
<td class="doxyParamItemDescription"><p>Number of operands in the call. void emitMapperCall(const LocationDescription &amp;Loc, Function *MapperFunc,
                      Value *SrcLocInfo, Value *MaptypesArg, Value *MapnamesArg,
                      struct MapperAllocas &amp;MapperAllocas, int64_t DeviceID,
                      unsigned NumOperands);</p></td>
</tr>
</table>
</dd>
</dl>

<p>/ Container for the arguments used to pass data to the runtime library. struct TargetDataRTArgs { / The array of base pointer passed to the runtime library. <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *BasePointersArray = nullptr; / The array of section pointers passed to the runtime library. <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *PointersArray = nullptr; / The array of sizes passed to the runtime library. <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *SizesArray = nullptr; / The array of map types passed to the runtime library for the beginning / of the region or for the entire region if there are no separate map / types for the region end. <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *MapTypesArray = nullptr; / The array of map types passed to the runtime library for the end of the / region, or nullptr if there are no separate map types for the region / end. <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *MapTypesArrayEnd = nullptr; / The array of user-defined mappers passed to the runtime library. <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *MappersArray = nullptr; / The array of original declaration names of mapped pointers sent to the / runtime library for debugging <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *MapNamesArray = nullptr;</p>


<p>explicit TargetDataRTArgs() {} explicit TargetDataRTArgs(Value *BasePointersArray, Value *PointersArray,
                              Value *SizesArray, Value *MapTypesArray,
                              Value *MapTypesArrayEnd, Value *MappersArray,
                              Value *MapNamesArray) : BasePointersArray(BasePointersArray), PointersArray(PointersArray), SizesArray(SizesArray), MapTypesArray(MapTypesArray), MapTypesArrayEnd(MapTypesArrayEnd), MappersArray(MappersArray), MapNamesArray(MapNamesArray) {} };</p>


<p>/ Container to pass the default attributes with which a kernel must be / launched, used to set kernel attributes and populate associated static / structures. / / For max values, &lt; 0 means unset, == 0 means set but unknown at compile / time. The number of max values will be 1 except for the case where / ompx_bare is set. struct TargetKernelDefaultAttrs { <a href="/web-llvm/docs/api/namespaces/llvm/omp/#aa0c0d79dafb0d22308ce48808689f430">omp::OMPTgtExecModeFlags</a> ExecFlags = <a href="/web-llvm/docs/api/namespaces/llvm/omp/#aa0c0d79dafb0d22308ce48808689f430afa583a38ff705195c9bce9dec0c5eff8">omp::OMPTgtExecModeFlags::OMP_TGT_EXEC_MODE_GENERIC</a>; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;int32_t, 3&gt;</a> MaxTeams = {-1}; int32_t MinTeams = 1; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;int32_t, 3&gt;</a> MaxThreads = {-1}; int32_t MinThreads = 1; };</p>


<p>/ Container to pass LLVM IR runtime values or constants related to the / number of teams and threads with which the kernel must be launched, as / well as the trip count of the loop, if it is an SPMD or Generic-SPMD / kernel. These must be defined in the host prior to the call to the kernel / launch OpenMP RTL function. struct TargetKernelRuntimeAttrs { <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;Value *, 3&gt;</a> MaxTeams = {nullptr}; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *MinTeams = nullptr; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;Value *, 3&gt;</a> TargetThreadLimit = {nullptr}; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;Value *, 3&gt;</a> TeamsThreadLimit = {nullptr};</p>


<p>/ 'parallel' construct 'num_threads' clause value, if present and it is an / SPMD kernel. <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *MaxThreads = nullptr;</p>


<p>/ Total number of iterations of the SPMD or Generic-SPMD kernel or null if / it is a generic kernel. <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *LoopTripCount = nullptr; };</p>


<p>/ Data structure that contains the needed information to construct the / kernel args vector. struct TargetKernelArgs { / Number of arguments passed to the runtime library. unsigned NumTargetItems = 0; / Arguments passed to the runtime library TargetDataRTArgs RTArgs; / The number of iterations <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *NumIterations = nullptr; / The number of teams. <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef&lt;Value *&gt;</a> NumTeams; / The number of threads. <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef&lt;Value *&gt;</a> NumThreads; / The size of the dynamic shared memory. <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *DynCGGroupMem = nullptr; / True if the kernel has 'no wait' clause. bool HasNoWait = false;</p>


<p>Constructors for TargetKernelArgs. TargetKernelArgs() {} TargetKernelArgs(unsigned NumTargetItems, TargetDataRTArgs RTArgs,
                     Value *NumIterations, ArrayRef&lt;Value *&gt; NumTeams,
                     ArrayRef&lt;Value *&gt; NumThreads, Value *DynCGGroupMem,
                     bool HasNoWait) : NumTargetItems(NumTargetItems), RTArgs(RTArgs), NumIterations(NumIterations), NumTeams(NumTeams), NumThreads(NumThreads), DynCGGroupMem(DynCGGroupMem), HasNoWait(HasNoWait) {} };</p>


<p>/ Create the kernel args vector used by emitTargetKernel. This function / creates various constant values that are used in the resulting args / vector. static void getKernelArgsVector(TargetKernelArgs &amp;KernelArgs,
                                  IRBuilderBase &amp;Builder,
                                  SmallVector&lt;Value *&gt; &amp;ArgsVector);</p>


<p>/ Struct that keeps the information that should be kept throughout / a 'target data' region. class TargetDataInfo { / Set to true if device pointer information have to be obtained. bool RequiresDevicePointerInfo = false; / Set to true if Clang emits separate runtime calls for the beginning and / end of the region. These calls might have separate map type arrays. bool SeparateBeginEndCalls = false;</p>


<p>public: TargetDataRTArgs RTArgs;</p>


<p><a href="/web-llvm/docs/api/structs/llvm/smallmapvector">SmallMapVector</a>&lt;const <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, std::pair&lt;Value *, Value *&gt;, 4&gt; DevicePtrInfoMap;</p>


<p>/ Indicate whether any user-defined mapper exists. bool HasMapper = false; / The total number of pointers passed to the runtime library. unsigned NumberOfPtrs = 0u;</p>


<p>bool EmitDebug = false;</p>


<p>/ Whether the <span class="doxyComputerOutput">target ... data</span> directive has a <span class="doxyComputerOutput">nowait</span> clause. bool HasNoWait = false;</p>


<p>explicit TargetDataInfo() {} explicit TargetDataInfo(bool RequiresDevicePointerInfo,
                            bool SeparateBeginEndCalls) : RequiresDevicePointerInfo(RequiresDevicePointerInfo), SeparateBeginEndCalls(SeparateBeginEndCalls) {} / Clear information about the data arrays. void clearArrayInfo() { RTArgs = TargetDataRTArgs(); HasMapper = false; NumberOfPtrs = 0u; } / Return true if the current target data information has valid arrays. bool <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a103d8cfe62c1651cd70e181746f8a840">isValid()</a> { return RTArgs.BasePointersArray &amp;&amp; RTArgs.PointersArray &amp;&amp; RTArgs.SizesArray &amp;&amp; RTArgs.MapTypesArray &amp;&amp; (!HasMapper || RTArgs.MappersArray) &amp;&amp; NumberOfPtrs; } bool requiresDevicePointerInfo() { return RequiresDevicePointerInfo; } bool separateBeginEndCalls() { return SeparateBeginEndCalls; } };</p>


<p>enum class DeviceInfoTy { None, Pointer, Address }; using MapValuesArrayTy = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;Value *, 4&gt;</a>; using MapDeviceInfoArrayTy = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;DeviceInfoTy, 4&gt;</a>; using MapFlagsArrayTy = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;omp::OpenMPOffloadMappingFlags, 4&gt;</a>; using MapNamesArrayTy = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;Constant *, 4&gt;</a>; using MapDimArrayTy = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;uint64_t, 4&gt;</a>; using MapNonContiguousArrayTy = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;MapValuesArrayTy, 4&gt;</a>;</p>


<p>/ This structure contains combined information generated for mappable / clauses, including base pointers, pointers, sizes, map types, user-defined / mappers, and non-contiguous information. struct MapInfosTy { struct StructNonContiguousInfo { bool IsNonContiguous = false; MapDimArrayTy Dims; MapNonContiguousArrayTy Offsets; MapNonContiguousArrayTy Counts; MapNonContiguousArrayTy Strides; }; MapValuesArrayTy BasePointers; MapValuesArrayTy Pointers; MapDeviceInfoArrayTy DevicePointers; MapValuesArrayTy Sizes; MapFlagsArrayTy Types; MapNamesArrayTy Names; StructNonContiguousInfo NonContigInfo;</p>


<p>/ Append arrays in <em>CurInfo</em>. void append(MapInfosTy &amp;CurInfo) { BasePointers.append(CurInfo.BasePointers.begin(), CurInfo.BasePointers.end()); Pointers.append(CurInfo.Pointers.begin(), CurInfo.Pointers.end()); DevicePointers.append(CurInfo.DevicePointers.begin(), CurInfo.DevicePointers.end()); Sizes.append(CurInfo.Sizes.begin(), CurInfo.Sizes.end()); Types.append(CurInfo.Types.begin(), CurInfo.Types.end()); Names.append(CurInfo.Names.begin(), CurInfo.Names.end()); NonContigInfo.Dims.append(CurInfo.NonContigInfo.Dims.begin(), CurInfo.NonContigInfo.Dims.end()); NonContigInfo.Offsets.append(CurInfo.NonContigInfo.Offsets.begin(), CurInfo.NonContigInfo.Offsets.end()); NonContigInfo.Counts.append(CurInfo.NonContigInfo.Counts.begin(), CurInfo.NonContigInfo.Counts.end()); NonContigInfo.Strides.append(CurInfo.NonContigInfo.Strides.begin(), CurInfo.NonContigInfo.Strides.end()); } };</p>


<p>/ Callback function type for functions emitting the host fallback code that / is executed when the kernel launch fails. It takes an insertion point as / parameter where the code should be emitted. It returns an insertion point / that points right after after the emitted code. using EmitFallbackCallbackTy = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref&lt;InsertPointOrErrorTy(InsertPointTy)&gt;</a>;</p>


<p>/ Generate a target region entry call and host fallback call. / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location at which the request originated and is fulfilled. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OutlinedFnID</td>
<td class="doxyParamItemDescription"><p>The ooulined function <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EmitTargetCallFallbackCB</td>
<td class="doxyParamItemDescription"><p>Call back function to generate host / fallback code. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Args</td>
<td class="doxyParamItemDescription"><p>Data structure holding information about the kernel arguments. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DeviceID</td>
<td class="doxyParamItemDescription"><p>Identifier for the device via the 'device' clause. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RTLoc</td>
<td class="doxyParamItemDescription"><p>Source location identifier /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>The insertion point to be used for alloca instructions. <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a> emitKernelLaunch(const LocationDescription &amp;Loc, Value *OutlinedFnID,
                   EmitFallbackCallbackTy EmitTargetCallFallbackCB,
                   TargetKernelArgs &amp;Args, Value *DeviceID, Value *RTLoc,
                   InsertPointTy AllocaIP);</p></td>
</tr>
</table>
</dd>
</dl>

<p>/ Callback type for generating the bodies of device directives that require / outer target tasks (e.g. in case of having <span class="doxyComputerOutput">nowait</span> or <span class="doxyComputerOutput">depend</span> clauses). / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DeviceID</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the device on which the target region will / execute. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RTLoc</td>
<td class="doxyParamItemDescription"><p>Source location identifier / \Param TargetTaskAllocaIP Insertion point for the alloca block of the / generated task. / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>an error, if any were triggered during execution. using TargetTaskBodyCallbackTy = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt;<a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">Error(Value *DeviceID, Value *RTLoc,
                         IRBuilderBase::InsertPoint TargetTaskAllocaIP)</a>&gt;;</p>
</dd>
</dl>


<p>/ Generate a target-task for the target construct / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">TaskBodyCB</td>
<td class="doxyParamItemDescription"><p>Callback to generate the actual body of the target task. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DeviceID</td>
<td class="doxyParamItemDescription"><p>Identifier for the device via the 'device' clause. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RTLoc</td>
<td class="doxyParamItemDescription"><p>Source location identifier /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>The insertion point to be used for alloca instructions. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Dependencies</td>
<td class="doxyParamItemDescription"><p>Vector of <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/dependdata">DependData</a> objects holding information of / dependencies as specified by the 'depend' clause. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HasNoWait</td>
<td class="doxyParamItemDescription"><p>True if the target construct had 'nowait' on it, false / otherwise <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a> emitTargetTask(
      TargetTaskBodyCallbackTy TaskBodyCB, Value *DeviceID, Value *RTLoc,
      OpenMPIRBuilder::InsertPointTy AllocaIP,
      const SmallVector&lt;llvm::OpenMPIRBuilder::DependData&gt; &amp;Dependencies,
      bool HasNoWait);</p></td>
</tr>
</table>
</dd>
</dl>

<p>/ Emit the arguments to be passed to the runtime library based on the / arrays of base pointers, pointers, sizes, map types, and mappers. If / ForEndCall, emit map types to be passed for the end of the region instead / of the beginning. void emitOffloadingArraysArgument(<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp;Builder, OpenMPIRBuilder::TargetDataRTArgs &amp;RTArgs, OpenMPIRBuilder::TargetDataInfo &amp;Info, bool ForEndCall = false);</p>


<p>/ Emit an array of struct descriptors to be assigned to the offload args. void emitNonContiguousDescriptor(InsertPointTy AllocaIP,
                                   InsertPointTy CodeGenIP,
                                   MapInfosTy &amp;CombinedInfo,
                                   TargetDataInfo &amp;Info);</p>


<p>/ Emit the arrays used to pass the captures and map information to the / offloading runtime library. If there is no map or capture information, / return nullptr by reference. Accepts a reference to a MapInfosTy object / that contains information generated for mappable clauses, / including base pointers, pointers, sizes, map types, user-defined mappers. void emitOffloadingArrays( <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP, MapInfosTy &amp;CombinedInfo, TargetDataInfo &amp;Info, bool IsNonContiguous = false, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref&lt;void(unsigned int, Value *)&gt;</a> DeviceAddrCB = nullptr, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref&lt;Value *(unsigned int)&gt;</a> CustomMapperCB = nullptr);</p>


<p>/ Allocates memory for and populates the arrays required for offloading / (offload_{baseptrs|ptrs|mappers|sizes|maptypes|mapnames}). Then, it / emits their base addresses as arguments to be passed to the runtime / library. In essence, this function is a combination of / emitOffloadingArrays and emitOffloadingArraysArgument and should arguably / be preferred by clients of <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder">OpenMPIRBuilder</a>. void emitOffloadingArraysAndArgs( <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP, TargetDataInfo &amp;Info, TargetDataRTArgs &amp;RTArgs, MapInfosTy &amp;CombinedInfo, bool IsNonContiguous = false, bool ForEndCall = false, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref&lt;void(unsigned int, Value *)&gt;</a> DeviceAddrCB = nullptr, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref&lt;Value *(unsigned int)&gt;</a> CustomMapperCB = nullptr);</p>


<p>/ Creates offloading entry for the provided entry <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> <em><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></em>, address <em>/</em> Addr, size <em>Size</em>, and flags <em>Flags</em>. void createOffloadEntry(<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *ID, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *Addr, uint64_t Size, int32_t Flags, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name = "");</p>


<p>/ The kind of errors that can occur when emitting the offload entries and / metadata. enum EmitMetadataErrorKind { EMIT_MD_TARGET_REGION_ERROR, EMIT_MD_DECLARE_TARGET_ERROR, EMIT_MD_GLOBAL_VAR_LINK_ERROR };</p>


<p>/ Callback function type using EmitMetadataErrorReportFunctionTy = std::function&lt;void(EmitMetadataErrorKind, TargetRegionEntryInfo)&gt;;</p>


<p>Emit the offloading entries and metadata so that the device codegen side can easily figure out what to emit. The produced metadata looks like this:</p>


<p>!omp_offload.info = !{!1, ...}</p>


<p>We only generate metadata for function that contain target regions. void createOffloadEntriesAndInfoMetadata(
      EmitMetadataErrorReportFunctionTy &amp;ErrorReportFunction);</p>


<p>public: / Generator for __kmpc_copyprivate / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The source location description. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BufSize</td>
<td class="doxyParamItemDescription"><p>Number of elements in the buffer. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CpyBuf</td>
<td class="doxyParamItemDescription"><p>List of pointers to data to be copied. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CpyFn</td>
<td class="doxyParamItemDescription"><p>function to call for copying data. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DidIt</td>
<td class="doxyParamItemDescription"><p>flag variable; 1 for 'single' thread, 0 otherwise. / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion position <em>after</em> the CopyPrivate call.</p></dd>
</dl>


<p><a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> createCopyPrivate(const LocationDescription &amp;Loc,
                                  llvm::Value *BufSize, llvm::Value *CpyBuf,
                                  llvm::Value *CpyFn, llvm::Value *DidIt);</p>


<p>/ Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> single' / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The source location description. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the region code. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FiniCB</td>
<td class="doxyParamItemDescription"><p>Callback to finalize variable copies. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsNowait</td>
<td class="doxyParamItemDescription"><p>If false, a barrier is emitted. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CPVars</td>
<td class="doxyParamItemDescription"><p>copyprivate variables. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CPFuncs</td>
<td class="doxyParamItemDescription"><p>copy functions to use for each copyprivate variable. / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion position <em>after</em> the single call. <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a> createSingle(const <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp;<a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a>, <a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a> BodyGenCB, <a href="#a0c571620ff53fdb78e7404f5261dbd23">FinalizeCallbackTy</a> FiniCB, bool IsNowait, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef&lt;llvm::Value *&gt;</a> CPVars = {}, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef&lt;llvm::Function *&gt;</a> CPFuncs = {});</p></dd>
</dl>


<p>/ Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> master' / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the region code. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FiniCB</td>
<td class="doxyParamItemDescription"><p>Callback to finalize variable copies. / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>The insertion position <em>after</em> the master. <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a> createMaster(const LocationDescription &amp;Loc,
                                    BodyGenCallbackTy BodyGenCB,
                                    FinalizeCallbackTy FiniCB);</p>
</dd>
</dl>


<p>/ Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> masked' / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the region code. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FiniCB</td>
<td class="doxyParamItemDescription"><p>Callback to finialize variable copies. / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>The insertion position <em>after</em> the masked. <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a> createMasked(const LocationDescription &amp;Loc,
                                    BodyGenCallbackTy BodyGenCB,
                                    FinalizeCallbackTy FiniCB, Value *Filter);</p>
</dd>
</dl>


<p>/ Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> critical' / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the region body code. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FiniCB</td>
<td class="doxyParamItemDescription"><p>Callback to finalize variable copies. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CriticalName</td>
<td class="doxyParamItemDescription"><p>name of the lock used by the critical directive /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HintInst</td>
<td class="doxyParamItemDescription"><p>Hint <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> for hint clause associated with critical / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>The insertion position <em>after</em> the critical. <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a> createCritical(const LocationDescription &amp;Loc,
                                      BodyGenCallbackTy BodyGenCB,
                                      FinalizeCallbackTy FiniCB,
                                      StringRef CriticalName, Value *HintInst);</p>
</dd>
</dl>


<p>/ Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> ordered depend (source | sink)' / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>The insertion point to be used for alloca instructions. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumLoops</td>
<td class="doxyParamItemDescription"><p>The number of loops in depend clause. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">StoreValues</td>
<td class="doxyParamItemDescription"><p>The value will be stored in vector address. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>The name of alloca instruction. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsDependSource</td>
<td class="doxyParamItemDescription"><p>If true, depend source; otherwise, depend sink. / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>The insertion position <em>after</em> the ordered. <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> createOrderedDepend(const LocationDescription &amp;Loc,
                                    InsertPointTy AllocaIP, unsigned NumLoops,
                                    ArrayRef&lt;llvm::Value *&gt; StoreValues,
                                    const Twine &amp;Name, bool IsDependSource);</p>
</dd>
</dl>


<p>/ Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> ordered [threads | simd]' / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the region code. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FiniCB</td>
<td class="doxyParamItemDescription"><p>Callback to finalize variable copies. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsThreads</td>
<td class="doxyParamItemDescription"><p>If true, with threads clause or without clause; / otherwise, with simd clause; / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>The insertion position <em>after</em> the ordered. <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a> createOrderedThreadsSimd(const LocationDescription &amp;Loc,
                                                BodyGenCallbackTy BodyGenCB,
                                                FinalizeCallbackTy FiniCB,
                                                bool IsThreads);</p>
</dd>
</dl>


<p>/ Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> sections' / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>The insertion points to be used for alloca instructions. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SectionCBs</td>
<td class="doxyParamItemDescription"><p>Callbacks that will generate body of each section. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PrivCB</td>
<td class="doxyParamItemDescription"><p>Callback to copy a given variable (think copy constructor). /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FiniCB</td>
<td class="doxyParamItemDescription"><p>Callback to finalize variable copies. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsCancellable</td>
<td class="doxyParamItemDescription"><p>Flag to indicate a cancellable parallel region. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsNowait</td>
<td class="doxyParamItemDescription"><p>If true, barrier - to ensure all sections are executed / before moving forward will not be generated. /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>The insertion position <em>after</em> the sections. <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a> createSections(const LocationDescription &amp;Loc, InsertPointTy AllocaIP,
                 ArrayRef&lt;StorableBodyGenCallbackTy&gt; SectionCBs,
                 PrivatizeCallbackTy PrivCB, FinalizeCallbackTy FiniCB,
                 bool IsCancellable, bool IsNowait);</p>
</dd>
</dl>


<p>/ Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> section' / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the region body code. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FiniCB</td>
<td class="doxyParamItemDescription"><p>Callback to finalize variable copies. /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>The insertion position <em>after</em> the section. <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a> createSection(const LocationDescription &amp;Loc,
                                     BodyGenCallbackTy BodyGenCB,
                                     FinalizeCallbackTy FiniCB);</p>
</dd>
</dl>


<p>/ Generator for <span class="doxyComputerOutput">#omp teams</span> / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location where the teams construct was encountered. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the region code. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumTeamsLower</td>
<td class="doxyParamItemDescription"><p>Lower bound on number of teams. If this is nullptr, / it is as if lower bound is specified as equal to upperbound. If / this is non-null, then upperbound must also be non-null. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumTeamsUpper</td>
<td class="doxyParamItemDescription"><p>Upper bound on the number of teams. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ThreadLimit</td>
<td class="doxyParamItemDescription"><p>on the number of threads that may participate in a / contention group created by each team. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IfExpr</td>
<td class="doxyParamItemDescription"><p>is the integer argument value of the if condition on the / teams clause. <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a> createTeams(const <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp;<a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a>, <a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a> BodyGenCB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *NumTeamsLower = nullptr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *NumTeamsUpper = nullptr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *ThreadLimit = nullptr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *IfExpr = nullptr);</p></td>
</tr>
</table>
</dd>
</dl>

<p>/ Generate conditional branch and relevant BasicBlocks through which private / threads copy the 'copyin' variables from Master copy to threadprivate / copies. / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">IP</td>
<td class="doxyParamItemDescription"><p>insertion block for copyin conditional /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MasterVarPtr</td>
<td class="doxyParamItemDescription"><p>a pointer to the master variable /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PrivateVarPtr</td>
<td class="doxyParamItemDescription"><p>a pointer to the threadprivate variable /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IntPtrTy</td>
<td class="doxyParamItemDescription"><p>Pointer size type /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BranchtoEnd</td>
<td class="doxyParamItemDescription"><p>Create a branch between the copyin.not.master blocks and copy.in.end block / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion point where copying operation to be emitted. <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> createCopyinClauseBlocks(<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> IP, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *MasterAddr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *PrivateAddr, <a href="/web-llvm/docs/api/classes/llvm/integertype">llvm::IntegerType</a> *IntPtrTy, bool BranchtoEnd = true);</p></dd>
</dl>


<p>/ Create a runtime call for kmpc_Alloc / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>Size of allocated memory space /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Allocator</td>
<td class="doxyParamItemDescription"><p>Allocator information instruction /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Name of call <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> for OMP_alloc / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> to the OMP_Alloc call <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *createOMPAlloc(const <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp;<a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a>, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *Size, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *Allocator, std::string Name = "");</p></dd>
</dl>


<p>/ Create a runtime call for kmpc_free / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Addr</td>
<td class="doxyParamItemDescription"><p>Address of memory space to be freed /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Allocator</td>
<td class="doxyParamItemDescription"><p>Allocator information instruction /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Name of call <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> for OMP_Free / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> to the OMP_Free call <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *createOMPFree(const <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp;<a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a>, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *Addr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *Allocator, std::string Name = "");</p></dd>
</dl>


<p>/ Create a runtime call for kmpc_threadprivate_cached / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Pointer</td>
<td class="doxyParamItemDescription"><p>pointer to data to be cached /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>size of data to be cached /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Name of call <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> for callinst / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> to the thread private cache call. <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *createCachedThreadPrivate(const <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp;<a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a>, <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> *Pointer, <a href="/web-llvm/docs/api/classes/llvm/constantint">llvm::ConstantInt</a> *Size, const <a href="/web-llvm/docs/api/classes/llvm/twine">llvm::Twine</a> &amp;Name = <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a>(""));</p></dd>
</dl>


<p>/ Create a runtime call for __tgt_interop_init / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InteropVar</td>
<td class="doxyParamItemDescription"><p>variable to be allocated /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InteropType</td>
<td class="doxyParamItemDescription"><p>type of interop operation /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Device</td>
<td class="doxyParamItemDescription"><p>devide to which offloading will occur /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumDependences</td>
<td class="doxyParamItemDescription"><p>number of dependence variables /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DependenceAddress</td>
<td class="doxyParamItemDescription"><p>pointer to dependence variables /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HaveNowaitClause</td>
<td class="doxyParamItemDescription"><p>does nowait clause exist / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> to the __tgt_interop_init call <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *createOMPInteropInit(const <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp;<a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a>, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *InteropVar, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#afeaad9a7fc12d9246c2e42578fddc718">omp::OMPInteropType</a> InteropType, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *Device, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *NumDependences, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *DependenceAddress, bool HaveNowaitClause);</p></dd>
</dl>


<p>/ Create a runtime call for __tgt_interop_destroy / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InteropVar</td>
<td class="doxyParamItemDescription"><p>variable to be allocated /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Device</td>
<td class="doxyParamItemDescription"><p>devide to which offloading will occur /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumDependences</td>
<td class="doxyParamItemDescription"><p>number of dependence variables /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DependenceAddress</td>
<td class="doxyParamItemDescription"><p>pointer to dependence variables /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HaveNowaitClause</td>
<td class="doxyParamItemDescription"><p>does nowait clause exist / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> to the __tgt_interop_destroy call <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *createOMPInteropDestroy(const <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp;<a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a>, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *InteropVar, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *Device, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *NumDependences, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *DependenceAddress, bool HaveNowaitClause);</p></dd>
</dl>


<p>/ Create a runtime call for __tgt_interop_use / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InteropVar</td>
<td class="doxyParamItemDescription"><p>variable to be allocated /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Device</td>
<td class="doxyParamItemDescription"><p>devide to which offloading will occur /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumDependences</td>
<td class="doxyParamItemDescription"><p>number of dependence variables /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DependenceAddress</td>
<td class="doxyParamItemDescription"><p>pointer to dependence variables /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HaveNowaitClause</td>
<td class="doxyParamItemDescription"><p>does nowait clause exist / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> to the __tgt_interop_use call <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *createOMPInteropUse(const <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp;<a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a>, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *InteropVar, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *Device, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *NumDependences, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *DependenceAddress, bool HaveNowaitClause);</p></dd>
</dl>


<p>/ The <span class="doxyComputerOutput">omp target</span> interface / / For more information about the usage of this interface, /</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>openmp/libomptarget/deviceRTLs/common/include/target.h / /{</p></dd>
</dl>


<p>/ Create a runtime call for kmpc_target_init / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Attrs</td>
<td class="doxyParamItemDescription"><p>Structure containing the default attributes, including / numbers of threads and teams to launch the kernel with. <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> createTargetInit(
      const LocationDescription &amp;Loc,
      const llvm::OpenMPIRBuilder::TargetKernelDefaultAttrs &amp;Attrs);</p></td>
</tr>
</table>
</dd>
</dl>

<p>/ Create a runtime call for kmpc_target_deinit / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TeamsReductionDataSize</td>
<td class="doxyParamItemDescription"><p>The maximal size of all the reduction data / for teams reduction. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TeamsReductionBufferLength</td>
<td class="doxyParamItemDescription"><p>The number of elements (each of up to / <span class="doxyComputerOutput">TeamsReductionDataSize</span> size), in the teams reduction buffer. void createTargetDeinit(const <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp;<a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a>, int32_t TeamsReductionDataSize = 0, int32_t TeamsReductionBufferLength = 1024);</p></td>
</tr>
</table>
</dd>
</dl>

<p>/}</p>


<p>/ Helpers to read/write kernel annotations from the IR. / /{</p>


<p>/ Read/write a bounds on threads for <span class="doxyComputerOutput">Kernel</span>. Read will return 0 if none / is set. static std::pair&lt;int32_t, int32_t&gt; readThreadBoundsForKernel(const Triple &amp;T, Function &amp;Kernel); static void writeThreadBoundsForKernel(const Triple &amp;T, Function &amp;Kernel,
                                         int32_t LB, int32_t UB);</p>


<p>/ Read/write a bounds on teams for <span class="doxyComputerOutput">Kernel</span>. Read will return 0 if none / is set. static std::pair&lt;int32_t, int32_t&gt; readTeamBoundsForKernel(const Triple &amp;T,
                                                             Function &amp;Kernel); static void writeTeamsForKernel(const Triple &amp;T, Function &amp;Kernel, int32_t LB,
                                  int32_t UB); /}</p>


<p>private: Sets the function attributes expected for the outlined function void setOutlinedTargetRegionFunctionAttributes(Function *OutlinedFn);</p>


<p>Creates the function ID/Address for the given outlined function. In the case of an embedded device function the address of the function is used, in the case of a non-offload function a constant is created. <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *createOutlinedFunctionID(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *OutlinedFn, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> EntryFnIDName);</p>


<p>Creates the region entry address for the outlined function <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *createTargetRegionEntryAddr(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *OutlinedFunction, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> EntryFnName);</p>


<p>public: / Functions used to generate a function with the given name. using FunctionGenCallback = std::function&lt;Expected&lt;Function *&gt;(StringRef FunctionName)&gt;;</p>


<p>/ Create a unique name for the entry function using the source location / information of the current target region. The name will be something like: / / __omp_offloading_DD_FFFF_PP_lBB[_CC] / / where DD_FFFF is an <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> unique to the file (device and file IDs), PP is the / mangled name of the function that encloses the target region and BB is the / line number of the target region. CC is a count added when more than one / region is located at the same location. / / If this target outline function is not an offload entry, we don't need to / register it. This may happen if it is guarded by an if clause that is / false at compile time, or no target archs have been specified. / / The created target region <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> is used by the runtime library to identify / the current target region, so it only has to be unique and not / necessarily point to anything. It could be the pointer to the outlined / function that implements the target region, but we aren't using that so / that the compiler doesn't need to keep that, and could therefore inline / the host function if proven worthwhile during optimization. In the other / hand, if emitting code for the device, the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> has to be the function / address so that it can retrieved from the offloading entry and launched / by the runtime library. We also mark the outlined function to have / external linkage in case we are emitting code for the device, because / these functions will be entry points to the device. / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">InfoManager</td>
<td class="doxyParamItemDescription"><p>The info manager keeping track of the offload entries /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EntryInfo</td>
<td class="doxyParamItemDescription"><p>The entry information about the function /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GenerateFunctionCallback</td>
<td class="doxyParamItemDescription"><p>The callback function to generate the code /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OutlinedFunction</td>
<td class="doxyParamItemDescription"><p>Pointer to the outlined function /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EntryFnIDName</td>
<td class="doxyParamItemDescription"><p>Name of the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> o be created <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> emitTargetRegionFunction(TargetRegionEntryInfo &amp;EntryInfo,
                                 FunctionGenCallback &amp;GenerateFunctionCallback,
                                 bool IsOffloadEntry, Function *&amp;OutlinedFn,
                                 Constant *&amp;OutlinedFnID);</p></td>
</tr>
</table>
</dd>
</dl>

<p>/ Registers the given function and sets up the attribtues of the function / Returns the FunctionID. / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">InfoManager</td>
<td class="doxyParamItemDescription"><p>The info manager keeping track of the offload entries /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EntryInfo</td>
<td class="doxyParamItemDescription"><p>The entry information about the function /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OutlinedFunction</td>
<td class="doxyParamItemDescription"><p>Pointer to the outlined function /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EntryFnName</td>
<td class="doxyParamItemDescription"><p>Name of the outlined function /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EntryFnIDName</td>
<td class="doxyParamItemDescription"><p>Name of the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> o be created <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *registerTargetRegionFunction(<a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo">TargetRegionEntryInfo</a> &amp;EntryInfo, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *OutlinedFunction, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> EntryFnName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> EntryFnIDName);</p></td>
</tr>
</table>
</dd>
</dl>

<p>/ <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> of BodyGen to use for region codegen / / Priv: If device pointer privatization is required, emit the body of the / region here. It will have to be duplicated: with and without / privatization. / DupNoPriv: If we need device pointer privatization, we need / to emit the body of the region with no privatization in the 'else' branch / of the conditional. / NoPriv: If we don't require privatization of device / pointers, we emit the body in between the runtime calls. This avoids / duplicating the body code. enum BodyGenTy { Priv, DupNoPriv, NoPriv };</p>


<p>/ Callback type for creating the map infos for the kernel parameters. /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CodeGenIP</td>
<td class="doxyParamItemDescription"><p>is the insertion point where code should be generated, / if any. using GenMapInfoCallbackTy = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref&lt;MapInfosTy &amp;(InsertPointTy CodeGenIP)&gt;</a>;</p></td>
</tr>
</table>
</dd>
</dl>

<p>private: / Emit the array initialization or deletion portion for user-defined mapper / code generation. First, it evaluates whether an array section is mapped / and whether the <em>MapType</em> instructs to delete this section. If <em>IsInit</em> / is true, and <em>MapType</em> indicates to not delete this array, array / initialization code is generated. If <em>IsInit</em> is false, and <em>MapType</em> / indicates to delete this array, array deletion code is generated. void emitUDMapperArrayInitOrDel(Function *MapperFn, llvm::Value *MapperHandle,
                                  llvm::Value *Base, llvm::Value *Begin,
                                  llvm::Value *Size, llvm::Value *MapType,
                                  llvm::Value *MapName, TypeSize ElementSize,
                                  llvm::BasicBlock *ExitBB, bool IsInit);</p>


<p>public: / Emit the user-defined mapper function. The code generation follows the / pattern in the example below. /</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/// void .omp_mapper.&lt;type_name&gt;.&lt;mapper_id&gt;.(void *rt_mapper_handle,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///                                           void *base, void *begin,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///                                           int64_t size, int64_t type,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///                                           void *name = nullptr) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///   // Allocate space for an array section first or add a base/begin for</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///   // pointer dereference.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///   if ((size &gt; 1 || (base != begin &amp;&amp; maptype.IsPtrAndObj)) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///       !maptype.IsDelete)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///     __tgt_push_mapper_component(rt_mapper_handle, base, begin,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///                                 size*sizeof(Ty), clearToFromMember(type));</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///   // Map members.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///   for (unsigned i = 0; i &lt; size; i++) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///     // For each component specified by this mapper:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///     for (auto c : begin[i]-&gt;all_components) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///       if (c.hasMapper())</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///         (*c.Mapper())(rt_mapper_handle, c.arg_base, c.arg_begin,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///         c.arg_size,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///                       c.arg_type, c.arg_name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///       else</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///         __tgt_push_mapper_component(rt_mapper_handle, c.arg_base,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///                                     c.arg_begin, c.arg_size, c.arg_type,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///                                     c.arg_name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///   // Delete the array section.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///   if (size &gt; 1 &amp;&amp; maptype.IsDelete)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///     __tgt_push_mapper_component(rt_mapper_handle, base, begin,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">///                                 size*sizeof(Ty), clearToFromMember(type));</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/// }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/// </span></span></div>

</div>


<p>/ /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">PrivAndGenMapInfoCB</td>
<td class="doxyParamItemDescription"><p>Callback that privatizes code and populates the / MapInfos and returns. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ElemTy</td>
<td class="doxyParamItemDescription"><p>DeclareMapper element type. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FuncName</td>
<td class="doxyParamItemDescription"><p>Optional param to specify mapper function name. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CustomMapperCB</td>
<td class="doxyParamItemDescription"><p>Optional callback to generate code related to / custom mappers. <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *emitUserDefinedMapper( <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt;MapInfosTy &amp;(<a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP, <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> *PtrPHI, <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> *BeginArg)&gt; PrivAndGenMapInfoCB, <a href="/web-llvm/docs/api/classes/llvm/type">llvm::Type</a> *ElemTy, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FuncName, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref&lt;bool(unsigned int, Function **)&gt;</a> CustomMapperCB = nullptr);</p></td>
</tr>
</table>
</dd>
</dl>

<p>/ Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> target data' / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location where the target data construct was encountered. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>The insertion points to be used for alloca instructions. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CodeGenIP</td>
<td class="doxyParamItemDescription"><p>The insertion point at which the target directive code / should be placed. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsBegin</td>
<td class="doxyParamItemDescription"><p>If true then emits begin mapper call otherwise emits / end mapper call. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DeviceID</td>
<td class="doxyParamItemDescription"><p>Stores the DeviceID from the device clause. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IfCond</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> which corresponds to the if clause condition. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Info</td>
<td class="doxyParamItemDescription"><p>Stores all information realted to the <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Data directive. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GenMapInfoCB</td>
<td class="doxyParamItemDescription"><p>Callback that populates the MapInfos and returns. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Optional Callback to generate the region code. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DeviceAddrCB</td>
<td class="doxyParamItemDescription"><p>Optional callback to generate code related to / use_device_ptr and use_device_addr. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CustomMapperCB</td>
<td class="doxyParamItemDescription"><p>Optional callback to generate code related to / custom mappers. <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a> createTargetData( const <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp;<a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a>, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> CodeGenIP, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *DeviceID, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *IfCond, TargetDataInfo &amp;Info, GenMapInfoCallbackTy GenMapInfoCB, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a4c503140c7f851151906d85b515330e9">omp::RuntimeFunction</a> *MapperFunc = nullptr, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt;<a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy(InsertPointTy CodeGenIP,
                                        BodyGenTy BodyGenType)</a>&gt; BodyGenCB = nullptr, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref&lt;void(unsigned int, Value *)&gt;</a> DeviceAddrCB = nullptr, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref&lt;Value *(unsigned int)&gt;</a> CustomMapperCB = nullptr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *SrcLocInfo = nullptr);</p></td>
</tr>
</table>
</dd>
</dl>

<p>using TargetBodyGenCallbackTy = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt;<a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy(
      InsertPointTy AllocaIP, InsertPointTy CodeGenIP)</a>&gt;;</p>


<p>using TargetGenArgAccessorsCallbackTy = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt;<a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy(
      Argument &amp;Arg, Value *Input, Value *&amp;RetVal, InsertPointTy AllocaIP,
      InsertPointTy CodeGenIP)</a>&gt;;</p>


<p>/ Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> target' / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>where the target data construct was encountered. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsOffloadEntry</td>
<td class="doxyParamItemDescription"><p>whether it is an offload entry. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CodeGenIP</td>
<td class="doxyParamItemDescription"><p>The insertion point where the call to the outlined / function should be emitted. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EntryInfo</td>
<td class="doxyParamItemDescription"><p>The entry information about the function. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DefaultAttrs</td>
<td class="doxyParamItemDescription"><p>Structure containing the default attributes, including / numbers of threads and teams to launch the kernel with. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RuntimeAttrs</td>
<td class="doxyParamItemDescription"><p>Structure containing the runtime numbers of threads / and teams to launch the kernel with. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IfCond</td>
<td class="doxyParamItemDescription"><p>value of the <span class="doxyComputerOutput">if</span> clause. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Inputs</td>
<td class="doxyParamItemDescription"><p>The input values to the region that will be passed. / as arguments to the outlined function. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the region code. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ArgAccessorFuncCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate accessors / instructions for passed in target arguments where neccessary /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Dependencies</td>
<td class="doxyParamItemDescription"><p>A vector of <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/dependdata">DependData</a> objects that carry / dependency information as passed in the depend clause /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HasNowait</td>
<td class="doxyParamItemDescription"><p>Whether the target construct has a <span class="doxyComputerOutput">nowait</span> clause or / not. <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a> createTarget( const <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp;<a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a>, bool IsOffloadEntry, <a href="#aafc1886793b898052f87edd7e9fdbaa3">OpenMPIRBuilder::InsertPointTy</a> AllocaIP, <a href="#aafc1886793b898052f87edd7e9fdbaa3">OpenMPIRBuilder::InsertPointTy</a> CodeGenIP, <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo">TargetRegionEntryInfo</a> &amp;EntryInfo, const TargetKernelDefaultAttrs &amp;DefaultAttrs, const TargetKernelRuntimeAttrs &amp;RuntimeAttrs, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *IfCond, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;Value *&gt;</a> &amp;Inputs, GenMapInfoCallbackTy GenMapInfoCB, TargetBodyGenCallbackTy BodyGenCB, TargetGenArgAccessorsCallbackTy ArgAccessorFuncCB, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;DependData&gt;</a> Dependencies = {}, bool HasNowait = false);</p></td>
</tr>
</table>
</dd>
</dl>

<p>/ Returns __kmpc_for_static_init_* runtime function for the specified / size <em>IVSize</em> and sign <em>IVSigned</em>. Will create a distribute call / __kmpc_distribute_static_init* if <em>IsGPUDistribute</em> is set. <a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a> createForStaticInitFunction(unsigned IVSize, bool IVSigned,
                                             bool IsGPUDistribute);</p>


<p>/ Returns __kmpc_dispatch_init_* runtime function for the specified / size <em>IVSize</em> and sign <em>IVSigned</em>. <a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a> createDispatchInitFunction(unsigned IVSize, bool IVSigned);</p>


<p>/ Returns __kmpc_dispatch_next_* runtime function for the specified / size <em>IVSize</em> and sign <em>IVSigned</em>. <a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a> createDispatchNextFunction(unsigned IVSize, bool IVSigned);</p>


<p>/ Returns __kmpc_dispatch_fini_* runtime function for the specified / size <em>IVSize</em> and sign <em>IVSigned</em>. <a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a> createDispatchFiniFunction(unsigned IVSize, bool IVSigned);</p>


<p>/ Returns __kmpc_dispatch_deinit runtime function. <a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a> createDispatchDeinitFunction();</p>


<p>/ Declarations for LLVM-IR types (simple, array, function and structure) are / generated below. Their names are defined and used in OpenMPKinds.def. Here / we provide the declarations, the initializeTypes function will provide the / values. / /{ #define <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h/#afd21bf6bbf67e4d7213a29ade471a8ee">OMP_TYPE(VarName, InitValue)</a> 
<br/>
 #define <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h/#aafa57f1c2700b16129c83badeb165f9c">OMP_ARRAY_TYPE(VarName, ElemTy, ArraySize)</a> \ \</p>


<p>#define <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h/#ad08bb874382ad7ded92c133a57714c49">OMP_FUNCTION_TYPE(VarName, IsVarArg, ReturnType, ...)</a> \ \</p>


<p>#define <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h/#ae4b3b7ecfcc7dcb96f3d5d57cea7a022">OMP_STRUCT_TYPE(VarName, StrName, ...)</a> \ \</p>


<p>/}</p>


<p>private: / Create all simple and struct types exposed by the runtime and remember / the llvm::PointerTypes of them for easy access later. void initializeTypes(Module &amp;M);</p>


<p>/ Common interface for generating entry calls for OMP Directives. / if the directive has a region/body, It will set the insertion / point to the body / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OMPD</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/directive">Directive</a> to generate entry blocks for /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EntryCall</td>
<td class="doxyParamItemDescription"><p>Call to the entry OMP Runtime <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ExitBB</td>
<td class="doxyParamItemDescription"><p>block where the region ends. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Conditional</td>
<td class="doxyParamItemDescription"><p>indicate if the entry call result will be used / to evaluate a conditional of whether a thread will execute / body code or not. / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion position in exit block <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> emitCommonDirectiveEntry(omp::Directive OMPD, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *EntryCall, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *ExitBB, bool Conditional = false);</p></dd>
</dl>


<p>/ Common interface to finalize the region / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OMPD</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/directive">Directive</a> to generate exiting code for /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FinIP</td>
<td class="doxyParamItemDescription"><p>Insertion point for emitting Finalization code and exit call /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ExitCall</td>
<td class="doxyParamItemDescription"><p>Call to the ending OMP Runtime <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HasFinalize</td>
<td class="doxyParamItemDescription"><p>indicate if the directive will require finalization / and has a finalization callback in the stack that / should be called. / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion position in exit block <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a> emitCommonDirectiveExit(omp::Directive OMPD, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> FinIP, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *ExitCall, bool HasFinalize = true);</p></dd>
</dl>


<p>/ Common Interface to generate OMP inlined regions / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OMPD</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/directive">Directive</a> to generate inlined region for /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EntryCall</td>
<td class="doxyParamItemDescription"><p>Call to the entry OMP Runtime <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ExitCall</td>
<td class="doxyParamItemDescription"><p>Call to the ending OMP Runtime <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Body code generation callback. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FiniCB</td>
<td class="doxyParamItemDescription"><p>Finalization Callback. Will be called when finalizing region /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Conditional</td>
<td class="doxyParamItemDescription"><p>indicate if the entry call result will be used / to evaluate a conditional of whether a thread will execute / body code or not. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HasFinalize</td>
<td class="doxyParamItemDescription"><p>indicate if the directive will require finalization / and has a finalization callback in the stack that / should be called. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsCancellable</td>
<td class="doxyParamItemDescription"><p>if HasFinalize is set to true, indicate if the / the directive should be cancellable. /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion point after the region <a href="#af24d1c61cec57095ced3b08a6dd99ee8">InsertPointOrErrorTy</a> EmitOMPInlinedRegion(omp::Directive OMPD, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *EntryCall, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *ExitCall, <a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a> BodyGenCB, <a href="#a0c571620ff53fdb78e7404f5261dbd23">FinalizeCallbackTy</a> FiniCB, bool Conditional = false, bool HasFinalize = true, bool IsCancellable = false);</p></dd>
</dl>


<p>/ Get the platform-specific name separator. /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Parts</td>
<td class="doxyParamItemDescription"><p>different parts of the final name that needs separation /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FirstSeparator</td>
<td class="doxyParamItemDescription"><p>First separator used between the initial two / parts of the name. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Separator</td>
<td class="doxyParamItemDescription"><p>separator used between all of the rest consecutive / parts of the name static std::string getNameWithSeparators(ArrayRef&lt;StringRef&gt; Parts,
                                           StringRef FirstSeparator,
                                           StringRef Separator);</p></td>
</tr>
</table>
</dd>
</dl>

<p>/ Returns corresponding lock object for the specified critical region / name. If the lock object does not exist it is created, otherwise the / reference to the existing copy is returned. /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CriticalName</td>
<td class="doxyParamItemDescription"><p>Name of the critical region. / <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *getOMPCriticalRegionLock(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CriticalName);</p></td>
</tr>
</table>
</dd>
</dl>

<p>/ Callback type for Atomic <a href="/web-llvm/docs/api/classes/llvm/expression">Expression</a> update / ex: /</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/// unsigned x = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/// #pragma omp atomic update</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/// x = Expr(x_old);  //Expr() is any legal operation</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/// </span></span></div>

</div>


<p>/ /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">XOld</td>
<td class="doxyParamItemDescription"><p>the value of the atomic memory address to use for update /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IRB</td>
<td class="doxyParamItemDescription"><p>reference to the <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a> to use / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to update X to. using AtomicUpdateCallbackTy = const <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt;Expected&lt;Value *&gt;(Value *XOld, IRBuilder&lt;&gt; &amp;IRB)&gt;;</p></dd>
</dl>


<p>private: enum AtomicKind { Read, Write, Update, Capture, Compare };</p>


<p>/ Determine whether to emit flush or not / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AO</td>
<td class="doxyParamItemDescription"><p>The required atomic ordering /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AK</td>
<td class="doxyParamItemDescription"><p>The OpenMP atomic operation kind used. / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>wether a flush was emitted or not bool checkAndEmitFlushAfterAtomic(const LocationDescription &amp;Loc,
                                    AtomicOrdering AO, AtomicKind AK);</p>
</dd>
</dl>


<p>/ Emit atomic update for constructs: X = X BinOp Expr ,or X = Expr BinOp X / For complex Operations: X = UpdateOp(X) =&gt; CmpExch X, old_X, UpdateOp(X) / Only Scalar data types. / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>The insertion point to be used for alloca / instructions. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">X</td>
<td class="doxyParamItemDescription"><p>The target atomic pointer to be updated /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">XElemTy</td>
<td class="doxyParamItemDescription"><p>The element type of the atomic pointer. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Expr</td>
<td class="doxyParamItemDescription"><p>The value to update X with. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AO</td>
<td class="doxyParamItemDescription"><p>Atomic ordering of the generated atomic / instructions. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RMWOp</td>
<td class="doxyParamItemDescription"><p>The binary operation used for update. If / operation is not supported by atomicRMW, / or belong to {FADD, FSUB, BAD_BINOP}. / Then a <span class="doxyComputerOutput">cmpExch</span> based atomic will be generated. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UpdateOp</td>
<td class="doxyParamItemDescription"><p>Code generator for complex expressions that cannot be / expressed through atomicrmw instruction. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VolatileX</td>
<td class="doxyParamItemDescription"><p>true if <em>X</em> volatile? /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsXBinopExpr</td>
<td class="doxyParamItemDescription"><p>true if <em>X</em> is Left H.S. in Right H.S. part of the / update expression, false otherwise. / (e.g. true for X = X BinOp Expr) / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>A pair of the old value of X before the update, and the value / used for the update. <a href="/web-llvm/docs/api/classes/llvm/expected">Expected&lt;std::pair&lt;Value *, Value *&gt;&gt;</a> emitAtomicUpdate(InsertPointTy AllocaIP, Value *X, Type *XElemTy, Value *Expr,
                   AtomicOrdering AO, AtomicRMWInst::BinOp RMWOp,
                   AtomicUpdateCallbackTy &amp;UpdateOp, bool VolatileX,
                   bool IsXBinopExpr);</p>
</dd>
</dl>


<p>/ Emit the binary op. described by <span class="doxyComputerOutput">RMWOp</span>, using <span class="doxyComputerOutput">Src1</span> and <span class="doxyComputerOutput">Src2</span> . / / \Return The instruction <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *emitRMWOpAsInstruction(<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *Src1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *Src2, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615">AtomicRMWInst::BinOp</a> RMWOp);</p>


<p>public: / a struct to pack relevant information while generating atomic Ops struct AtomicOpValue { <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *Var = nullptr; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *ElemTy = nullptr; bool IsSigned = false; bool IsVolatile = false; };</p>


<p>/ Emit atomic Read for : V = X — Only Scalar data types. / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">X</td>
<td class="doxyParamItemDescription"><p>The target pointer to be atomically read /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">V</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> address where to store atomically read / value /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AO</td>
<td class="doxyParamItemDescription"><p>Atomic ordering of the generated atomic / instructions. / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>Insertion point after generated atomic read IR. <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> createAtomicRead(const LocationDescription &amp;Loc,
                                 AtomicOpValue &amp;X, AtomicOpValue &amp;V,
                                 AtomicOrdering AO);</p>
</dd>
</dl>


<p>/ Emit atomic write for : X = Expr — Only Scalar data types. / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">X</td>
<td class="doxyParamItemDescription"><p>The target pointer to be atomically written to /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Expr</td>
<td class="doxyParamItemDescription"><p>The value to store. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AO</td>
<td class="doxyParamItemDescription"><p>Atomic ordering of the generated atomic / instructions. / /</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>Insertion point after generated atomic Write IR. <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> createAtomicWrite(const LocationDescription &amp;Loc,
                                  AtomicOpValue &amp;X, Value *Expr,
                                  AtomicOrdering AO);</p>
</dd>
</dl>


<p>/ Emit atomic update for constructs: X = X BinOp Expr ,or X = Expr BinOp X / For complex Operations: X = UpdateOp(X) =&gt; CmpExch X, old_X, UpdateOp(X) / Only Scalar data types. / /</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>The insertion point to be used for alloca instructions. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">X</td>
<td class="doxyParamItemDescription"><p>The target atomic pointer to be updated /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Expr</td>
<td class="doxyParamItemDescription"><p>The value to update X with. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AO</td>
<td class="doxyParamItemDescription"><p>Atomic ordering of the generated atomic instructions. /</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RMWOp</td>
<td class="doxyParamItemDescription"><p>The binary operation used for update. If operation / is not supported by atomicRMW, or belong to / {FADD, FSUB, BAD_BINOP}. Then a <span class="doxyComputerOutput">cmpExch</span> based atomic will be generated.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UpdateOp</td>
<td class="doxyParamItemDescription"><p>Code generator for complex expressions that cannot be expressed through atomicrmw instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsXBinopExpr</td>
<td class="doxyParamItemDescription"><p>true if <em>X</em> is Left H.S. in Right H.S. part of the update expression, false otherwise. (e.g. true for X = X BinOp Expr)</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Insertion point after generated atomic update IR.</p></dd>
</dl>


<p>Declaration at line 3264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 8574 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a756b28f370cd5a39bc0ee3e5333b9c9b">isConflictIP</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aac5759c83abd6a4af236401a7cfe7a0f">llvm::Type::isFloatingPointTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615aa1184a7e35e94d162a2d40f2b11beeb2">llvm::AtomicRMWInst::Max</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a39edb6e51c1ad37244e8b32a2af4077d">llvm::AtomicRMWInst::Min</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a79479229269c1abc7dba0840d19b97cf">llvm::IRBuilderBase::saveIP</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615abe171d96ba8de66fb30e08c00211591e">llvm::AtomicRMWInst::UMax</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615aa53854e09143f57d2ff2ad6ac89dc55d">llvm::AtomicRMWInst::UMin</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### createBarrier() {#abca6530c9099bd1b1c3e0a5c32381f07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::createBarrier (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, omp::Directive Kind, bool ForceSimpleCall=false, bool CheckCancelFlag=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emitter methods for OpenMP directives.</p>


<p>{ Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> barrier'</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location where the barrier directive was encountered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Kind</td>
<td class="doxyParamItemDescription"><p>The kind of directive that caused the barrier.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ForceSimpleCall</td>
<td class="doxyParamItemDescription"><p>Flag to force a simple (=non-cancellation) barrier.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CheckCancelFlag</td>
<td class="doxyParamItemDescription"><p>Flag to indicate a cancel barrier return value should be checked and acted upon.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ThreadID</td>
<td class="doxyParamItemDescription"><p>Optional parameter to pass in any existing ThreadID value.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion point after the barrier.</p></dd>
</dl>


<p>Declaration at line 669 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 1007 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a79479229269c1abc7dba0840d19b97cf">llvm::IRBuilderBase::saveIP</a>.</p>


<p>Referenced by <a href="#a04285415a321e48322c08f3b9185540e">createCancel</a>.</p>

</div>
</div>

### createCancel() {#a04285415a321e48322c08f3b9185540e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::createCancel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * IfCondition, omp::Directive CanceledDirective)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> cancel'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location where the directive was encountered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IfCondition</td>
<td class="doxyParamItemDescription"><p>The evaluated 'if' clause expression, if any.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CanceledDirective</td>
<td class="doxyParamItemDescription"><p>The kind of directive that is cancled.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion point after the barrier.</p></dd>
</dl>


<p>Declaration at line 681 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 1060 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="#abca6530c9099bd1b1c3e0a5c32381f07">createBarrier</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a39acc29443d48968a798fb22a76fa4c0">llvm::IRBuilderBase::CreateUnreachable</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac8778dcbd35e8ae5902050117feb57a0">llvm::IRBuilderBase::restoreIP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a79479229269c1abc7dba0840d19b97cf">llvm::IRBuilderBase::saveIP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7ac00229d8c59902686f52ed061cdc80">llvm::SplitBlockAndInsertIfThenElse</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### createCanonicalLoop() {#ae0287686a5ffe03bc264972c862726ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; CanonicalLoopInfo * &gt; OpenMPIRBuilder::createCanonicalLoop (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#a296d2e28bddf1051d614f48b61005899">LoopBodyGenCallbackTy</a> BodyGenCB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * TripCount, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="loop")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for the control flow structure of an OpenMP canonical loop.</p>


<p>This generator operates on the logical iteration space of the loop, i.e. the caller only has to provide a loop trip count of the loop as defined by base language semantics. The trip count is interpreted as an unsigned integer. The induction variable passed to <span class="doxyComputerOutput">BodyGenCB</span> will be of the same type and run from 0 to <span class="doxyComputerOutput">TripCount</span> - 1. It is up to the callback to convert the logical iteration variable to the loop counter variable in the loop body.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description. The insert location can be between two instructions or the end of a degenerate block (e.g. a BB under construction).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the loop body code.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TripCount</td>
<td class="doxyParamItemDescription"><p>Number of iterations the loop body is executed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Base name used to derive BB and instruction names.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An object representing the created control flow structure which can be used for loop-associated directives.</p></dd>
</dl>


<p>Declaration at line 725 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 4025 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa7bfcadb5535fe8aad5032762b7bfe159">After</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a32ff799dcb39887a8d21322020f305ba">llvm::CanonicalLoopInfo::assertOK</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#abab736a0141f903dc32a6f48828ad908">llvm::IRBuilderBase::CreateBr</a>, <a href="#a445fa52d77040bccb16bfea111234a2e">createLoopSkeleton</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a92d8bce979891dc43b6573e8cca2e58c">llvm::CanonicalLoopInfo::getAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a8031442528bff99473596a0de4aa0422">llvm::CanonicalLoopInfo::getBodyIP</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#af4131f5f461f1138483addfd7cd7f579">llvm::CanonicalLoopInfo::getIndVar</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#a62ee7ece4986606d41363bc1f70d5ab2">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getNextNode</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a1b4bf7c97cdc8159fd73d48063f0b250">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#ad50eb30e70ff2a9ea7f220547e2b6f6d">llvm::CanonicalLoopInfo::getPreheader</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a78e14f66d8a8405c6882b5ff6a3b7617">llvm::spliceBB</a>.</p>


<p>Referenced by <a href="#ac669acbd0f638c6ef32977575362052e">createCanonicalLoop</a>.</p>

</div>
</div>

### createCanonicalLoop() {#ac669acbd0f638c6ef32977575362052e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; CanonicalLoopInfo * &gt; OpenMPIRBuilder::createCanonicalLoop (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#a296d2e28bddf1051d614f48b61005899">LoopBodyGenCallbackTy</a> BodyGenCB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Start, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Stop, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Step, bool IsSigned, bool InclusiveStop, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> ComputeIP={}, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="loop")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for the control flow structure of an OpenMP canonical loop.</p>


<p>Instead of a logical iteration space, this allows specifying user-defined loop counter values using increment, upper- and lower bounds. To disambiguate the terminology when counting downwards, instead of lower bounds we use <span class="doxyComputerOutput">Start</span> for the loop counter value in the first body iteration.</p>


<p>Consider the following limitations:</p>


<ul class="doxyList ">
<li>A loop counter space over all integer values of its bit-width cannot be represented. E.g using uint8_t, its loop trip count of 256 cannot be stored into an 8 bit integer):

DO I = 0, 255, 1</li>
<li>Unsigned wrapping is only supported when wrapping only "once"; E.g. effectively counting downwards:

for (uint8_t i = 100u; i &gt; 0; i += 127u)</li>
</ul>

<p>TODO: May need to add additional parameters to represent:</p>


<ul class="doxyList ">
<li>Allow representing downcounting with unsigned integers.</li>
<li>Sign of the step and the comparison operator might disagree:

for (int i = 0; i &lt; 42; i -= 1u)

<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the loop body code.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Start</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> of the loop counter for the first iterations.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Stop</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> counter values past this will stop the loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Step</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> counter increment after each iteration; negative means counting down.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsSigned</td>
<td class="doxyParamItemDescription"><p>Whether Start, Stop and Step are signed integers.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InclusiveStop</td>
<td class="doxyParamItemDescription"><p>Whether <span class="doxyComputerOutput">Stop</span> itself is a valid value for the loop counter.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ComputeIP</td>
<td class="doxyParamItemDescription"><p>Insertion point for instructions computing the trip count. Can be used to ensure the trip count is available at the outermost loop of a loop nest. If not set, defaults to the preheader of the generated loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Base name used to derive BB and instruction names.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An object representing the created control flow structure which can be used for loop-associated directives.</p></dd>
</dl></li>
</ul>

<p>Declaration at line 777 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 4055 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="#ae0287686a5ffe03bc264972c862726ea">createCanonicalLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae0bd6c2fab2d18443038a8f3a2b64856">llvm::IRBuilderBase::CreateICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac2bfef55549675e0ea117f29cd7309be">llvm::IRBuilderBase::CreateICmpSLT</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aecd40f9a16dc0ef1e0bc416599f89277">llvm::IRBuilderBase::CreateMul</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a7704bf68951054ffeb3efe605750e2d9">llvm::IRBuilderBase::CreateNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a49b228f797f9b3563256da446100c3ac">llvm::IRBuilderBase::CreateSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a92c83e803f2cf22906da0aaec44ff6d7">llvm::IRBuilderBase::CreateSub</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6b68047eda0d6d6eec5dd564ed1a22b8">llvm::IRBuilderBase::CreateUDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/insertpoint/#a85b9635b21610f18b51007437bcc26cf">llvm::IRBuilderBase::InsertPoint::isSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac8778dcbd35e8ae5902050117feb57a0">llvm::IRBuilderBase::restoreIP</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a79479229269c1abc7dba0840d19b97cf">llvm::IRBuilderBase::saveIP</a>.</p>

</div>
</div>

### createFlush() {#afc2cc623eda981e1b3fbb61a44e80ef8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::createFlush (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> flush'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location where the flush directive was encountered</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 1766 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### createLoopSkeleton() {#a445fa52d77040bccb16bfea111234a2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CanonicalLoopInfo * OpenMPIRBuilder::createLoopSkeleton (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * TripCount, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * PreInsertBefore, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * PostInsertBefore, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create the control flow structure of a canonical OpenMP loop.</p>


<p>The emitted loop will be disconnected, i.e. no edge to the loop's preheader and no terminator in the AfterBB. The <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder">OpenMPIRBuilder</a>'s <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a> location is not preserved.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> used for the instructions in the skeleton.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TripCount</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to be used for the trip count.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">F</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> in which to insert the BasicBlocks.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PreInsertBefore</td>
<td class="doxyParamItemDescription"><p>Where to insert BBs that execute before the body, typically the body itself.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PostInsertBefore</td>
<td class="doxyParamItemDescription"><p>Where to insert BBs that execute after the body.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Base name used to derive BB and instruction names.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> that represents the emitted loop.</p></dd>
</dl>


<p>Declaration at line 3379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 3958 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/phinode/#a089cccb6f231efee72abc76d0f9c695f">llvm::PHINode::addIncoming</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa7bfcadb5535fe8aad5032762b7bfe159">After</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a32ff799dcb39887a8d21322020f305ba">llvm::CanonicalLoopInfo::assertOK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#abab736a0141f903dc32a6f48828ad908">llvm::IRBuilderBase::CreateBr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a972c30f044db799668bdcace5544edeb">llvm::IRBuilderBase::CreateCondBr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a09b4daefdf5b73efba51ce7ae6cd45c5">llvm::IRBuilderBase::CreateICmpULT</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a876fb556ecea804faa2cd8ad1e498ec3">llvm::IRBuilderBase::CreatePHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a63fc74646456a3bed261512f21efe29c">llvm::IRBuilderBase::SetCurrentDebugLocation</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>.</p>


<p>Referenced by <a href="#a08610118e213de1b759470f0eafb9b18">collapseLoops</a>, <a href="#ae0287686a5ffe03bc264972c862726ea">createCanonicalLoop</a> and <a href="#a76e12ec076e7af4be7b8b77a5d53d3fc">tileLoops</a>.</p>

</div>
</div>

### createParallel() {#a4f81b9940e1869e146636dc533455929}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::createParallel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="#a49e35e3ee470add16efcde1ab5d5556b">BodyGenCallbackTy</a> BodyGenCB, <a href="#a71b5ba020f68829f5a1fd99f48b63d42">PrivatizeCallbackTy</a> PrivCB, <a href="#a0c571620ff53fdb78e7404f5261dbd23">FinalizeCallbackTy</a> FiniCB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * IfCondition, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NumThreads, omp::ProcBindKind ProcBind, bool IsCancellable)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> parallel'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The insert and source location description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>The insertion points to be used for alloca instructions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BodyGenCB</td>
<td class="doxyParamItemDescription"><p>Callback that will generate the region code.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PrivCB</td>
<td class="doxyParamItemDescription"><p>Callback to copy a given variable (think copy constructor).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FiniCB</td>
<td class="doxyParamItemDescription"><p>Callback to finalize variable copies.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IfCondition</td>
<td class="doxyParamItemDescription"><p>The evaluated 'if' clause expression, if any.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NumThreads</td>
<td class="doxyParamItemDescription"><p>The evaluated 'num_threads' clause expression, if any.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ProcBind</td>
<td class="doxyParamItemDescription"><p>The value of the 'proc_bind' clause (see ProcBindKind).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsCancellable</td>
<td class="doxyParamItemDescription"><p>Flag to indicate a cancellable parallel region.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The insertion position <em>after</em> the parallel.</p></dd>
</dl>


<p>Declaration at line 699 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 1427 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a1b30cd686a320a8e5cb4532fd3a552a8">llvm::IRBuilderBase::CreateAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#abab736a0141f903dc32a6f48828ad908">llvm::IRBuilderBase::CreateBr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac79ca3c2d2d74cf33684397a91846564">llvm::IRBuilderBase::CreateIntCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aabfc20af4dcf7d94262824dcac2e7bed">llvm::IRBuilderBase::CreateStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3377eac88526e806d9d887c4a0ba2a73">llvm::dyn_cast_if_present</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#ac178f4fc4e4a0642610c374256b9fb27">llvm::SetVector&lt; T, Vector, Set, N &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/insertpoint/#a3d072f8ac5e1b0724c4bb5a77adae9da">llvm::IRBuilderBase::InsertPoint::getBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncallee/#ac5d8da677233fa2e1e7039508ed56e0e">llvm::FunctionCallee::getCallee</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa2ed385be8984b4306762990278eb13d">llvm::IRBuilderBase::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a161fd4e9fa5367f64c2a4c9e921c3ad3">llvm::BasicBlock::getFirstInsertionPt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a60a6d6c205f483fa96597a960f3c093b">llvm::IRBuilderBase::GetInsertBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#a62ee7ece4986606d41363bc1f70d5ab2">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getNextNode</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a1b4bf7c97cdc8159fd73d48063f0b250">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aef9e9fcf4c5dfce90276ca16d91b8e46">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#afffa0ff2e1527ab545cef33be915c656">hostParallelCallback</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af09e4096de244d2fb345891328714a63">llvm::Instruction::insertAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a788a72ddbf1bd572b3fcd7a5e7ec8cff">Int32</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a756b28f370cd5a39bc0ee3e5333b9c9b">isConflictIP</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a14d9be6f03ca789eb7489fa89273aa40">llvm::SetVector&lt; T, Vector, Set, N &gt;::remove_if</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac8778dcbd35e8ae5902050117feb57a0">llvm::IRBuilderBase::restoreIP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a79479229269c1abc7dba0840d19b97cf">llvm::IRBuilderBase::saveIP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a52c990590792c91dd20b6d45acebe359">llvm::BasicBlock::splitBasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac6c9ffe7979754415f4ca0d677174bc2">llvm::SplitBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#af7668ce8080668a4f0ceac24e70c9f00">targetParallelCallback</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeloadsintofakeuses-cpp/#a0b427ca665b192edbeb8d6ca3c8f19fd">Uses</a>.</p>

</div>
</div>

### createPlatformSpecificName() {#a488c861f8a68e5f78ceca8b57acd8be5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string OpenMPIRBuilder::createPlatformSpecificName (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Parts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the create a name using the platform specific separators.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Parts</td>
<td class="doxyParamItemDescription"><p>parts of the final name that needs separation The created name has a first separator between the first and second part and a second separator between all other parts. E.g. with FirstSeparator "$" and Separator "." and parts: "p1", "p2", "p3", "p4" The resulting name is "p1$p2.p3.p4" The separators are retrieved from the <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilderconfig">OpenMPIRBuilderConfig</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 7636 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>Referenced by <a href="#ae327be8503a76bd4dccfff4713a38553">registerTargetGlobalVariable</a>.</p>

</div>
</div>

### createTaskwait() {#a419ffad9e4d59275e299ce1ad3c73cd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::createTaskwait (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> taskwait'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location where the taskwait directive was encountered.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 1785 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### createTaskyield() {#a0b0ed7f600549e4239bf10b5b85de66c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::createTaskyield (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/locationdescription">LocationDescription</a> &amp; Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generator for '<a href="/web-llvm/docs/api/namespaces/llvm/omp">omp</a> taskyield'.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/namespaces/llvm/loc"&gt;Loc&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The location where the taskyield directive was encountered.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 1803 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### finalize() {#a784adc2347b72f745ff1239aef3a3c26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::finalize (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Fn=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finalize the underlying module, e.g., by outlining regions.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Fn</td>
<td class="doxyParamItemDescription"><p>The function to be finalized. If not used, all functions are finalized.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 701 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a01875e4204852069dd4b7938cab4140b">llvm::Function::addFnAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a16413f1a88d8baca228d0a1b4cc0bfc6">llvm::SmallPtrSetImplBase::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a266367eb01c634406b32f816d2d9c6bf">llvm::BasicBlock::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a8dd327a937563afdb08250abc43820b0">llvm::BasicBlock::eraseFromParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a169f0c26ef46161741fdd120a806f853">llvm::Function::getEntryBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a4c319db4fe05c27cfe55bd133a87414d">llvm::Function::getFnAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a8743c58384e11cb6228f6f871304ad35">llvm::Function::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#aba0055050d741f60b6e0523507a2c79f">llvm::Value::getNumUses</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#acdd05db170cbfee8a0fcbc047b8504e5">llvm::Function::getReturnType</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a57f1945911ca1e95d0f51d7c3516b529">llvm::BasicBlock::getUniqueSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ae8eaa0b4eeac52a2b2282cb1bfd981ae">llvm::Type::isVoidTy</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a6e4c46869d9d198562f7b8628814e407">raiseUserConstantDataAllocasToEntryBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a1c2af7a9e501d399f06ca7e10eef46e4">llvm::BasicBlock::rbegin</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a29e0a562beb4b5d20eb0c426b363ceed">llvm::Function::removeFromParent</a> and <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a9237251072bf6816163abc2d053212ee">llvm::BasicBlock::rend</a>.</p>

</div>
</div>

### getAddrOfDeclareTargetVar() {#afdc1b8675a946ce055c64607ba75af3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * OpenMPIRBuilder::getAddrOfDeclareTargetVar (<a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#ab9575c71365de4083a7be6ef6572d534">OffloadEntriesInfoManager::OMPTargetGlobalVarEntryKind</a> CaptureClause, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#a2dc9d099b77ee3b8db3b00ad9273823d">OffloadEntriesInfoManager::OMPTargetDeviceClauseKind</a> DeviceClause, bool IsDeclaration, bool IsExternallyVisible, <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo">TargetRegionEntryInfo</a> EntryInfo, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> MangledName, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * &gt; &amp; GeneratedRefs, bool OpenMPSIMD, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &gt; TargetTriple, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * LlvmPtrTy, std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *()&gt; GlobalInitializer, std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a>()&gt; VariableLinkage)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieve (or create if non-existent) the address of a declare target variable, used in conjunction with registerTargetGlobalVariable to create declare target global variables.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CaptureClause</td>
<td class="doxyParamItemDescription"><p>- enumerator corresponding to the OpenMP capture clause used in conjunction with the variable being registered (link, to, enter).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DeviceClause</td>
<td class="doxyParamItemDescription"><p>- enumerator corresponding to the OpenMP capture clause used in conjunction with the variable being registered (nohost, host, any)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsDeclaration</td>
<td class="doxyParamItemDescription"><p>- boolean stating if the variable being registered is a declaration-only and not a definition</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsExternallyVisible</td>
<td class="doxyParamItemDescription"><p>- boolean stating if the variable is externally visible</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EntryInfo</td>
<td class="doxyParamItemDescription"><p>- Unique entry information for the value generated using getTargetEntryUniqueInfo, used to name generated pointer references to the declare target variable</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MangledName</td>
<td class="doxyParamItemDescription"><p>- the mangled name of the variable being registered</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GeneratedRefs</td>
<td class="doxyParamItemDescription"><p>- references generated by invocations of registerTargetGlobalVariable invoked from getAddrOfDeclareTargetVar, these are required by Clang for book keeping.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OpenMPSIMD</td>
<td class="doxyParamItemDescription"><p>- if OpenMP SIMD mode is currently enabled</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TargetTriple</td>
<td class="doxyParamItemDescription"><p>- The OpenMP device target triple we are compiling for</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LlvmPtrTy</td>
<td class="doxyParamItemDescription"><p>- The type of the variable we are generating or retrieving an address for</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GlobalInitializer</td>
<td class="doxyParamItemDescription"><p>- a lambda function which creates a constant used for initializing a pointer reference to the variable in certain cases. If a nullptr is passed, it will default to utilising the original variable to initialize the pointer reference.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VariableLinkage</td>
<td class="doxyParamItemDescription"><p>- a lambda function which returns the variables linkage type, if unspecified and a nullptr is given, it will instead utilise the linkage stored on the existing global variable in the LLVMModule.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 887 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9475 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo/#a80293a526ecd17ee44ce5b982dff1ca1">llvm::TargetRegionEntryInfo::FileID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#aa5ef00e5a7487cc6c5bfed0f301fa1cc">getOrCreateInternalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#ab9575c71365de4083a7be6ef6572d534a1b9b415348a31bfeaa94e778e0421ddf">llvm::OffloadEntriesInfoManager::OMPTargetGlobalVarEntryEnter</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#ab9575c71365de4083a7be6ef6572d534abe3a7916fb5f7a79d6aea6c0356e71a6">llvm::OffloadEntriesInfoManager::OMPTargetGlobalVarEntryLink</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#ab9575c71365de4083a7be6ef6572d534acf96797e65a60ff4302eb2bbdbbd8880">llvm::OffloadEntriesInfoManager::OMPTargetGlobalVarEntryTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="#ae327be8503a76bd4dccfff4713a38553">registerTargetGlobalVariable</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca8d13a9bcecfac72febceb1103afa048f">llvm::GlobalValue::WeakAnyLinkage</a>.</p>


<p>Referenced by <a href="#ae327be8503a76bd4dccfff4713a38553">registerTargetGlobalVariable</a>.</p>

</div>
</div>

### getFlagMemberOffset() {#ac86b562509588cbc00fbdc441c615bd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned OpenMPIRBuilder::getFlagMemberOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the offset of the OMP_MAP_MEMBER_OF field.</p>

<p>Declaration at line 943 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9439 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a02d7a52c47f2d71a111aef9d4fb70ecbaa450a4e59275b4081714a7a28f217e6c">llvm::omp::OMP_MAP_MEMBER_OF</a>.</p>


<p>Referenced by <a href="#a4f82182a8cc23f854efdbd453f685086">getMemberOfFlag</a>.</p>

</div>
</div>

### getMemberOfFlag() {#a4f82182a8cc23f854efdbd453f685086}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">omp::OpenMPOffloadMappingFlags OpenMPIRBuilder::getMemberOfFlag (unsigned Position)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get OMP_MAP_MEMBER_OF flag with extra bits reserved based on the position given.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Position</td>
<td class="doxyParamItemDescription"><p>- A value indicating the position of the parent of the member in the kernel argument structure, often retrieved by the parents position in the combined information vectors used to generate the structure itself. Multiple children (member's of) with the same parent will use the same returned member flag.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 952 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9450 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>Reference <a href="#ac86b562509588cbc00fbdc441c615bd3">getFlagMemberOffset</a>.</p>

</div>
</div>

### getOrCreateInternalVariable() {#aa5ef00e5a7487cc6c5bfed0f301fa1cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * OpenMPIRBuilder::getOrCreateInternalVariable (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Name, unsigned AddressSpace=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets (if variable with the given name already exist) or creates internal global variable with the specified Name.</p>


<p>The created variable has linkage CommonLinkage by default and is initialized by null value.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ty</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> of the global variable. If it is exist already the type must be the same.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>Name of the variable.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 3410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 7642 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca08c6a63ca3d9cdb39fb584655bf5c501">llvm::GlobalValue::CommonLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a6b882824580b4666f692474ecbae56ad">llvm::Module::getTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0">llvm::GlobalValue::NotThreadLocal</a>.</p>


<p>Referenced by <a href="#afdc1b8675a946ce055c64607ba75af3a">getAddrOfDeclareTargetVar</a> and <a href="#ae327be8503a76bd4dccfff4713a38553">registerTargetGlobalVariable</a>.</p>

</div>
</div>

### initialize() {#a1af99f6f33b0db83a3e941fcb819fa29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::initialize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize the internal state, this will put structures types and potentially other helpers into the underlying module.</p>


<p>Must be called before any other method and only once! This internal state includes types used in the <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder">OpenMPIRBuilder</a> generated from OMPKinds.def.</p>


<p>Declaration at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 676 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### loadOffloadInfoMetadata() {#a2242b144e54fa6203dae5c5b27fff17c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::loadOffloadInfoMetadata (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Loads all the offload entries information from the host IR metadata.</p>


<p>This function is only meant to be used with device code generation.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">M</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> to load <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> info from. <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> passed maybe loaded from bitcode file, i.e, different from OpenMPIRBuilder::M module.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 3393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9612 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#aefadc356da16598ff8c210dafbf4a2b7">ompOffloadInfoName</a> and <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#adc55e223d70c06a924fd5cb248052d9d">llvm::NamedMDNode::operands</a>.</p>


<p>Referenced by <a href="#ac6293b7ea84a4deac85481dd10dad437">loadOffloadInfoMetadata</a>.</p>

</div>
</div>

### loadOffloadInfoMetadata() {#ac6293b7ea84a4deac85481dd10dad437}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::loadOffloadInfoMetadata (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> HostFilePath)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Loads all the offload entries information from the host IR metadata read from the file passed in as the HostFilePath argument.</p>


<p>This function is only meant to be used with device code generation.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">HostFilePath</td>
<td class="doxyParamItemDescription"><p>The path to the host IR file, used to load in offload metadata for the device, allowing host and device to maintain the same metadata mapping.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 3402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9658 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4891d521956b735baba56d4dc193f5cd">llvm::expectedToErrorOrAndEmitErrors</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#aa98611beefe78f907beeee7305cc8174">llvm::MemoryBuffer::getFile</a>, <a href="#a2242b144e54fa6203dae5c5b27fff17c">loadOffloadInfoMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a170525c5f5e06bd2555d40a0499b8b6d">llvm::parseBitcodeFile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### popFinalizationCB() {#af2e7210874149ecbd52c8ce44ca4f416}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::OpenMPIRBuilder::popFinalizationCB ()</td>
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

<p>Pop the last finalization callback from the finalization stack.</p>


<p>NOTE: Temporary solution until Clang CG is gone.</p>


<p>Definition at line 568 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### pushFinalizationCB() {#a977f2477d245a9d554642492fedd049a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::OpenMPIRBuilder::pushFinalizationCB (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/finalizationinfo">FinalizationInfo</a> &amp; FI)</td>
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

<p>Push a finalization callback on the finalization stack.</p>


<p>NOTE: Temporary solution until Clang CG is gone.</p>


<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### registerTargetGlobalVariable() {#ae327be8503a76bd4dccfff4713a38553}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::registerTargetGlobalVariable (<a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#ab9575c71365de4083a7be6ef6572d534">OffloadEntriesInfoManager::OMPTargetGlobalVarEntryKind</a> CaptureClause, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#a2dc9d099b77ee3b8db3b00ad9273823d">OffloadEntriesInfoManager::OMPTargetDeviceClauseKind</a> DeviceClause, bool IsDeclaration, bool IsExternallyVisible, <a href="/web-llvm/docs/api/structs/llvm/targetregionentryinfo">TargetRegionEntryInfo</a> EntryInfo, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> MangledName, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * &gt; &amp; GeneratedRefs, bool OpenMPSIMD, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &gt; TargetTriple, std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *()&gt; GlobalInitializer, std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a>()&gt; VariableLinkage, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * LlvmPtrTy, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Registers a target variable for device or host.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CaptureClause</td>
<td class="doxyParamItemDescription"><p>- enumerator corresponding to the OpenMP capture clause used in conjunction with the variable being registered (link, to, enter).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DeviceClause</td>
<td class="doxyParamItemDescription"><p>- enumerator corresponding to the OpenMP capture clause used in conjunction with the variable being registered (nohost, host, any)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsDeclaration</td>
<td class="doxyParamItemDescription"><p>- boolean stating if the variable being registered is a declaration-only and not a definition</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsExternallyVisible</td>
<td class="doxyParamItemDescription"><p>- boolean stating if the variable is externally visible</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">EntryInfo</td>
<td class="doxyParamItemDescription"><p>- Unique entry information for the value generated using getTargetEntryUniqueInfo, used to name generated pointer references to the declare target variable</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MangledName</td>
<td class="doxyParamItemDescription"><p>- the mangled name of the variable being registered</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GeneratedRefs</td>
<td class="doxyParamItemDescription"><p>- references generated by invocations of registerTargetGlobalVariable these are required by Clang for book keeping.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OpenMPSIMD</td>
<td class="doxyParamItemDescription"><p>- if OpenMP SIMD mode is currently enabled</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TargetTriple</td>
<td class="doxyParamItemDescription"><p>- The OpenMP device target triple we are compiling for</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GlobalInitializer</td>
<td class="doxyParamItemDescription"><p>- a lambda function which creates a constant used for initializing a pointer reference to the variable in certain cases. If a nullptr is passed, it will default to utilising the original variable to initialize the pointer reference.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VariableLinkage</td>
<td class="doxyParamItemDescription"><p>- a lambda function which returns the variables linkage type, if unspecified and a nullptr is given, it will instead utilise the linkage stored on the existing global variable in the LLVMModule.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LlvmPtrTy</td>
<td class="doxyParamItemDescription"><p>- The type of the variable we are generating or retrieving an address for</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Addr</td>
<td class="doxyParamItemDescription"><p>- the original llvm value (addr) of the variable to be registered</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 931 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9531 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a488c861f8a68e5f78ceca8b57acd8be5">createPlatformSpecificName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9dda4472ee0b7ea92ab49eedf6e13d50">llvm::divideCeil</a>, <a href="#afdc1b8675a946ce055c64607ba75af3a">getAddrOfDeclareTargetVar</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3547d58a060ee2e4a29cbea85bef91af">llvm::GlobalValue::getLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="#aa5ef00e5a7487cc6c5bfed0f301fa1cc">getOrCreateInternalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caf2b592edf18170e7aff4e8f3bae3360c">llvm::GlobalValue::LinkOnceODRLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#a2dc9d099b77ee3b8db3b00ad9273823da168f6569c38da7979aa5e36d0a21b871">llvm::OffloadEntriesInfoManager::OMPTargetDeviceClauseAny</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#ab9575c71365de4083a7be6ef6572d534a1b9b415348a31bfeaa94e778e0421ddf">llvm::OffloadEntriesInfoManager::OMPTargetGlobalVarEntryEnter</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#ab9575c71365de4083a7be6ef6572d534abe3a7916fb5f7a79d6aea6c0356e71a6">llvm::OffloadEntriesInfoManager::OMPTargetGlobalVarEntryLink</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/#ab9575c71365de4083a7be6ef6572d534acf96797e65a60ff4302eb2bbdbbd8880">llvm::OffloadEntriesInfoManager::OMPTargetGlobalVarEntryTo</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca8d13a9bcecfac72febceb1103afa048f">llvm::GlobalValue::WeakAnyLinkage</a>.</p>


<p>Referenced by <a href="#afdc1b8675a946ce055c64607ba75af3a">getAddrOfDeclareTargetVar</a>.</p>

</div>
</div>

### setConfig() {#a3cf3a832c89fb823f696ce21ecf37b9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::OpenMPIRBuilder::setConfig (<a href="/web-llvm/docs/api/classes/llvm/openmpirbuilderconfig">OpenMPIRBuilderConfig</a> C)</td>
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



<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### setCorrectMemberOfFlag() {#abeea5a3df7d0266470cd04bb721db70e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::setCorrectMemberOfFlag (<a href="/web-llvm/docs/api/namespaces/llvm/omp/#a02d7a52c47f2d71a111aef9d4fb70ecb">omp::OpenMPOffloadMappingFlags</a> &amp; Flags, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a02d7a52c47f2d71a111aef9d4fb70ecb">omp::OpenMPOffloadMappingFlags</a> MemberOfFlag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an initial flag set, this function modifies it to contain the passed in MemberOfFlag generated from the getMemberOfFlag function.</p>


<p>The results are dependent on the existing flag bits set in the original flag set.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flags</td>
<td class="doxyParamItemDescription"><p>- The original set of flags to be modified with the passed in MemberOfFlag.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MemberOfFlag</td>
<td class="doxyParamItemDescription"><p>- A modified OMP_MAP_MEMBER_OF flag, adjusted slightly based on the getMemberOfFlag which adjusts the flag bits based on the members position in its parent.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 963 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9456 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a02d7a52c47f2d71a111aef9d4fb70ecbaa450a4e59275b4081714a7a28f217e6c">llvm::omp::OMP_MAP_MEMBER_OF</a> and <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a02d7a52c47f2d71a111aef9d4fb70ecba67bb5754d8a930a0abad5e820064be2d">llvm::omp::OMP_MAP_PTR_AND_OBJ</a>.</p>

</div>
</div>

### tileLoops() {#a76e12ec076e7af4be7b8b77a5d53d3fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; CanonicalLoopInfo * &gt; OpenMPIRBuilder::tileLoops (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * &gt; Loops, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; TileSizes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tile a loop nest.</p>


<p>Tiles the loops of <span class="doxyComputerOutput">Loops</span> by the tile sizes in <span class="doxyComputerOutput">TileSizes</span>. Loops in <span class="doxyComputerOutput"></span>/ Loops must be perfectly nested, from outermost to innermost loop (i.e. Loops.front() is the outermost loop). The trip count <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> of every loop and every tile sizes must be usable in the outermost loop's preheader. This implies that the loop nest is rectangular.</p>


<p>Example:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = 0; i &lt; 15; ++i) </span><span class="doxyHighlightComment">// Canonical loop "i"</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> j = 0; <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea363b122c528f54df4a0446b6bab05515">j</a> &lt; 14; ++<a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea363b122c528f54df4a0446b6bab05515">j</a>) </span><span class="doxyHighlightComment">// Canonical loop "j"</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      body(i, j);</span></span></div>

</div>


<p>After tiling with Loops={i,j} and TileSizes={5,7}, the loop is changed to</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i1 = 0; i1 &lt; 3; ++i1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> j1 = 0; j1 &lt; 2; ++j1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i2 = 0; i2 &lt; 5; ++i2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> j2 = 0; j2 &lt; 7; ++j2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        body(i1*3+i2, j1*3+j2);</span></span></div>

</div>


<p>The returned vector are the loops {i1,j1,i2,j2}. The loops i1 and j1 are referred to the floor, and the loops i2 and j2 are the tiles. Tiling also handles non-constant trip counts, non-constant tile sizes and trip counts that are not multiples of the tile size. In the latter case the tile loop of the last floor-loop iteration will have fewer iterations than specified as its tile size.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug location for instructions added by tiling, for instance the floor- and tile trip count computation.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Loops</td>
<td class="doxyParamItemDescription"><p>Loops to tile. The <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> objects are invalidated by this method, i.e. should not used after tiling.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TileSizes</td>
<td class="doxyParamItemDescription"><p>For each loop in <span class="doxyComputerOutput">Loops</span>, the tile size for that dimensions.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A list of generated loops. Contains twice as many loops as the input loop nest; the first half are the floor loops and the second half are the tile loops.</p></dd>
</dl>


<p>Declaration at line 1161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 5015 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ada72881d16e555ca8525a916364048f9a69820949e2fb6d1d719487d27f0df883">llvm::Continue</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8c75539a39f167f352b37ccdd788a7e4">llvm::IRBuilderBase::CreateICmpEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="#a445fa52d77040bccb16bfea111234a2e">createLoopSkeleton</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aecd40f9a16dc0ef1e0bc416599f89277">llvm::IRBuilderBase::CreateMul</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a49b228f797f9b3563256da446100c3ac">llvm::IRBuilderBase::CreateSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6b68047eda0d6d6eec5dd564ed1a22b8">llvm::IRBuilderBase::CreateUDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae884a856c5f31ab8fcf64f81db130dcd">llvm::IRBuilderBase::CreateURem</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9e6950f7f17700d5c0d61ad0b846ec5c">llvm::IRBuilderBase::CreateZExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a92d8bce979891dc43b6573e8cca2e58c">llvm::CanonicalLoopInfo::getAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a47521ec347ef7b522745bf89e2e2d19a">llvm::CanonicalLoopInfo::getBody</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#ad3bf46daef8ce8176a68bcec0320dfd3">llvm::CanonicalLoopInfo::getExit</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#af4131f5f461f1138483addfd7cd7f579">llvm::CanonicalLoopInfo::getIndVar</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#ac37a6cf77f6f82b6bb28af4d9c8626d0">llvm::CanonicalLoopInfo::getLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a1b4bf7c97cdc8159fd73d48063f0b250">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#ad50eb30e70ff2a9ea7f220547e2b6f6d">llvm::CanonicalLoopInfo::getPreheader</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#ac72ebc430ef7dcf1791c66080ddedd9d">llvm::CanonicalLoopInfo::getPreheaderIP</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#aef9e9fcf4c5dfce90276ca16d91b8e46">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp/#ada7c1594a393ede3ce32602d64d7ddb2">Loops</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#abdcdbfc178873f5055fbcf98bad92f53">redirectAllPredecessorsTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3057c2b7e1e25de160497b1ef3985c2a">redirectTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#af0ce60c4a958016f62ce78f1eda423af">removeUnusedBlocksFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac8778dcbd35e8ae5902050117feb57a0">llvm::IRBuilderBase::restoreIP</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a63fc74646456a3bed261512f21efe29c">llvm::IRBuilderBase::SetCurrentDebugLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#af1138294df67ee063ee3b7632a2f843f">TileSize</a>.</p>


<p>Referenced by <a href="#a5e2b7ac5f48193117a340aa15b085719">unrollLoopPartial</a>.</p>

</div>
</div>

### unrollLoopFull() {#a28a2a9806d828609fe107f766d2dd569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::unrollLoopFull (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * Loop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fully unroll a loop.</p>


<p>Instead of unrolling the loop immediately (and duplicating its body instructions), it is deferred to LLVM's <a href="/web-llvm/docs/api/classes/llvm/loopunrollpass">LoopUnrollPass</a> by adding loop metadata.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug location for instructions added by unrolling.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/loop"&gt;Loop&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The loop to unroll. The loop will be invalidated.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 5254 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#adf813540e363817b85e9eecef51269b5">addLoopMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa2ed385be8984b4306762990278eb13d">llvm::IRBuilderBase::getContext</a>.</p>

</div>
</div>

### unrollLoopHeuristic() {#a4ca0068cb6a50615c74ecdb8f23839e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::unrollLoopHeuristic (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * Loop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fully or partially unroll a loop.</p>


<p>How the loop is unrolled is determined using LLVM's <a href="/web-llvm/docs/api/classes/llvm/loopunrollpass">LoopUnrollPass</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug location for instructions added by unrolling.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/loop"&gt;Loop&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The loop to unroll. The loop will be invalidated.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 5261 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#adf813540e363817b85e9eecef51269b5">addLoopMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa2ed385be8984b4306762990278eb13d">llvm::IRBuilderBase::getContext</a>.</p>

</div>
</div>

### unrollLoopPartial() {#a5e2b7ac5f48193117a340aa15b085719}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::unrollLoopPartial (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * Loop, int32_t Factor, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> ** UnrolledCLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Partially unroll a loop.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> of the unrolled loop for use with chained loop-associated directive can be requested using <span class="doxyComputerOutput">UnrolledCLI</span>. Not needing the <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> allows more efficient code generation by deferring the actual unrolling to the <a href="/web-llvm/docs/api/classes/llvm/loopunrollpass">LoopUnrollPass</a> using loop metadata. A loop-associated directive applied to the unrolled loop needs to know the new trip count which means that if using a heuristically determined unroll factor (<span class="doxyComputerOutput">Factor</span> == 0), that factor must be computed immediately. We are using the same logic as the <a href="/web-llvm/docs/api/classes/llvm/loopunrollpass">LoopUnrollPass</a> to derived the unroll factor, but which assumes that some canonicalization has taken place (e.g. Mem2Reg, LICM, GVN, Inlining, etc.). That is, the heuristic will perform better when the unrolled loop's <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> is not needed.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug location for instructions added by unrolling.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/loop"&gt;Loop&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>The loop to unroll. The loop will be invalidated.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Factor</td>
<td class="doxyParamItemDescription"><p>The factor to unroll the loop by. A factor of 0 indicates that a heuristic should be used to determine the unroll-factor.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">UnrolledCLI</td>
<td class="doxyParamItemDescription"><p>If non-null, receives the <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> of the partially unrolled loop. Otherwise, uses loop metadata to defer unrolling to the <a href="/web-llvm/docs/api/classes/llvm/loopunrollpass">LoopUnrollPass</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 5612 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#adf813540e363817b85e9eecef51269b5">addLoopMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a946282957319b8c23ab9f169abb504c4">computeHeuristicUnrollFactor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#affbb7e2e9ad8d18114816f2443d672b9">llvm::MDString::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a13e877ef779ba7a0688081079f4f9b03">llvm::Type::getIntegerBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#a76e12ec076e7af4be7b8b77a5d53d3fc">tileLoops</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### applyDynamicWorkshareLoop() {#a040fad70b742c2d5fb4df1006b8e2fe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::applyDynamicWorkshareLoop (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * CLI, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a231ea6a9a0009e38969a20d4293119c7">omp::OMPScheduleType</a> SchedType, bool NeedsBarrier, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Chunk=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Modifies the canonical loop to be a dynamically-scheduled workshare loop.</p>


<p>This takes a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a></span> representing a canonical loop, such as the one created by <span class="doxyComputerOutput">createCanonicalLoop</span> and emits additional instructions to turn it into a workshare loop. In particular, it calls to an OpenMP runtime function in the preheader to obtain, and then in each iteration to update the loop counter.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug location for instructions added for the workshare-loop construct itself.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CLI</td>
<td class="doxyParamItemDescription"><p>A descriptor of the canonical loop to workshare.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>An insertion point for Alloca instructions usable in the preheader of the loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SchedType</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> of scheduling to be passed to the init function.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NeedsBarrier</td>
<td class="doxyParamItemDescription"><p>Indicates whether a barrier must be insterted after the loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Chunk</td>
<td class="doxyParamItemDescription"><p>The size of loop chunk considered as a unit when scheduling. If <span class="doxyComputerOutput">nullptr</span>, defaults to 1.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Point where to insert code after the workshare construct.</p></dd>
</dl>


<p>Declaration at line 1051 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 4723 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### applyStaticChunkedWorkshareLoop() {#ae5ac7c7120c51e85a0a9b107b278773f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::applyStaticChunkedWorkshareLoop (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * CLI, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, bool NeedsBarrier, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ChunkSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Modifies the canonical loop a statically-scheduled workshare loop with a user-specified chunk size.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug location for instructions added for the workshare-loop construct itself.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CLI</td>
<td class="doxyParamItemDescription"><p>A descriptor of the canonical loop to workshare.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>An insertion point for Alloca instructions usable in the preheader of the loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NeedsBarrier</td>
<td class="doxyParamItemDescription"><p>Indicates whether a barrier must be inserted after the loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ChunkSize</td>
<td class="doxyParamItemDescription"><p>The user-specified chunk size.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Point where to insert code after the workshare construct.</p></dd>
</dl>


<p>Declaration at line 1025 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 4235 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### applyStaticWorkshareLoop() {#a4844b18964505b7687f7261c6eccde30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointOrErrorTy OpenMPIRBuilder::applyStaticWorkshareLoop (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * CLI, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, bool NeedsBarrier)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Modifies the canonical loop to be a statically-scheduled workshare loop.</p>


<p>This takes a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a></span> representing a canonical loop, such as the one created by <span class="doxyComputerOutput">createCanonicalLoop</span> and emits additional instructions to turn it into a workshare loop. In particular, it calls to an OpenMP runtime function in the preheader to obtain the loop bounds to be used in the current thread, updates the relevant instructions in the canonical loop and calls to an OpenMP runtime finalization function after the loop.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug location for instructions added for the workshare-loop construct itself.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CLI</td>
<td class="doxyParamItemDescription"><p>A descriptor of the canonical loop to workshare.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>An insertion point for Alloca instructions usable in the preheader of the loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NeedsBarrier</td>
<td class="doxyParamItemDescription"><p>Indicates whether a barrier must be inserted after the loop.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Point where to insert code after the workshare construct.</p></dd>
</dl>


<p>Declaration at line 1007 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 4143 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### applyWorkshareLoopTarget() {#a3614ae5b7da8dfc1d3b6e74e3b114ae8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointTy OpenMPIRBuilder::applyWorkshareLoopTarget (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * CLI, <a href="#aafc1886793b898052f87edd7e9fdbaa3">InsertPointTy</a> AllocaIP, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#ab6fb146c332fd3f3d677ee65081fe669">omp::WorksharingLoopType</a> LoopType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Modifies the canonical loop to be a statically-scheduled workshare loop which is executed on the device.</p>


<p>This takes a <span class="doxyComputerOutput">CLI</span> representing a canonical loop, such as the one created by</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#ae0287686a5ffe03bc264972c862726ea">createCanonicalLoop</a> and emits additional <a href="/web-llvm/docs/api/namespaces/llvm/#a7e3e687ddfdcbacd404bcf17b917dd88">instructions</a> to turn it into a workshare loop. In particular, it calls to an OpenMP runtime <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a> in the <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#aecea88f231914d2a6dc7ecf19a57f583">preheader</a> to call OpenMP device rtl <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a> which handles worksharing of loop body interations.</p></dd>
</dl>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DL</td>
<td class="doxyParamItemDescription"><p>Debug location for instructions added for the workshare-loop construct itself.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CLI</td>
<td class="doxyParamItemDescription"><p>A descriptor of the canonical loop to workshare.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">AllocaIP</td>
<td class="doxyParamItemDescription"><p>An insertion point for Alloca instructions usable in the preheader of the loop.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LoopType</td>
<td class="doxyParamItemDescription"><p>Information about type of loop worksharing. It corresponds to type of loop workshare OpenMP pragma.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Point where to insert code after the workshare construct.</p></dd>
</dl>


<p>Declaration at line 985 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 4528 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### createIfVersion() {#af94ce0ccebe00cffe61b5a50ba679eb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OpenMPIRBuilder::createIfVersion (<a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> * Loop, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * IfCond, <a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &amp; VMap, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; NamePrefix="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create alternative version of the loop to support if clause.</p>


<p>OpenMP if clause can require to generate second loop. This loop will be executed when if clause condition is not met. createIfVersion adds branch instruction to the copied loop if <span class="doxyComputerOutput">ifCond</span> is not met.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/loop"&gt;Loop&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>Original loop which should be versioned.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IfCond</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> which corresponds to if clause condition</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VMap</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to value map to define relation between original and copied loop values and loop blocks.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NamePrefix</td>
<td class="doxyParamItemDescription"><p>Optional name prefix for if.then if.else blocks.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1069 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 5269 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ompOffloadInfoName {#aefadc356da16598ff8c210dafbf4a2b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string llvm::OpenMPIRBuilder::ompOffloadInfoName = "omp_offload.info"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>OMP Offload Info <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> name string.</p>

<p>Definition at line 3385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a2242b144e54fa6203dae5c5b27fff17c">loadOffloadInfoMetadata</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getOpenMPDefaultSimdAlign() {#ac5b407054e7727d04053af9c3f1a5568}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned OpenMPIRBuilder::getOpenMPDefaultSimdAlign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TargetTriple, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; bool &gt; &amp; Features)</td>
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

<p>Get the default alignment value for given target.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">TargetTriple</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> triple</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Features</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a> which describes extra CPU features</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 850 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 5326 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a0338eabc8ab4dff6368bdfae6ec94cbc">llvm::Triple::isPPC</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#acf7f07dbe7dd1f7edd291b75005280bb">llvm::Triple::isWasm</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a31d94b95418472bb1179f7c130ad3667">llvm::Triple::isX86</a> and <a href="/web-llvm/docs/api/classes/llvm/stringmap/#aa6528965c64b379c2cb311599babdd66">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::lookup</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
