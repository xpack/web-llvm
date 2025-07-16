---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/xcoretargetobjectfile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `XCoreTargetObjectFile` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::XCoreTargetObjectFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoretargetobjectfile-h">Target/XCore/XCoreTargetObjectFile.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf">TargetLoweringObjectFileELF</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c4f64159bcbdb3eaca20c9bbac48f77">Initialize</a> (MCContext &amp;Ctx, const TargetMachine &amp;TM) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method must be called before any actual lowering is done. <a href="#a2c4f64159bcbdb3eaca20c9bbac48f77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a820356be1c79740facb142ac6eaa9e39">getExplicitSectionGlobal</a> (const GlobalObject *GO, SectionKind Kind, const TargetMachine &amp;TM) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets should implement this method to assign a section to globals with an explicit section specfied. <a href="#a820356be1c79740facb142ac6eaa9e39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2b50ec3a5402b3063da7211a176f8ff">SelectSectionForGlobal</a> (const GlobalObject *GO, SectionKind Kind, const TargetMachine &amp;TM) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb3d2db5017c0d0142f336a103f5ce1e">getSectionForConstant</a> (const DataLayout &amp;DL, SectionKind Kind, const Constant *C, Align &amp;Alignment) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a constant with the <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a>, return a section that it should be placed in. <a href="#abb3d2db5017c0d0142f336a103f5ce1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f8ea148c2d9a31ed363ff5a362a5288">BSSSectionLarge</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac750fc18b06b3ab7d2440e49078b58fe">DataSectionLarge</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a070429f4e6e56c26cc71dc94c32ecc4d">ReadOnlySectionLarge</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb3a5ea09fabe04cb25dec2b67bd7bbb">DataRelROSectionLarge</a></td>
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


<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoretargetobjectfile-h">XCoreTargetObjectFile.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getExplicitSectionGlobal() {#a820356be1c79740facb142ac6eaa9e39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * XCoreTargetObjectFile::getExplicitSectionGlobal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> * GO, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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

<p>Targets should implement this method to assign a section to globals with an explicit section specfied.</p>


<p>The implementation of this method can assume that GO-&gt;hasSection() is true.</p>


<p>Declaration at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoretargetobjectfile-h">XCoreTargetObjectFile.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoretargetobjectfile-cpp">XCoreTargetObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#afcda39b4059eca86c10397b7a938a729">llvm::MCObjectFileInfo::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a3fddc32fd70ea36b8482c9055eb68c40">llvm::MCContext::getELFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a0b2e3fb45c4435c29abebf7768a77cd6">llvm::GlobalObject::getSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoretargetobjectfile-cpp/#a840f72ad92cd8088d7dee198d6e773ec">getXCoreSectionFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoretargetobjectfile-cpp/#a6a55a92bdc3219ca1bf2407233f1f792">getXCoreSectionType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a4ef15b6d500629e31fb3787b7a0d7bb0">llvm::TargetLoweringObjectFile::TM</a>.</p>

</div>
</div>

### getSectionForConstant() {#abb3d2db5017c0d0142f336a103f5ce1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * XCoreTargetObjectFile::getSectionForConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &amp; Alignment)</td>
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

<p>Given a constant with the <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a>, return a section that it should be placed in.</p>


<p>Given a mergeable constant with the specified size and relocation information, return a section that it should be placed in.</p>


<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoretargetobjectfile-h">XCoreTargetObjectFile.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoretargetobjectfile-cpp">XCoreTargetObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a13afc727a076f284996b88d722fa312b">llvm::MCObjectFileInfo::MergeableConst16Section</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a1f7abaf19f8d77aa383376e7275492bf">llvm::MCObjectFileInfo::MergeableConst4Section</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a30b67c811ff50fad1141f3826d24ebdc">llvm::MCObjectFileInfo::MergeableConst8Section</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#ac01fb290af1907633ce3c08fa92b25e7">llvm::MCObjectFileInfo::ReadOnlySection</a>.</p>

</div>
</div>

### Initialize() {#a2c4f64159bcbdb3eaca20c9bbac48f77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XCoreTargetObjectFile::Initialize (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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

<p>This method must be called before any actual lowering is done.</p>


<p>Initialize - this method must be called before any actual lowering is done.</p>


<p>This specifies the current context for codegen, and gives the lowering implementations a chance to set up their default sections.</p>


