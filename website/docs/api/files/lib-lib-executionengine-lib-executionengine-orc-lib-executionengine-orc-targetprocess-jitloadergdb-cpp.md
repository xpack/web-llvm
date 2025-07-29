---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/jitloadergdb-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `JITLoaderGDB.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/jitloadergdb-h">llvm/ExecutionEngine/Orc/TargetProcess/JITLoaderGDB.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">llvm/Support/FormatVariadic.h</a>"
#include &lt;cstdint&gt;
#include &lt;mutex&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#af6e33f1bd74f3e8de4d6dab912350808">LLVM_ALWAYS_EXPORT</a> <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ac6a5e0eb6a9944baf6ba14b640eab6e1">LLVM_ATTRIBUTE_NOINLINE</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ded170868808789dd9cf41e17b5f71e">__jit_debug_register_code</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a753634e998fff5c5a1f7ddce884fe2d6">appendJITDebugDescriptor</a> (const char *ObjAddr, size_t Size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/shared/cwrapperfunctionresult">orc::shared::CWrapperFunctionResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2466da8324a7d989ef9edcfa212f1b1">llvm_orc_registerJITLoaderGDBAllocAction</a> (const char *Data, size_t Size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/shared/cwrapperfunctionresult">orc::shared::CWrapperFunctionResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd603fce37d2915f38e123d529b2b45d">llvm_orc_registerJITLoaderGDBWrapper</a> (const char *Data, uint64_t Size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6a07066a1c61cdd2b56aae047856009">JitDescriptorVersion</a> = 1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#af6e33f1bd74f3e8de4d6dab912350808">LLVM_ALWAYS_EXPORT</a> struct <a href="/web-llvm/docs/api/structs/jit-descriptor">jit_descriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada1077eb13bc59f0333ce46d861925f9">__jit_debug_descriptor</a> = ...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"orc"</td>
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

### \_\_jit\_debug\_register\_code() {#a5ded170868808789dd9cf41e17b5f71e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ALWAYS_EXPORT LLVM_ATTRIBUTE_NOINLINE void __jit_debug_register_code ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/jitloadergdb-cpp">JITLoaderGDB.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ac6a5e0eb6a9944baf6ba14b640eab6e1">LLVM_ATTRIBUTE_NOINLINE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/jitloadergdb-h/#aa179ff9a1e20ecc81138aaca91a0cfc9">llvm_orc_registerJITLoaderGDBAllocAction</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/jitloadergdb-h/#a0bce71a267532196975543a4ead461c1">llvm_orc_registerJITLoaderGDBWrapper</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-gdbregistrationlistener-cpp-/#ac04610af527ea2371b9c4aad7a11b539">anonymous{GDBRegistrationListener.cpp}::NotifyDebugger</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-gdbregistrationlistener-cpp-/#aed8b12338da2e3c7fb1d304c36637450">anonymous{GDBRegistrationListener.cpp}::requiredSymbolDefinitionsFromOrcTargetProcess</a>.</p>

</div>
</div>

### appendJITDebugDescriptor() {#a753634e998fff5c5a1f7ddce884fe2d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void appendJITDebugDescriptor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ObjAddr, size_t Size)</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/jitloadergdb-cpp">JITLoaderGDB.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp/#a0203c5bae237f4c8fd1c14f5d5879de4">__jit_debug_descriptor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/jitloadergdb-h/#a7bdc22420dff03da746c36ea0d1e61e3a7ccf38e37a6098410fdc26338f5ff57e">JIT_REGISTER_FN</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/jit-code-entry/#a25cdb6113b18a2bec6ead7a8d9d4624c">jit_code_entry::prev_entry</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/jitloadergdb-h/#aa179ff9a1e20ecc81138aaca91a0cfc9">llvm_orc_registerJITLoaderGDBAllocAction</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/targetprocess/jitloadergdb-h/#a0bce71a267532196975543a4ead461c1">llvm_orc_registerJITLoaderGDBWrapper</a>.</p>

</div>
</div>

### llvm\_orc\_registerJITLoaderGDBAllocAction() {#ab2466da8324a7d989ef9edcfa212f1b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">orc::shared::CWrapperFunctionResult llvm_orc_registerJITLoaderGDBAllocAction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Data, size_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/jitloadergdb-cpp">JITLoaderGDB.cpp</a>.</p>


<p>References <a href="#a5ded170868808789dd9cf41e17b5f71e">__jit_debug_register_code</a>, <a href="#a753634e998fff5c5a1f7ddce884fe2d6">appendJITDebugDescriptor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a123fead50246387983ee340507115ef4">llvm::release</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### llvm\_orc\_registerJITLoaderGDBWrapper() {#abd603fce37d2915f38e123d529b2b45d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">orc::shared::CWrapperFunctionResult llvm_orc_registerJITLoaderGDBWrapper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Data, uint64_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/jitloadergdb-cpp">JITLoaderGDB.cpp</a>.</p>


<p>References <a href="#a5ded170868808789dd9cf41e17b5f71e">__jit_debug_register_code</a>, <a href="#a753634e998fff5c5a1f7ddce884fe2d6">appendJITDebugDescriptor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a123fead50246387983ee340507115ef4">llvm::release</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### \_\_jit\_debug\_descriptor {#ada1077eb13bc59f0333ce46d861925f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ALWAYS_EXPORT struct jit_descriptor __jit_debug_descriptor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {<a href="#af6a07066a1c61cdd2b56aae047856009">JitDescriptorVersion</a>, 0,
                                                nullptr, nullptr}
</div>
</dd>
</dl>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/jitloadergdb-cpp">JITLoaderGDB.cpp</a>.</p>


<p>Referenced by <a href="#a753634e998fff5c5a1f7ddce884fe2d6">appendJITDebugDescriptor</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-gdbregistrationlistener-cpp-/#ac04610af527ea2371b9c4aad7a11b539">anonymous{GDBRegistrationListener.cpp}::NotifyDebugger</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-gdbregistrationlistener-cpp-/#aed8b12338da2e3c7fb1d304c36637450">anonymous{GDBRegistrationListener.cpp}::requiredSymbolDefinitionsFromOrcTargetProcess</a>.</p>

</div>
</div>

### JitDescriptorVersion {#af6a07066a1c61cdd2b56aae047856009}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t JitDescriptorVersion = 1</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/jitloadergdb-cpp">JITLoaderGDB.cpp</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"orc"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/jitloadergdb-cpp">JITLoaderGDB.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
