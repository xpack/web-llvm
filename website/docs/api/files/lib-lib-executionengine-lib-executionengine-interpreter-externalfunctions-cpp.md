---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ExternalFunctions.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/interpreter-h">Interpreter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "llvm/Config/config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/genericvalue-h">llvm/ExecutionEngine/GenericValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dynamiclibrary-h">llvm/Support/DynamicLibrary.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mutex-h">llvm/Support/Mutex.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
#include &lt;cmath&gt;
#include &lt;csignal&gt;
#include &lt;cstdint&gt;
#include &lt;cstdio&gt;
#include &lt;cstring&gt;
#include &lt;map&gt;
#include &lt;mutex&gt;
#include &lt;string&gt;
#include &lt;utility&gt;
#include &lt;vector&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-externalfunctions-cpp-">anonymous{ExternalFunctions.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-externalfunctions-cpp-/functions">Functions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62734f5491c71583869b1da8d274dc45">getTypeID</a> (Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static ExFunc</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a290f71a162bc8e8fd0bc72b222c029fc">lookupFunction</a> (const Function *F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad1e29c3396ee6767ae57daf811cf741">lle_X_atexit</a> (FunctionType *FT, ArrayRef&lt; GenericValue &gt; Args)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af27906fd6eda254d084555719d92addc">lle_X_exit</a> (FunctionType *FT, ArrayRef&lt; GenericValue &gt; Args)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd1480e48330abf8d121a1256335ea9f">lle_X_abort</a> (FunctionType *FT, ArrayRef&lt; GenericValue &gt; Args)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af822dab9663edf0d220a1173caa04fd3">lle_X_sprintf</a> (FunctionType *FT, ArrayRef&lt; GenericValue &gt; Args)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a6f902aa46f47ecaf6073b49f7c8306">lle_X_printf</a> (FunctionType *FT, ArrayRef&lt; GenericValue &gt; Args)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe3a830bf1bd165a58e0bf0499feedb8">lle_X_sscanf</a> (FunctionType *FT, ArrayRef&lt; GenericValue &gt; args)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74b9b90fef5720d53bbac0bd1f285f57">lle_X_scanf</a> (FunctionType *FT, ArrayRef&lt; GenericValue &gt; args)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a672d8c321da1766cdfa0b2589a7b08a8">lle_X_fprintf</a> (FunctionType *FT, ArrayRef&lt; GenericValue &gt; Args)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a623f8609173635b1ac532fbd1e8e79af">lle_X_memset</a> (FunctionType *FT, ArrayRef&lt; GenericValue &gt; Args)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ff6b03e58263fea037fd2d63d023a08">lle_X_memcpy</a> (FunctionType *FT, ArrayRef&lt; GenericValue &gt; Args)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/interpreter">Interpreter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f422dfbc738ed5acebbbff28996ba95">TheInterpreter</a></td>
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

## Functions

### getTypeID() {#a62734f5491c71583869b1da8d274dc45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char getTypeID (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp">ExternalFunctions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa2989d3024a84b4dda9d77419b1648554">llvm::Type::ArrayTyID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa0ec130d9ce9883b3e9c6071ee19a4b16">llvm::Type::FunctionTyID</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a2cb59ea8f9e8543986d40c48acfd24a3">getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa8e724092b0496fe3d16e29863b46c249">llvm::Type::IntegerTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaae68df805bc15b023748c2a78b80563ff">llvm::Type::PointerTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa812a573d23fbb37aacd025e2a0588156">llvm::Type::StructTyID</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa567ac2c7944f770cfb2c2cffc94b3520">llvm::Type::VoidTyID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#afb55f797ff051b3fc29a0cf5f7465f12">llvm::ConstantDataSequential::getElementAsAPFloat</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#gabdeddb888028f5efec64d710a5c70e83">LLVMCreateGenericValueOfFloat</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#ga07086a2b6347e7f7e96a841331c7e55b">LLVMGenericValueToFloat</a>, <a href="/web-llvm/docs/api/groups/llvmccoretype/#ga112756467f0988613faa6043d674d843">LLVMGetTypeKind</a> and <a href="#a290f71a162bc8e8fd0bc72b222c029fc">lookupFunction</a>.</p>

</div>
</div>

### lle\_X\_abort() {#acd1480e48330abf8d121a1256335ea9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue lle_X_abort (<a href="/web-llvm/docs/api/classes/functiontype">FunctionType</a> * FT, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> &gt; Args)</td>
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



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp">ExternalFunctions.cpp</a>.</p>

</div>
</div>

### lle\_X\_atexit() {#aad1e29c3396ee6767ae57daf811cf741}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue lle_X_atexit (<a href="/web-llvm/docs/api/classes/functiontype">FunctionType</a> * FT, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> &gt; Args)</td>
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



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp">ExternalFunctions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3ff7c50d6ac50925243afaa521aa36a">llvm::GVTOP</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a> and <a href="#a5f422dfbc738ed5acebbbff28996ba95">TheInterpreter</a>.</p>

</div>
</div>

### lle\_X\_exit() {#af27906fd6eda254d084555719d92addc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue lle_X_exit (<a href="/web-llvm/docs/api/classes/functiontype">FunctionType</a> * FT, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> &gt; Args)</td>
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



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp">ExternalFunctions.cpp</a>.</p>


