---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/targetloweringobjectfilexcoff
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TargetLoweringObjectFileXCOFF` Class



## Declaration

<div class="doxyDeclaration">
class llvm::TargetLoweringObjectFileXCOFF { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">llvm/CodeGen/TargetLoweringObjectFileImpl.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile">TargetLoweringObjectFile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe71c4025859f94c78936998b7218596">TargetLoweringObjectFileXCOFF</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6561682cb6b2f1c0146fbddf88ed7e7f">~TargetLoweringObjectFileXCOFF</a> () override=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bf32141c5a35cf431382b87f661175d">Initialize</a> (MCContext &amp;Ctx, const TargetMachine &amp;TM) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method must be called before any actual lowering is done. <a href="#a1bf32141c5a35cf431382b87f661175d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40fe0525283caf34c373b1beaaf90b05">shouldPutJumpTableInFunctionSection</a> (bool UsesLabelDifference, const Function &amp;F) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6027e9f6e624a2ac869c29f803baa739">getExplicitSectionGlobal</a> (const GlobalObject *GO, SectionKind Kind, const TargetMachine &amp;TM) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets should implement this method to assign a section to globals with an explicit section specfied. <a href="#a6027e9f6e624a2ac869c29f803baa739">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6afaf11e33b0ea1c5430230f355bb769">getStaticCtorSection</a> (unsigned Priority, const MCSymbol *KeySym) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcbafe3b616d6981774cd09196a87089">getStaticDtorSection</a> (unsigned Priority, const MCSymbol *KeySym) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54fef84d5923e0eae22f02f8836487ae">lowerRelativeReference</a> (const GlobalValue *LHS, const GlobalValue *RHS, const TargetMachine &amp;TM) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa6dda813be79bdc7753ef52b9b5ec56">SelectSectionForGlobal</a> (const GlobalObject *GO, SectionKind Kind, const TargetMachine &amp;TM) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59f70e2f83b2a97372e18a6c6316550d">getSectionForJumpTable</a> (const Function &amp;F, const TargetMachine &amp;TM) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81d5951cc0d223b8709e34fdf56152fe">getSectionForConstant</a> (const DataLayout &amp;DL, SectionKind Kind, const Constant *C, Align &amp;Alignment) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a constant with the <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a>, return a section that it should be placed in. <a href="#a81d5951cc0d223b8709e34fdf56152fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adee710107b7fec9dcf8076bd0dc44d2d">getSectionForFunctionDescriptor</a> (const Function *F, const TargetMachine &amp;TM) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>On targets that use separate function descriptor symbols, return a section for the descriptor given its symbol. <a href="#adee710107b7fec9dcf8076bd0dc44d2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24e99c9fbb9fedd3a9b504d09ddfa21b">getSectionForTOCEntry</a> (const MCSymbol *Sym, const TargetMachine &amp;TM) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>On targets that support TOC entries, return a section for the entry given the symbol it refers to. <a href="#a24e99c9fbb9fedd3a9b504d09ddfa21b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ddf5387f9cd603891e1933c2f84cf65">getSectionForExternalReference</a> (const GlobalObject *GO, const TargetMachine &amp;TM) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For external functions, this will always return a function descriptor csect. <a href="#a2ddf5387f9cd603891e1933c2f84cf65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab62f64f95c7f4a90a4d54f55e1b39967">getTargetSymbol</a> (const GlobalValue *GV, const TargetMachine &amp;TM) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For functions, this will always return a function descriptor symbol. <a href="#ab62f64f95c7f4a90a4d54f55e1b39967">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e40bda8245f90bbe4a72d083b4d8431">getFunctionEntryPointSymbol</a> (const GlobalValue *Func, const TargetMachine &amp;TM) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If supported, return the function entry point symbol. <a href="#a3e40bda8245f90bbe4a72d083b4d8431">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afff1a14d07c4f0d35848b797930090c6">getSectionForLSDA</a> (const Function &amp;F, const MCSymbol &amp;FnSym, const TargetMachine &amp;TM) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For functions, this will return the LSDA section. <a href="#afff1a14d07c4f0d35848b797930090c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa217c0d4fe1f12c81f44863f2a37b06">ShouldEmitEHBlock</a> (const MachineFunction *MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0feea92aabe11ff92dddf017ec2ef4e8">ShouldSetSSPCanaryBitInTB</a> (const MachineFunction *MF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d1987fcd07a91cbecea1c8ea8f174d3">getEHInfoTableSymbol</a> (const MachineFunction *MF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70">XCOFF::StorageClass</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79b16b25c08c277de4d27f75a22f95e4">getStorageClassForGlobal</a> (const GlobalValue *GV)</td>
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


<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">TargetLoweringObjectFileImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TargetLoweringObjectFileXCOFF() {#afe71c4025859f94c78936998b7218596}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetLoweringObjectFileXCOFF::TargetLoweringObjectFileXCOFF ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">TargetLoweringObjectFileImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~TargetLoweringObjectFileXCOFF() {#a6561682cb6b2f1c0146fbddf88ed7e7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetLoweringObjectFileXCOFF::~TargetLoweringObjectFileXCOFF ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">TargetLoweringObjectFileImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a4ef15b6d500629e31fb3787b7a0d7bb0">llvm::TargetLoweringObjectFile::TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getExplicitSectionGlobal() {#a6027e9f6e624a2ac869c29f803baa739}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * TargetLoweringObjectFileXCOFF::getExplicitSectionGlobal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> * GO, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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


<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">TargetLoweringObjectFileImpl.h</a>, definition at line 2383 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#afcda39b4059eca86c10397b7a938a729">llvm::MCObjectFileInfo::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a0b2e3fb45c4435c29abebf7768a77cd6">llvm::GlobalObject::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a435597fd04ebfd9b5fb5708a4309febb">llvm::MCContext::getXCOFFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#ade7dc7510e950cd1c1181138b390f965">llvm::GlobalObject::hasSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a4ef15b6d500629e31fb3787b7a0d7bb0">llvm::TargetLoweringObjectFile::TM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502cac7850ad5e926ed392928b68832be764e">llvm::XCOFF::XMC_PR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502ca8013b2bcd044df8d46c49e8b96eb9a52">llvm::XCOFF::XMC_RO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502ca54b665a90facd18af1df67a6cf1194d5">llvm::XCOFF::XMC_RW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502caa250286dfb78ab47b0ba96d5b0f9bc51">llvm::XCOFF::XMC_TD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ae6213556e13de39091f6861f199d7b1fabc703e0e4100086f310d23f214a3cf03">llvm::XCOFF::XTY_SD</a>.</p>

</div>
</div>

### getFunctionEntryPointSymbol() {#a3e40bda8245f90bbe4a72d083b4d8431}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * TargetLoweringObjectFileXCOFF::getFunctionEntryPointSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * Func, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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

<p>If supported, return the function entry point symbol.</p>


<p>Otherwise, returns nullptr. Func must be a function or an alias which has a function as base object.</p>


<p>Declaration at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">TargetLoweringObjectFileImpl.h</a>, definition at line 2643 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#afcda39b4059eca86c10397b7a938a729">llvm::MCObjectFileInfo::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a05a26c90a4811f2e63a64f0c3660ae09">llvm::TargetLoweringObjectFile::getNameWithPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ac11eef690074972378846024abbe8722">llvm::MCContext::getOrCreateSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionxcoff/#a8681532d1e34a00500cd1da99179878f">llvm::MCSectionXCOFF::getQualNameSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a36d55da4fb88dbef3b548a7e25c99dd7">llvm::SectionKind::getText</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a435597fd04ebfd9b5fb5708a4309febb">llvm::MCContext::getXCOFFSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4956305191cdba7f9995569d011a5ab7">llvm::isa_and_nonnull</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a4ef15b6d500629e31fb3787b7a0d7bb0">llvm::TargetLoweringObjectFile::TM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502cac7850ad5e926ed392928b68832be764e">llvm::XCOFF::XMC_PR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ae6213556e13de39091f6861f199d7b1fad8a6731bed03a3891075d7ba162f83ba">llvm::XCOFF::XTY_ER</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ae6213556e13de39091f6861f199d7b1fabc703e0e4100086f310d23f214a3cf03">llvm::XCOFF::XTY_SD</a>.</p>


<p>Referenced by <a href="#afa6dda813be79bdc7753ef52b9b5ec56">SelectSectionForGlobal</a>.</p>

</div>
</div>

### getSectionForConstant() {#a81d5951cc0d223b8709e34fdf56152fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * TargetLoweringObjectFileXCOFF::getSectionForConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> &amp; Alignment)</td>
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


<p>Declaration at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">TargetLoweringObjectFileImpl.h</a>, definition at line 2562 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a4c403c28c309d3dcee0ddaf70bda29fc">llvm::MCObjectFileInfo::ReadOnly16Section</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a6552bb97aa2622ca7c1a18f17f8eda38">llvm::MCObjectFileInfo::ReadOnly8Section</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#ac01fb290af1907633ce3c08fa92b25e7">llvm::MCObjectFileInfo::ReadOnlySection</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### getSectionForExternalReference() {#a2ddf5387f9cd603891e1933c2f84cf65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * TargetLoweringObjectFileXCOFF::getSectionForExternalReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> * GO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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

<p>For external functions, this will always return a function descriptor csect.</p>

<p>Declaration at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">TargetLoweringObjectFileImpl.h</a>, definition at line 2416 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#afcda39b4059eca86c10397b7a938a729">llvm::MCObjectFileInfo::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a587678b6051996e25d2bd6ebce323c9c">llvm::SectionKind::getData</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a13a2c76a48665ee3f4782fba7ddd72e1">llvm::SectionKind::getMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a05a26c90a4811f2e63a64f0c3660ae09">llvm::TargetLoweringObjectFile::getNameWithPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a52126ae2091b18cecfd5ad0f0012839a">llvm::GlobalValue::getThreadLocalMode</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a435597fd04ebfd9b5fb5708a4309febb">llvm::MCContext::getXCOFFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ad9d88ae321b98d8a3b7f394977ae6d7f">llvm::Value::hasName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6b66f492cbea5f4b4f434d7178477116">llvm::GlobalValue::isDeclarationForLinker</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a239427c2c3a01e23bd15b29633696536">llvm::GlobalValue::isThreadLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62ac9f6ea05a2d4cca9e093366042dfa6b8">llvm::GlobalValue::LocalDynamicTLSModel</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a4ef15b6d500629e31fb3787b7a0d7bb0">llvm::TargetLoweringObjectFile::TM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502ca4ffc8d36538dfbb1c9eac9236b0855fb">llvm::XCOFF::XMC_DS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502caf3ddd7ad51b55d1c692d1cd3662e0fce">llvm::XCOFF::XMC_TC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502caa250286dfb78ab47b0ba96d5b0f9bc51">llvm::XCOFF::XMC_TD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502ca9b07ec722c8247ad2535a8c28b218220">llvm::XCOFF::XMC_UA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502cab35fc11d2968b541a2442c6138a1ba09">llvm::XCOFF::XMC_UL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ae6213556e13de39091f6861f199d7b1fad8a6731bed03a3891075d7ba162f83ba">llvm::XCOFF::XTY_ER</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ae6213556e13de39091f6861f199d7b1fabc703e0e4100086f310d23f214a3cf03">llvm::XCOFF::XTY_SD</a>.</p>


<p>Referenced by <a href="#ab62f64f95c7f4a90a4d54f55e1b39967">getTargetSymbol</a>.</p>

</div>
</div>

### getSectionForFunctionDescriptor() {#adee710107b7fec9dcf8076bd0dc44d2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * TargetLoweringObjectFileXCOFF::getSectionForFunctionDescriptor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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

<p>On targets that use separate function descriptor symbols, return a section for the descriptor given its symbol.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> only with defined functions.</p>


<p>Declaration at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">TargetLoweringObjectFileImpl.h</a>, definition at line 2675 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#afcda39b4059eca86c10397b7a938a729">llvm::MCObjectFileInfo::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a587678b6051996e25d2bd6ebce323c9c">llvm::SectionKind::getData</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a05a26c90a4811f2e63a64f0c3660ae09">llvm::TargetLoweringObjectFile::getNameWithPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a435597fd04ebfd9b5fb5708a4309febb">llvm::MCContext::getXCOFFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a4ef15b6d500629e31fb3787b7a0d7bb0">llvm::TargetLoweringObjectFile::TM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502ca4ffc8d36538dfbb1c9eac9236b0855fb">llvm::XCOFF::XMC_DS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ae6213556e13de39091f6861f199d7b1fabc703e0e4100086f310d23f214a3cf03">llvm::XCOFF::XTY_SD</a>.</p>


<p>Referenced by <a href="#ab62f64f95c7f4a90a4d54f55e1b39967">getTargetSymbol</a>.</p>

</div>
</div>

### getSectionForJumpTable() {#a59f70e2f83b2a97372e18a6c6316550d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * TargetLoweringObjectFileXCOFF::getSectionForJumpTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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



<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">TargetLoweringObjectFileImpl.h</a>, definition at line 2539 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#afcda39b4059eca86c10397b7a938a729">llvm::MCObjectFileInfo::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a05a26c90a4811f2e63a64f0c3660ae09">llvm::TargetLoweringObjectFile::getNameWithPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#af4b0b8bc19062c7b0195fc7239c4dbea">llvm::SectionKind::getReadOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a435597fd04ebfd9b5fb5708a4309febb">llvm::MCContext::getXCOFFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#ac01fb290af1907633ce3c08fa92b25e7">llvm::MCObjectFileInfo::ReadOnlySection</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a4ef15b6d500629e31fb3787b7a0d7bb0">llvm::TargetLoweringObjectFile::TM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502ca8013b2bcd044df8d46c49e8b96eb9a52">llvm::XCOFF::XMC_RO</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ae6213556e13de39091f6861f199d7b1fabc703e0e4100086f310d23f214a3cf03">llvm::XCOFF::XTY_SD</a>.</p>

</div>
</div>

### getSectionForLSDA() {#afff1a14d07c4f0d35848b797930090c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * TargetLoweringObjectFileXCOFF::getSectionForLSDA (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; FnSym, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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

<p>For functions, this will return the LSDA section.</p>


<p>If option -ffunction-sections is on, this will return a unique csect with the function name appended to .gcc_except_table as a suffix of the LSDA section name.</p>


<p>Declaration at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">TargetLoweringObjectFileImpl.h</a>, definition at line 2716 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#afcda39b4059eca86c10397b7a938a729">llvm::MCObjectFileInfo::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a435597fd04ebfd9b5fb5708a4309febb">llvm::MCContext::getXCOFFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a3958cbb873bc9ea9f052fd2e467c50d8">llvm::MCObjectFileInfo::LSDASection</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a4ef15b6d500629e31fb3787b7a0d7bb0">llvm::TargetLoweringObjectFile::TM</a>.</p>

</div>
</div>

### getSectionForTOCEntry() {#a24e99c9fbb9fedd3a9b504d09ddfa21b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * TargetLoweringObjectFileXCOFF::getSectionForTOCEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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

<p>On targets that support TOC entries, return a section for the entry given the symbol it refers to.</p>


<p>TODO: Implement this interface for existing <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> targets.</p>


<p>Declaration at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">TargetLoweringObjectFileImpl.h</a>, definition at line 2684 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolxcoff/#a5ef9bbf615c9136516bbdff6b4749a63a70dbe554aa66c75d8d5053a94d9dde5d">llvm::MCSymbolXCOFF::CM_Large</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#afcda39b4059eca86c10397b7a938a729">llvm::MCObjectFileInfo::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a587678b6051996e25d2bd6ebce323c9c">llvm::SectionKind::getData</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolxcoff/#a4d630f0a9c4b8acf156da5c42f0d3cf7">llvm::MCSymbolXCOFF::getPerSymbolCodeModel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolxcoff/#a29896ac9b731b80cfb021fb432b73d7d">llvm::MCSymbolXCOFF::getSymbolTableName</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a435597fd04ebfd9b5fb5708a4309febb">llvm::MCContext::getXCOFFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolxcoff/#a3010d5888201be4274e1b80d16eb77f4">llvm::MCSymbolXCOFF::hasPerSymbolCodeModel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolxcoff/#a6397be1a70c3c747af829c3d590e329d">llvm::MCSymbolXCOFF::isEHInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a4ef15b6d500629e31fb3787b7a0d7bb0">llvm::TargetLoweringObjectFile::TM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502caf3ddd7ad51b55d1c692d1cd3662e0fce">llvm::XCOFF::XMC_TC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502ca01440f6a3c58a05d2ee20ba480d16443">llvm::XCOFF::XMC_TE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ae6213556e13de39091f6861f199d7b1fabc703e0e4100086f310d23f214a3cf03">llvm::XCOFF::XTY_SD</a>.</p>

</div>
</div>

### getStaticCtorSection() {#a6afaf11e33b0ea1c5430230f355bb769}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * TargetLoweringObjectFileXCOFF::getStaticCtorSection (unsigned Priority, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * KeySym)</td>
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



<p>Declaration at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">TargetLoweringObjectFileImpl.h</a>, definition at line 2601 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### getStaticDtorSection() {#afcbafe3b616d6981774cd09196a87089}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * TargetLoweringObjectFileXCOFF::getStaticDtorSection (unsigned Priority, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * KeySym)</td>
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



<p>Declaration at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">TargetLoweringObjectFileImpl.h</a>, definition at line 2606 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### getTargetSymbol() {#ab62f64f95c7f4a90a4d54f55e1b39967}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * TargetLoweringObjectFileXCOFF::getTargetSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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

<p>For functions, this will always return a function descriptor symbol.</p>

<p>Declaration at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">TargetLoweringObjectFileImpl.h</a>, definition at line 2347 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a587678b6051996e25d2bd6ebce323c9c">llvm::SectionKind::getData</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a2d7d72e2fddb81783b50ad05b746bc19">llvm::TargetLoweringObjectFile::getKindForGlobal</a>, <a href="#a2ddf5387f9cd603891e1933c2f84cf65">getSectionForExternalReference</a>, <a href="#adee710107b7fec9dcf8076bd0dc44d2d">getSectionForFunctionDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a530d168e733ea6e9f298d3f22dcee93d">llvm::SectionKind::isBSSLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a911975a33944b0773374a1e0eedf05a4">llvm::SectionKind::isText</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a14071b73bc38df9556c17bb05769223a">llvm::SectionKind::isThreadBSSLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#afff8f24c3c3553fc64f4661de4b494ff">llvm::TargetLoweringObjectFile::SectionForGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a4ef15b6d500629e31fb3787b7a0d7bb0">llvm::TargetLoweringObjectFile::TM</a>.</p>

</div>
</div>

### Initialize() {#a1bf32141c5a35cf431382b87f661175d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetLoweringObjectFileXCOFF::Initialize (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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


<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">TargetLoweringObjectFileImpl.h</a>, definition at line 2582 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#ab7083905b99d9b99558408bc3c4258d7">llvm::TargetLoweringObjectFile::CallSiteEncoding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255a0e91cc214494d9c9f9c8adcf03be6e51">llvm::dwarf::DW_EH_PE_datarel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ac859bd9ec26a2398dd13f4f9262f0595">llvm::dwarf::DW_EH_PE_indirect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255a68bcc7d64ea60cf76503e913360e0b01">llvm::dwarf::DW_EH_PE_sdata4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ab4f228eae8e91cb5eb218c4372d2cd75">llvm::dwarf::DW_EH_PE_sdata8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255abfafdba601fd5cab55113f2cdb96c033">llvm::dwarf::DW_EH_PE_udata4</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a33fe94054a904130a7c774f78423c8b7">llvm::TargetMachine::getTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a61a9950a12d517382dd40feb73973aea">llvm::TargetLoweringObjectFile::Initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a5f731b828cdcc60463ae559727393f30">llvm::TargetLoweringObjectFile::LSDAEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a164b617295bf723fe55723195171a46c">llvm::TargetLoweringObjectFile::PersonalityEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a41b7ef3f8dfda6e2083314d26c57764c">llvm::TargetLoweringObjectFile::SupportDebugThreadLocalLocation</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#aab96a7026012e54b4d0fb40465b0515e">llvm::TargetLoweringObjectFile::TTypeEncoding</a>.</p>

</div>
</div>

### lowerRelativeReference() {#a54fef84d5923e0eae22f02f8836487ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * TargetLoweringObjectFileXCOFF::lowerRelativeReference (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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



<p>Declaration at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">TargetLoweringObjectFileImpl.h</a>, definition at line 2611 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a4ef15b6d500629e31fb3787b7a0d7bb0">llvm::TargetLoweringObjectFile::TM</a>.</p>

</div>
</div>

### SelectSectionForGlobal() {#afa6dda813be79bdc7753ef52b9b5ec56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * TargetLoweringObjectFileXCOFF::SelectSectionForGlobal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> * GO, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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



<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">TargetLoweringObjectFileImpl.h</a>, definition at line 2448 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#affe937af7bd751518ed18a8d3e34c687">llvm::MCObjectFileInfo::DataSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#afcda39b4059eca86c10397b7a938a729">llvm::MCObjectFileInfo::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a587678b6051996e25d2bd6ebce323c9c">llvm::SectionKind::getData</a>, <a href="#a3e40bda8245f90bbe4a72d083b4d8431">getFunctionEntryPointSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a05a26c90a4811f2e63a64f0c3660ae09">llvm::TargetLoweringObjectFile::getNameWithPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#af4b0b8bc19062c7b0195fc7239c4dbea">llvm::SectionKind::getReadOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a435597fd04ebfd9b5fb5708a4309febb">llvm::MCContext::getXCOFFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ac10ac4576e030b231e1fbb5a8272f01f">llvm::GlobalValue::hasCommonLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#ac01fb290af1907633ce3c08fa92b25e7">llvm::MCObjectFileInfo::ReadOnlySection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a293288e990da3ee0cd54c7c340e33030">llvm::MCObjectFileInfo::TextSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a2ff225c3f7de6dd8cd9162f786493529">llvm::MCObjectFileInfo::TLSDataSection</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a4ef15b6d500629e31fb3787b7a0d7bb0">llvm::TargetLoweringObjectFile::TM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502cadc9c6c9efab40595101d1c98cb7bb4de">llvm::XCOFF::XMC_BS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502ca8013b2bcd044df8d46c49e8b96eb9a52">llvm::XCOFF::XMC_RO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502ca54b665a90facd18af1df67a6cf1194d5">llvm::XCOFF::XMC_RW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502caa250286dfb78ab47b0ba96d5b0f9bc51">llvm::XCOFF::XMC_TD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502ca58bcd5a7d086b06a4971a18c4596e711">llvm::XCOFF::XMC_TL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502cab35fc11d2968b541a2442c6138a1ba09">llvm::XCOFF::XMC_UL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ae6213556e13de39091f6861f199d7b1fa533de1d99e6b391e90e30a38b9e3a954">llvm::XCOFF::XTY_CM</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ae6213556e13de39091f6861f199d7b1fabc703e0e4100086f310d23f214a3cf03">llvm::XCOFF::XTY_SD</a>.</p>

</div>
</div>

### shouldPutJumpTableInFunctionSection() {#a40fe0525283caf34c373b1beaaf90b05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetLoweringObjectFileXCOFF::shouldPutJumpTableInFunctionSection (bool UsesLabelDifference, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Declaration at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">TargetLoweringObjectFileImpl.h</a>, definition at line 2555 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getEHInfoTableSymbol() {#a5d1987fcd07a91cbecea1c8ea8f174d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * TargetLoweringObjectFileXCOFF::getEHInfoTableSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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



<p>Declaration at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">TargetLoweringObjectFileImpl.h</a>, definition at line 2339 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a752546c51633c140d9ca4ab98b4781b6">llvm::MachineFunction::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a28a68f98b1944a3a50635a007c3c3907">llvm::MachineFunction::getFunctionNumber</a> and <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ac11eef690074972378846024abbe8722">llvm::MCContext::getOrCreateSymbol</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a510ab470dd00d91fa971cc403b09a5ec">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitFunctionBodyEnd</a>.</p>

</div>
</div>

### getStorageClassForGlobal() {#a79b16b25c08c277de4d27f75a22f95e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XCOFF::StorageClass TargetLoweringObjectFileXCOFF::getStorageClassForGlobal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
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



<p>Declaration at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">TargetLoweringObjectFileImpl.h</a>, definition at line 2619 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca96ad6314ba9210b223b93dc3e15baf99">llvm::GlobalValue::AppendingLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caa67f293befacbbf974525116ccf2ff42">llvm::GlobalValue::AvailableExternallyLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a19f57c169e86a4332accccf291954261">llvm::XCOFF::C_EXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70aeffba1492a002e3d506d9eca64672a24">llvm::XCOFF::C_HIDEXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a8f5d26c17483f47bf923e263a4de4c2e">llvm::XCOFF::C_WEAKEXT</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca08c6a63ca3d9cdb39fb584655bf5c501">llvm::GlobalValue::CommonLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caa81fc8db28ac4af45766fbab2e79d466">llvm::GlobalValue::ExternalWeakLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3547d58a060ee2e4a29cbea85bef91af">llvm::GlobalValue::getLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca5ebf288ceb5bbeb7025564727db6d705">llvm::GlobalValue::LinkOnceAnyLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caf2b592edf18170e7aff4e8f3bae3360c">llvm::GlobalValue::LinkOnceODRLinkage</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca04ed141708c0fd16723d212502b046ae">llvm::GlobalValue::PrivateLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca8d13a9bcecfac72febceb1103afa048f">llvm::GlobalValue::WeakAnyLinkage</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca696bb1c9b0b0e76bb70c61f68866452a">llvm::GlobalValue::WeakODRLinkage</a>.</p>

</div>
</div>

### ShouldEmitEHBlock() {#afa217c0d4fe1f12c81f44863f2a37b06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetLoweringObjectFileXCOFF::ShouldEmitEHBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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



<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">TargetLoweringObjectFileImpl.h</a>, definition at line 2309 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d508f23e2580095561902c39911fb9b">llvm::classifyEHPersonality</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa3fd81545fc9f10418752ee043f8645f">llvm::MachineFunction::getLandingPads</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a53aef6c19072ac0d22e5d5820898733f">llvm::isNoOpWithoutInvoke</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a510ab470dd00d91fa971cc403b09a5ec">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitFunctionBodyEnd</a> and <a href="/web-llvm/docs/api/classes/llvm/aixexception/#a1e6ef18a51de2a6db89efe13415ccb32">llvm::AIXException::endFunction</a>.</p>

</div>
</div>

### ShouldSetSSPCanaryBitInTB() {#a0feea92aabe11ff92dddf017ec2ef4e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TargetLoweringObjectFileXCOFF::ShouldSetSSPCanaryBitInTB (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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



<p>Declaration at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">TargetLoweringObjectFileImpl.h</a>, definition at line 2327 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">TargetLoweringObjectFileImpl.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
