---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-gcovprofiling-cpp-/gcovrecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GCOVRecord` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{GCOVProfiling.cpp}::GCOVRecord { ... }
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovblock">GCOVBlock</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovfunction">GCOVFunction</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovlines">GCOVLines</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac00184608e51488222ea733f0d31d2c4">GCOVRecord</a> (GCOVProfiler *P)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07920a71f30fb9eee10a97d4e4a7a410">write</a> (uint32_t i)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa49cafc4b1e700289da51762c5680da1">writeString</a> (StringRef s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a104aa891c45625cb5146b72ce9996f9b">writeBytes</a> (const char *Bytes, int Size)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovprofiler">GCOVProfiler</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a642d495294e1f95a74c02a8046b23298">P</a></td>
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


<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp">GCOVProfiling.cpp</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### GCOVRecord() {#ac00184608e51488222ea733f0d31d2c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{GCOVProfiling.cpp}::GCOVRecord::GCOVRecord (<a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovprofiler">GCOVProfiler</a> * P)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp">GCOVProfiling.cpp</a>.</p>


<p>Reference <a href="#a642d495294e1f95a74c02a8046b23298">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovblock/#a7702b5d3fad485b672db9cba93af5951">anonymous{GCOVProfiling.cpp}::GCOVBlock::GCOVBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovblock/#a321c75641625bf61f80572331993cff2">anonymous{GCOVProfiling.cpp}::GCOVBlock::GCOVFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovfunction/#aa843f97b9cc03fe72d109c21eea6c15a">anonymous{GCOVProfiling.cpp}::GCOVFunction::GCOVFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovlines/#a0cd45051304e4a1ae54823666c3dfef0">anonymous{GCOVProfiling.cpp}::GCOVLines::GCOVLines</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### write() {#a07920a71f30fb9eee10a97d4e4a7a410}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{GCOVProfiling.cpp}::GCOVRecord::write (uint32_t i)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp">GCOVProfiling.cpp</a>.</p>


<p>Reference <a href="#a642d495294e1f95a74c02a8046b23298">P</a>.</p>

</div>
</div>

### writeBytes() {#a104aa891c45625cb5146b72ce9996f9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{GCOVProfiling.cpp}::GCOVRecord::writeBytes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Bytes, int Size)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp">GCOVProfiling.cpp</a>.</p>


<p>References <a href="#a642d495294e1f95a74c02a8046b23298">P</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### writeString() {#aa49cafc4b1e700289da51762c5680da1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{GCOVProfiling.cpp}::GCOVRecord::writeString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> s)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp">GCOVProfiling.cpp</a>.</p>


<p>Reference <a href="#a642d495294e1f95a74c02a8046b23298">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovfunction/#a9141ca1168edd7cd985be48a52bd218f">anonymous{GCOVProfiling.cpp}::GCOVFunction::writeOut</a> and <a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovlines/#a0781c1d5d279bf0ec8baf073624d8214">anonymous{GCOVProfiling.cpp}::GCOVLines::writeOut</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### P {#a642d495294e1f95a74c02a8046b23298}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCOVProfiler* anonymous{GCOVProfiling.cpp}::GCOVRecord::P</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp">GCOVProfiling.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovblock/#a321c75641625bf61f80572331993cff2">anonymous{GCOVProfiling.cpp}::GCOVBlock::GCOVFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovfunction/#aa843f97b9cc03fe72d109c21eea6c15a">anonymous{GCOVProfiling.cpp}::GCOVFunction::GCOVFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovlines/#a0cd45051304e4a1ae54823666c3dfef0">anonymous{GCOVProfiling.cpp}::GCOVLines::GCOVLines</a>, <a href="#ac00184608e51488222ea733f0d31d2c4">GCOVRecord</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovblock/#a2fff578004530c009dd7ca51e04ae1d8">anonymous{GCOVProfiling.cpp}::GCOVBlock::getFile</a>, <a href="#a07920a71f30fb9eee10a97d4e4a7a410">write</a>, <a href="#a104aa891c45625cb5146b72ce9996f9b">writeBytes</a> and <a href="#aa49cafc4b1e700289da51762c5680da1">writeString</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp">GCOVProfiling.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
