---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-inteljiteventlistener-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{IntelJITEventListener.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{IntelJITEventListener.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/intelittnotifyinfo">IntelIttnotifyInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/inteljiteventlistener">IntelJITEventListener</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a9de37a123b4362809ea9d12abc877e2e">LineNumberInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34295cd852aa896f64c8665f1c2ac292">DILineInfoToIntelJITFormat</a> (uintptr_t StartAddress, uintptr_t Address, DILineInfo Line)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#adc57d106ae825b561c956511e6cd93b8">iJIT_Method_Load</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6914f5f9e02468ebb7278d069dc68129">FunctionDescToIntelJITFormat</a> (IntelJITEventsWrapper &amp;Wrapper, const char *FnName, uintptr_t FnStart, size_t FnSize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5094885b654e66770472d1e6802b21f">getBackwardCompatibilityMode</a> ()</td>
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

### DILineInfoToIntelJITFormat() {#a34295cd852aa896f64c8665f1c2ac292}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LineNumberInfo anonymous{IntelJITEventListener.cpp}::DILineInfoToIntelJITFormat (uintptr_t StartAddress, uintptr_t Address, <a href="/web-llvm/docs/api/structs/llvm/dilineinfo">DILineInfo</a> Line)</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitevents/inteljiteventlistener-cpp">IntelJITEventListener.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/inteljiteventlistener/#a89cbcd5cb777a56db440c87f1ebffdb4">anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::notifyObjectLoaded</a>.</p>

</div>
</div>

### FunctionDescToIntelJITFormat() {#a6914f5f9e02468ebb7278d069dc68129}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iJIT_Method_Load anonymous{IntelJITEventListener.cpp}::FunctionDescToIntelJITFormat (<a href="/web-llvm/docs/api/classes/llvm/inteljiteventswrapper">IntelJITEventsWrapper</a> &amp; Wrapper, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * FnName, uintptr_t FnStart, size_t FnSize)</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitevents/inteljiteventlistener-cpp">IntelJITEventListener.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitprofiling/jitprofiling-h/#a95ebe83a5829131400c97607ca80c3eba5bdd71c0c65348e20edfde628c45e842">iJDE_JittingAPI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpualiasanalysis-cpp/#a63f565f28385a6f2c7a4756ff6f3fa16">Wrapper</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/inteljiteventlistener/#a89cbcd5cb777a56db440c87f1ebffdb4">anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::notifyObjectLoaded</a>.</p>

</div>
</div>

### getBackwardCompatibilityMode() {#ac5094885b654e66770472d1e6802b21f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{IntelJITEventListener.cpp}::getBackwardCompatibilityMode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitevents/inteljiteventlistener-cpp">IntelJITEventListener.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1881146f2dcc2ca57c9c5f77f938db9d">llvm::StringRef::getAsInteger</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/inteljiteventlistener/#a1b51573bc0b0e62d37537759a24a44c3">anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::notifyFreeingObject</a> and <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/inteljiteventlistener/#a89cbcd5cb777a56db440c87f1ebffdb4">anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::notifyObjectLoaded</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/inteljitevents/inteljiteventlistener-cpp">IntelJITEventListener.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
