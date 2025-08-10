---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/spirv/spirvsubtarget-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `SPIRVSubtarget.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvsubtarget-h">SPIRVSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirv-h">SPIRV.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcommandline-h">SPIRVCommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvlegalizerinfo-h">SPIRVLegalizerInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvregisterbankinfo-h">SPIRVRegisterBankInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-h">SPIRVTargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/host-h">llvm/TargetParser/Host.h</a>"
#include "SPIRVGenSubtargetInfo.inc"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46e4eede3aee99a7f5a3603e0b8f4cda">isAtLeastVer</a> (VersionTuple Target, VersionTuple VerToCompareTo)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad624f12d83062740bb603bc8c01deb97">SPVTranslatorCompat</a>("translator-compatibility-mode", cl::desc("SPIR-V Translator compatibility mode"), cl::Optional, cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; std::set&lt; SPIRV::Extension::Extension &gt;, false, <a href="/web-llvm/docs/api/structs/llvm/spirvextensionsparser">SPIRVExtensionsParser</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb3e6d0c41c374eb76421fe8549919e5">Extensions</a>("spirv-ext", cl::desc("Specify list of enabled SPIR-V extensions"))</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"spirv-subtarget"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9edcf2eb5fb8161f71f0b6540ad9cf95">GET_SUBTARGETINFO_TARGET_DESC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7e319f7bba8b140ee2d876cc3f8308b">GET_SUBTARGETINFO_CTOR</a></td>
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


<div class="doxySectionDef">

## Functions

### isAtLeastVer() {#a46e4eede3aee99a7f5a3603e0b8f4cda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isAtLeastVer (<a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> Target, <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> VerToCompareTo)</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvsubtarget-cpp">SPIRVSubtarget.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spirvsubtarget/#a4cca5f61624859f7fe4525775d1eb65c">llvm::SPIRVSubtarget::canDirectlyComparePointers</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvsubtarget/#a88c6e1984655f52aac82039ffac5c1f8">llvm::SPIRVSubtarget::isAtLeastOpenCLVer</a> and <a href="/web-llvm/docs/api/classes/llvm/spirvsubtarget/#a69406caa4380be5b7b2ebaffc53d2ad1">llvm::SPIRVSubtarget::isAtLeastSPIRVVer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### Extensions {#aeb3e6d0c41c374eb76421fe8549919e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::set&lt; SPIRV::Extension::Extension &gt;, false, SPIRVExtensionsParser &gt; Extensions("spirv-ext", cl::desc("Specify list of enabled SPIR-V extensions"))</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvsubtarget-cpp">SPIRVSubtarget.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/aarch64/extensionset/#ae5407a967d3a81aaf557ecbf7a934be9">llvm::AArch64::ExtensionSet::addArchDefaults</a>, <a href="/web-llvm/docs/api/structs/llvm/aarch64/extensionset/#a7a63a256c9ab499323f8b43f3fa735b4">llvm::AArch64::ExtensionSet::addCPUDefaults</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvsubtarget/#a2f7e8a9ce4dd0f092200948d52ccc3f8">llvm::SPIRVSubtarget::addExtensionsToClOpt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#aad0d200082eb13318b21911aa84cafd3">llvm::AArch64::getExtensionByID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#ae76d0c5289150cd3c7c1cd39bdde4d9b">llvm::AArch64::getExtensionFeatures</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ae98ab6ceaf59e5c16d5bbb9d6979efae">llvm::ARM::getExtensionFeatures</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#a23a8a2a541f391128f65c7a17cf6c0d5">llvm::CSKY::getExtensionFeatures</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a15a5fd60e82aee4943453b83b8d74a3f">llvm::getSymbolicOperandExtensions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a1a125d48909fc453d01785064bfb5e67">llvm::AArch64::parseArchExtension</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#ac4c4980b676618fba12e68c665318200">llvm::AArch64::PrintSupportedExtensions</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvsubtarget/#abd74ffbddd24daf4ebae4d6f48e35fc7">llvm::SPIRVSubtarget::SPIRVSubtarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#ac86711dd664d206e40b114dcdd856c9a">llvm::AArch64::targetFeatureToExtension</a> and <a href="/web-llvm/docs/api/structs/llvm/aarch64/extensionset/#a99f85cae5335e38e992e25213e742e1f">llvm::AArch64::ExtensionSet::toLLVMFeatureList</a>.</p>

</div>
</div>

### SPVTranslatorCompat {#ad624f12d83062740bb603bc8c01deb97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; SPVTranslatorCompat("translator-compatibility-mode", cl::desc("SPIR-V Translator compatibility mode"), cl::Optional, cl::init(false))</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvsubtarget-cpp">SPIRVSubtarget.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spirvsubtarget/#a4cca5f61624859f7fe4525775d1eb65c">llvm::SPIRVSubtarget::canDirectlyComparePointers</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"spirv-subtarget"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvsubtarget-cpp">SPIRVSubtarget.cpp</a>.</p>

</div>
</div>

### GET\_SUBTARGETINFO\_CTOR {#aa7e319f7bba8b140ee2d876cc3f8308b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_SUBTARGETINFO_CTOR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvsubtarget-cpp">SPIRVSubtarget.cpp</a>.</p>

</div>
</div>

### GET\_SUBTARGETINFO\_TARGET\_DESC {#a9edcf2eb5fb8161f71f0b6540ad9cf95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_SUBTARGETINFO_TARGET_DESC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvsubtarget-cpp">SPIRVSubtarget.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
