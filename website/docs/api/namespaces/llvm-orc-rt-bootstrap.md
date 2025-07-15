---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/orc/rt-bootstrap
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `rt_bootstrap` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::orc::rt_bootstrap { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/executorsharedmemorymapperservice">ExecutorSharedMemoryMapperService</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutordylibmanager">SimpleExecutorDylibManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simple page-based allocator. <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutordylibmanager/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutormemorymanager">SimpleExecutorMemoryManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simple page-based allocator. <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutormemorymanager/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename WriteT, typename SPSWriteT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/orc/shared/cwrapperfunctionresult">llvm::orc::shared::CWrapperFunctionResult</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a153dc6823a589d531a84ffb878ef97c3">writeUIntsWrapper</a> (const char *ArgData, size_t ArgSize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/orc/shared/cwrapperfunctionresult">llvm::orc::shared::CWrapperFunctionResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf97028eb83da976471ddd35151826e2">writeBuffersWrapper</a> (const char *ArgData, size_t ArgSize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/orc/shared/cwrapperfunctionresult">llvm::orc::shared::CWrapperFunctionResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86ef3091ab5b291b2d0da5a82c1375a4">writePointersWrapper</a> (const char *ArgData, size_t ArgSize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/orc/shared/cwrapperfunctionresult">llvm::orc::shared::CWrapperFunctionResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa426d973cb19ceb73313af9043a0f3f7">runAsMainWrapper</a> (const char *ArgData, size_t ArgSize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/orc/shared/cwrapperfunctionresult">llvm::orc::shared::CWrapperFunctionResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fd747bb0dc9d8e1ad63288b1b6a604b">runAsVoidFunctionWrapper</a> (const char *ArgData, size_t ArgSize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/orc/shared/cwrapperfunctionresult">llvm::orc::shared::CWrapperFunctionResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd6eab68573896815e1b7e3fbb7554d0">runAsIntFunctionWrapper</a> (const char *ArgData, size_t ArgSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80380ad8a5c79d75366b0c1d968a4b7c">addTo</a> (StringMap&lt; ExecutorAddr &gt; &amp;M)</td>
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

### addTo() {#a80380ad8a5c79d75366b0c1d968a4b7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::rt_bootstrap::addTo (<a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt; &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/orcrtbootstrap-cpp">OrcRTBootstrap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#a8adb0ae35f7e95c960c86cfe19bc7215">llvm::orc::ExecutorAddr::fromPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/rt/#aca94690d0b8e760f473aab2fa27d5c23">llvm::orc::rt::MemoryWriteBuffersWrapperName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/rt/#aa89935ea06c8efbd5b88cc51afd4d38f">llvm::orc::rt::MemoryWritePointersWrapperName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/rt/#a16a7b80a8e73315cd597145aa582492f">llvm::orc::rt::MemoryWriteUInt16sWrapperName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/rt/#ab1a53cab0630ca7f22bc6c2074fc5be8">llvm::orc::rt::MemoryWriteUInt32sWrapperName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/rt/#aa48f07bac1a7bc98ef719170b0ebb6b9">llvm::orc::rt::MemoryWriteUInt64sWrapperName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/rt/#aa7198652f85526109e77300b9b67f559">llvm::orc::rt::MemoryWriteUInt8sWrapperName</a>, <a href="#afd6eab68573896815e1b7e3fbb7554d0">runAsIntFunctionWrapper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/rt/#a29f1789497f8bff6fa2ff287fc252d0a">llvm::orc::rt::RunAsIntFunctionWrapperName</a>, <a href="#aa426d973cb19ceb73313af9043a0f3f7">runAsMainWrapper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/rt/#ae0d022df65cef8fec8bc53d39f9d918a">llvm::orc::rt::RunAsMainWrapperName</a>, <a href="#a3fd747bb0dc9d8e1ad63288b1b6a604b">runAsVoidFunctionWrapper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/rt/#ac46df3c9953b16c7deb29b22d05bd6db">llvm::orc::rt::RunAsVoidFunctionWrapperName</a>, <a href="#abf97028eb83da976471ddd35151826e2">writeBuffersWrapper</a>, <a href="#a86ef3091ab5b291b2d0da5a82c1375a4">writePointersWrapper</a> and <a href="#a153dc6823a589d531a84ffb878ef97c3">writeUIntsWrapper</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepcserver/#a0d4f063da3bf0cb25ecdf1d8efb56b11">llvm::orc::SimpleRemoteEPCServer::defaultBootstrapSymbols</a>.</p>

</div>
</div>

### runAsIntFunctionWrapper() {#afd6eab68573896815e1b7e3fbb7554d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::shared::CWrapperFunctionResult llvm::orc::rt_bootstrap::runAsIntFunctionWrapper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ArgData, size_t ArgSize)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/orcrtbootstrap-cpp">OrcRTBootstrap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a123fead50246387983ee340507115ef4">llvm::release</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a4b98a575435b7792989794e2e617461d">llvm::orc::runAsIntFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#af5df5d5fa49d180d3ca3de567f60de79">llvm::orc::ExecutorAddr::toPtr</a>.</p>


<p>Referenced by <a href="#a80380ad8a5c79d75366b0c1d968a4b7c">addTo</a>.</p>

</div>
</div>

### runAsMainWrapper() {#aa426d973cb19ceb73313af9043a0f3f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::shared::CWrapperFunctionResult llvm::orc::rt_bootstrap::runAsMainWrapper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ArgData, size_t ArgSize)</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/orcrtbootstrap-cpp">OrcRTBootstrap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a123fead50246387983ee340507115ef4">llvm::release</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ae96b02ba0679637389c230e9536a40fc">llvm::orc::runAsMain</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#af5df5d5fa49d180d3ca3de567f60de79">llvm::orc::ExecutorAddr::toPtr</a>.</p>


<p>Referenced by <a href="#a80380ad8a5c79d75366b0c1d968a4b7c">addTo</a>.</p>

</div>
</div>

### runAsVoidFunctionWrapper() {#a3fd747bb0dc9d8e1ad63288b1b6a604b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::shared::CWrapperFunctionResult llvm::orc::rt_bootstrap::runAsVoidFunctionWrapper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ArgData, size_t ArgSize)</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/orcrtbootstrap-cpp">OrcRTBootstrap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a123fead50246387983ee340507115ef4">llvm::release</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a3967432b472134605de76e49e274064b">llvm::orc::runAsVoidFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#af5df5d5fa49d180d3ca3de567f60de79">llvm::orc::ExecutorAddr::toPtr</a>.</p>


<p>Referenced by <a href="#a80380ad8a5c79d75366b0c1d968a4b7c">addTo</a>.</p>

</div>
</div>

### writeBuffersWrapper() {#abf97028eb83da976471ddd35151826e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::shared::CWrapperFunctionResult llvm::orc::rt_bootstrap::writeBuffersWrapper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ArgData, size_t ArgSize)</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/orcrtbootstrap-cpp">OrcRTBootstrap.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a123fead50246387983ee340507115ef4">llvm::release</a>.</p>


<p>Referenced by <a href="#a80380ad8a5c79d75366b0c1d968a4b7c">addTo</a>.</p>

</div>
</div>

### writePointersWrapper() {#a86ef3091ab5b291b2d0da5a82c1375a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::shared::CWrapperFunctionResult llvm::orc::rt_bootstrap::writePointersWrapper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ArgData, size_t ArgSize)</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/orcrtbootstrap-cpp">OrcRTBootstrap.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a123fead50246387983ee340507115ef4">llvm::release</a>.</p>


<p>Referenced by <a href="#a80380ad8a5c79d75366b0c1d968a4b7c">addTo</a>.</p>

</div>
</div>

### writeUIntsWrapper() {#a153dc6823a589d531a84ffb878ef97c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename WriteT, typename SPSWriteT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::shared::CWrapperFunctionResult llvm::orc::rt_bootstrap::writeUIntsWrapper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ArgData, size_t ArgSize)</td>
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



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/orcrtbootstrap-cpp">OrcRTBootstrap.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a123fead50246387983ee340507115ef4">llvm::release</a>.</p>


<p>Referenced by <a href="#a80380ad8a5c79d75366b0c1d968a4b7c">addTo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/targetprocess/orcrtbootstrap-cpp">OrcRTBootstrap.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
