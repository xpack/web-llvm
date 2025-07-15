---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcgendwarfinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCGenDwarfInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MCGenDwarfInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">llvm/MC/MCDwarf.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af945d198ed58841b8d57f45a11e2987e">Emit</a> (MCStreamer *MCOS)</td>
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


<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### Emit() {#af945d198ed58841b8d57f45a11e2987e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCGenDwarfInfo::Emit (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> * MCOS)</td>
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



<p>Declaration at line 466 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>, definition at line 1170 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a299bf2f0329389424760f4a7c8af75ac">llvm::MCContext::createTempSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a917f23f8bbeb0cb04446cf1dfa039787">llvm::MCAsmInfo::doesDwarfUseRelocationsAcrossSections</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ae3810dff97d2b1f712f053e18a98f383">EmitGenDwarfAbbrev</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a1b98f9e375747640ed4f1f019b0558aa">EmitGenDwarfAranges</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#acd1c7609888ea3462f400dcfbca2e486">emitGenDwarfRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a822ae1a4f19b7b00a297a100749f9b8a">llvm::MCStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aa565526e57992a6482d7062b03933b99">llvm::MCContext::finalizeDwarfSections</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aa3beac794c4afb5b1fb6d06cb7786587">llvm::MCContext::getAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#ac10c6a9d85782db274d19ef8f828d9fc">llvm::MCObjectFileInfo::getDwarfAbbrevSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#ae17df2cce5c5b2cb1688d22f2d90820c">llvm::MCObjectFileInfo::getDwarfARangesSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a82d739b35c6534d476fc5bf7d2ee57cb">llvm::MCObjectFileInfo::getDwarfInfoSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aa51d3a6818627c9f45797eeef1f1b91c">llvm::MCStreamer::getDwarfLineTableSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a99c58fcbed2434b9535b866015cd0259">llvm::MCContext::getDwarfVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a0ffd38472bf725df4e4c3cac8c0ad771">llvm::MCContext::getGenDwarfSectionSyms</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a01d6d82d18a5da901c50a546932c4264">llvm::MCContext::getObjectFileInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac4f84451dc4abc997c960d484953b1d2">llvm::MCStreamer::switchSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a5333321f84976a4bf06be40827ca62d8">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::finishImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#aa8d1c93368ccaad9bdc429b25633f943">llvm::MCObjectStreamer::finishImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
