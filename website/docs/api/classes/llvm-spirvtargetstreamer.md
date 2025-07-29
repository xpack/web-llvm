---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/spirvtargetstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SPIRVTargetStreamer` Class



## Declaration

<div class="doxyDeclaration">
class llvm::SPIRVTargetStreamer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvtargetstreamer-h">Target/SPIRV/MCTargetDesc/SPIRVTargetStreamer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer">MCTargetStreamer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> specific streamer interface. <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb775f75feab478ee0d82a0b82ed0cd9">SPIRVTargetStreamer</a> (MCStreamer &amp;S)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba21776fce6ff2d68e26d218ffa38ff5">~SPIRVTargetStreamer</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19505606d837566fa13b21c7441d84fb">changeSection</a> (const MCSection *CurSection, MCSection *Section, uint32_t SubSection, raw_ostream &amp;OS) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update streamer for a new active section. <a href="#a19505606d837566fa13b21c7441d84fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvtargetstreamer-h">SPIRVTargetStreamer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SPIRVTargetStreamer() {#afb775f75feab478ee0d82a0b82ed0cd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVTargetStreamer::SPIRVTargetStreamer (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvtargetstreamer-h">SPIRVTargetStreamer.h</a>, definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvtargetstreamer-cpp">SPIRVTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#acfff4f9a518231ee043200a694fcbafa">llvm::MCTargetStreamer::MCTargetStreamer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SPIRVTargetStreamer() {#aba21776fce6ff2d68e26d218ffa38ff5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SPIRVTargetStreamer::~SPIRVTargetStreamer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvtargetstreamer-h">SPIRVTargetStreamer.h</a>, definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvtargetstreamer-cpp">SPIRVTargetStreamer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### changeSection() {#a19505606d837566fa13b21c7441d84fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SPIRVTargetStreamer::changeSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * CurSection, <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section, uint32_t SubSection, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update streamer for a new active section.</p>


<p>This is called by popSection and switchSection, if the current section changes.</p>


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvtargetstreamer-h">SPIRVTargetStreamer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvtargetstreamer-cpp">SPIRVTargetStreamer.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvtargetstreamer-h">SPIRVTargetStreamer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
