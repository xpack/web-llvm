---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/genericvalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `GenericValue` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::GenericValue { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/genericvalue-h">llvm/ExecutionEngine/GenericValue.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d2861e693ffddd71d582850c766ad8e">GenericValue</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a486b5999512a929d63ac73f5763e27fd">GenericValue</a> (void *V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9810b36b4c4c17901d491f5aac030623">DoubleVal</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5160197592bd1fc5c8cc81cd803e0629">FloatVal</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a41f670c80fbc831d70a472b03c4739ae">PointerTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23f8c75218aea0cfcfe0f3e4223d3b02">PointerVal</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7495c89b67b21446ed9951586a17b345">UIntPairVal</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41a10771a4ea1018e2df8e845620c78c">Untyped</a>[8]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/structs/llvm/genericvalue">llvm::GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29601fcced9ee0d94715817e48afe9dc"></a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc1cecb2e860959165c8ad83d0d26023">IntVal</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa46325f5b23e83bb49e497cfce2f1b89">AggregateVal</a></td>
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


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/genericvalue-h">GenericValue.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GenericValue() {#a7d2861e693ffddd71d582850c766ad8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GenericValue::GenericValue ()</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/genericvalue-h">GenericValue.h</a>.</p>


<p>References <a href="#adc1cecb2e860959165c8ad83d0d26023">IntVal</a> and <a href="#a7495c89b67b21446ed9951586a17b345">UIntPairVal</a>.</p>

</div>
</div>

### GenericValue() {#a486b5999512a929d63ac73f5763e27fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GenericValue::GenericValue (void * V)</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/genericvalue-h">GenericValue.h</a>.</p>


<p>References <a href="#adc1cecb2e860959165c8ad83d0d26023">IntVal</a> and <a href="#a23f8c75218aea0cfcfe0f3e4223d3b02">PointerVal</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

###  {#a29601fcced9ee0d94715817e48afe9dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::GenericValue llvm::GenericValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/genericvalue-h">GenericValue.h</a>.</p>

</div>
</div>

### AggregateVal {#aa46325f5b23e83bb49e497cfce2f1b89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;GenericValue&gt; llvm::GenericValue::AggregateVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/genericvalue-h">GenericValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a9dbb09eb50c3c8609ff46bf6add8c2ee">executeFCMP_BOOL</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#ad84c8e547a3add8cc581d6fbec1ea5cb">executeFCMP_ONE</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a9a1b97d63e55b8f92d4d2e5468fb7cf6">executeFCMP_ORD</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a4ecb49f4c2b5b1041e0ad44dc213f5b0">executeFCMP_UNO</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a4f71481be990c1361b473eea6c18df11">executeSelectInst</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a08ed33d3b3f8b9e21167918d5de40014">llvm::ExecutionEngine::StoreValueToMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ac56427a25d7626e4b748e8fbf1fdf9bb">llvm::Interpreter::visitAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ad931a9b6a516452142c12592afe8968d">llvm::Interpreter::visitBinaryOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a582723c984e76cf38ba855426a60a235">llvm::Interpreter::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a555a1a7ce9538b817e65c911ed7da13a">llvm::Interpreter::visitExtractValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a86b39d8533c9fd7c518a6ebc3456e6d1">llvm::Interpreter::visitInsertElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a47c795f3e83fbfbd37c1b890c850dbe7">llvm::Interpreter::visitInsertValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a39600b19581391dccc382a54d6b79be2">llvm::Interpreter::visitLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#adaccb8a2292bd0d7fecec1c16d177cd3">llvm::Interpreter::visitShl</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a1023db1599beb0118dd1ffe91d85f172">llvm::Interpreter::visitShuffleVectorInst</a>.</p>

</div>
</div>

### DoubleVal {#a9810b36b4c4c17901d491f5aac030623}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double llvm::GenericValue::DoubleVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/genericvalue-h">GenericValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a9a1b97d63e55b8f92d4d2e5468fb7cf6">executeFCMP_ORD</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a4ecb49f4c2b5b1041e0ad44dc213f5b0">executeFCMP_UNO</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a6afbe60697d1b461028d733f1380e22d">executeFNegInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#ab2b2089ccf34571233f731db1c299b85">executeFRemInst</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#gabdeddb888028f5efec64d710a5c70e83">LLVMCreateGenericValueOfFloat</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a0198943262fb715d77dfd24ef32f9399">llvm::MCJIT::runFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a08ed33d3b3f8b9e21167918d5de40014">llvm::ExecutionEngine::StoreValueToMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a582723c984e76cf38ba855426a60a235">llvm::Interpreter::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a555a1a7ce9538b817e65c911ed7da13a">llvm::Interpreter::visitExtractValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a86b39d8533c9fd7c518a6ebc3456e6d1">llvm::Interpreter::visitInsertElementInst</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a47c795f3e83fbfbd37c1b890c850dbe7">llvm::Interpreter::visitInsertValueInst</a>.</p>

</div>
</div>

### FloatVal {#a5160197592bd1fc5c8cc81cd803e0629}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float llvm::GenericValue::FloatVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/genericvalue-h">GenericValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a9a1b97d63e55b8f92d4d2e5468fb7cf6">executeFCMP_ORD</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a4ecb49f4c2b5b1041e0ad44dc213f5b0">executeFCMP_UNO</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a6afbe60697d1b461028d733f1380e22d">executeFNegInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#ab2b2089ccf34571233f731db1c299b85">executeFRemInst</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#gabdeddb888028f5efec64d710a5c70e83">LLVMCreateGenericValueOfFloat</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a0198943262fb715d77dfd24ef32f9399">llvm::MCJIT::runFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a08ed33d3b3f8b9e21167918d5de40014">llvm::ExecutionEngine::StoreValueToMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a582723c984e76cf38ba855426a60a235">llvm::Interpreter::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a555a1a7ce9538b817e65c911ed7da13a">llvm::Interpreter::visitExtractValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a86b39d8533c9fd7c518a6ebc3456e6d1">llvm::Interpreter::visitInsertElementInst</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a47c795f3e83fbfbd37c1b890c850dbe7">llvm::Interpreter::visitInsertValueInst</a>.</p>

</div>
</div>

### IntVal {#adc1cecb2e860959165c8ad83d0d26023}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::GenericValue::IntVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/genericvalue-h">GenericValue.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a9dbb09eb50c3c8609ff46bf6add8c2ee">executeFCMP_BOOL</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a9a1b97d63e55b8f92d4d2e5468fb7cf6">executeFCMP_ORD</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a4ecb49f4c2b5b1041e0ad44dc213f5b0">executeFCMP_UNO</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/execution-cpp/#a4f71481be990c1361b473eea6c18df11">executeSelectInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a27a48d828a2227311270264ae0e78f8c">llvm::Interpreter::exitCalled</a>, <a href="#a7d2861e693ffddd71d582850c766ad8e">GenericValue</a>, <a href="#a486b5999512a929d63ac73f5763e27fd">GenericValue</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp/#aad1e29c3396ee6767ae57daf811cf741">lle_X_atexit</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp/#a7ff6b03e58263fea037fd2d63d023a08">lle_X_memcpy</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp/#a623f8609173635b1ac532fbd1e8e79af">lle_X_memset</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp/#a74b9b90fef5720d53bbac0bd1f285f57">lle_X_scanf</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp/#af822dab9663edf0d220a1173caa04fd3">lle_X_sprintf</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp/#abe3a830bf1bd165a58e0bf0499feedb8">lle_X_sscanf</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#ga49e6ddbb4ef1d059831f3dc1e82141d9">LLVMCreateGenericValueOfInt</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#gaca63029362a3a1da53f00e79b6423aac">LLVMGenericValueToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#adec0e730f80de19f31127faedf39008c">llvm::ExecutionEngine::LoadValueFromMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a0198943262fb715d77dfd24ef32f9399">llvm::MCJIT::runFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a97bbf524ee03354bb73dce9614b0e959">llvm::ExecutionEngine::runFunctionAsMain</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a08ed33d3b3f8b9e21167918d5de40014">llvm::ExecutionEngine::StoreValueToMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ac56427a25d7626e4b748e8fbf1fdf9bb">llvm::Interpreter::visitAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ad931a9b6a516452142c12592afe8968d">llvm::Interpreter::visitBinaryOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a582723c984e76cf38ba855426a60a235">llvm::Interpreter::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a555a1a7ce9538b817e65c911ed7da13a">llvm::Interpreter::visitExtractValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a86b39d8533c9fd7c518a6ebc3456e6d1">llvm::Interpreter::visitInsertElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a47c795f3e83fbfbd37c1b890c850dbe7">llvm::Interpreter::visitInsertValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a39600b19581391dccc382a54d6b79be2">llvm::Interpreter::visitLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#adaccb8a2292bd0d7fecec1c16d177cd3">llvm::Interpreter::visitShl</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a54b80362711a465bb0430383cbf50837">llvm::Interpreter::visitVAArgInst</a>.</p>

</div>
</div>

### PointerVal {#a23f8c75218aea0cfcfe0f3e4223d3b02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerTy llvm::GenericValue::PointerVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/genericvalue-h">GenericValue.h</a>.</p>


<p>Referenced by <a href="#a486b5999512a929d63ac73f5763e27fd">GenericValue</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3ff7c50d6ac50925243afaa521aa36a">llvm::GVTOP</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#ga06ad92a8617a97e7e453ff49d90c6b71">LLVMCreateGenericValueOfPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a08ed33d3b3f8b9e21167918d5de40014">llvm::ExecutionEngine::StoreValueToMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a555a1a7ce9538b817e65c911ed7da13a">llvm::Interpreter::visitExtractValueInst</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a47c795f3e83fbfbd37c1b890c850dbe7">llvm::Interpreter::visitInsertValueInst</a>.</p>

</div>
</div>

### UIntPairVal {#a7495c89b67b21446ed9951586a17b345}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct IntPair llvm::GenericValue::UIntPairVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/genericvalue-h">GenericValue.h</a>.</p>


<p>Referenced by <a href="#a7d2861e693ffddd71d582850c766ad8e">GenericValue</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a54b80362711a465bb0430383cbf50837">llvm::Interpreter::visitVAArgInst</a> and <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ab12c231bbdababc7fddf09a0c2825ae9">llvm::Interpreter::visitVAStartInst</a>.</p>

</div>
</div>

### Untyped {#a41a10771a4ea1018e2df8e845620c78c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned char llvm::GenericValue::Untyped[8]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/genericvalue-h">GenericValue.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/genericvalue-h">GenericValue.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
