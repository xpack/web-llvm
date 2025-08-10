---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/win64eh/arm64unwindemitter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ARM64UnwindEmitter` Class



## Declaration

<div class="doxyDeclaration">
class llvm::Win64EH::ARM64UnwindEmitter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwin64eh-h">llvm/MC/MCWin64EH.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/wineh/unwindemitter">UnwindEmitter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af344ffc71b7b9b6972bda73c603051a8">Emit</a> (MCStreamer &amp;Streamer) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This emits the unwind info sections (.pdata and .xdata in PE/COFF). <a href="#af344ffc71b7b9b6972bda73c603051a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23e988e2f737319fba0ad0f50b4791c3">EmitUnwindInfo</a> (MCStreamer &amp;Streamer, WinEH::FrameInfo *FI, bool HandlerData) const override</td>
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


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwin64eh-h">MCWin64EH.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### Emit() {#af344ffc71b7b9b6972bda73c603051a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Win64EH::ARM64UnwindEmitter::Emit (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer)</td>
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

<p>This emits the unwind info sections (.pdata and .xdata in PE/COFF).</p>

<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwin64eh-h">MCWin64EH.h</a>, definition at line 2541 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a66a4df49046ec16dd9c64d36ba3cb62c">ARM64EmitRuntimeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a6574f704d2fbd168f81e7552695170a8">ARM64EmitUnwindInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a28fee3751eb70ba6768349da24ac79d4">llvm::MCStreamer::getAssociatedPDataSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7304c7ee4dda7ad7b71afed08c070cd8">llvm::MCStreamer::getAssociatedXDataSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acd501c2b93172880cbeaf7e3ab0cc49d">llvm::MCStreamer::getWinFrameInfos</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac4f84451dc4abc997c960d484953b1d2">llvm::MCStreamer::switchSection</a>.</p>

</div>
</div>

### EmitUnwindInfo() {#a23e988e2f737319fba0ad0f50b4791c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Win64EH::ARM64UnwindEmitter::EmitUnwindInfo (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer, <a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo">WinEH::FrameInfo</a> * FI, bool HandlerData)</td>
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



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwin64eh-h">MCWin64EH.h</a>, definition at line 2566 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a6574f704d2fbd168f81e7552695170a8">ARM64EmitUnwindInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2168a8bae9fa55fb113c07c2f66c11f3">llvm::MCStreamer::emitCFILabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7304c7ee4dda7ad7b71afed08c070cd8">llvm::MCStreamer::getAssociatedXDataSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ad7f64bcc544dcefb2e068282af1c549d">info</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac4f84451dc4abc997c960d484953b1d2">llvm::MCStreamer::switchSection</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcwin64eh-h">MCWin64EH.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp">MCWin64EH.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
