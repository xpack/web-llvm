---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/executionengine/gdbregistrationlistener-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `GDBRegistrationListener.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/executionengine-h">llvm-c/ExecutionEngine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jiteventlistener-h">llvm/ExecutionEngine/JITEventListener.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">llvm/Object/ObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mutex-h">llvm/Support/Mutex.h</a>"
#include &lt;mutex&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-gdbregistrationlistener-cpp-">anonymous{GDBRegistrationListener.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/jit-code-entry">jit_code_entry</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/jit-descriptor">jit_descriptor</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-gdbregistrationlistener-cpp-/registeredobjectinfo">RegisteredObjectInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-gdbregistrationlistener-cpp-/gdbjitregistrationlistener">GDBJITRegistrationListener</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Global access point for the JIT debugging interface designed for use with a singleton toolbox. <a href="/web-llvm/docs/api/classes/anonymous-gdbregistrationlistener-cpp-/gdbjitregistrationlistener/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">jit_actions_t { <a href="#a7bdc22420dff03da746c36ea0d1e61e3">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfc836ae108641ea6231b8d9def3a15a">__jit_debug_register_code</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad4bf262b53178061f7b936e3d1ff43bf">LLVMJITEventListenerRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#ga9ff6e0b848af7f64c654c8240e1fb4ab">LLVMCreateGDBRegistrationListener</a> (void)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0203c5bae237f4c8fd1c14f5d5879de4">__jit_debug_descriptor</a></td>
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

### jit\_actions\_t {#a7bdc22420dff03da746c36ea0d1e61e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum jit_actions_t </td>
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
<td class="doxyEnumItemName">JIT_NOACTION<a id="a7bdc22420dff03da746c36ea0d1e61e3ab377153f3ed86c501cb1146c7d22b0d0"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">JIT_REGISTER_FN<a id="a7bdc22420dff03da746c36ea0d1e61e3a7ccf38e37a6098410fdc26338f5ff57e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">JIT_UNREGISTER_FN<a id="a7bdc22420dff03da746c36ea0d1e61e3a48c61cea990bfeda4289f748f0f248fc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### \_\_jit\_debug\_register\_code() {#acfc836ae108641ea6231b8d9def3a15a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void __jit_debug_register_code ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/jitloadergdb-cpp">JITLoaderGDB.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ac6a5e0eb6a9944baf6ba14b640eab6e1">LLVM_ATTRIBUTE_NOINLINE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/jitloadergdb-h/#aa179ff9a1e20ecc81138aaca91a0cfc9">llvm_orc_registerJITLoaderGDBAllocAction</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/jitloadergdb-h/#a0bce71a267532196975543a4ead461c1">llvm_orc_registerJITLoaderGDBWrapper</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-gdbregistrationlistener-cpp-/#ac04610af527ea2371b9c4aad7a11b539">anonymous{GDBRegistrationListener.cpp}::NotifyDebugger</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-gdbregistrationlistener-cpp-/#aed8b12338da2e3c7fb1d304c36637450">anonymous{GDBRegistrationListener.cpp}::requiredSymbolDefinitionsFromOrcTargetProcess</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### \_\_jit\_debug\_descriptor {#a0203c5bae237f4c8fd1c14f5d5879de4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct jit_descriptor __jit_debug_descriptor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/jitloadergdb-cpp">JITLoaderGDB.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/jitloadergdb-cpp/#a753634e998fff5c5a1f7ddce884fe2d6">appendJITDebugDescriptor</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-gdbregistrationlistener-cpp-/#ac04610af527ea2371b9c4aad7a11b539">anonymous{GDBRegistrationListener.cpp}::NotifyDebugger</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-gdbregistrationlistener-cpp-/#aed8b12338da2e3c7fb1d304c36637450">anonymous{GDBRegistrationListener.cpp}::requiredSymbolDefinitionsFromOrcTargetProcess</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
