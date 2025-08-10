---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/xray/xrayfileheader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `XRayFileHeader` Struct

<p>XRay traces all have a header providing some top-matter information useful to help tools determine how to interpret the information available in the trace. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::xray::XRayFileHeader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/xrayrecord-h">llvm/XRay/XRayRecord.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc34b30bb2aa2eb255188095f98c755f">Version</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Version of the XRay implementation that produced this file. <a href="#acc34b30bb2aa2eb255188095f98c755f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2278020c11cb76aed417e370aafd4469">Type</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A numeric identifier for the type of file this is. <a href="#a2278020c11cb76aed417e370aafd4469">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a8d6c9691e5b509b0eac7c88653ab35">ConstantTSC</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the CPU that produced the timestamp counters (TSC) move at a constant rate. <a href="#a1a8d6c9691e5b509b0eac7c88653ab35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab54f9934a050863d45df8afeb1822faa">NonstopTSC</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the CPU that produced the timestamp counters (TSC) do not stop. <a href="#ab54f9934a050863d45df8afeb1822faa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a339e015c9be8d198e2920293112f2d9a">CycleFrequency</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of cycles per second for the CPU that produced the timestamp counter (TSC) values. <a href="#a339e015c9be8d198e2920293112f2d9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a970f58b713f42aaeb9800870708f9f21">FreeFormData</a>[16] = {}</td>
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

<p>XRay traces all have a header providing some top-matter information useful to help tools determine how to interpret the information available in the trace.</p>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/xrayrecord-h">XRayRecord.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### ConstantTSC {#a1a8d6c9691e5b509b0eac7c88653ab35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::xray::XRayFileHeader::ConstantTSC = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether the CPU that produced the timestamp counters (TSC) move at a constant rate.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/xrayrecord-h">XRayRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-trace-cpp-/#a7782cd0e983ec47c2ebde56b05575ecb">anonymous{Trace.cpp}::loadYAMLLog</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a204ed5f5be7dc0399e00cf74d6295a5e">llvm::xray::readBinaryFormatHeader</a>.</p>

</div>
</div>

### CycleFrequency {#a339e015c9be8d198e2920293112f2d9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::xray::XRayFileHeader::CycleFrequency = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of cycles per second for the CPU that produced the timestamp counter (TSC) values.</p>


<p>Useful for estimating the amount of time that elapsed between two TSCs on some platforms.</p>


<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/xrayrecord-h">XRayRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-trace-cpp-/#a7782cd0e983ec47c2ebde56b05575ecb">anonymous{Trace.cpp}::loadYAMLLog</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a204ed5f5be7dc0399e00cf74d6295a5e">llvm::xray::readBinaryFormatHeader</a>.</p>

</div>
</div>

### FreeFormData {#a970f58b713f42aaeb9800870708f9f21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::xray::XRayFileHeader::FreeFormData[16] = {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/xrayrecord-h">XRayRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/xray/fdrtracewriter/#ac7333c2977ef0c36d662ef9cff756703">llvm::xray::FDRTraceWriter::FDRTraceWriter</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a204ed5f5be7dc0399e00cf74d6295a5e">llvm::xray::readBinaryFormatHeader</a>.</p>

</div>
</div>

### NonstopTSC {#ab54f9934a050863d45df8afeb1822faa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::xray::XRayFileHeader::NonstopTSC = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether the CPU that produced the timestamp counters (TSC) do not stop.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/xrayrecord-h">XRayRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-trace-cpp-/#a7782cd0e983ec47c2ebde56b05575ecb">anonymous{Trace.cpp}::loadYAMLLog</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a204ed5f5be7dc0399e00cf74d6295a5e">llvm::xray::readBinaryFormatHeader</a>.</p>

</div>
</div>

### Type {#a2278020c11cb76aed417e370aafd4469}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::xray::XRayFileHeader::Type = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A numeric identifier for the type of file this is.</p>


<p>Best used in combination with Version.</p>


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/xrayrecord-h">XRayRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-trace-cpp-/#a7782cd0e983ec47c2ebde56b05575ecb">anonymous{Trace.cpp}::loadYAMLLog</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a204ed5f5be7dc0399e00cf74d6295a5e">llvm::xray::readBinaryFormatHeader</a>.</p>

</div>
</div>

### Version {#acc34b30bb2aa2eb255188095f98c755f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::xray::XRayFileHeader::Version = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Version of the XRay implementation that produced this file.</p>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/xrayrecord-h">XRayRecord.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-trace-cpp-/#a6b4f89ac434c992939934e78f19cd33e">anonymous{Trace.cpp}::loadFDRLog</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-trace-cpp-/#ab12a9d7c65de7b4e040ca540157bf373">anonymous{Trace.cpp}::loadNaiveFormatLog</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-trace-cpp-/#a7782cd0e983ec47c2ebde56b05575ecb">anonymous{Trace.cpp}::loadYAMLLog</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a204ed5f5be7dc0399e00cf74d6295a5e">llvm::xray::readBinaryFormatHeader</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/xrayrecord-h">XRayRecord.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
