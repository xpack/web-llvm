---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/telemetry/manager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Manager` Class

<p>This class is the main interaction point between any LLVM tool and this framework. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::telemetry::Manager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/telemetry/telemetry-h">llvm/Telemetry/Telemetry.h</a>"
</div>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8036ecd5562bb6fd67830bc182ab5a52">~Manager</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1059139755ac7a9bad30a9c24aae533f">preDispatch</a> (TelemetryInfo *Entry)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c3390e611720f9695e36e5c9a62aca2">dispatch</a> (TelemetryInfo *Entry)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a888a637953e3de96f1afd41dd92efe66">addDestination</a> (std::unique_ptr&lt; Destination &gt; Destination)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/telemetry/destination">Destination</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c82c966ef073da806164442153fa3fa">Destinations</a></td>
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

<p>This class is the main interaction point between any LLVM tool and this framework.</p>


<p>It is responsible for collecting telemetry data from the tool being monitored and transmitting the data elsewhere.</p>


<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/telemetry/telemetry-h">Telemetry.h</a>.</p>


<div class="doxySectionDef">

## Public Destructor

### \~Manager() {#a8036ecd5562bb6fd67830bc182ab5a52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::telemetry::Manager::~Manager ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/telemetry/telemetry-h">Telemetry.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addDestination() {#a888a637953e3de96f1afd41dd92efe66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::telemetry::Manager::addDestination (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/telemetry/destination">Destination</a> &gt; Destination)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/telemetry/telemetry-h">Telemetry.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/telemetry/telemetry-cpp">Telemetry.cpp</a>.</p>

</div>
</div>

### dispatch() {#a9c3390e611720f9695e36e5c9a62aca2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::telemetry::Manager::dispatch (<a href="/web-llvm/docs/api/structs/llvm/telemetry/telemetryinfo">TelemetryInfo</a> * Entry)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/telemetry/telemetry-h">Telemetry.h</a>, definition at line 10 of file <a href="/web-llvm/docs/api/files/lib/lib/telemetry/telemetry-cpp">Telemetry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="#a1059139755ac7a9bad30a9c24aae533f">preDispatch</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### preDispatch() {#a1059139755ac7a9bad30a9c24aae533f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::telemetry::Manager::preDispatch (<a href="/web-llvm/docs/api/structs/llvm/telemetry/telemetryinfo">TelemetryInfo</a> * Entry)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/telemetry/telemetry-h">Telemetry.h</a>.</p>


<p>Referenced by <a href="#a9c3390e611720f9695e36e5c9a62aca2">dispatch</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Destinations {#a5c82c966ef073da806164442153fa3fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;Destination&gt; &gt; llvm::telemetry::Manager::Destinations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/telemetry/telemetry-h">Telemetry.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/telemetry/telemetry-h">Telemetry.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/telemetry/telemetry-cpp">Telemetry.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
