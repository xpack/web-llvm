---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarfcfiexception
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DwarfCFIException` Class



## Declaration

<div class="doxyDeclaration">
class llvm::DwarfCFIException { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexception-h">CodeGen/AsmPrinter/DwarfException.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ehstreamer">EHStreamer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits exception handling directives. <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7b960a20f8d91ff62d697bae1a4d921">DwarfCFIException</a> (AsmPrinter *A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46d70cf0c3e5b5acfaab7003d203a6a5">~DwarfCFIException</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96fc5ffe2ecf42de68fc799201ad72d7">endModule</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit all exception information that should come after the content. <a href="#a96fc5ffe2ecf42de68fc799201ad72d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2d29f19a7e1b49d4ecf82154691a33d">beginFunction</a> (const MachineFunction *MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gather pre-function exception information. <a href="#af2d29f19a7e1b49d4ecf82154691a33d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9426a42a3f02c0367711fb8f3ebbb297">endFunction</a> (const MachineFunction *) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gather and emit post-function exception information. <a href="#a9426a42a3f02c0367711fb8f3ebbb297">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a39b36e2558580b82448046a957b229">beginBasicBlockSection</a> (const MachineBasicBlock &amp;MBB) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> the beginning of a new basic-block-section within a function. <a href="#a4a39b36e2558580b82448046a957b229">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43ad56f21d39d07911749e59241bffd3">endBasicBlockSection</a> (const MachineBasicBlock &amp;MBB) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> the end of a basic-block-section within a function. <a href="#a43ad56f21d39d07911749e59241bffd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c92d5748d1a86f1ef17e5b883a7b73f">addPersonality</a> (const GlobalValue *Personality)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b28bd2c77e48c5c415338c865590f86">shouldEmitPersonality</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Per-function flag to indicate if .cfi_personality should be emitted. <a href="#a2b28bd2c77e48c5c415338c865590f86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bdde1580e244b3858691b5c077a0121">forceEmitPersonality</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Per-function flag to indicate if .cfi_personality must be emitted. <a href="#a3bdde1580e244b3858691b5c077a0121">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0304a63f65789c9657f039c3e4c9181b">shouldEmitLSDA</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Per-function flag to indicate if .cfi_lsda should be emitted. <a href="#a0304a63f65789c9657f039c3e4c9181b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d0b1040601030cf6c431a7ffac5d069">shouldEmitCFI</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Per-function flag to indicate if frame CFI info should be emitted. <a href="#a4d0b1040601030cf6c431a7ffac5d069">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acda3c0ec7810541eb5e927e080106dc3">hasEmittedCFISections</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Per-module flag to indicate if .cfi_section has beeen emitted. <a href="#acda3c0ec7810541eb5e927e080106dc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3de64016635ef1fe62241bc745d8e44d">Personalities</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vector of all personality functions seen so far in the module. <a href="#a3de64016635ef1fe62241bc745d8e44d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexception-h">DwarfException.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DwarfCFIException() {#ae7b960a20f8d91ff62d697bae1a4d921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfCFIException::DwarfCFIException (<a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexception-h">DwarfException.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcfiexception-cpp">DwarfCFIException.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#ae951249a56bafbb7b57c4f571f9b4a3a">llvm::EHStreamer::EHStreamer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DwarfCFIException() {#a46d70cf0c3e5b5acfaab7003d203a6a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DwarfCFIException::~DwarfCFIException ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexception-h">DwarfException.h</a>.</p>


<p>References <a href="#a4a39b36e2558580b82448046a957b229">beginBasicBlockSection</a>, <a href="#af2d29f19a7e1b49d4ecf82154691a33d">beginFunction</a>, <a href="#a43ad56f21d39d07911749e59241bffd3">endBasicBlockSection</a>, <a href="#a9426a42a3f02c0367711fb8f3ebbb297">endFunction</a>, <a href="#a96fc5ffe2ecf42de68fc799201ad72d7">endModule</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### beginBasicBlockSection() {#a4a39b36e2558580b82448046a957b229}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCFIException::beginBasicBlockSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> the beginning of a new basic-block-section within a function.</p>


<p>Always called immediately after beginFunction for the first basic-block. When basic-block-sections are enabled, called before the first block of each such section.</p>


<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexception-h">DwarfException.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcfiexception-cpp">DwarfCFIException.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a346d40526a13ec03f632cd9fd1b51ca9">llvm::EHStreamer::Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#af13923757ac4e6379f33a942c8e57295aa603905470e2a5b8c13e96b579ef0dba">llvm::AsmPrinter::Debug</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#af13923757ac4e6379f33a942c8e57295a088a2013906137902c9832d2f5a3a940">llvm::AsmPrinter::EH</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a5603bcae76f2c812e71b8eecf54a7104">llvm::TargetLoweringObjectFile::getCFIPersonalitySymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a504aef9e44f9b0eb4531479466587ca4">llvm::TargetLoweringObjectFile::getLSDAEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a6a79201edcd6ca5c3159c17b20dfe273">llvm::TargetLoweringObjectFile::getPersonalityEncoding</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a8cb51f746d76c12843c38bba07e25377">llvm::EHStreamer::MMI</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#a46d70cf0c3e5b5acfaab7003d203a6a5">~DwarfCFIException</a>.</p>

</div>
</div>

### beginFunction() {#af2d29f19a7e1b49d4ecf82154691a33d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCFIException::beginFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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

<p>Gather pre-function exception information.</p>


<p>Assumes being emitted immediately after the function entry point.</p>


<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexception-h">DwarfException.h</a>, definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcfiexception-cpp">DwarfCFIException.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a346d40526a13ec03f632cd9fd1b51ca9">llvm::EHStreamer::Asm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d508f23e2580095561902c39911fb9b">llvm::classifyEHPersonality</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255af88641d07cb5fdb688ad0d4e78314222">llvm::dwarf::DW_EH_PE_omit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aa3beac794c4afb5b1fb6d06cb7786587">llvm::MCContext::getAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a752546c51633c140d9ca4ab98b4781b6">llvm::MachineFunction::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#af2741cb32381997a1e0f074f63d977ae">llvm::MCAsmInfo::getExceptionHandlingType</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa3fd81545fc9f10418752ee043f8645f">llvm::MachineFunction::getLandingPads</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a504aef9e44f9b0eb4531479466587ca4">llvm::TargetLoweringObjectFile::getLSDAEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a6a79201edcd6ca5c3159c17b20dfe273">llvm::TargetLoweringObjectFile::getPersonalityEncoding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a53aef6c19072ac0d22e5d5820898733f">llvm::isNoOpWithoutInvoke</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#af13923757ac4e6379f33a942c8e57295a6adf97f83acf6453d4a6a4b1070f3754">llvm::AsmPrinter::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a7d1990d31ae8e1811a57705c8a52d140">llvm::MCAsmInfo::usesCFIForEH</a>.</p>


<p>Referenced by <a href="#a46d70cf0c3e5b5acfaab7003d203a6a5">~DwarfCFIException</a>.</p>

</div>
</div>

### endBasicBlockSection() {#a43ad56f21d39d07911749e59241bffd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCFIException::endBasicBlockSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> the end of a basic-block-section within a function.</p>


<p>When basic-block-sections are enabled, called after the last block in each such section (including the last section in the function). When basic-block-sections are disabled, called at the end of a function, immediately prior to markFunctionEnd.</p>


<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexception-h">DwarfException.h</a>, definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcfiexception-cpp">DwarfCFIException.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a346d40526a13ec03f632cd9fd1b51ca9">llvm::EHStreamer::Asm</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="#a46d70cf0c3e5b5acfaab7003d203a6a5">~DwarfCFIException</a>.</p>

</div>
</div>

### endFunction() {#a9426a42a3f02c0367711fb8f3ebbb297}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCFIException::endFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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

<p>Gather and emit post-function exception information.</p>


<p>endFunction - Gather and emit post-function exception information.</p>


<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexception-h">DwarfException.h</a>, definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcfiexception-cpp">DwarfCFIException.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a420cc4a7a63b33a52659768b133b5f1b">llvm::EHStreamer::emitExceptionTable</a>.</p>


<p>Referenced by <a href="#a46d70cf0c3e5b5acfaab7003d203a6a5">~DwarfCFIException</a>.</p>

</div>
</div>

### endModule() {#a96fc5ffe2ecf42de68fc799201ad72d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCFIException::endModule ()</td>
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

<p>Emit all exception information that should come after the content.</p>


<p>endModule - Emit all exception information that should come after the content.</p>


<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexception-h">DwarfException.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcfiexception-cpp">DwarfCFIException.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a346d40526a13ec03f632cd9fd1b51ca9">llvm::EHStreamer::Asm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ab4fde659cfd2ad21ef1920dca7f22255ac859bd9ec26a2398dd13f4f9262f0595">llvm::dwarf::DW_EH_PE_indirect</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#adf68c4286c958e3b8943fb177072e703">llvm::TargetLoweringObjectFile::emitPersonalityValue</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a6a79201edcd6ca5c3159c17b20dfe273">llvm::TargetLoweringObjectFile::getPersonalityEncoding</a>.</p>


<p>Referenced by <a href="#a46d70cf0c3e5b5acfaab7003d203a6a5">~DwarfCFIException</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addPersonality() {#a0c92d5748d1a86f1ef17e5b883a7b73f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfCFIException::addPersonality (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * Personality)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexception-h">DwarfException.h</a>, definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcfiexception-cpp">DwarfCFIException.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### forceEmitPersonality {#a3bdde1580e244b3858691b5c077a0121}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfCFIException::forceEmitPersonality = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Per-function flag to indicate if .cfi_personality must be emitted.</p>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexception-h">DwarfException.h</a>.</p>

</div>
</div>

### hasEmittedCFISections {#acda3c0ec7810541eb5e927e080106dc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfCFIException::hasEmittedCFISections = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Per-module flag to indicate if .cfi_section has beeen emitted.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexception-h">DwarfException.h</a>.</p>

</div>
</div>

### Personalities {#a3de64016635ef1fe62241bc745d8e44d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;const GlobalValue *&gt; llvm::DwarfCFIException::Personalities</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vector of all personality functions seen so far in the module.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexception-h">DwarfException.h</a>.</p>

</div>
</div>

### shouldEmitCFI {#a4d0b1040601030cf6c431a7ffac5d069}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfCFIException::shouldEmitCFI = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Per-function flag to indicate if frame CFI info should be emitted.</p>

<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexception-h">DwarfException.h</a>.</p>

</div>
</div>

### shouldEmitLSDA {#a0304a63f65789c9657f039c3e4c9181b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfCFIException::shouldEmitLSDA = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Per-function flag to indicate if .cfi_lsda should be emitted.</p>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexception-h">DwarfException.h</a>.</p>

</div>
</div>

### shouldEmitPersonality {#a2b28bd2c77e48c5c415338c865590f86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfCFIException::shouldEmitPersonality = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Per-function flag to indicate if .cfi_personality should be emitted.</p>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexception-h">DwarfException.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcfiexception-cpp">DwarfCFIException.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfexception-h">DwarfException.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
