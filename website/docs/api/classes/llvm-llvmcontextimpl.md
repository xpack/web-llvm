---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/llvmcontextimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LLVMContextImpl` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::LLVMContextImpl { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">IR/LLVMContextImpl.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1831916bef7a206f18131b6d938cd80d">ArrayConstantsTy</a> = <a href="/web-llvm/docs/api/classes/llvm/constantuniquemap">ConstantUniqueMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantarray">ConstantArray</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c8e54d804d71547e188646ebcea9203">StructConstantsTy</a> = <a href="/web-llvm/docs/api/classes/llvm/constantuniquemap">ConstantUniqueMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantstruct">ConstantStruct</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a907d6e309611bf4c05cfa34965e5ca51">VectorConstantsTy</a> = <a href="/web-llvm/docs/api/classes/llvm/constantuniquemap">ConstantUniqueMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantvector">ConstantVector</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31a3b2d4153f19b04caae0596c91beea">FunctionTypeSet</a> = <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *, <a href="/web-llvm/docs/api/structs/llvm/functiontypekeyinfo">FunctionTypeKeyInfo</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99586e38e8292178db61156524fdae89">StructTypeSet</a> = <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *, <a href="/web-llvm/docs/api/structs/llvm/anonstructtypekeyinfo">AnonStructTypeKeyInfo</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8128667a1c6f8bfeb7ccaf466763c2e7">TargetExtTypeSet</a> = <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/targetexttype">TargetExtType</a> *, <a href="/web-llvm/docs/api/structs/llvm/targetexttypekeyinfo">TargetExtTypeKeyInfo</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e1a4a8b289a88693e8cde2f69a9573b">ValueHandlesTy</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase">ValueHandleBase</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ValueHandles - This map keeps track of all of the value handles that are watching a Value*. <a href="#a3e1a4a8b289a88693e8cde2f69a9573b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0c345f7af54ce4d7760ba46cafda829">LLVMContextImpl</a> (LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a>&lt; uint32_t &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ca6e14339dfb653b003a458b80a4802">getOrInsertBundleTag</a> (StringRef Tag)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80ea243020c76d126ec3b7ab15ef98a7">getOperandBundleTags</a> (SmallVectorImpl&lt; StringRef &gt; &amp;Tags) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95831dc8eb81573c3fbc0d9bb9b5d648">getOperandBundleTagID</a> (StringRef Tag) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52c04e90a18244956f4a4f1d4b34fc64">getOrInsertSyncScopeID</a> (StringRef SSN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getOrInsertSyncScopeID - Maps synchronization scope name to synchronization scope <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#a52c04e90a18244956f4a4f1d4b34fc64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a8135ce55ec23fa669cc75cbe9bbbbb">getSyncScopeNames</a> (SmallVectorImpl&lt; StringRef &gt; &amp;SSNs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSyncScopeNames - Populates client supplied <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> with synchronization scope names registered with <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>. <a href="#a0a8135ce55ec23fa669cc75cbe9bbbbb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3da55a4479ec3a5551c1f8c1692d27a">getSyncScopeName</a> (SyncScope::ID Id) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSyncScopeName - Returns the name of a <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> registered with <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>, if any. <a href="#ab3da55a4479ec3a5551c1f8c1692d27a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a567c40e54b0f262c0628a0858d3cfef4">dropTriviallyDeadConstantArrays</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destroy the ConstantArrays if they are not used. <a href="#a567c40e54b0f262c0628a0858d3cfef4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optpassgate">OptPassGate</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6224046d8c0becf4d115077e047840fd">getOptPassGate</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Access the object which can disable optional passes and individual optimizations at compile time. <a href="#a6224046d8c0becf4d115077e047840fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a598e220b87343b4ab3d79b933e944266">setOptPassGate</a> (OptPassGate &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the object which can disable optional passes and individual optimizations at compile time. <a href="#a598e220b87343b4ab3d79b933e944266">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9751861133b9513c99ea00d34c2bb226">setTrailingDbgRecords</a> (BasicBlock *B, DbgMarker *M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ef702eb2f7d1c2e407d84aaf80abd7e">getTrailingDbgRecords</a> (BasicBlock *B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a860776385fdeb0b48627421c8c19c4cd">deleteTrailingDbgRecords</a> (BasicBlock *B)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a271edc637955bfe7e14822b65232952a">OwnedModules</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OwnedModules - The set of modules instantiated in this context, and which will be automatically deleted if this context is deleted. <a href="#a271edc637955bfe7e14822b65232952a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66adecf60a5af16521adc8e487822fcb">MachineFunctionNums</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MachineFunctionNums - Keep the next available unique number available for a <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> in given module. <a href="#a66adecf60a5af16521adc8e487822fcb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/remarks/remarkstreamer">remarks::RemarkStreamer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f9ffb199060f6ce4914e30b4ec45ce5">MainRemarkStreamer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The main remark streamer used by all the other streamers (e.g. <a href="#a7f9ffb199060f6ce4914e30b4ec45ce5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/diagnostichandler">DiagnosticHandler</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d266e2863d21d8440b10d3ba8459b49">DiagHandler</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60ca5513ecfaf1900eeb107df01b4921">RespectDiagnosticFilters</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a093c2d1ceee19d121b383b07dd126f0f">DiagnosticsHotnessRequested</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ff727d15564ae8b68804e7affbc6014">DiagnosticsHotnessThreshold</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The minimum hotness value a diagnostic needs in order to be included in optimization diagnostics. <a href="#a8ff727d15564ae8b68804e7affbc6014">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cf29558abcb57557b1ad4d3e4165e6d">DiagnosticsMisExpectTolerance</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The percentage of difference between profiling branch weights and llvm.expect branch weights to tolerate when emiting MisExpect diagnostics. <a href="#a4cf29558abcb57557b1ad4d3e4165e6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9c800f160b2c0cbe0f17c4ac6cfeab5">MisExpectWarningRequested</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/llvmremarkstreamer">LLVMRemarkStreamer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c722375f3fbaf09c9ad347f48f7c679">LLVMRS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The specialized remark streamer used by LLVM's <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a>. <a href="#a5c722375f3fbaf09c9ad347f48f7c679">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a8671da9544d8cfdf4ccc798e560bdccc">LLVMContext::YieldCallbackTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e78b85d9aad8a6f57c093705f5f7377">YieldCallback</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1727c74daa04e8276724f6de6deefa4">YieldOpaqueHandle</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/#a0974858ce658c475882ec1f6082145de">ValueName</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f816abcc93f58b2ea13618d148571a6">ValueNames</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b588ed032999d7b5686ae8c360b2936">IntZeroConstants</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09021e2b1d263b878063b554afd2dd3c">IntOneConstants</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c303c93282542e5eb52a4582b50c12f">IntConstants</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt;, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a1940276b765c03535ce27337364739">IntSplatConstants</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a>, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a246739267b102ead8bf1df4244a3cf00">FPConstants</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &gt;, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/constantfp">ConstantFP</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcf3927d5d1a9591fde1bd287202396f">FPSplatConstants</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/attributeimpl">AttributeImpl</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d5c45796336faff2d002acf79822eed">AttrsSet</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/attributelistimpl">AttributeListImpl</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88d04028d866b4402b3b3afd0c556cd9">AttrsLists</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/attributesetnode">AttributeSetNode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86df617fc1143331a89e8a72411eec7f">AttrsSetNodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2757063573b80cb1423828875aee939f">MDStringCache</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/valueasmetadata">ValueAsMetadata</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9825bb3a01150a90106e731b9fe23df">ValuesAsMetadata</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *, <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue">MetadataAsValue</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f84a0b5ee0bc1f89540f7dac8cf80a0">MetadataAsValues</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/diarglist">DIArgList</a> *, <a href="/web-llvm/docs/api/structs/llvm/diarglistinfo">DIArgListInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1d6012d83c37ebdb4d1c311d6a7c62f">DIArgLists</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *, <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af750ba05f1932996166443b9de31e0ac">DITypeMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a486a6a1f8fa108a74b851328dca40143">DistinctMDNodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrangelistattributeimpl">ConstantRangeListAttributeImpl</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab69a0e7093a29bbd1badab6978c224b">ConstantRangeListAttributes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/constantaggregatezero">ConstantAggregateZero</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2730bea5049aa895d5576a08f020d052">CAZConstants</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1831916bef7a206f18131b6d938cd80d">ArrayConstantsTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5a9f7116acdae2b3cc1135592745bd4">ArrayConstants</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a6c8e54d804d71547e188646ebcea9203">StructConstantsTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78cf754889634eb9bcd3fbbae006ccc8">StructConstants</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a907d6e309611bf4c05cfa34965e5ca51">VectorConstantsTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ad082a7058a5071c015ff18cb1d9d02">VectorConstants</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/constantpointernull">ConstantPointerNull</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27267b9113fe5612e822aaa90bdc3130">CPNConstants</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/targetexttype">TargetExtType</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/constanttargetnone">ConstantTargetNone</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cd8b08cb9114ed1b27a90c79b13fb71">CTNConstants</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/undefvalue">UndefValue</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61efa06e00257bf060f040285796ad66">UVConstants</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/poisonvalue">PoisonValue</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3887b5bd85846ac49e356acceac66bed">PVConstants</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential">ConstantDataSequential</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a782391b2d09b2ce386bc7b3cceddccd8">CDSConstants</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt;, <a href="/web-llvm/docs/api/classes/llvm/blockaddress">BlockAddress</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a391d28e01be2d447a86d2bf65abb87e6">BlockAddresses</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *, <a href="/web-llvm/docs/api/classes/llvm/dsolocalequivalent">DSOLocalEquivalent</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6df8cfa0a66d2bf993b785867409fab">DSOLocalEquivalents</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *, <a href="/web-llvm/docs/api/classes/llvm/nocfivalue">NoCFIValue</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ca254b9ecfa479e9ca139e3935bf9a1">NoCFIValues</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantuniquemap">ConstantUniqueMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantptrauth">ConstantPtrAuth</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bb2388d55e07ee44857ece1dbc4aece">ConstantPtrAuths</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantuniquemap">ConstantUniqueMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantexpr">ConstantExpr</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93700cfa46f68a6f83edadd6baaa80a3">ExprConstants</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantuniquemap">ConstantUniqueMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/inlineasm">InlineAsm</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9a2da2321bac0d860e669057aa11d6d">InlineAsms</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bec169369c9b3d9d93a4a0446c9b2d8">TheTrueVal</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31be55ec6c7ff877970345924ef5360a">TheFalseVal</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af24d867582451a918bccd13312a43614">VoidTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b7edf39d72912406edad668135f2a6a">LabelTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4344c5f584f62f2258d455340a6b880a">HalfTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cb7fe0720c48ba8fb0a3f22e9b7f178">BFloatTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9935ea89798e706d71c07df052d8ad7">FloatTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f8038fc9deb1ab370ee0b48df0d0996">DoubleTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02c738bfd8bfffbe459f84cdeb4ff3f2">MetadataTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea8b78a5e4b967d6310f492d401e181f">TokenTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bdfed2761afc9ad9138fc657e051135">X86_FP80Ty</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2fa2d8454fd4d6990ff46623ea4d54b">FP128Ty</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa9e13311374a56c97a28c6be9b4a51e">PPC_FP128Ty</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41ab916b680d90327508bd4c94401b16">X86_AMXTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a875e29869b5d4e27e5593927ce3ffbee">Int1Ty</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87e78b20e48f1a8c41f0a3e6d4748fdc">Int8Ty</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a290d03d5c83b8da571c5dc6e8b32a528">Int16Ty</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e521c21ddbbb77b396e87f73b7ef944">Int32Ty</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42ad6696dfe051f4caf4ebe5bb6ea622">Int64Ty</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac40414b8a45ce751efafbce3e1eabbe">Int128Ty</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/constanttokennone">ConstantTokenNone</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ee4d8c911290fbaec8dc80acb3b4567">TheNoneToken</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7176f21e453f3b16e41d7c9084139746">Alloc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/uniquestringsaver">UniqueStringSaver</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b7a55908da35f0359df5eb4279015ca">Saver</a> {<a href="#a7176f21e453f3b16e41d7c9084139746">Alloc</a>}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrangeattributeimpl">ConstantRangeAttributeImpl</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d9d7a6dea8a065912b098f383144ced">ConstantRangeAttributeAlloc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ffb52d71ceda7afe461295959e88965">IntegerTypes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a31a3b2d4153f19b04caae0596c91beea">FunctionTypeSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af37084d813c63755211059f16a420356">FunctionTypes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a99586e38e8292178db61156524fdae89">StructTypeSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e3b47fc0a8f19fe8ba30c3c91532945">AnonStructTypes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1dbc2a398635aa424e045dcde7455e6">NamedStructTypes</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefb06147164bc496c5a09bedfb990642">NamedStructTypesUniqueID</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8128667a1c6f8bfeb7ccaf466763c2e7">TargetExtTypeSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3587a9d36772eaec39f456f6555de356">TargetExtTypes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, uint64_t &gt;, <a href="/web-llvm/docs/api/classes/llvm/arraytype">ArrayType</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64af069523bc7b72992f0e8550d03fa7">ArrayTypes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> &gt;, <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e9a22974a198cd487877b4beec90b91">VectorTypes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae079fd41bca5adfddc03e668fb9ef1d">AS0PointerType</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95f679f7d5ae1da04854ce807c9ea9e2">PointerTypes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, unsigned &gt;, <a href="/web-llvm/docs/api/classes/llvm/typedpointertype">TypedPointerType</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a625e880e5572f923e5f15c52c2a917a0">ASTypedPointerTypes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3e1a4a8b289a88693e8cde2f69a9573b">ValueHandlesTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab23b4c9009afa5058b6845920e164251">ValueHandles</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a2bd036574f4d51f20be99e0f3beb27">CustomMDKindNames</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CustomMDKindNames - Map to hold the metadata string to <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> mapping. <a href="#a6a2bd036574f4d51f20be99e0f3beb27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/mdattachments">MDAttachments</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6577bf24ddcb2a2cd401ee3e4704527a">ValueMetadata</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collection of metadata used in this context. <a href="#a6577bf24ddcb2a2cd401ee3e4704527a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 1 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a382cf610134589ebfa0040f2af7b7066">AssignmentIDToInstrs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map <a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> -&gt; Instructions with that attachment. <a href="#a382cf610134589ebfa0040f2af7b7066">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> *, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a778c21fabbe327d5a5b9192d52127298">GlobalObjectSections</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collection of per-GlobalObject sections used in this context. <a href="#a778c21fabbe327d5a5b9192d52127298">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a016dccd2194d0bcf0c171921ac089569">GlobalValuePartitions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collection of per-GlobalValue partitions used in this context. <a href="#a016dccd2194d0bcf0c171921ac089569">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *, <a href="/web-llvm/docs/api/structs/llvm/globalvalue/sanitizermetadata">GlobalValue::SanitizerMetadata</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0870bd38114456f0b723d2a5dc741879">GlobalValueSanitizerMetadata</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, unsigned &gt;, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca1a729e7039b0dd16190f74be5911b7">DiscriminatorTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DiscriminatorTable - This table maps <a href="file:line">file:line</a> locations to an integer representing the next DWARF path discriminator to assign to instructions in different blocks at the same location. <a href="#aca1a729e7039b0dd16190f74be5911b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d36c0d4f9a44fad4ca4867c407d8d4c">BundleTagCache</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A set of interned tags for operand bundles. <a href="#a6d36c0d4f9a44fad4ca4867c407d8d4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95e537127a71dc94522132234e1c751c">SSC</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A set of interned synchronization scopes. <a href="#a95e537127a71dc94522132234e1c751c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ebfdb2e37ef3ea1f52498332b80f2a0">GCNames</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maintain the GC name for each function. <a href="#a5ebfdb2e37ef3ea1f52498332b80f2a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c7699b477d925fed0264d67fedf2138">DiscardValueNames</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag to indicate if <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> (other than <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a>) retains their name or not. <a href="#a5c7699b477d925fed0264d67fedf2138">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optpassgate">OptPassGate</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a2eb1327e30482e9f9feba4be032098">OPG</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefd0c34f5360aebd059382bfb2adbe22">TrailingDbgRecords</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mapping of blocks to collections of "trailing" DbgVariableRecords. <a href="#aefd0c34f5360aebd059382bfb2adbe22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1debdaadc09d824caa03270fb2e4a78b">DefaultTargetCPU</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a651a1b04a988601e18ad3c319d16ea7a">DefaultTargetFeatures</a></td>
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


<p>Definition at line 1469 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ArrayConstantsTy {#a1831916bef7a206f18131b6d938cd80d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LLVMContextImpl::ArrayConstantsTy =  ConstantUniqueMap&lt;ConstantArray&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1561 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### FunctionTypeSet {#a31a3b2d4153f19b04caae0596c91beea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LLVMContextImpl::FunctionTypeSet =  DenseSet&lt;FunctionType *, FunctionTypeKeyInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1611 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### StructConstantsTy {#a6c8e54d804d71547e188646ebcea9203}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LLVMContextImpl::StructConstantsTy =  ConstantUniqueMap&lt;ConstantStruct&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1564 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### StructTypeSet {#a99586e38e8292178db61156524fdae89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LLVMContextImpl::StructTypeSet =  DenseSet&lt;StructType *, AnonStructTypeKeyInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1613 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### TargetExtTypeSet {#a8128667a1c6f8bfeb7ccaf466763c2e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LLVMContextImpl::TargetExtTypeSet =  DenseSet&lt;TargetExtType *, TargetExtTypeKeyInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1618 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### ValueHandlesTy {#a3e1a4a8b289a88693e8cde2f69a9573b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LLVMContextImpl::ValueHandlesTy =  DenseMap&lt;Value *, ValueHandleBase *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ValueHandles - This map keeps track of all of the value handles that are watching a Value*.</p>


<p>The Value::HasValueHandle bit is used to know whether or not a value has an entry in this map.</p>


<p>Definition at line 1630 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### VectorConstantsTy {#a907d6e309611bf4c05cfa34965e5ca51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LLVMContextImpl::VectorConstantsTy =  ConstantUniqueMap&lt;ConstantVector&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1567 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LLVMContextImpl() {#ad0c345f7af54ce4d7760ba46cafda829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContextImpl::LLVMContextImpl (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1697 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-cpp">LLVMContextImpl.cpp</a>.</p>


<p>References <a href="#a8cb7fe0720c48ba8fb0a3f22e9b7f178">BFloatTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a6d266e2863d21d8440b10d3ba8459b49">DiagHandler</a>, <a href="#a8f8038fc9deb1ab370ee0b48df0d0996">DoubleTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloat-cpp/#ad51bb65198c820479d8dfb791398bdb4">DoubleTyID</a>, <a href="#ac9935ea89798e706d71c07df052d8ad7">FloatTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloat-cpp/#a4b16746dbe37b7e366f5e2721505b686">FloatTyID</a>, <a href="#af2fa2d8454fd4d6990ff46623ea4d54b">FP128Ty</a>, <a href="#a4344c5f584f62f2258d455340a6b880a">HalfTy</a>, <a href="#aac40414b8a45ce751efafbce3e1eabbe">Int128Ty</a>, <a href="#a290d03d5c83b8da571c5dc6e8b32a528">Int16Ty</a>, <a href="#a875e29869b5d4e27e5593927ce3ffbee">Int1Ty</a>, <a href="#a1e521c21ddbbb77b396e87f73b7ef944">Int32Ty</a>, <a href="#a42ad6696dfe051f4caf4ebe5bb6ea622">Int64Ty</a>, <a href="#a87e78b20e48f1a8c41f0a3e6d4748fdc">Int8Ty</a>, <a href="#a3b7edf39d72912406edad668135f2a6a">LabelTy</a>, <a href="#a02c738bfd8bfffbe459f84cdeb4ff3f2">MetadataTy</a>, <a href="#afa9e13311374a56c97a28c6be9b4a51e">PPC_FP128Ty</a>, <a href="#aea8b78a5e4b967d6310f492d401e181f">TokenTy</a>, <a href="#af24d867582451a918bccd13312a43614">VoidTy</a>, <a href="#a41ab916b680d90327508bd4c94401b16">X86_AMXTy</a> and <a href="#a9bdfed2761afc9ad9138fc657e051135">X86_FP80Ty</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LLVMContextImpl() {#a5d9383a7827bb76858af4b9dd1a7e0ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContextImpl::~LLVMContextImpl ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1698 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-cpp">LLVMContextImpl.cpp</a>.</p>


<p>References <a href="#ab5a9f7116acdae2b3cc1135592745bd4">ArrayConstants</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a86df617fc1143331a89e8a72411eec7f">AttrsSetNodes</a>, <a href="#a2730bea5049aa895d5576a08f020d052">CAZConstants</a>, <a href="#a782391b2d09b2ce386bc7b3cceddccd8">CDSConstants</a>, <a href="#aab69a0e7093a29bbd1badab6978c224b">ConstantRangeListAttributes</a>, <a href="#a27267b9113fe5612e822aaa90bdc3130">CPNConstants</a>, <a href="#a8cd8b08cb9114ed1b27a90c79b13fb71">CTNConstants</a>, <a href="#ab1d6012d83c37ebdb4d1c311d6a7c62f">DIArgLists</a>, <a href="#a486a6a1f8fa108a74b851328dca40143">DistinctMDNodes</a>, <a href="#a93700cfa46f68a6f83edadd6baaa80a3">ExprConstants</a>, <a href="#a246739267b102ead8bf1df4244a3cf00">FPConstants</a>, <a href="#afcf3927d5d1a9591fde1bd287202396f">FPSplatConstants</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac9a2da2321bac0d860e669057aa11d6d">InlineAsms</a>, <a href="#a3c303c93282542e5eb52a4582b50c12f">IntConstants</a>, <a href="#a09021e2b1d263b878063b554afd2dd3c">IntOneConstants</a>, <a href="#a9a1940276b765c03535ce27337364739">IntSplatConstants</a>, <a href="#a0b588ed032999d7b5686ae8c360b2936">IntZeroConstants</a>, <a href="#a0f84a0b5ee0bc1f89540f7dac8cf80a0">MetadataAsValues</a>, <a href="#a271edc637955bfe7e14822b65232952a">OwnedModules</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a3887b5bd85846ac49e356acceac66bed">PVConstants</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="#a78cf754889634eb9bcd3fbbae006ccc8">StructConstants</a>, <a href="#aefd0c34f5360aebd059382bfb2adbe22">TrailingDbgRecords</a>, <a href="#a61efa06e00257bf060f040285796ad66">UVConstants</a>, <a href="#a6577bf24ddcb2a2cd401ee3e4704527a">ValueMetadata</a>, <a href="#ab9825bb3a01150a90106e731b9fe23df">ValuesAsMetadata</a> and <a href="#a5ad082a7058a5071c015ff18cb1d9d02">VectorConstants</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### deleteTrailingDbgRecords() {#a860776385fdeb0b48627421c8c19c4cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LLVMContextImpl::deleteTrailingDbgRecords (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * B)</td>
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



<p>Definition at line 1742 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#aefd0c34f5360aebd059382bfb2adbe22">TrailingDbgRecords</a>.</p>

</div>
</div>

### dropTriviallyDeadConstantArrays() {#a567c40e54b0f262c0628a0858d3cfef4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContextImpl::dropTriviallyDeadConstantArrays ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Destroy the ConstantArrays if they are not used.</p>

<p>Declaration at line 1701 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>, definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-cpp">LLVMContextImpl.cpp</a>.</p>


<p>References <a href="#ab5a9f7116acdae2b3cc1135592745bd4">ArrayConstants</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#ac178f4fc4e4a0642610c374256b9fb27">llvm::SetVector&lt; T, Vector, Set, N &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a> and <a href="/web-llvm/docs/api/classes/llvm/setvector/#af9880d625c506aacc716ee1c9a29ff8b">llvm::SetVector&lt; T, Vector, Set, N &gt;::pop_back_val</a>.</p>

</div>
</div>

### getOperandBundleTagID() {#a95831dc8eb81573c3fbc0d9bb9b5d648}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t LLVMContextImpl::getOperandBundleTagID (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1666 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>, definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-cpp">LLVMContextImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6d36c0d4f9a44fad4ca4867c407d8d4c">BundleTagCache</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>.</p>

</div>
</div>

### getOperandBundleTags() {#a80ea243020c76d126ec3b7ab15ef98a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContextImpl::getOperandBundleTags (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; Tags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1665 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>, definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-cpp">LLVMContextImpl.cpp</a>.</p>


<p>References <a href="#a6d36c0d4f9a44fad4ca4867c407d8d4c">BundleTagCache</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### getOptPassGate() {#a6224046d8c0becf4d115077e047840fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptPassGate &amp; LLVMContextImpl::getOptPassGate ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Access the object which can disable optional passes and individual optimizations at compile time.</p>


<p>Gets the <a href="/web-llvm/docs/api/classes/llvm/optpassgate">OptPassGate</a> for this <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl">LLVMContextImpl</a>, which defaults to the singleton <a href="/web-llvm/docs/api/classes/llvm/optbisect">OptBisect</a> if not explicitly set.</p>


<p>Declaration at line 1707 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>, definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-cpp">LLVMContextImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a40dfa1d23e21383d154cb6905aaa8031">llvm::getGlobalPassGate</a> and <a href="#a8a2eb1327e30482e9f9feba4be032098">OPG</a>.</p>

</div>
</div>

### getOrInsertBundleTag() {#a6ca6e14339dfb653b003a458b80a4802}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMapEntry&lt; uint32_t &gt; * LLVMContextImpl::getOrInsertBundleTag (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1664 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>, definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-cpp">LLVMContextImpl.cpp</a>.</p>


<p>References <a href="#a6d36c0d4f9a44fad4ca4867c407d8d4c">BundleTagCache</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>.</p>

</div>
</div>

### getOrInsertSyncScopeID() {#a52c04e90a18244956f4a4f1d4b34fc64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SyncScope::ID LLVMContextImpl::getOrInsertSyncScopeID (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SSN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getOrInsertSyncScopeID - Maps synchronization scope name to synchronization scope <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>


<p>Every synchronization scope registered with <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> has unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> except pre-defined ones.</p>


<p>Declaration at line 1675 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>, definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-cpp">LLVMContextImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a95e537127a71dc94522132234e1c751c">SSC</a>.</p>

</div>
</div>

### getSyncScopeName() {#ab3da55a4479ec3a5551c1f8c1692d27a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; StringRef &gt; LLVMContextImpl::getSyncScopeName (<a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> Id)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getSyncScopeName - Returns the name of a <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> registered with <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>, if any.</p>

<p>Declaration at line 1684 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>, definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-cpp">LLVMContextImpl.cpp</a>.</p>


<p>References <a href="#a95e537127a71dc94522132234e1c751c">SSC</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abe2c24a8dc2fb979e8e54e15f088169ca5fc53fc8197865c63285f74b1e147013">llvm::SSE</a>.</p>

</div>
</div>

### getSyncScopeNames() {#a0a8135ce55ec23fa669cc75cbe9bbbbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContextImpl::getSyncScopeNames (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; SSNs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getSyncScopeNames - Populates client supplied <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> with synchronization scope names registered with <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>.</p>


<p>Synchronization scope names are ordered by increasing synchronization scope IDs.</p>


<p>Declaration at line 1680 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>, definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-cpp">LLVMContextImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>, <a href="#a95e537127a71dc94522132234e1c751c">SSC</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abe2c24a8dc2fb979e8e54e15f088169ca5fc53fc8197865c63285f74b1e147013">llvm::SSE</a>.</p>

</div>
</div>

### getTrailingDbgRecords() {#a6ef702eb2f7d1c2e407d84aaf80abd7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgMarker * llvm::LLVMContextImpl::getTrailingDbgRecords (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * B)</td>
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



<p>Definition at line 1738 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#aefd0c34f5360aebd059382bfb2adbe22">TrailingDbgRecords</a>.</p>

</div>
</div>

### setOptPassGate() {#a598e220b87343b4ab3d79b933e944266}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMContextImpl::setOptPassGate (<a href="/web-llvm/docs/api/classes/llvm/optpassgate">OptPassGate</a> &amp; OPG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the object which can disable optional passes and individual optimizations at compile time.</p>


<p>The lifetime of the object must be guaranteed to extend as long as the <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> is used by compilation.</p>


<p>Declaration at line 1714 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>, definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-cpp">LLVMContextImpl.cpp</a>.</p>


<p>Reference <a href="#a8a2eb1327e30482e9f9feba4be032098">OPG</a>.</p>

</div>
</div>

### setTrailingDbgRecords() {#a9751861133b9513c99ea00d34c2bb226}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LLVMContextImpl::setTrailingDbgRecords (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * B, <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> * M)</td>
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



<p>Definition at line 1733 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#aefd0c34f5360aebd059382bfb2adbe22">TrailingDbgRecords</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Alloc {#a7176f21e453f3b16e41d7c9084139746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::LLVMContextImpl::Alloc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1604 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/typedpointertype/#ad0b317acb44e242226165a34d550702d">llvm::TypedPointerType::get</a>.</p>

</div>
</div>

### AnonStructTypes {#a4e3b47fc0a8f19fe8ba30c3c91532945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructTypeSet llvm::LLVMContextImpl::AnonStructTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1614 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### ArrayConstants {#ab5a9f7116acdae2b3cc1135592745bd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayConstantsTy llvm::LLVMContextImpl::ArrayConstants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1562 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a567c40e54b0f262c0628a0858d3cfef4">dropTriviallyDeadConstantArrays</a> and <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### ArrayTypes {#a64af069523bc7b72992f0e8550d03fa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;std::pair&lt;Type *, uint64_t&gt;, ArrayType *&gt; llvm::LLVMContextImpl::ArrayTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1621 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### AS0PointerType {#aae079fd41bca5adfddc03e668fb9ef1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType* llvm::LLVMContextImpl::AS0PointerType = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1623 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### AssignmentIDToInstrs {#a382cf610134589ebfa0040f2af7b7066}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;DIAssignID *, SmallVector&lt;Instruction *, 1&gt; &gt; llvm::LLVMContextImpl::AssignmentIDToInstrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map <a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> -&gt; Instructions with that attachment.</p>


<p>Managed by <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> via Instruction::updateDIAssignIDMapping. Query using the at:: functions defined in DebugInfo.h.</p>


<p>Definition at line 1642 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### ASTypedPointerTypes {#a625e880e5572f923e5f15c52c2a917a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;std::pair&lt;Type *, unsigned&gt;, TypedPointerType *&gt; llvm::LLVMContextImpl::ASTypedPointerTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1625 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/typedpointertype/#ad0b317acb44e242226165a34d550702d">llvm::TypedPointerType::get</a>.</p>

</div>
</div>

### AttrsLists {#a88d04028d866b4402b3b3afd0c556cd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSet&lt;AttributeListImpl&gt; llvm::LLVMContextImpl::AttrsLists</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1531 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### AttrsSet {#a4d5c45796336faff2d002acf79822eed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSet&lt;AttributeImpl&gt; llvm::LLVMContextImpl::AttrsSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1530 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### AttrsSetNodes {#a86df617fc1143331a89e8a72411eec7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSet&lt;AttributeSetNode&gt; llvm::LLVMContextImpl::AttrsSetNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1532 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### BFloatTy {#a8cb7fe0720c48ba8fb0a3f22e9b7f178}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type llvm::LLVMContextImpl::BFloatTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1597 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ad0c345f7af54ce4d7760ba46cafda829">LLVMContextImpl</a>.</p>

</div>
</div>

### BlockAddresses {#a391d28e01be2d447a86d2bf65abb87e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;std::pair&lt;const Function *, const BasicBlock *&gt;, BlockAddress *&gt; llvm::LLVMContextImpl::BlockAddresses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1581 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### BundleTagCache {#a6d36c0d4f9a44fad4ca4867c407d8d4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;uint32_t&gt; llvm::LLVMContextImpl::BundleTagCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A set of interned tags for operand bundles.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a> maps bundle tags to their IDs.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a1bf5d4ba3822ef0e75e953a9d19734a5">LLVMContext::getOperandBundleTagID</a></p></dd>
</dl>


<p>Definition at line 1662 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a95831dc8eb81573c3fbc0d9bb9b5d648">getOperandBundleTagID</a>, <a href="#a80ea243020c76d126ec3b7ab15ef98a7">getOperandBundleTags</a> and <a href="#a6ca6e14339dfb653b003a458b80a4802">getOrInsertBundleTag</a>.</p>

</div>
</div>

### CAZConstants {#a2730bea5049aa895d5576a08f020d052}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Type *, std::unique_ptr&lt;ConstantAggregateZero&gt; &gt; llvm::LLVMContextImpl::CAZConstants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1559 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### CDSConstants {#a782391b2d09b2ce386bc7b3cceddccd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;std::unique_ptr&lt;ConstantDataSequential&gt; &gt; llvm::LLVMContextImpl::CDSConstants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1578 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### ConstantPtrAuths {#a8bb2388d55e07ee44857ece1dbc4aece}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantUniqueMap&lt;ConstantPtrAuth&gt; llvm::LLVMContextImpl::ConstantPtrAuths</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1587 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantptrauth/#a51865b50a70495e06b48656da4e22e34">llvm::ConstantPtrAuth::get</a>.</p>

</div>
</div>

### ConstantRangeAttributeAlloc {#a8d9d7a6dea8a065912b098f383144ced}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;ConstantRangeAttributeImpl&gt; llvm::LLVMContextImpl::ConstantRangeAttributeAlloc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1607 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### ConstantRangeListAttributes {#aab69a0e7093a29bbd1badab6978c224b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;ConstantRangeListAttributeImpl *&gt; llvm::LLVMContextImpl::ConstantRangeListAttributes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1557 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### CPNConstants {#a27267b9113fe5612e822aaa90bdc3130}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;PointerType *, std::unique_ptr&lt;ConstantPointerNull&gt; &gt; llvm::LLVMContextImpl::CPNConstants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1570 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### CTNConstants {#a8cd8b08cb9114ed1b27a90c79b13fb71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;TargetExtType *, std::unique_ptr&lt;ConstantTargetNone&gt; &gt; llvm::LLVMContextImpl::CTNConstants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1572 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### CustomMDKindNames {#a6a2bd036574f4d51f20be99e0f3beb27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;unsigned&gt; llvm::LLVMContextImpl::CustomMDKindNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CustomMDKindNames - Map to hold the metadata string to <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> mapping.</p>

<p>Definition at line 1634 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### DefaultTargetCPU {#a1debdaadc09d824caa03270fb2e4a78b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::LLVMContextImpl::DefaultTargetCPU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1744 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### DefaultTargetFeatures {#a651a1b04a988601e18ad3c319d16ea7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::LLVMContextImpl::DefaultTargetFeatures</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1745 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### DiagHandler {#a6d266e2863d21d8440b10d3ba8459b49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DiagnosticHandler&gt; llvm::LLVMContextImpl::DiagHandler</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1484 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ad0c345f7af54ce4d7760ba46cafda829">LLVMContextImpl</a>.</p>

</div>
</div>

### DiagnosticsHotnessRequested {#a093c2d1ceee19d121b383b07dd126f0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLVMContextImpl::DiagnosticsHotnessRequested = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1486 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### DiagnosticsHotnessThreshold {#a8ff727d15564ae8b68804e7affbc6014}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::LLVMContextImpl::DiagnosticsHotnessThreshold = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The minimum hotness value a diagnostic needs in order to be included in optimization diagnostics.</p>


<p>The threshold is an Optional value, which maps to one of the 3 states: 1). 0 =&gt; threshold disabled. All emarks will be printed. 2). positive int =&gt; manual threshold by user. Remarks with hotness exceed threshold will be printed. 3). None =&gt; 'auto' threshold by user. The actual value is not available at command line, but will be synced with hotness threhold from profile summary during compilation.</p>


<p>State 1 and 2 are considered as terminal states. State transition is only allowed from 3 to 2, when the threshold is first synced with profile summary. This ensures that the threshold is set only once and stays constant.</p>


<p>If threshold option is not specified, it is disabled (0) by default.</p>


<p>Definition at line 1505 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### DiagnosticsMisExpectTolerance {#a4cf29558abcb57557b1ad4d3e4165e6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint32_t&gt; llvm::LLVMContextImpl::DiagnosticsMisExpectTolerance = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The percentage of difference between profiling branch weights and llvm.expect branch weights to tolerate when emiting MisExpect diagnostics.</p>

<p>Definition at line 1509 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### DIArgLists {#ab1d6012d83c37ebdb4d1c311d6a7c62f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;DIArgList *, DIArgListInfo&gt; llvm::LLVMContextImpl::DIArgLists</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1537 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diarglist/#a262bd33fc97cc729eb9418cc281dc69d">llvm::DIArgList::handleChangedOperand</a> and <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### DiscardValueNames {#a5c7699b477d925fed0264d67fedf2138}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLVMContextImpl::DiscardValueNames = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag to indicate if <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> (other than <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a>) retains their name or not.</p>

<p>Definition at line 1695 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### DiscriminatorTable {#aca1a729e7039b0dd16190f74be5911b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;std::pair&lt;const char *, unsigned&gt;, unsigned&gt; llvm::LLVMContextImpl::DiscriminatorTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>DiscriminatorTable - This table maps <a href="file:line">file:line</a> locations to an integer representing the next DWARF path discriminator to assign to instructions in different blocks at the same location.</p>

<p>Definition at line 1656 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### DistinctMDNodes {#a486a6a1f8fa108a74b851328dca40143}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MDNode *&gt; llvm::LLVMContextImpl::DistinctMDNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1550 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a478c26e31b9b99fab1ba3036f966f5c9">llvm::MDNode::storeDistinctInContext</a> and <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### DITypeMap {#af750ba05f1932996166443b9de31e0ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;DenseMap&lt;const MDString *, DICompositeType *&gt; &gt; llvm::LLVMContextImpl::DITypeMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1544 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### DoubleTy {#a8f8038fc9deb1ab370ee0b48df0d0996}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type llvm::LLVMContextImpl::DoubleTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1597 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ad0c345f7af54ce4d7760ba46cafda829">LLVMContextImpl</a>.</p>

</div>
</div>

### DSOLocalEquivalents {#ad6df8cfa0a66d2bf993b785867409fab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const GlobalValue *, DSOLocalEquivalent *&gt; llvm::LLVMContextImpl::DSOLocalEquivalents</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1583 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dsolocalequivalent/#a552470933dc4c1724248d9773e36b4de">llvm::DSOLocalEquivalent::get</a>.</p>

</div>
</div>

### ExprConstants {#a93700cfa46f68a6f83edadd6baaa80a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantUniqueMap&lt;ConstantExpr&gt; llvm::LLVMContextImpl::ExprConstants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1589 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ab00c6dc5086df2a37cd2e78715968861">llvm::ConstantExpr::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a078455f9a6da73bc84f24700a81d19d7">llvm::ConstantExpr::getExtractElement</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp/#ab51a11840c2b6aa3b4f8045953a658d5">getFoldedCast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#aa0e2f7f2755f0a5cb30f1cc35957cb27">llvm::ConstantExpr::getGetElementPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a64d6bd55aa4447bb25f1361993223450">llvm::ConstantExpr::getInsertElement</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a6f6506f0bc515fe29da3b58565300017">llvm::ConstantExpr::getShuffleVector</a> and <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### FloatTy {#ac9935ea89798e706d71c07df052d8ad7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type llvm::LLVMContextImpl::FloatTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1597 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ad0c345f7af54ce4d7760ba46cafda829">LLVMContextImpl</a>.</p>

</div>
</div>

### FP128Ty {#af2fa2d8454fd4d6990ff46623ea4d54b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type llvm::LLVMContextImpl::FP128Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1599 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ad0c345f7af54ce4d7760ba46cafda829">LLVMContextImpl</a>.</p>

</div>
</div>

### FPConstants {#a246739267b102ead8bf1df4244a3cf00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;APFloat, std::unique_ptr&lt;ConstantFP&gt; &gt; llvm::LLVMContextImpl::FPConstants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1526 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantfp/#ac27bcb2dc1fa6aa905e8cc86af54de0f">llvm::ConstantFP::get</a> and <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### FPSplatConstants {#afcf3927d5d1a9591fde1bd287202396f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;std::pair&lt;ElementCount, APFloat&gt;, std::unique_ptr&lt;ConstantFP&gt; &gt; llvm::LLVMContextImpl::FPSplatConstants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1528 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### FunctionTypes {#af37084d813c63755211059f16a420356}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionTypeSet llvm::LLVMContextImpl::FunctionTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1612 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### GCNames {#a5ebfdb2e37ef3ea1f52498332b80f2a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Function *, std::string&gt; llvm::LLVMContextImpl::GCNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maintain the GC name for each function.</p>


<p>This saves allocating an additional word in <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> for programs which do not use GC (i.e., most programs) at the cost of increased overhead for clients which do use GC.</p>


<p>Definition at line 1691 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### GlobalObjectSections {#a778c21fabbe327d5a5b9192d52127298}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const GlobalObject *, StringRef&gt; llvm::LLVMContextImpl::GlobalObjectSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collection of per-GlobalObject sections used in this context.</p>

<p>Definition at line 1645 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a959c99adbdc7f8375cf866916c6b60f2">llvm::GlobalObject::setSection</a>.</p>

</div>
</div>

### GlobalValuePartitions {#a016dccd2194d0bcf0c171921ac089569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const GlobalValue *, StringRef&gt; llvm::LLVMContextImpl::GlobalValuePartitions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collection of per-GlobalValue partitions used in this context.</p>

<p>Definition at line 1648 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a72237a63b5edcf78a32453822139f1d5">llvm::GlobalValue::getPartition</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aff8740863a5ee2650339400236b6224b">llvm::GlobalValue::setPartition</a>.</p>

</div>
</div>

### GlobalValueSanitizerMetadata {#a0870bd38114456f0b723d2a5dc741879}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const GlobalValue *, GlobalValue::SanitizerMetadata&gt; llvm::LLVMContextImpl::GlobalValueSanitizerMetadata</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1651 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a10dbf1e2be9c60af49efb9bfded99225">llvm::GlobalValue::getSanitizerMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a1b8db417ccdc447464add1a3d9358759">llvm::GlobalValue::removeSanitizerMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#add48ed79a5cd63c7165f3f4da102b9fd">llvm::GlobalValue::setSanitizerMetadata</a>.</p>

</div>
</div>

### HalfTy {#a4344c5f584f62f2258d455340a6b880a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type llvm::LLVMContextImpl::HalfTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1597 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ad0c345f7af54ce4d7760ba46cafda829">LLVMContextImpl</a>.</p>

</div>
</div>

### InlineAsms {#ac9a2da2321bac0d860e669057aa11d6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantUniqueMap&lt;InlineAsm&gt; llvm::LLVMContextImpl::InlineAsms</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1591 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a44dec91bb943f56f8bba3e9171a76947">llvm::InlineAsm::get</a> and <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### Int128Ty {#aac40414b8a45ce751efafbce3e1eabbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType llvm::LLVMContextImpl::Int128Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1600 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ad0c345f7af54ce4d7760ba46cafda829">LLVMContextImpl</a>.</p>

</div>
</div>

### Int16Ty {#a290d03d5c83b8da571c5dc6e8b32a528}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType llvm::LLVMContextImpl::Int16Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1600 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ad0c345f7af54ce4d7760ba46cafda829">LLVMContextImpl</a>.</p>

</div>
</div>

### Int1Ty {#a875e29869b5d4e27e5593927ce3ffbee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType llvm::LLVMContextImpl::Int1Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1600 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ad0c345f7af54ce4d7760ba46cafda829">LLVMContextImpl</a>.</p>

</div>
</div>

### Int32Ty {#a1e521c21ddbbb77b396e87f73b7ef944}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType llvm::LLVMContextImpl::Int32Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1600 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ad0c345f7af54ce4d7760ba46cafda829">LLVMContextImpl</a>.</p>

</div>
</div>

### Int64Ty {#a42ad6696dfe051f4caf4ebe5bb6ea622}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType llvm::LLVMContextImpl::Int64Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1600 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ad0c345f7af54ce4d7760ba46cafda829">LLVMContextImpl</a>.</p>

</div>
</div>

### Int8Ty {#a87e78b20e48f1a8c41f0a3e6d4748fdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType llvm::LLVMContextImpl::Int8Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1600 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ad0c345f7af54ce4d7760ba46cafda829">LLVMContextImpl</a>.</p>

</div>
</div>

### IntConstants {#a3c303c93282542e5eb52a4582b50c12f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;APInt, std::unique_ptr&lt;ConstantInt&gt; &gt; llvm::LLVMContextImpl::IntConstants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1522 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantint/#a4757205dd7df6b811f16d2bec12c46d8">llvm::ConstantInt::get</a> and <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### IntegerTypes {#a9ffb52d71ceda7afe461295959e88965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, IntegerType *&gt; llvm::LLVMContextImpl::IntegerTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1609 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### IntOneConstants {#a09021e2b1d263b878063b554afd2dd3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, std::unique_ptr&lt;ConstantInt&gt; &gt; llvm::LLVMContextImpl::IntOneConstants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1521 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantint/#a4757205dd7df6b811f16d2bec12c46d8">llvm::ConstantInt::get</a> and <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### IntSplatConstants {#a9a1940276b765c03535ce27337364739}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;std::pair&lt;ElementCount, APInt&gt;, std::unique_ptr&lt;ConstantInt&gt; &gt; llvm::LLVMContextImpl::IntSplatConstants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1524 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### IntZeroConstants {#a0b588ed032999d7b5686ae8c360b2936}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, std::unique_ptr&lt;ConstantInt&gt; &gt; llvm::LLVMContextImpl::IntZeroConstants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1520 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantint/#a4757205dd7df6b811f16d2bec12c46d8">llvm::ConstantInt::get</a> and <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### LabelTy {#a3b7edf39d72912406edad668135f2a6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type llvm::LLVMContextImpl::LabelTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1597 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ad0c345f7af54ce4d7760ba46cafda829">LLVMContextImpl</a>.</p>

</div>
</div>

### LLVMRS {#a5c722375f3fbaf09c9ad347f48f7c679}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;LLVMRemarkStreamer&gt; llvm::LLVMContextImpl::LLVMRS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The specialized remark streamer used by LLVM's <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a>.</p>

<p>Definition at line 1513 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### MachineFunctionNums {#a66adecf60a5af16521adc8e487822fcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Module *, unsigned&gt; llvm::LLVMContextImpl::MachineFunctionNums</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MachineFunctionNums - Keep the next available unique number available for a <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> in given module.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> must in OwnedModules.</p>


<p>Definition at line 1477 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### MainRemarkStreamer {#a7f9ffb199060f6ce4914e30b4ec45ce5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;remarks::RemarkStreamer&gt; llvm::LLVMContextImpl::MainRemarkStreamer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The main remark streamer used by all the other streamers (e.g.</p>


<p>IR, MIR, frontends, etc.). This should only be used by the specific streamers, and never directly.</p>


<p>Definition at line 1482 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### MDStringCache {#a2757063573b80cb1423828875aee939f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;MDString, BumpPtrAllocator&gt; llvm::LLVMContextImpl::MDStringCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1534 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### MetadataAsValues {#a0f84a0b5ee0bc1f89540f7dac8cf80a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Metadata *, MetadataAsValue *&gt; llvm::LLVMContextImpl::MetadataAsValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1536 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue/#aa8f5b66c1e3e1c2f0740764818920442">llvm::MetadataAsValue::~MetadataAsValue</a>.</p>

</div>
</div>

### MetadataTy {#a02c738bfd8bfffbe459f84cdeb4ff3f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type llvm::LLVMContextImpl::MetadataTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1597 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ad0c345f7af54ce4d7760ba46cafda829">LLVMContextImpl</a>.</p>

</div>
</div>

### MisExpectWarningRequested {#ab9c800f160b2c0cbe0f17c4ac6cfeab5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLVMContextImpl::MisExpectWarningRequested = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1510 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### NamedStructTypes {#aa1dbc2a398635aa424e045dcde7455e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;StructType *&gt; llvm::LLVMContextImpl::NamedStructTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1615 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### NamedStructTypesUniqueID {#aefb06147164bc496c5a09bedfb990642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LLVMContextImpl::NamedStructTypesUniqueID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1616 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### NoCFIValues {#a5ca254b9ecfa479e9ca139e3935bf9a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const GlobalValue *, NoCFIValue *&gt; llvm::LLVMContextImpl::NoCFIValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1585 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/nocfivalue/#a12b8ccc251129b734bf00e84515d2711">llvm::NoCFIValue::get</a>.</p>

</div>
</div>

### OPG {#a8a2eb1327e30482e9f9feba4be032098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptPassGate* llvm::LLVMContextImpl::OPG = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1703 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a6224046d8c0becf4d115077e047840fd">getOptPassGate</a> and <a href="#a598e220b87343b4ab3d79b933e944266">setOptPassGate</a>.</p>

</div>
</div>

### OwnedModules {#a271edc637955bfe7e14822b65232952a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Module *, 4&gt; llvm::LLVMContextImpl::OwnedModules</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>OwnedModules - The set of modules instantiated in this context, and which will be automatically deleted if this context is deleted.</p>

<p>Definition at line 1473 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### PointerTypes {#a95f679f7d5ae1da04854ce807c9ea9e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, PointerType *&gt; llvm::LLVMContextImpl::PointerTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1624 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### PPC\_FP128Ty {#afa9e13311374a56c97a28c6be9b4a51e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type llvm::LLVMContextImpl::PPC_FP128Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1599 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ad0c345f7af54ce4d7760ba46cafda829">LLVMContextImpl</a>.</p>

</div>
</div>

### PVConstants {#a3887b5bd85846ac49e356acceac66bed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Type *, std::unique_ptr&lt;PoisonValue&gt; &gt; llvm::LLVMContextImpl::PVConstants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1576 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### RespectDiagnosticFilters {#a60ca5513ecfaf1900eeb107df01b4921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LLVMContextImpl::RespectDiagnosticFilters = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1485 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### Saver {#a9b7a55908da35f0359df5eb4279015ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UniqueStringSaver llvm::LLVMContextImpl::Saver {<a href="#a7176f21e453f3b16e41d7c9084139746">Alloc</a>}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1605 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aff8740863a5ee2650339400236b6224b">llvm::GlobalValue::setPartition</a> and <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a959c99adbdc7f8375cf866916c6b60f2">llvm::GlobalObject::setSection</a>.</p>

</div>
</div>

### SSC {#a95e537127a71dc94522132234e1c751c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;SyncScope::ID&gt; llvm::LLVMContextImpl::SSC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A set of interned synchronization scopes.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a> maps synchronization scope names to their respective synchronization scope IDs.</p>


<p>Definition at line 1670 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a52c04e90a18244956f4a4f1d4b34fc64">getOrInsertSyncScopeID</a>, <a href="#ab3da55a4479ec3a5551c1f8c1692d27a">getSyncScopeName</a> and <a href="#a0a8135ce55ec23fa669cc75cbe9bbbbb">getSyncScopeNames</a>.</p>

</div>
</div>

### StructConstants {#a78cf754889634eb9bcd3fbbae006ccc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructConstantsTy llvm::LLVMContextImpl::StructConstants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1565 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### TargetExtTypes {#a3587a9d36772eaec39f456f6555de356}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetExtTypeSet llvm::LLVMContextImpl::TargetExtTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1619 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### TheFalseVal {#a31be55ec6c7ff877970345924ef5360a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantInt* llvm::LLVMContextImpl::TheFalseVal = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1594 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>.</p>

</div>
</div>

### TheNoneToken {#a4ee4d8c911290fbaec8dc80acb3b4567}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ConstantTokenNone&gt; llvm::LLVMContextImpl::TheNoneToken</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1602 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constanttokennone/#a8e29fb8e39fb67b3bb746dbba47fcb29">llvm::ConstantTokenNone::get</a>.</p>

</div>
</div>

### TheTrueVal {#a1bec169369c9b3d9d93a4a0446c9b2d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantInt* llvm::LLVMContextImpl::TheTrueVal = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1593 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>.</p>

</div>
</div>

### TokenTy {#aea8b78a5e4b967d6310f492d401e181f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type llvm::LLVMContextImpl::TokenTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1598 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ad0c345f7af54ce4d7760ba46cafda829">LLVMContextImpl</a>.</p>

</div>
</div>

### TrailingDbgRecords {#aefd0c34f5360aebd059382bfb2adbe22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;BasicBlock *, DbgMarker *&gt; llvm::LLVMContextImpl::TrailingDbgRecords</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mapping of blocks to collections of "trailing" DbgVariableRecords.</p>


<p>As part of the "RemoveDIs" project, debug-info variable location records are going to cease being instructions... which raises the problem of where should they be recorded when we remove the terminator of a blocks, such as:</p>


<p>foo = add i32 0, 0 br label bar</p>


<p>If the branch is removed, a legitimate transient state while editing a block, any debug-records between those two instructions will not have a location. Each block thus records any <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> records that "trail" in such a way. These are stored in <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> because typically LLVM only edits a small number of blocks at a time, so there's no need to bloat <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> with such a data structure.</p>


<p>Definition at line 1730 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a860776385fdeb0b48627421c8c19c4cd">deleteTrailingDbgRecords</a>, <a href="#a6ef702eb2f7d1c2e407d84aaf80abd7e">getTrailingDbgRecords</a>, <a href="#a9751861133b9513c99ea00d34c2bb226">setTrailingDbgRecords</a> and <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### UVConstants {#a61efa06e00257bf060f040285796ad66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Type *, std::unique_ptr&lt;UndefValue&gt; &gt; llvm::LLVMContextImpl::UVConstants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1574 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### ValueHandles {#ab23b4c9009afa5058b6845920e164251}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueHandlesTy llvm::LLVMContextImpl::ValueHandles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1631 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### ValueMetadata {#a6577bf24ddcb2a2cd401ee3e4704527a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Value *, MDAttachments&gt; llvm::LLVMContextImpl::ValueMetadata</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collection of metadata used in this context.</p>

<p>Definition at line 1637 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/value/#aa1b0638c63ba711320b3bb9c69367ed6">llvm::Value::addMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ad151fceb9a0e77a8a8017d4f68791811">llvm::Value::clearMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a9d88e21e9caa53945e903fd8c8700b4f">llvm::Value::eraseMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab1198eef44b311a7984cfc8fc97fac6d">llvm::Value::eraseMetadataIf</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#aade703948f2fdabdc65868bdf42d3141">llvm::Instruction::getAAMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3d200b1568f70b28ae0eb9bec58d6690">llvm::Value::getAllMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#aa8b1bc6f9347dade1932d5e0a0be7904">llvm::Value::getMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a338590123630c357df6340c38d066572">llvm::Value::setMetadata</a> and <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### ValueNames {#a4f816abcc93f58b2ea13618d148571a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Value *, ValueName *&gt; llvm::LLVMContextImpl::ValueNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1518 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### ValuesAsMetadata {#ab9825bb3a01150a90106e731b9fe23df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Value *, ValueAsMetadata *&gt; llvm::LLVMContextImpl::ValuesAsMetadata</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1535 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### VectorConstants {#a5ad082a7058a5071c015ff18cb1d9d02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorConstantsTy llvm::LLVMContextImpl::VectorConstants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1568 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#a5d9383a7827bb76858af4b9dd1a7e0ee">~LLVMContextImpl</a>.</p>

</div>
</div>

### VectorTypes {#a7e9a22974a198cd487877b4beec90b91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;std::pair&lt;Type *, ElementCount&gt;, VectorType *&gt; llvm::LLVMContextImpl::VectorTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1622 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### VoidTy {#af24d867582451a918bccd13312a43614}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type llvm::LLVMContextImpl::VoidTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1597 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ad0c345f7af54ce4d7760ba46cafda829">LLVMContextImpl</a>.</p>

</div>
</div>

### X86\_AMXTy {#a41ab916b680d90327508bd4c94401b16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type llvm::LLVMContextImpl::X86_AMXTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1599 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ad0c345f7af54ce4d7760ba46cafda829">LLVMContextImpl</a>.</p>

</div>
</div>

### X86\_FP80Ty {#a9bdfed2761afc9ad9138fc657e051135}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type llvm::LLVMContextImpl::X86_FP80Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1599 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>


<p>Referenced by <a href="#ad0c345f7af54ce4d7760ba46cafda829">LLVMContextImpl</a>.</p>

</div>
</div>

### YieldCallback {#a9e78b85d9aad8a6f57c093705f5f7377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext::YieldCallbackTy llvm::LLVMContextImpl::YieldCallback = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1515 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

### YieldOpaqueHandle {#ad1727c74daa04e8276724f6de6deefa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::LLVMContextImpl::YieldOpaqueHandle = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1516 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-cpp">LLVMContextImpl.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
