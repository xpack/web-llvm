---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-gdbregistrationlistener-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{GDBRegistrationListener.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{GDBRegistrationListener.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">llvm::DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/jiteventlistener/#aefc8c6bb6d8f5a09e48f4b9db9c10024">JITEventListener::ObjectKey</a>, <a href="/web-llvm/docs/api/structs/anonymous-gdbregistrationlistener-cpp-/registeredobjectinfo">RegisteredObjectInfo</a> &gt; <a href="#ad24beec920a5d33ddb8f0d2af143b376">RegisteredObjectBufferMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a6881c00738b22a600dfee25a1c32dab3">LLVM_ATTRIBUTE_USED</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed8b12338da2e3c7fb1d304c36637450">requiredSymbolDefinitionsFromOrcTargetProcess</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac04610af527ea2371b9c4aad7a11b539">NotifyDebugger</a> (jit_code_entry *JITCodeEntry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do the registration. <a href="#ac04610af527ea2371b9c4aad7a11b539">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Typedefs

### RegisteredObjectBufferMap {#ad24beec920a5d33ddb8f0d2af143b376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef llvm::DenseMap&lt;JITEventListener::ObjectKey, RegisteredObjectInfo&gt; anonymous{GDBRegistrationListener.cpp}::RegisteredObjectBufferMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### NotifyDebugger() {#ac04610af527ea2371b9c4aad7a11b539}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{GDBRegistrationListener.cpp}::NotifyDebugger (<a href="/web-llvm/docs/api/structs/jit-code-entry">jit_code_entry</a> * JITCodeEntry)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Do the registration.</p>

<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp/#a0203c5bae237f4c8fd1c14f5d5879de4">__jit_debug_descriptor</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp/#acfc836ae108641ea6231b8d9def3a15a">__jit_debug_register_code</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/jitloadergdb-h/#a7bdc22420dff03da746c36ea0d1e61e3a7ccf38e37a6098410fdc26338f5ff57e">JIT_REGISTER_FN</a>, <a href="/web-llvm/docs/api/structs/jit-code-entry/#af8d9022c7880fcb0cfe18807d9232b62">jit_code_entry::next_entry</a> and <a href="/web-llvm/docs/api/structs/jit-code-entry/#a25cdb6113b18a2bec6ead7a8d9d4624c">jit_code_entry::prev_entry</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-gdbregistrationlistener-cpp-/gdbjitregistrationlistener/#ae41608a898388d10b4a7d39b4f94e32e">anonymous{GDBRegistrationListener.cpp}::GDBJITRegistrationListener::notifyObjectLoaded</a>.</p>

</div>
</div>

### requiredSymbolDefinitionsFromOrcTargetProcess() {#aed8b12338da2e3c7fb1d304c36637450}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_USED void anonymous{GDBRegistrationListener.cpp}::requiredSymbolDefinitionsFromOrcTargetProcess ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp/#a0203c5bae237f4c8fd1c14f5d5879de4">__jit_debug_descriptor</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp/#acfc836ae108641ea6231b8d9def3a15a">__jit_debug_register_code</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a6881c00738b22a600dfee25a1c32dab3">LLVM_ATTRIBUTE_USED</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp">GDBRegistrationListener.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