<p>Declaration at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoretargetobjectfile-h">XCoreTargetObjectFile.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoretargetobjectfile-cpp">XCoreTargetObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#ae1df1d88e9ee995e0fd2a17edeaf3321">llvm::MCObjectFileInfo::BSSSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a8c9f99d2a934df382458e6e2d6602f8e">llvm::MCObjectFileInfo::CStringSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a876733c60b97ed94e37dce47534b4ccf">llvm::MCObjectFileInfo::DataRelROSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#affe937af7bd751518ed18a8d3e34c687">llvm::MCObjectFileInfo::DataSection</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a2793bce814c8f8c6fc2f41d4156a4ebb">llvm::TargetLoweringObjectFileELF::Initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a13afc727a076f284996b88d722fa312b">llvm::MCObjectFileInfo::MergeableConst16Section</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a1f7abaf19f8d77aa383376e7275492bf">llvm::MCObjectFileInfo::MergeableConst4Section</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a30b67c811ff50fad1141f3826d24ebdc">llvm::MCObjectFileInfo::MergeableConst8Section</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#ac01fb290af1907633ce3c08fa92b25e7">llvm::MCObjectFileInfo::ReadOnlySection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a0e54850eb2f8e74ae549f6dd70926723">llvm::ELF::SHF_MERGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a1997ac83cc5cdf3e9ccc1e2de7bb8d45">llvm::ELF::SHF_STRINGS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015ae4bcae1b3b4fa53eba0886cbd799f0a8">llvm::ELF::SHF_WRITE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca45212cec20bcd4ca3449dcd8654010ac">llvm::ELF::SHT_NOBITS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca18ae5a64ac74a4265698b956bc797b32">llvm::ELF::SHT_PROGBITS</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a4ef15b6d500629e31fb3787b7a0d7bb0">llvm::TargetLoweringObjectFile::TM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a4ab836558404032ae5aff6eb0f2dcc37">llvm::ELF::XCORE_SHF_CP_SECTION</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a01f370565620641139690a6b8767fd5c">llvm::ELF::XCORE_SHF_DP_SECTION</a>.</p>

</div>
</div>

### SelectSectionForGlobal() {#ac2b50ec3a5402b3063da7211a176f8ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * XCoreTargetObjectFile::SelectSectionForGlobal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> * GO, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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



<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoretargetobjectfile-h">XCoreTargetObjectFile.h</a>, definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoretargetobjectfile-cpp">XCoreTargetObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#ae1df1d88e9ee995e0fd2a17edeaf3321">llvm::MCObjectFileInfo::BSSSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c937fbf10326806d20a93eb896569ad">llvm::CodeModelLargeSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a8c9f99d2a934df382458e6e2d6602f8e">llvm::MCObjectFileInfo::CStringSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a876733c60b97ed94e37dce47534b4ccf">llvm::MCObjectFileInfo::DataRelROSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#affe937af7bd751518ed18a8d3e34c687">llvm::MCObjectFileInfo::DataSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aa5d2c67dadc073dac78224224ee89350">llvm::GlobalValue::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3ba1af4b9d9faa4a33729bbbecee83d1">llvm::GlobalValue::hasLocalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a8ad67a33bae235fe3cca1c3e5a91ed2d">llvm::Type::isSized</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a13afc727a076f284996b88d722fa312b">llvm::MCObjectFileInfo::MergeableConst16Section</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a1f7abaf19f8d77aa383376e7275492bf">llvm::MCObjectFileInfo::MergeableConst4Section</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a30b67c811ff50fad1141f3826d24ebdc">llvm::MCObjectFileInfo::MergeableConst8Section</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#ac01fb290af1907633ce3c08fa92b25e7">llvm::MCObjectFileInfo::ReadOnlySection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa2554ef60dc191c6005ba9eecbc9aea0">llvm::CodeModel::Small</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a293288e990da3ee0cd54c7c340e33030">llvm::MCObjectFileInfo::TextSection</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a4ef15b6d500629e31fb3787b7a0d7bb0">llvm::TargetLoweringObjectFile::TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BSSSectionLarge {#a0f8ea148c2d9a31ed363ff5a362a5288}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::XCoreTargetObjectFile::BSSSectionLarge</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoretargetobjectfile-h">XCoreTargetObjectFile.h</a>.</p>

</div>
</div>

### DataRelROSectionLarge {#acb3a5ea09fabe04cb25dec2b67bd7bbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::XCoreTargetObjectFile::DataRelROSectionLarge</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoretargetobjectfile-h">XCoreTargetObjectFile.h</a>.</p>

</div>
</div>

### DataSectionLarge {#ac750fc18b06b3ab7d2440e49078b58fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::XCoreTargetObjectFile::DataSectionLarge</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoretargetobjectfile-h">XCoreTargetObjectFile.h</a>.</p>

</div>
</div>

### ReadOnlySectionLarge {#a070429f4e6e56c26cc71dc94c32ecc4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection* llvm::XCoreTargetObjectFile::ReadOnlySectionLarge</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoretargetobjectfile-h">XCoreTargetObjectFile.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoretargetobjectfile-cpp">XCoreTargetObjectFile.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoretargetobjectfile-h">XCoreTargetObjectFile.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
