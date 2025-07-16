---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/hexagon-mc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `Hexagon_MC` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::Hexagon_MC { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa93fa22630383fe07736811e31c03f81">selectHexagonCPU</a> (StringRef CPU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee59f67f23fccbef39abc4ecd6092d54">completeHVXFeatures</a> (const FeatureBitset &amp;FB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb851cd69bea258a1020b268d3de3abd">createHexagonMCSubtargetInfo</a> (const Triple &amp;TT, StringRef CPU, StringRef FS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/namespaces/llvm/hexagon">Hexagon</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> instance. <a href="#afb851cd69bea258a1020b268d3de3abd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42d7fe1ef88cc2906006661704af630f">getArchSubtarget</a> (MCSubtargetInfo const *STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3006e90ba5c4717808c3c35e1a778a5">addArchSubtarget</a> (MCSubtargetInfo const *STI, StringRef FS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14ab5a27df8fdb9f291f2545ffb610a3">GetELFFlags</a> (const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">llvm::ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0723502ac4518553dd0ae456238893ca">GetVectRegRev</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ddfa3e93456cffcbd3e4beff76d2d50">getHVXVersion</a> (const FeatureBitset &amp;Features)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a135e6f2cdc120b46545bd36075323a2a">getArchVersion</a> (const FeatureBitset &amp;Features)</td>
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

### addArchSubtarget() {#ab3006e90ba5c4717808c3c35e1a778a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Hexagon_MC::addArchSubtarget (<a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * STI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>, definition at line 644 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-/#a2ca86546c248f0d993f0b5ad6982daf2">anonymous{HexagonMCTargetDesc.cpp}::ArchSubtarget</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-/#a0772196a4e2b7dd77953b82267cb2cd1">anonymous{HexagonMCTargetDesc.cpp}::ArchSubtargetMutex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a83a294111af6d4412163b209725ca556">llvm::StringRef::contains</a>, <a href="#afb851cd69bea258a1020b268d3de3abd">createHexagonMCSubtargetInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a5d5452528429597f223826cbc63ca867">llvm::MCSubtargetInfo::getCPU</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a1ef6ef4ff039e873e9f66e21e3e55e26">llvm::MCSubtargetInfo::getTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>


<p>Referenced by <a href="#afb851cd69bea258a1020b268d3de3abd">createHexagonMCSubtargetInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#a3f194fc9ae635216053fb7435c6c90d6">llvm::HexagonSubtarget::HexagonSubtarget</a>.</p>

</div>
</div>

### completeHVXFeatures() {#aee59f67f23fccbef39abc4ecd6092d54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FeatureBitset llvm::Hexagon_MC::completeHVXFeatures (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; FB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>, definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a54e5f414a306634a73023a4ca94aa776">llvm::FeatureBitset::set</a> and <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a4fce0696a3465a5f24d788288f23f6bf">llvm::FeatureBitset::test</a>.</p>


<p>Referenced by <a href="#afb851cd69bea258a1020b268d3de3abd">createHexagonMCSubtargetInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#ac33e274ca277cfe840f699acc1b8a814">llvm::HexagonSubtarget::initializeSubtargetDependencies</a>.</p>

</div>
</div>

### createHexagonMCSubtargetInfo() {#afb851cd69bea258a1020b268d3de3abd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSubtargetInfo * llvm::Hexagon_MC::createHexagonMCSubtargetInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/namespaces/llvm/hexagon">Hexagon</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> instance.</p>


<p>This is exposed so Asm parser, etc. do not need to go through <a href="/web-llvm/docs/api/structs/llvm/targetregistry">TargetRegistry</a>.</p>


<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>, definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>References <a href="#ab3006e90ba5c4717808c3c35e1a778a5">addArchSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#ae64b1825b82ce592840287c8ebad2d2a">checkFeature</a>, <a href="#aee59f67f23fccbef39abc4ecd6092d54">completeHVXFeatures</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a83a294111af6d4412163b209725ca556">llvm::StringRef::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae67719f41ce92d645a687f546ccffccc">llvm::HexagonDisableDuplex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#a8377a5a0fe394aab78e4bc5b6b0ce059">isCPUValid</a>, <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a20907c2cbc50e3cad93df4c7e49e2b3b">llvm::FeatureBitset::reset</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-/#a0f981e76fa8f3adc086087882cb8d783">anonymous{HexagonMCTargetDesc.cpp}::selectCPUAndFS</a>, <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a54e5f414a306634a73023a4ca94aa776">llvm::FeatureBitset::set</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#ab3006e90ba5c4717808c3c35e1a778a5">addArchSubtarget</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#a98a868de586290904766e4922d3e870b">LLVMInitializeHexagonTargetMC</a>.</p>

</div>
</div>

### getArchSubtarget() {#a42d7fe1ef88cc2906006661704af630f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSubtargetInfo const  * llvm::Hexagon_MC::getArchSubtarget (<a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>, definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-/#a2ca86546c248f0d993f0b5ad6982daf2">anonymous{HexagonMCTargetDesc.cpp}::ArchSubtarget</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-/#a0772196a4e2b7dd77953b82267cb2cd1">anonymous{HexagonMCTargetDesc.cpp}::ArchSubtargetMutex</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a5d5452528429597f223826cbc63ca867">llvm::MCSubtargetInfo::getCPU</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#ab42646dbb9ee42d95ca9d8f05de0daf6">llvm::HexagonMCInstrInfo::canonicalizePacket</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#a963b35ab133a680b8e40743b1780d099">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::getInstruction</a>.</p>

</div>
</div>

### getArchVersion() {#a135e6f2cdc120b46545bd36075323a2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Hexagon_MC::getArchVersion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; Features)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>, definition at line 669 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a4fce0696a3465a5f24d788288f23f6bf">llvm::FeatureBitset::test</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagontargetstreamer/#a5054529ea7e565e73dfc1d396dc50303">llvm::HexagonTargetStreamer::emitTargetAttributes</a>.</p>

</div>
</div>

### GetELFFlags() {#a14ab5a27df8fdb9f291f2545ffb610a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Hexagon_MC::GetELFFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>, definition at line 681 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac4f36b280e179e2a248a45a7d42f9b8ca05da28b096671a99e24d32faba3fd8af">llvm::ELF::EF_HEXAGON_MACH_V5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac4f36b280e179e2a248a45a7d42f9b8caaa32c7f78922db8b9e64309d99750a24">llvm::ELF::EF_HEXAGON_MACH_V55</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac4f36b280e179e2a248a45a7d42f9b8cab6227571cbecef02c885b717b9f85f48">llvm::ELF::EF_HEXAGON_MACH_V60</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac4f36b280e179e2a248a45a7d42f9b8ca50c381c85f18205f26390b15b9d84565">llvm::ELF::EF_HEXAGON_MACH_V62</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac4f36b280e179e2a248a45a7d42f9b8ca41b37e89979e1dbf5bffbd811f274fb0">llvm::ELF::EF_HEXAGON_MACH_V65</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac4f36b280e179e2a248a45a7d42f9b8caa2fc346add3cc43cb0dfe839a614d609">llvm::ELF::EF_HEXAGON_MACH_V66</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac4f36b280e179e2a248a45a7d42f9b8ca49aa97568d197307f761dc8fd99e8bde">llvm::ELF::EF_HEXAGON_MACH_V67</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac4f36b280e179e2a248a45a7d42f9b8ca374635c53dcc3a9cc0354c0888819257">llvm::ELF::EF_HEXAGON_MACH_V67T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac4f36b280e179e2a248a45a7d42f9b8ca80e371b37428af2b95ef71e48c6c28b3">llvm::ELF::EF_HEXAGON_MACH_V68</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac4f36b280e179e2a248a45a7d42f9b8caea0c80d0165ee912bc28cfa762a9c143">llvm::ELF::EF_HEXAGON_MACH_V69</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac4f36b280e179e2a248a45a7d42f9b8ca77fe9e271e1446358a9ce47b7ba847d3">llvm::ELF::EF_HEXAGON_MACH_V71</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac4f36b280e179e2a248a45a7d42f9b8ca22077411a17780669b475ea1332658f6">llvm::ELF::EF_HEXAGON_MACH_V71T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac4f36b280e179e2a248a45a7d42f9b8ca6c0cbb5f6a1d047caa24d671b406ccda">llvm::ELF::EF_HEXAGON_MACH_V73</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac4f36b280e179e2a248a45a7d42f9b8cadd5782db92efa6aed917c29cad6cba8a">llvm::ELF::EF_HEXAGON_MACH_V75</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac4f36b280e179e2a248a45a7d42f9b8ca089ed9d603257533467b6a9a5d580e7a">llvm::ELF::EF_HEXAGON_MACH_V79</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a5d5452528429597f223826cbc63ca867">llvm::MCSubtargetInfo::getCPU</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonmctargetdesc-cpp-/hexagontargetelfstreamer/#a08a63a7b8a4b95d82daa67e148736cd0">anonymous{HexagonMCTargetDesc.cpp}::HexagonTargetELFStreamer::HexagonTargetELFStreamer</a>.</p>

</div>
</div>

### getHVXVersion() {#a2ddfa3e93456cffcbd3e4beff76d2d50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; llvm::Hexagon_MC::getHVXVersion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; Features)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>, definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/featurebitset/#a4fce0696a3465a5f24d788288f23f6bf">llvm::FeatureBitset::test</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagontargetstreamer/#a5054529ea7e565e73dfc1d396dc50303">llvm::HexagonTargetStreamer::emitTargetAttributes</a>.</p>

</div>
</div>

### GetVectRegRev() {#a0723502ac4518553dd0ae456238893ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ArrayRef&lt; MCPhysReg &gt; llvm::Hexagon_MC::GetVectRegRev ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>, definition at line 701 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#a3372d351ec7fac9fb1066e77d36f1276">llvm::HexagonRegisterInfo::getReservedRegs</a>.</p>

</div>
</div>

### selectHexagonCPU() {#aa93fa22630383fe07736811e31c03f81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::Hexagon_MC::selectHexagonCPU (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a>, definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#afa4a019c2bb19ba4f60ae265214aa072">DefaultArch</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#ada3a2b0c364e8d049ebe9b2dd1ab3d3f">HexagonGetArchVariant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a72eaee9433568ed277e40ed923f7bb50">llvm::createHexagonAsmBackend</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonmctargetdesc-cpp-/#a0f981e76fa8f3adc086087882cb8d783">anonymous{HexagonMCTargetDesc.cpp}::selectCPUAndFS</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp">HexagonMCTargetDesc.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h">HexagonMCTargetDesc.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
