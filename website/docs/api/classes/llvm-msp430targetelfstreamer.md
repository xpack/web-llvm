---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/msp430targetelfstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MSP430TargetELFStreamer` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MSP430TargetELFStreamer { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08e72085c1973f94f76c4444c65e35e5">MSP430TargetELFStreamer</a> (MCStreamer &amp;S, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b5498d2226ad38bba79c61bc904a642">getStreamer</a> ()</td>
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


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/mctargetdesc/msp430elfstreamer-cpp">MSP430ELFStreamer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MSP430TargetELFStreamer() {#a08e72085c1973f94f76c4444c65e35e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MSP430TargetELFStreamer::MSP430TargetELFStreamer (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/mctargetdesc/msp430elfstreamer-cpp">MSP430ELFStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/msp430attrs/#a27a424631b2c2ec3a3a551dd05c8cc93af6e6e0940c30b36b2642e2cb54710d79">llvm::MSP430Attrs::CMSmall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msp430attrs/#ae49561fdd49aea591688b6a1ebd5c77faae0077abe3b8ebb1e7b7ff9e7530ced5">llvm::MSP430Attrs::DMSmall</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a3fddc32fd70ea36b8482c9055eb68c40">llvm::MCContext::getELFSection</a>, <a href="#a1b5498d2226ad38bba79c61bc904a642">getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msp430attrs/#ac4bcc6f1a5cb5507e75bfef0838487dba6ac0d486bed62bb45d2b8eb31f54c04c">llvm::MSP430Attrs::ISAMSP430</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msp430attrs/#ac4bcc6f1a5cb5507e75bfef0838487dbaae190d525d227f1cd4df77ffd22956cd">llvm::MSP430Attrs::ISAMSP430X</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#acfff4f9a518231ee043200a694fcbafa">llvm::MCTargetStreamer::MCTargetStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcaaf45144f3b05bf61bc236de6e4de0308">llvm::ELF::SHT_MSP430_ATTRIBUTES</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#ac5c639960b526c507f505f9e3ebb915d">llvm::MCTargetStreamer::Streamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msp430attrs/#a25e36607b32e2fa00c5a41e8733acad2aaf6ddc682decf3aab85a609719eec5ef">llvm::MSP430Attrs::TagCodeModel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/msp430attrs/#a25e36607b32e2fa00c5a41e8733acad2a0c699a7ac7fd7947ab3740b46c70f9fc">llvm::MSP430Attrs::TagDataModel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/msp430attrs/#a25e36607b32e2fa00c5a41e8733acad2a4d25d5b65af344dd4b939cb17406b6b0">llvm::MSP430Attrs::TagISA</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getStreamer() {#a1b5498d2226ad38bba79c61bc904a642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCELFStreamer &amp; llvm::MSP430TargetELFStreamer::getStreamer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/mctargetdesc/msp430elfstreamer-cpp">MSP430ELFStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#ac5c639960b526c507f505f9e3ebb915d">llvm::MCTargetStreamer::Streamer</a>.</p>


<p>Referenced by <a href="#a08e72085c1973f94f76c4444c65e35e5">MSP430TargetELFStreamer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/mctargetdesc/msp430elfstreamer-cpp">MSP430ELFStreamer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