<p>Reference <a href="#a5f422dfbc738ed5acebbbff28996ba95">TheInterpreter</a>.</p>

</div>
</div>

### lle\_X\_fprintf() {#a672d8c321da1766cdfa0b2589a7b08a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue lle_X_fprintf (<a href="/web-llvm/docs/api/classes/functiontype">FunctionType</a> * FT, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> &gt; Args)</td>
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



<p>Definition at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp">ExternalFunctions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3ff7c50d6ac50925243afaa521aa36a">llvm::GVTOP</a>, <a href="#af822dab9663edf0d220a1173caa04fd3">lle_X_sprintf</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a77905b5e34e8754df1ed4051e0ad9d1a">llvm::PTOGV</a>.</p>

</div>
</div>

### lle\_X\_memcpy() {#a7ff6b03e58263fea037fd2d63d023a08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue lle_X_memcpy (<a href="/web-llvm/docs/api/classes/functiontype">FunctionType</a> * FT, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> &gt; Args)</td>
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



<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp">ExternalFunctions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac3ff7c50d6ac50925243afaa521aa36a">llvm::GVTOP</a> and <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a>.</p>

</div>
</div>

### lle\_X\_memset() {#a623f8609173635b1ac532fbd1e8e79af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue lle_X_memset (<a href="/web-llvm/docs/api/classes/functiontype">FunctionType</a> * FT, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> &gt; Args)</td>
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



<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp">ExternalFunctions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac3ff7c50d6ac50925243afaa521aa36a">llvm::GVTOP</a> and <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a>.</p>

</div>
</div>

### lle\_X\_printf() {#a7a6f902aa46f47ecaf6073b49f7c8306}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue lle_X_printf (<a href="/web-llvm/docs/api/classes/functiontype">FunctionType</a> * FT, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> &gt; Args)</td>
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



<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp">ExternalFunctions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="#af822dab9663edf0d220a1173caa04fd3">lle_X_sprintf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">llvm::outs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a77905b5e34e8754df1ed4051e0ad9d1a">llvm::PTOGV</a>.</p>

</div>
</div>

### lle\_X\_scanf() {#a74b9b90fef5720d53bbac0bd1f285f57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue lle_X_scanf (<a href="/web-llvm/docs/api/classes/functiontype">FunctionType</a> * FT, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> &gt; args)</td>
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



<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp">ExternalFunctions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a4d6da696b3c753c5e5fbcc4d21d4cb71">args</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3ff7c50d6ac50925243afaa521aa36a">llvm::GVTOP</a> and <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a>.</p>

</div>
</div>

### lle\_X\_sprintf() {#af822dab9663edf0d220a1173caa04fd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue lle_X_sprintf (<a href="/web-llvm/docs/api/classes/functiontype">FunctionType</a> * FT, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> &gt; Args)</td>
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



<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp">ExternalFunctions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3ff7c50d6ac50925243afaa521aa36a">llvm::GVTOP</a>, <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#a5f422dfbc738ed5acebbbff28996ba95">TheInterpreter</a>.</p>


<p>Referenced by <a href="#a672d8c321da1766cdfa0b2589a7b08a8">lle_X_fprintf</a> and <a href="#a7a6f902aa46f47ecaf6073b49f7c8306">lle_X_printf</a>.</p>

</div>
</div>

### lle\_X\_sscanf() {#abe3a830bf1bd165a58e0bf0499feedb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GenericValue lle_X_sscanf (<a href="/web-llvm/docs/api/classes/functiontype">FunctionType</a> * FT, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/genericvalue">GenericValue</a> &gt; args)</td>
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



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp">ExternalFunctions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a4d6da696b3c753c5e5fbcc4d21d4cb71">args</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3ff7c50d6ac50925243afaa521aa36a">llvm::GVTOP</a> and <a href="/web-llvm/docs/api/structs/llvm/genericvalue/#adc1cecb2e860959165c8ad83d0d26023">llvm::GenericValue::IntVal</a>.</p>

</div>
</div>

### lookupFunction() {#a290f71a162bc8e8fd0bc72b222c029fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExFunc lookupFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp">ExternalFunctions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-externalfunctions-cpp-/#a6e8894c7b626a952916252b2c9991a84">anonymous{ExternalFunctions.cpp}::getFunctions</a>, <a href="#a62734f5491c71583869b1da8d274dc45">getTypeID</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary/#ae003d16a33e81b88943d3e3aa179fcc4">llvm::sys::DynamicLibrary::SearchForAddressOfSymbol</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ac90cfcdb0c2a25c0969106ebff1be9f8">llvm::Interpreter::callExternalFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### TheInterpreter {#a5f422dfbc738ed5acebbbff28996ba95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Interpreter* TheInterpreter</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp">ExternalFunctions.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ac90cfcdb0c2a25c0969106ebff1be9f8">llvm::Interpreter::callExternalFunction</a>, <a href="#aad1e29c3396ee6767ae57daf811cf741">lle_X_atexit</a>, <a href="#af27906fd6eda254d084555719d92addc">lle_X_exit</a> and <a href="#af822dab9663edf0d220a1173caa04fd3">lle_X_sprintf</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
