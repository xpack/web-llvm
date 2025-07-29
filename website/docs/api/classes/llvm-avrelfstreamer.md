---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/avrelfstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AVRELFStreamer` Class

<p>A target streamer for an <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> object file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AVRELFStreamer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrelfstreamer-h">Target/AVR/MCTargetDesc/AVRELFStreamer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/avrtargetstreamer">AVRTargetStreamer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A generic <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> target output stream. <a href="/web-llvm/docs/api/classes/llvm/avrtargetstreamer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a680bdc9c72ca2dfa148f8b0092a75337">AVRELFStreamer</a> (MCStreamer &amp;S, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer">MCELFStreamer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a065efdd76998bf470448a4d3885e73bc">getStreamer</a> ()</td>
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

<p>A target streamer for an <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> object file.</p>

<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrelfstreamer-h">AVRELFStreamer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AVRELFStreamer() {#a680bdc9c72ca2dfa148f8b0092a75337}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AVRELFStreamer::AVRELFStreamer (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrelfstreamer-h">AVRELFStreamer.h</a>, definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrelfstreamer-cpp">AVRELFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/avrtargetstreamer/#aa83f2f0948bfec5d056cc5d60b01f27f">llvm::AVRTargetStreamer::AVRTargetStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ad987c1e8cb698d475eff233b5c217c5ea819ada9869b697e64c1b30e0247f8f36">llvm::ELF::EF_AVR_LINKRELAX_PREPARED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a65639d47c4e2ec7156b6f4af0f290420">llvm::getEFlagsForFeatureSet</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a53afee158973a8af8c60263ddb5b2d07">llvm::MCSubtargetInfo::getFeatureBits</a>, <a href="#a065efdd76998bf470448a4d3885e73bc">getStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a88517f360c788177b14d3d3d85182145">llvm::MCELFStreamer::getWriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getStreamer() {#a065efdd76998bf470448a4d3885e73bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCELFStreamer &amp; llvm::AVRELFStreamer::getStreamer ()</td>
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



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrelfstreamer-h">AVRELFStreamer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#ac5c639960b526c507f505f9e3ebb915d">llvm::MCTargetStreamer::Streamer</a>.</p>


<p>Referenced by <a href="#a680bdc9c72ca2dfa148f8b0092a75337">AVRELFStreamer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrelfstreamer-cpp">AVRELFStreamer.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrelfstreamer-h">AVRELFStreamer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
