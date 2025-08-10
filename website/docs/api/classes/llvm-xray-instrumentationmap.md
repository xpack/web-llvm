---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/xray/instrumentationmap
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InstrumentationMap` Class

<p>The <a href="/web-llvm/docs/api/classes/llvm/xray/instrumentationmap">InstrumentationMap</a> represents the computed function id's and indicated function addresses from an object file (or a YAML file). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::xray::InstrumentationMap { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/instrumentationmap-h">llvm/XRay/InstrumentationMap.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a333606f105ee7aba2513c816d73a455d">FunctionAddressMap</a> = std::unordered_map&lt; int32_t, uint64_t &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a513854f44c6ca8bdc1aac60568e8f9d2">FunctionAddressReverseMap</a> = std::unordered_map&lt; uint64_t, int32_t &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a923dd7374caba5d32a646fb6b6ca3333">SledContainer</a> = std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/xray/sledentry">SledEntry</a> &gt;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/xray/instrumentationmap">InstrumentationMap</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaf13d3707b370b3fb23a592fa975ad4">loadInstrumentationMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Loads the instrumentation map from |Filename|. <a href="#afaf13d3707b370b3fb23a592fa975ad4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a333606f105ee7aba2513c816d73a455d">FunctionAddressMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb5d32c8d8b3e0811c43f07eacba38db">getFunctionAddresses</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provides a raw accessor to the unordered map of function addresses. <a href="#adb5d32c8d8b3e0811c43f07eacba38db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; int32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5f4f8c8b113f4e548fdb0a69bbae019">getFunctionId</a> (uint64_t Addr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an XRay computed function id, provided a function address. <a href="#ac5f4f8c8b113f4e548fdb0a69bbae019">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae78ffbfcbbf0cf8bad2e69a363e246f0">getFunctionAddr</a> (int32_t FuncId) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the function address for a function id. <a href="#ae78ffbfcbbf0cf8bad2e69a363e246f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a923dd7374caba5d32a646fb6b6ca3333">SledContainer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a763dee34469daec9fffbe352f3df1461">sleds</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide read-only access to the entries of the instrumentation map. <a href="#a763dee34469daec9fffbe352f3df1461">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a923dd7374caba5d32a646fb6b6ca3333">SledContainer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32167933c3b655929614f7725af98b7a">Sleds</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a333606f105ee7aba2513c816d73a455d">FunctionAddressMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a688234e6da45a4e4329dd8d9bcbd4452">FunctionAddresses</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a513854f44c6ca8bdc1aac60568e8f9d2">FunctionAddressReverseMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb01118f3f32d796172bf63dbc6146c3">FunctionIds</a></td>
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

## Description {#details}

<p>The <a href="/web-llvm/docs/api/classes/llvm/xray/instrumentationmap">InstrumentationMap</a> represents the computed function id's and indicated function addresses from an object file (or a YAML file).</p>


<p>This provides an interface to just the mapping between the function id, and the function address.</p>


<p>We also provide raw access to the actual instrumentation map entries we find associated with a particular object file.</p>


<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/instrumentationmap-h">InstrumentationMap.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### FunctionAddressMap {#a333606f105ee7aba2513c816d73a455d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::xray::InstrumentationMap::FunctionAddressMap =  std::unordered_map&lt;int32_t, uint64_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/instrumentationmap-h">InstrumentationMap.h</a>.</p>

</div>
</div>

### FunctionAddressReverseMap {#a513854f44c6ca8bdc1aac60568e8f9d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::xray::InstrumentationMap::FunctionAddressReverseMap =  std::unordered_map&lt;uint64_t, int32_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/instrumentationmap-h">InstrumentationMap.h</a>.</p>

</div>
</div>

### SledContainer {#a923dd7374caba5d32a646fb6b6ca3333}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::xray::InstrumentationMap::SledContainer =  std::vector&lt;SledEntry&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/instrumentationmap-h">InstrumentationMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### loadInstrumentationMap {#afaf13d3707b370b3fb23a592fa975ad4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/xray/instrumentationmap">InstrumentationMap</a> &gt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Loads the instrumentation map from |Filename|.</p>


<p>This auto-deduces the type of the instrumentation map.</p>


<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/instrumentationmap-h">InstrumentationMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFunctionAddr() {#ae78ffbfcbbf0cf8bad2e69a363e246f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; InstrumentationMap::getFunctionAddr (int32_t FuncId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the function address for a function id.</p>

<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/instrumentationmap-h">InstrumentationMap.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/instrumentationmap-cpp">InstrumentationMap.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getFunctionAddresses() {#adb5d32c8d8b3e0811c43f07eacba38db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FunctionAddressMap &amp; llvm::xray::InstrumentationMap::getFunctionAddresses ()</td>
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

<p>Provides a raw accessor to the unordered map of function addresses.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/instrumentationmap-h">InstrumentationMap.h</a>.</p>

</div>
</div>

### getFunctionId() {#ac5f4f8c8b113f4e548fdb0a69bbae019}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; int32_t &gt; InstrumentationMap::getFunctionId (uint64_t Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns an XRay computed function id, provided a function address.</p>

<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/instrumentationmap-h">InstrumentationMap.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/instrumentationmap-cpp">InstrumentationMap.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### sleds() {#a763dee34469daec9fffbe352f3df1461}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SledContainer &amp; llvm::xray::InstrumentationMap::sleds ()</td>
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

<p>Provide read-only access to the entries of the instrumentation map.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/instrumentationmap-h">InstrumentationMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FunctionAddresses {#a688234e6da45a4e4329dd8d9bcbd4452}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddressMap llvm::xray::InstrumentationMap::FunctionAddresses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/instrumentationmap-h">InstrumentationMap.h</a>.</p>

</div>
</div>

### FunctionIds {#acb01118f3f32d796172bf63dbc6146c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAddressReverseMap llvm::xray::InstrumentationMap::FunctionIds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/instrumentationmap-h">InstrumentationMap.h</a>.</p>

</div>
</div>

### Sleds {#a32167933c3b655929614f7725af98b7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SledContainer llvm::xray::InstrumentationMap::Sleds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/instrumentationmap-h">InstrumentationMap.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/instrumentationmap-h">InstrumentationMap.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/xray/instrumentationmap-cpp">InstrumentationMap.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
