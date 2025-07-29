---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sparctargetelfstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SparcTargetELFStreamer` Class



## Declaration

<div class="doxyDeclaration">
class llvm::SparcTargetELFStreamer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparctargetstreamer-h">Target/Sparc/MCTargetDesc/SparcTargetStreamer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sparctargetstreamer">SparcTargetStreamer</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9cdc85cd16aba10526f4fe2320b1e0d">SparcTargetELFStreamer</a> (MCStreamer &amp;S, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a522405b69d24945e30c6d547eabfc479">getStreamer</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42f61fc1b99ef45e8e58864e052084ef">emitSparcRegisterIgnore</a> (unsigned reg) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit ".register &lt;reg&gt;, #ignore". <a href="#a42f61fc1b99ef45e8e58864e052084ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd8aa8c39d5a833426dd9ac3485f09ee">emitSparcRegisterScratch</a> (unsigned reg) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit ".register &lt;reg&gt;, #scratch". <a href="#afd8aa8c39d5a833426dd9ac3485f09ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparctargetstreamer-h">SparcTargetStreamer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SparcTargetELFStreamer() {#af9cdc85cd16aba10526f4fe2320b1e0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SparcTargetELFStreamer::SparcTargetELFStreamer (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparctargetstreamer-h">SparcTargetStreamer.h</a>, definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparctargetstreamer-cpp">SparcTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a65639d47c4e2ec7156b6f4af0f290420">llvm::getEFlagsForFeatureSet</a>, <a href="#a522405b69d24945e30c6d547eabfc479">getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a88517f360c788177b14d3d3d85182145">llvm::MCELFStreamer::getWriter</a> and <a href="/web-llvm/docs/api/classes/llvm/sparctargetstreamer/#a664a57a906747c2fdc8d8d05e2292156">llvm::SparcTargetStreamer::SparcTargetStreamer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitSparcRegisterIgnore() {#a42f61fc1b99ef45e8e58864e052084ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SparcTargetELFStreamer::emitSparcRegisterIgnore (unsigned reg)</td>
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

<p>Emit ".register &lt;reg&gt;, #ignore".</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparctargetstreamer-h">SparcTargetStreamer.h</a>.</p>

</div>
</div>

### emitSparcRegisterScratch() {#afd8aa8c39d5a833426dd9ac3485f09ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SparcTargetELFStreamer::emitSparcRegisterScratch (unsigned reg)</td>
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

<p>Emit ".register &lt;reg&gt;, #scratch".</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparctargetstreamer-h">SparcTargetStreamer.h</a>.</p>

</div>
</div>

### getStreamer() {#a522405b69d24945e30c6d547eabfc479}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCELFStreamer &amp; SparcTargetELFStreamer::getStreamer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparctargetstreamer-h">SparcTargetStreamer.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparctargetstreamer-cpp">SparcTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#ac5c639960b526c507f505f9e3ebb915d">llvm::MCTargetStreamer::Streamer</a>.</p>


<p>Referenced by <a href="#af9cdc85cd16aba10526f4fe2320b1e0d">SparcTargetELFStreamer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparctargetstreamer-cpp">SparcTargetStreamer.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparctargetstreamer-h">SparcTargetStreamer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
