---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/pseudoprobedwarfdiscriminator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PseudoProbeDwarfDiscriminator` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::PseudoProbeDwarfDiscriminator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/pseudoprobe-h">llvm/IR/PseudoProbe.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65b110861bfbc06e20befde65915f078">packProbeData</a> (uint32_t Index, uint32_t Type, uint32_t Flags, uint32_t Factor, std::optional&lt; uint32_t &gt; DwarfBaseDiscriminator)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5db4061b62e740850ad71806b1dbd60e">extractProbeIndex</a> (uint32_t Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0c37806bfdb6415dbe3866307f6716c">extractDwarfBaseDiscriminator</a> (uint32_t Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84af1f287ce3b82e441023d58456653b">isDwarfBaseDiscriminatorEncoded</a> (uint32_t Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc49454167a56822ab9bf04310a2dbe1">extractProbeType</a> (uint32_t Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87b1baf4f84945b1e2ef2366d0d14dad">extractProbeAttributes</a> (uint32_t Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a003920e6fa1aac96fa977c7b3e6604fb">extractProbeFactor</a> (uint32_t Value)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d966c8251ff32615370f3658cec6887">FullDistributionFactor</a> = 100</td>
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


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/pseudoprobe-h">PseudoProbe.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### extractDwarfBaseDiscriminator() {#ad0c37806bfdb6415dbe3866307f6716c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint32_t &gt; llvm::PseudoProbeDwarfDiscriminator::extractDwarfBaseDiscriminator (uint32_t Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/pseudoprobe-h">PseudoProbe.h</a>.</p>


<p>Reference <a href="#a84af1f287ce3b82e441023d58456653b">isDwarfBaseDiscriminatorEncoded</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dilocation/#a98203aeac2bf8055f829ba0203e77665">llvm::DILocation::getBaseDiscriminatorFromDiscriminator</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a35bb2baa976d7716a9752ad544e8134f">anonymous{SampleProfile.cpp}::SampleProfileLoader::removePseudoProbeInstsDiscriminator</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4fb32c986b105bb7a53700e5988aab6e">llvm::setProbeDistributionFactor</a>.</p>

</div>
</div>

### extractProbeAttributes() {#a87b1baf4f84945b1e2ef2366d0d14dad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::PseudoProbeDwarfDiscriminator::extractProbeAttributes (uint32_t Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/pseudoprobe-h">PseudoProbe.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a202ea3964f0d9dd2bf8bf07cb89e0fb0">llvm::extractProbeFromDiscriminator</a>, <a href="/web-llvm/docs/api/classes/anonymous-pseudoprobeinserter-cpp-/pseudoprobeinserter/#acf62b36239ac36c52ffc9a58a18332ab">anonymous{PseudoProbeInserter.cpp}::PseudoProbeInserter::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4fb32c986b105bb7a53700e5988aab6e">llvm::setProbeDistributionFactor</a>.</p>

</div>
</div>

### extractProbeFactor() {#a003920e6fa1aac96fa977c7b3e6604fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::PseudoProbeDwarfDiscriminator::extractProbeFactor (uint32_t Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/pseudoprobe-h">PseudoProbe.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a202ea3964f0d9dd2bf8bf07cb89e0fb0">llvm::extractProbeFromDiscriminator</a>.</p>

</div>
</div>

### extractProbeIndex() {#a5db4061b62e740850ad71806b1dbd60e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::PseudoProbeDwarfDiscriminator::extractProbeIndex (uint32_t Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/pseudoprobe-h">PseudoProbe.h</a>.</p>


<p>Reference <a href="#a84af1f287ce3b82e441023d58456653b">isDwarfBaseDiscriminatorEncoded</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pseudoprobehandler/#a852e00b0a303d6be050e6b6ee092c9b6">llvm::PseudoProbeHandler::emitPseudoProbe</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a202ea3964f0d9dd2bf8bf07cb89e0fb0">llvm::extractProbeFromDiscriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation/#a98203aeac2bf8055f829ba0203e77665">llvm::DILocation::getBaseDiscriminatorFromDiscriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aeea4c49a1040f9305f6a09d7d7815544">llvm::sampleprof::FunctionSamples::getCallSiteIdentifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-pseudoprobeinserter-cpp-/pseudoprobeinserter/#acf62b36239ac36c52ffc9a58a18332ab">anonymous{PseudoProbeInserter.cpp}::PseudoProbeInserter::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4fb32c986b105bb7a53700e5988aab6e">llvm::setProbeDistributionFactor</a>.</p>

</div>
</div>

### extractProbeType() {#afc49454167a56822ab9bf04310a2dbe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::PseudoProbeDwarfDiscriminator::extractProbeType (uint32_t Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/pseudoprobe-h">PseudoProbe.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a202ea3964f0d9dd2bf8bf07cb89e0fb0">llvm::extractProbeFromDiscriminator</a>, <a href="/web-llvm/docs/api/classes/anonymous-pseudoprobeinserter-cpp-/pseudoprobeinserter/#acf62b36239ac36c52ffc9a58a18332ab">anonymous{PseudoProbeInserter.cpp}::PseudoProbeInserter::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4fb32c986b105bb7a53700e5988aab6e">llvm::setProbeDistributionFactor</a>.</p>

</div>
</div>

### isDwarfBaseDiscriminatorEncoded() {#a84af1f287ce3b82e441023d58456653b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PseudoProbeDwarfDiscriminator::isDwarfBaseDiscriminatorEncoded (uint32_t Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/pseudoprobe-h">PseudoProbe.h</a>.</p>


<p>Referenced by <a href="#ad0c37806bfdb6415dbe3866307f6716c">extractDwarfBaseDiscriminator</a> and <a href="#a5db4061b62e740850ad71806b1dbd60e">extractProbeIndex</a>.</p>

</div>
</div>

### packProbeData() {#a65b110861bfbc06e20befde65915f078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::PseudoProbeDwarfDiscriminator::packProbeData (uint32_t Index, uint32_t Type, uint32_t Flags, uint32_t Factor, std::optional&lt; uint32_t &gt; DwarfBaseDiscriminator)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/pseudoprobe-h">PseudoProbe.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprofileprober/#af77769bc44a5fe5006bbc89befd75e4b">llvm::SampleProfileProber::instrumentOneFunc</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4fb32c986b105bb7a53700e5988aab6e">llvm::setProbeDistributionFactor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### FullDistributionFactor {#a0d966c8251ff32615370f3658cec6887}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::PseudoProbeDwarfDiscriminator::FullDistributionFactor = 100</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/pseudoprobe-h">PseudoProbe.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a202ea3964f0d9dd2bf8bf07cb89e0fb0">llvm::extractProbeFromDiscriminator</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileprober/#af77769bc44a5fe5006bbc89befd75e4b">llvm::SampleProfileProber::instrumentOneFunc</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4fb32c986b105bb7a53700e5988aab6e">llvm::setProbeDistributionFactor</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/pseudoprobe-h">PseudoProbe.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
