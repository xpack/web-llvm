---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/targetregistry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `TargetRegistry` Struct

<p><a href="/web-llvm/docs/api/structs/llvm/targetregistry">TargetRegistry</a> - Generic interface to target specific features. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::TargetRegistry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83dab9de9ca6a733fcfbcf5cc1057894">TargetRegistry</a> ()=delete</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0dea2adf7c230e9226a20ecc348464e">printRegisteredTargetsForVersion</a> (raw_ostream &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>printRegisteredTargetsForVersion - Print the registered targets appropriately for inclusion in a tool's version output. <a href="#aa0dea2adf7c230e9226a20ecc348464e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Registry Access Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/targetregistry/iterator">iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1ae7fa8c7edcabe75a0fef8b6b91b98">targets</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85a69009ec328d5835241f56fb62cc6d">lookupTarget</a> (StringRef Triple, std::string &amp;Error)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>lookupTarget - Lookup a target based on a target triple. <a href="#a85a69009ec328d5835241f56fb62cc6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a9a7989eeb174879ae8581e33e61824">lookupTarget</a> (StringRef ArchName, Triple &amp;TheTriple, std::string &amp;Error)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>lookupTarget - Lookup a target based on an architecture name and a target triple. <a href="#a9a9a7989eeb174879ae8581e33e61824">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Target Registration Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb58373a69ea039dfcce69b9d1ba9ccb">RegisterTarget</a> (Target &amp;T, const char *Name, const char *ShortDesc, const char *BackendName, Target::ArchMatchFnTy ArchMatchFn, bool HasJIT=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/registertarget">RegisterTarget</a> - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> the given target. <a href="#abb58373a69ea039dfcce69b9d1ba9ccb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3af2448a3eae2807437e612c2334b58a">RegisterMCAsmInfo</a> (Target &amp;T, Target::MCAsmInfoCtorFnTy Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/registermcasminfo">RegisterMCAsmInfo</a> - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> implementation for the given target. <a href="#a3af2448a3eae2807437e612c2334b58a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3b434e41c37c5cf46a6c828c6590324">RegisterMCObjectFileInfo</a> (Target &amp;T, Target::MCObjectFileInfoCtorFnTy Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo">MCObjectFileInfo</a> implementation for the given target. <a href="#af3b434e41c37c5cf46a6c828c6590324">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abea956a9e4d1526501d68bee93470e53">RegisterMCInstrInfo</a> (Target &amp;T, Target::MCInstrInfoCtorFnTy Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/registermcinstrinfo">RegisterMCInstrInfo</a> - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> implementation for the given target. <a href="#abea956a9e4d1526501d68bee93470e53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a515b55c070d9124a373c062641765ed1">RegisterMCInstrAnalysis</a> (Target &amp;T, Target::MCInstrAnalysisCtorFnTy Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/registermcinstranalysis">RegisterMCInstrAnalysis</a> - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis">MCInstrAnalysis</a> implementation for the given target. <a href="#a515b55c070d9124a373c062641765ed1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0be8ffbacd90d86a1c1f27a032e2265e">RegisterMCRegInfo</a> (Target &amp;T, Target::MCRegInfoCtorFnTy Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/registermcreginfo">RegisterMCRegInfo</a> - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> implementation for the given target. <a href="#a0be8ffbacd90d86a1c1f27a032e2265e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a469331cb6070bffd3354391877547014">RegisterMCSubtargetInfo</a> (Target &amp;T, Target::MCSubtargetInfoCtorFnTy Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/registermcsubtargetinfo">RegisterMCSubtargetInfo</a> - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> implementation for the given target. <a href="#a469331cb6070bffd3354391877547014">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7abb11d1faa188e94cbe7b8aff7ca6c">RegisterTargetMachine</a> (Target &amp;T, Target::TargetMachineCtorTy Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/registertargetmachine">RegisterTargetMachine</a> - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> implementation for the given target. <a href="#aa7abb11d1faa188e94cbe7b8aff7ca6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a158db359a78dc87d4f7b2e96585b78ae">RegisterMCAsmBackend</a> (Target &amp;T, Target::MCAsmBackendCtorTy Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/registermcasmbackend">RegisterMCAsmBackend</a> - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> implementation for the given target. <a href="#a158db359a78dc87d4f7b2e96585b78ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a989e67da0496f15502f414d6b9891810">RegisterMCAsmParser</a> (Target &amp;T, Target::MCAsmParserCtorTy Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/registermcasmparser">RegisterMCAsmParser</a> - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser">MCTargetAsmParser</a> implementation for the given target. <a href="#a989e67da0496f15502f414d6b9891810">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c8d60c243575e4e3076756b51253385">RegisterAsmPrinter</a> (Target &amp;T, Target::AsmPrinterCtorTy Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/registerasmprinter">RegisterAsmPrinter</a> - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> an <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> implementation for the given target. <a href="#a0c8d60c243575e4e3076756b51253385">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d3c3e977776517a7c1a82060b16da9f">RegisterMCDisassembler</a> (Target &amp;T, Target::MCDisassemblerCtorTy Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RegisterMCDisassembler - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> implementation for the given target. <a href="#a8d3c3e977776517a7c1a82060b16da9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabd8e913cb341182f1ef8c24c25e50ad">RegisterMCInstPrinter</a> (Target &amp;T, Target::MCInstPrinterCtorTy Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RegisterMCInstPrinter - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a> implementation for the given target. <a href="#aabd8e913cb341182f1ef8c24c25e50ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e06603b238d255bf8d182eaa9e18c7a">RegisterMCCodeEmitter</a> (Target &amp;T, Target::MCCodeEmitterCtorTy Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/registermccodeemitter">RegisterMCCodeEmitter</a> - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> implementation for the given target. <a href="#a2e06603b238d255bf8d182eaa9e18c7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aade8ca8e50ff109c69a5953007ed18d7">RegisterCOFFStreamer</a> (Target &amp;T, Target::COFFStreamerCtorTy Fn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef0928a326d69d175d200274daa7303e">RegisterMachOStreamer</a> (Target &amp;T, Target::MachOStreamerCtorTy Fn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73452a801e9e22c8eac961cc7b598fe3">RegisterELFStreamer</a> (Target &amp;T, Target::ELFStreamerCtorTy Fn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a287265bb7705e8db447164b13444c85d">RegisterXCOFFStreamer</a> (Target &amp;T, Target::XCOFFStreamerCtorTy Fn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7829ce3a27ad6098c5997b933c8a42f9">RegisterNullTargetStreamer</a> (Target &amp;T, Target::NullTargetStreamerCtorTy Fn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5d003503498e90bccf7a5d1626e9af6">RegisterAsmTargetStreamer</a> (Target &amp;T, Target::AsmTargetStreamerCtorTy Fn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fb8d8db91a731340d7ce8dd79af8a70">RegisterObjectTargetStreamer</a> (Target &amp;T, Target::ObjectTargetStreamerCtorTy Fn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaad35464035e4f3cce37074ecb9698e">RegisterMCRelocationInfo</a> (Target &amp;T, Target::MCRelocationInfoCtorTy Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RegisterMCRelocationInfo - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> an <a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo">MCRelocationInfo</a> implementation for the given target. <a href="#afaad35464035e4f3cce37074ecb9698e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a47aba9e8635c85eef8e87912e87810">RegisterMCSymbolizer</a> (Target &amp;T, Target::MCSymbolizerCtorTy Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RegisterMCSymbolizer - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> an <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer">MCSymbolizer</a> implementation for the given target. <a href="#a0a47aba9e8635c85eef8e87912e87810">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedf9544809dabd3df6e329f3d79dbc31">RegisterCustomBehaviour</a> (Target &amp;T, Target::CustomBehaviourCtorTy Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RegisterCustomBehaviour - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a CustomBehaviour implementation for the given target. <a href="#aedf9544809dabd3df6e329f3d79dbc31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82742d6cae420864af2a90eaee015b8d">RegisterInstrPostProcess</a> (Target &amp;T, Target::InstrPostProcessCtorTy Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RegisterInstrPostProcess - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> an InstrPostProcess implementation for the given target. <a href="#a82742d6cae420864af2a90eaee015b8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedd553f3d07f89536fa2254cf9d52acc">RegisterInstrumentManager</a> (Target &amp;T, Target::InstrumentManagerCtorTy Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RegisterInstrumentManager - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> an InstrumentManager implementation for the given target. <a href="#aedd553f3d07f89536fa2254cf9d52acc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/structs/llvm/targetregistry">TargetRegistry</a> - Generic interface to target specific features.</p>

<p>Definition at line 641 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TargetRegistry() {#a83dab9de9ca6a733fcfbcf5cc1057894}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TargetRegistry::TargetRegistry ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### printRegisteredTargetsForVersion() {#aa0dea2adf7c230e9226a20ecc348464e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetRegistry::printRegisteredTargetsForVersion (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>printRegisteredTargetsForVersion - Print the registered targets appropriately for inclusion in a tool's version output.</p>

<p>Declaration at line 689 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>, definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/targetregistry-cpp">TargetRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#add1eb5637dd671428b6f138ed3db6428">llvm::array_pod_sort</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#ac6ca3b3b4350e97f01a52c70d15e83b5">llvm::Target::getShortDescription</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/targetregistry-cpp/#af1682dd0bdea3ecd4e9c5971ae1643f0">TargetArraySortFn</a> and <a href="#ad1ae7fa8c7edcabe75a0fef8b6b91b98">targets</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Registry Access

### lookupTarget {#a85a69009ec328d5835241f56fb62cc6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Target * TargetRegistry::lookupTarget (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Triple, std::string &amp; Error)</td>
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

<p>lookupTarget - Lookup a target based on a target triple.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/triple"&gt;Triple&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- The triple to use for finding a target.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/error"&gt;Error&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- On failure, an error string describing why no target was found.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 701 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>, definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/targetregistry-cpp">TargetRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5fc23559f17bbe5ff83ec0fed0a5fdcf">llvm::Triple::getArch</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#ad1ae7fa8c7edcabe75a0fef8b6b91b98">targets</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/thinltocodegeneratorimpl/targetmachinebuilder/#a057a55d2ecdfd54087c9d8ffbe9f9c2a">llvm::ThinLTOCodeGeneratorImpl::TargetMachineBuilder::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#abfc7ebfffc7baaf23279854fec1412ac">createTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilder/#ad851482024748222bc5538345ec2bd12">llvm::orc::JITTargetMachineBuilder::createTargetMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codegen/#a8f10e936389f0129adc2f5ded44fdd9a">llvm::codegen::createTargetMachineForTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfobjectfilebase/#ab5019ff9e3502f422f3d8668201f5756">llvm::object::ELFObjectFileBase::getPltEntries</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#a7472bfb367d052f75ef1e00fa660be70">llvm::dwarf_linker::classic::DwarfStreamer::init</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfemitterimpl/#a66fa607c96a11d3a9e973d33e733ac37">llvm::dwarf_linker::parallel::DwarfEmitterImpl::init</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a388c19dd51467226753e433499a85e44">initAndLookupTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/modulesymboltable-cpp/#af63cc4141d5da9ef88eb0ec4b2b3c959">initializeRecordStreamer</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga0ed319f9f853493c0b38e551ec2adfc5">LLVMCreateDisasmCPUFeatures</a>, <a href="/web-llvm/docs/api/groups/llvmctarget/#ga7a746a65818e0b6bd86e5f00a568e301">LLVMGetTargetFromTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#ad1c77f840dadc1ffb03432c9e688e4c6">llvm::logicalview::LVBinaryReader::loadGenericTargetInfo</a>, <a href="#a9a9a7989eeb174879ae8581e33e61824">lookupTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a7ef5bb146eb2c0e3a609a6a169ac4f44">llvm::EngineBuilder::selectTarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6d9c43797976f73bdbe0c75995f84865">llvm::SPIRVTranslate</a> and <a href="/web-llvm/docs/api/classes/llvm/bitcodewriter/#aaaca861df948bd93da0afb6891e9d662">llvm::BitcodeWriter::writeSymtab</a>.</p>

</div>
</div>

### lookupTarget {#a9a9a7989eeb174879ae8581e33e61824}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Target * TargetRegistry::lookupTarget (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ArchName, <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TheTriple, std::string &amp; Error)</td>
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

<p>lookupTarget - Lookup a target based on an architecture name and a target triple.</p>


<p>If the architecture name is non-empty, then the lookup is done by architecture. Otherwise, the target triple is used.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ArchName</td>
<td class="doxyParamItemDescription"><p>- The architecture to use for finding a target.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TheTriple</td>
<td class="doxyParamItemDescription"><p>- The triple to use for finding a target. The triple is updated with canonical architecture name if a lookup by architecture is done.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/error"&gt;Error&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- On failure, an error string describing why no target was found.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 714 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>, definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/targetregistry-cpp">TargetRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5d5efe3bb966ce825560b2e6dd46f8ec">llvm::Triple::getArchTypeForLLVMName</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a7bc9985614536143e793244dfb66028c">llvm::Triple::getTriple</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a85a69009ec328d5835241f56fb62cc6d">lookupTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#af70f4019638c4a7cccaaad403c25c048">llvm::Triple::setArch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="#ad1ae7fa8c7edcabe75a0fef8b6b91b98">targets</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5b44ea359fcb23c7b1bfdc029979614c">llvm::Triple::UnknownArch</a>.</p>

</div>
</div>

### targets {#ad1ae7fa8c7edcabe75a0fef8b6b91b98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; TargetRegistry::iterator &gt; TargetRegistry::targets ()</td>
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



<p>Declaration at line 694 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/targetregistry-cpp">TargetRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/mc/targetregistry-cpp/#a3f7b8ead5d8f67255b04b0a7b0e87405">FirstTarget</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmctarget/#ga14fa4ed2b3cf4ff0012d7598e66e89ec">LLVMGetFirstTarget</a>, <a href="/web-llvm/docs/api/groups/llvmctarget/#ga57bc27c27706c0ee7a36152ff7f65a56">LLVMGetTargetFromName</a>, <a href="#a9a9a7989eeb174879ae8581e33e61824">lookupTarget</a>, <a href="#a85a69009ec328d5835241f56fb62cc6d">lookupTarget</a>, <a href="#aa0dea2adf7c230e9226a20ecc348464e">printRegisteredTargetsForVersion</a> and <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a7ef5bb146eb2c0e3a609a6a169ac4f44">llvm::EngineBuilder::selectTarget</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Target Registration

### RegisterAsmPrinter {#a0c8d60c243575e4e3076756b51253385}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterAsmPrinter (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#adca9c871226ade6697c7b13e20e21580">Target::AsmPrinterCtorTy</a> Fn)</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/registerasmprinter">RegisterAsmPrinter</a> - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> an <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> implementation for the given target.</p>


<p>Clients are responsible for ensuring that registration doesn't occur while another thread is attempting to access the registry. Typically this is done by initializing all targets at program startup.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">T</td>
<td class="doxyParamItemDescription"><p>- The target being registered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Fn</td>
<td class="doxyParamItemDescription"><p>- A function to construct an <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> for the target.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 865 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuasmprinter-cpp/#a049a1d1af4ce3deb01a0fa15121de758">LLVMInitializeAMDGPUAsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#a463d61a5d359ec3dfb5a80cc4c1a9aae">LLVMInitializePowerPCAsmPrinter</a> and <a href="/web-llvm/docs/api/structs/llvm/registerasmprinter/#a5630fc1077a8c30cf6772b6538637041">llvm::RegisterAsmPrinter&lt; AsmPrinterImpl &gt;::RegisterAsmPrinter</a>.</p>

</div>
</div>

### RegisterAsmTargetStreamer {#af5d003503498e90bccf7a5d1626e9af6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterAsmTargetStreamer (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#a4f02ea797774ee98efc46489b1df8350">Target::AsmTargetStreamerCtorTy</a> Fn)</td>
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



<p>Definition at line 930 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#ac6cc590ea14328605b961daf062e51e8">LLVMInitializeAArch64TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumctargetdesc-cpp/#af6847ab00bc2a1f50ce559aaaeda2d0d">LLVMInitializeAMDGPUTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcmctargetdesc-cpp/#a5a2a9b7766a908fa2b912fef81c25849">LLVMInitializeARCTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a3d8bf90e641f417abcb5fcfe8685ecf8">LLVMInitializeARMTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmctargetdesc-cpp/#a6fbdffb36fc945879f1a767060c51e2c">LLVMInitializeAVRTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymctargetdesc-cpp/#a6f6d3c84199337a3cac544c658fe1106">LLVMInitializeCSKYTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#a98a868de586290904766e4922d3e870b">LLVMInitializeHexagonTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmctargetdesc-cpp/#a45bfbd633beacf42b102d7b0103a0d4c">LLVMInitializeLoongArchTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmctargetdesc-cpp/#a32aa9aae9369c8b517be80ffecbc711c">LLVMInitializeMipsTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxmctargetdesc-cpp/#a6cc0e9f51ef7d135cc855521020d9c08">LLVMInitializeNVPTXTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp/#a7355d88f591aa5dd5f1d812ea99218ec">LLVMInitializePowerPCTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmctargetdesc-cpp/#a1e93b89ed4a5f8e3974124fedfcf4b27">LLVMInitializeRISCVTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmctargetdesc-cpp/#a8c9015b70cac029d8b59b9331d506300">LLVMInitializeSparcTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvmctargetdesc-cpp/#a9615460be0935d2aab84ea024c2d821b">LLVMInitializeSPIRVTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmctargetdesc-cpp/#abbf3c4fe1fddd6f8c4afe905d4122929">LLVMInitializeSystemZTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemctargetdesc-cpp/#aa17f62e3150eef038e4a6d3fb31d2af3">LLVMInitializeVETargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-cpp/#a0f83ad11a759c56547fd4b239e605f5e">LLVMInitializeWebAssemblyTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#ab1904658c919a9d143695cabebd68f53">LLVMInitializeX86TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/mctargetdesc/xcoremctargetdesc-cpp/#a252ba3ed8208cac6aff7149891cc9c4a">LLVMInitializeXCoreTargetMC</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensamctargetdesc-cpp/#ad9def10e0f63f81dd8a4d3e2316f4795">LLVMInitializeXtensaTargetMC</a>.</p>

</div>
</div>

### RegisterCOFFStreamer {#aade8ca8e50ff109c69a5953007ed18d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterCOFFStreamer (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#a4ddfc1e7a4084500bc92a086a7dab3df">Target::COFFStreamerCtorTy</a> Fn)</td>
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



<p>Definition at line 909 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#ac6cc590ea14328605b961daf062e51e8">LLVMInitializeAArch64TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a3d8bf90e641f417abcb5fcfe8685ecf8">LLVMInitializeARMTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmctargetdesc-cpp/#a32aa9aae9369c8b517be80ffecbc711c">LLVMInitializeMipsTargetMC</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#ab1904658c919a9d143695cabebd68f53">LLVMInitializeX86TargetMC</a>.</p>

</div>
</div>

### RegisterCustomBehaviour {#aedf9544809dabd3df6e329f3d79dbc31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterCustomBehaviour (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#a8011a7ecf12feff066c1b6f2095f9b6d">Target::CustomBehaviourCtorTy</a> Fn)</td>
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

<p>RegisterCustomBehaviour - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a CustomBehaviour implementation for the given target.</p>


<p>Clients are responsible for ensuring that registration doesn't occur while another thread is attempting to access the registry. Typically this is done by initializing all targets at program startup.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">T</td>
<td class="doxyParamItemDescription"><p>- The target being registered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Fn</td>
<td class="doxyParamItemDescription"><p>- A function to construct a CustomBehaviour for the target.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 977 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-cpp/#abff2d688ab31b2b868abd61f30ff08d6">LLVMInitializeAMDGPUTargetMCA</a>.</p>

</div>
</div>

### RegisterELFStreamer {#a73452a801e9e22c8eac961cc7b598fe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterELFStreamer (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#af9bb9d7728ece754179abcfa58fe94d2">Target::ELFStreamerCtorTy</a> Fn)</td>
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



<p>Definition at line 917 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#ac6cc590ea14328605b961daf062e51e8">LLVMInitializeAArch64TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumctargetdesc-cpp/#af6847ab00bc2a1f50ce559aaaeda2d0d">LLVMInitializeAMDGPUTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a3d8bf90e641f417abcb5fcfe8685ecf8">LLVMInitializeARMTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmctargetdesc-cpp/#a6fbdffb36fc945879f1a767060c51e2c">LLVMInitializeAVRTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfmctargetdesc-cpp/#a57c49ae0d15b512ea03aa0c8bd297a45">LLVMInitializeBPFTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymctargetdesc-cpp/#a6f6d3c84199337a3cac544c658fe1106">LLVMInitializeCSKYTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#a98a868de586290904766e4922d3e870b">LLVMInitializeHexagonTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/mctargetdesc/lanaimctargetdesc-cpp/#a3c16773835d3cf48abb3332a6e735de6">LLVMInitializeLanaiTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmctargetdesc-cpp/#a45bfbd633beacf42b102d7b0103a0d4c">LLVMInitializeLoongArchTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmctargetdesc-cpp/#a32aa9aae9369c8b517be80ffecbc711c">LLVMInitializeMipsTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp/#a7355d88f591aa5dd5f1d812ea99218ec">LLVMInitializePowerPCTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmctargetdesc-cpp/#a1e93b89ed4a5f8e3974124fedfcf4b27">LLVMInitializeRISCVTargetMC</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#ab1904658c919a9d143695cabebd68f53">LLVMInitializeX86TargetMC</a>.</p>

</div>
</div>

### RegisterInstrPostProcess {#a82742d6cae420864af2a90eaee015b8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterInstrPostProcess (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#a0bb81212652860a7e5418351dcb2d5d6">Target::InstrPostProcessCtorTy</a> Fn)</td>
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

<p>RegisterInstrPostProcess - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> an InstrPostProcess implementation for the given target.</p>


<p>Clients are responsible for ensuring that registration doesn't occur while another thread is attempting to access the registry. Typically this is done by initializing all targets at program startup.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">T</td>
<td class="doxyParamItemDescription"><p>- The target being registered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Fn</td>
<td class="doxyParamItemDescription"><p>- A function to construct an InstrPostProcess for the target.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 991 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-cpp/#abff2d688ab31b2b868abd61f30ff08d6">LLVMInitializeAMDGPUTargetMCA</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mca/x86custombehaviour-cpp/#ad605a3a85d38e52ce2def870b0d02113">LLVMInitializeX86TargetMCA</a>.</p>

</div>
</div>

### RegisterInstrumentManager {#aedd553f3d07f89536fa2254cf9d52acc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterInstrumentManager (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#a0d4453ee8cbb971aa3132a67ee7d1131">Target::InstrumentManagerCtorTy</a> Fn)</td>
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

<p>RegisterInstrumentManager - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> an InstrumentManager implementation for the given target.</p>


<p>Clients are responsible for ensuring that registration doesn't occur while another thread is attempting to access the registry. Typically this is done by initializing all targets at program startup.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">T</td>
<td class="doxyParamItemDescription"><p>- The target being registered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Fn</td>
<td class="doxyParamItemDescription"><p>- A function to construct an InstrumentManager for the target.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1006 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mca/riscvcustombehaviour-cpp/#ad6c3b190f3ba99eb436c77c8ab194e78">LLVMInitializeRISCVTargetMCA</a>.</p>

</div>
</div>

### RegisterMachOStreamer {#aef0928a326d69d175d200274daa7303e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterMachOStreamer (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#a61a694976d191b3e94c01df7f3efab4b">Target::MachOStreamerCtorTy</a> Fn)</td>
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



<p>Definition at line 913 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#ac6cc590ea14328605b961daf062e51e8">LLVMInitializeAArch64TargetMC</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a3d8bf90e641f417abcb5fcfe8685ecf8">LLVMInitializeARMTargetMC</a>.</p>

</div>
</div>

### RegisterMCAsmBackend {#a158db359a78dc87d4f7b2e96585b78ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterMCAsmBackend (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#a43026d9c7072215fa3933cf0fc414708">Target::MCAsmBackendCtorTy</a> Fn)</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/registermcasmbackend">RegisterMCAsmBackend</a> - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> implementation for the given target.</p>


<p>Clients are responsible for ensuring that registration doesn't occur while another thread is attempting to access the registry. Typically this is done by initializing all targets at program startup.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">T</td>
<td class="doxyParamItemDescription"><p>- The target being registered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Fn</td>
<td class="doxyParamItemDescription"><p>- A function to construct an AsmBackend for the target.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 839 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#ac6cc590ea14328605b961daf062e51e8">LLVMInitializeAArch64TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumctargetdesc-cpp/#af6847ab00bc2a1f50ce559aaaeda2d0d">LLVMInitializeAMDGPUTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a3d8bf90e641f417abcb5fcfe8685ecf8">LLVMInitializeARMTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmctargetdesc-cpp/#a6fbdffb36fc945879f1a767060c51e2c">LLVMInitializeAVRTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfmctargetdesc-cpp/#a57c49ae0d15b512ea03aa0c8bd297a45">LLVMInitializeBPFTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymctargetdesc-cpp/#a6f6d3c84199337a3cac544c658fe1106">LLVMInitializeCSKYTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/mctargetdesc/directxmctargetdesc-cpp/#ae2650072c61d204c8fe4bc597fdc6672">LLVMInitializeDirectXTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#a98a868de586290904766e4922d3e870b">LLVMInitializeHexagonTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/mctargetdesc/lanaimctargetdesc-cpp/#a3c16773835d3cf48abb3332a6e735de6">LLVMInitializeLanaiTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmctargetdesc-cpp/#a45bfbd633beacf42b102d7b0103a0d4c">LLVMInitializeLoongArchTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kmctargetdesc-cpp/#a60d27d11f3d31ed0356606efc80102d0">LLVMInitializeM68kTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmctargetdesc-cpp/#a32aa9aae9369c8b517be80ffecbc711c">LLVMInitializeMipsTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/mctargetdesc/msp430mctargetdesc-cpp/#ae4728e7bd5eb4cc404ac5fbbbce5cec5">LLVMInitializeMSP430TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp/#a7355d88f591aa5dd5f1d812ea99218ec">LLVMInitializePowerPCTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmctargetdesc-cpp/#a1e93b89ed4a5f8e3974124fedfcf4b27">LLVMInitializeRISCVTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmctargetdesc-cpp/#a8c9015b70cac029d8b59b9331d506300">LLVMInitializeSparcTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvmctargetdesc-cpp/#a9615460be0935d2aab84ea024c2d821b">LLVMInitializeSPIRVTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmctargetdesc-cpp/#abbf3c4fe1fddd6f8c4afe905d4122929">LLVMInitializeSystemZTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemctargetdesc-cpp/#aa17f62e3150eef038e4a6d3fb31d2af3">LLVMInitializeVETargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-cpp/#a0f83ad11a759c56547fd4b239e605f5e">LLVMInitializeWebAssemblyTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#ab1904658c919a9d143695cabebd68f53">LLVMInitializeX86TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensamctargetdesc-cpp/#ad9def10e0f63f81dd8a4d3e2316f4795">LLVMInitializeXtensaTargetMC</a> and <a href="/web-llvm/docs/api/structs/llvm/registermcasmbackend/#ade05032ce74042169175c9b396c7ffdc">llvm::RegisterMCAsmBackend&lt; MCAsmBackendImpl &gt;::RegisterMCAsmBackend</a>.</p>

</div>
</div>

### RegisterMCAsmInfo {#a3af2448a3eae2807437e612c2334b58a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterMCAsmInfo (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#a0a7cbba18b8a0911bea364fd3f3451d5">Target::MCAsmInfoCtorFnTy</a> Fn)</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/registermcasminfo">RegisterMCAsmInfo</a> - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> implementation for the given target.</p>


<p>Clients are responsible for ensuring that registration doesn't occur while another thread is attempting to access the registry. Typically this is done by initializing all targets at program startup.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">T</td>
<td class="doxyParamItemDescription"><p>- The target being registered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Fn</td>
<td class="doxyParamItemDescription"><p>- A function to construct a <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> for the target.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 753 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymctargetdesc-cpp/#a6f6d3c84199337a3cac544c658fe1106">LLVMInitializeCSKYTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmctargetdesc-cpp/#a45bfbd633beacf42b102d7b0103a0d4c">LLVMInitializeLoongArchTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/mctargetdesc/msp430mctargetdesc-cpp/#ae4728e7bd5eb4cc404ac5fbbbce5cec5">LLVMInitializeMSP430TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmctargetdesc-cpp/#a1e93b89ed4a5f8e3974124fedfcf4b27">LLVMInitializeRISCVTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmctargetdesc-cpp/#abbf3c4fe1fddd6f8c4afe905d4122929">LLVMInitializeSystemZTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensamctargetdesc-cpp/#ad9def10e0f63f81dd8a4d3e2316f4795">LLVMInitializeXtensaTargetMC</a>, <a href="/web-llvm/docs/api/structs/llvm/registermcasminfo/#a8899c3123168c71a841789fc4b416bc1">llvm::RegisterMCAsmInfo&lt; MCAsmInfoImpl &gt;::RegisterMCAsmInfo</a> and <a href="/web-llvm/docs/api/structs/llvm/registermcasminfofn/#a3aa42e560a3b036302e3a0e20a4db6c5">llvm::RegisterMCAsmInfoFn::RegisterMCAsmInfoFn</a>.</p>

</div>
</div>

### RegisterMCAsmParser {#a989e67da0496f15502f414d6b9891810}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterMCAsmParser (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#af9a613f34829802f87fb3f5febb6507a">Target::MCAsmParserCtorTy</a> Fn)</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/registermcasmparser">RegisterMCAsmParser</a> - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser">MCTargetAsmParser</a> implementation for the given target.</p>


<p>Clients are responsible for ensuring that registration doesn't occur while another thread is attempting to access the registry. Typically this is done by initializing all targets at program startup.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">T</td>
<td class="doxyParamItemDescription"><p>- The target being registered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Fn</td>
<td class="doxyParamItemDescription"><p>- A function to construct an <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser">MCTargetAsmParser</a> for the target.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 852 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/registermcasmparser/#ab6919bc4a7aec5ed24784191cc70095b">llvm::RegisterMCAsmParser&lt; MCAsmParserImpl &gt;::RegisterMCAsmParser</a>.</p>

</div>
</div>

### RegisterMCCodeEmitter {#a2e06603b238d255bf8d182eaa9e18c7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterMCCodeEmitter (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#a1ad2dda902207f20a0d0dc24f65409d4">Target::MCCodeEmitterCtorTy</a> Fn)</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/registermccodeemitter">RegisterMCCodeEmitter</a> - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> implementation for the given target.</p>


<p>Clients are responsible for ensuring that registration doesn't occur while another thread is attempting to access the registry. Typically this is done by initializing all targets at program startup.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">T</td>
<td class="doxyParamItemDescription"><p>- The target being registered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Fn</td>
<td class="doxyParamItemDescription"><p>- A function to construct an <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> for the target.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 905 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#ac6cc590ea14328605b961daf062e51e8">LLVMInitializeAArch64TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumctargetdesc-cpp/#af6847ab00bc2a1f50ce559aaaeda2d0d">LLVMInitializeAMDGPUTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a3d8bf90e641f417abcb5fcfe8685ecf8">LLVMInitializeARMTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmctargetdesc-cpp/#a6fbdffb36fc945879f1a767060c51e2c">LLVMInitializeAVRTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfmctargetdesc-cpp/#a57c49ae0d15b512ea03aa0c8bd297a45">LLVMInitializeBPFTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymctargetdesc-cpp/#a6f6d3c84199337a3cac544c658fe1106">LLVMInitializeCSKYTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/mctargetdesc/directxmctargetdesc-cpp/#ae2650072c61d204c8fe4bc597fdc6672">LLVMInitializeDirectXTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#a98a868de586290904766e4922d3e870b">LLVMInitializeHexagonTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/mctargetdesc/lanaimctargetdesc-cpp/#a3c16773835d3cf48abb3332a6e735de6">LLVMInitializeLanaiTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmctargetdesc-cpp/#a45bfbd633beacf42b102d7b0103a0d4c">LLVMInitializeLoongArchTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kmctargetdesc-cpp/#a60d27d11f3d31ed0356606efc80102d0">LLVMInitializeM68kTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmctargetdesc-cpp/#a32aa9aae9369c8b517be80ffecbc711c">LLVMInitializeMipsTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/mctargetdesc/msp430mctargetdesc-cpp/#ae4728e7bd5eb4cc404ac5fbbbce5cec5">LLVMInitializeMSP430TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp/#a7355d88f591aa5dd5f1d812ea99218ec">LLVMInitializePowerPCTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmctargetdesc-cpp/#a1e93b89ed4a5f8e3974124fedfcf4b27">LLVMInitializeRISCVTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmctargetdesc-cpp/#a8c9015b70cac029d8b59b9331d506300">LLVMInitializeSparcTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvmctargetdesc-cpp/#a9615460be0935d2aab84ea024c2d821b">LLVMInitializeSPIRVTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmctargetdesc-cpp/#abbf3c4fe1fddd6f8c4afe905d4122929">LLVMInitializeSystemZTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemctargetdesc-cpp/#aa17f62e3150eef038e4a6d3fb31d2af3">LLVMInitializeVETargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-cpp/#a0f83ad11a759c56547fd4b239e605f5e">LLVMInitializeWebAssemblyTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#ab1904658c919a9d143695cabebd68f53">LLVMInitializeX86TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensamctargetdesc-cpp/#ad9def10e0f63f81dd8a4d3e2316f4795">LLVMInitializeXtensaTargetMC</a> and <a href="/web-llvm/docs/api/structs/llvm/registermccodeemitter/#a0c4ee554275c72dc666068145e36b430">llvm::RegisterMCCodeEmitter&lt; MCCodeEmitterImpl &gt;::RegisterMCCodeEmitter</a>.</p>

</div>
</div>

### RegisterMCDisassembler {#a8d3c3e977776517a7c1a82060b16da9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterMCDisassembler (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#a415b455751a15f39ce122ea02400618c">Target::MCDisassemblerCtorTy</a> Fn)</td>
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

<p>RegisterMCDisassembler - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> implementation for the given target.</p>


<p>Clients are responsible for ensuring that registration doesn't occur while another thread is attempting to access the registry. Typically this is done by initializing all targets at program startup.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">T</td>
<td class="doxyParamItemDescription"><p>- The target being registered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Fn</td>
<td class="doxyParamItemDescription"><p>- A function to construct an <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> for the target.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 878 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a937116e9c4a0863979038e9be05d1604">LLVMInitializeAArch64Disassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#abf297f3f63ca3282686b6b725d3ca818">LLVMInitializeAMDGPUDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#a87812879cf9b970b38668d2b1c1c7e46">LLVMInitializeARCDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa278d8e4687a87388f35b9d63569b3a4">LLVMInitializeARMDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#ae64f5d4662302ac25f4d9ab6e0f5e17a">LLVMInitializeAVRDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/disassembler/bpfdisassembler-cpp/#a68b7b81c8452fef2a2c55374b2c1020d">LLVMInitializeBPFDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#a4b8d70b11b38d66c590505c6e97990e3">LLVMInitializeCSKYDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a2a7be637e77772d13f3cb8976fd40e26">LLVMInitializeHexagonDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/disassembler/lanaidisassembler-cpp/#a58c788bf8078444aa61008a70c9d77c0">LLVMInitializeLanaiDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/disassembler/loongarchdisassembler-cpp/#a9c45f02a91fb54fb1f1f0ba8c4da1e77">LLVMInitializeLoongArchDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/disassembler/m68kdisassembler-cpp/#a663216d33b120b3f4c7e181ae055595d">LLVMInitializeM68kDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#af30d43c4117f5ef8cd82a778aa3ce38c">LLVMInitializeMipsDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp/#a5d7efe5f6d2d6b3e091d245b621d4450">LLVMInitializeMSP430Disassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/disassembler/ppcdisassembler-cpp/#a23e71205a1f02a8366a0530ec04e6f56">LLVMInitializePowerPCDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#ad982bc371e77bd90d8c3ef90909379a3">LLVMInitializeRISCVDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/disassembler/sparcdisassembler-cpp/#a597a1749b319b1320aa1987a804f636c">LLVMInitializeSparcDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/disassembler/systemzdisassembler-cpp/#a75dfd8bcdb5822d649b827b78a889992">LLVMInitializeSystemZDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp/#ad88a246e4481af7d20c2e1430b90a0d1">LLVMInitializeVEDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/disassembler/webassemblydisassembler-cpp/#a118b8ed070d1a870887631942629d39c">LLVMInitializeWebAssemblyDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ad94a7ec0e2ddf818814c86ab2eca39f0">LLVMInitializeX86Disassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#aae3a06bbf7034d74374c6acfe81f9bb1">LLVMInitializeXCoreDisassembler</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#a2f8ff26b6100f84d64aa1700205ad980">LLVMInitializeXtensaDisassembler</a>.</p>

</div>
</div>

### RegisterMCInstPrinter {#aabd8e913cb341182f1ef8c24c25e50ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterMCInstPrinter (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#af8d3098e1eb0b664f3f1b50909c57467">Target::MCInstPrinterCtorTy</a> Fn)</td>
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

<p>RegisterMCInstPrinter - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a> implementation for the given target.</p>


<p>Clients are responsible for ensuring that registration doesn't occur while another thread is attempting to access the registry. Typically this is done by initializing all targets at program startup.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">T</td>
<td class="doxyParamItemDescription"><p>- The target being registered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Fn</td>
<td class="doxyParamItemDescription"><p>- A function to construct an <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a> for the target.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 892 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#ac6cc590ea14328605b961daf062e51e8">LLVMInitializeAArch64TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumctargetdesc-cpp/#af6847ab00bc2a1f50ce559aaaeda2d0d">LLVMInitializeAMDGPUTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcmctargetdesc-cpp/#a5a2a9b7766a908fa2b912fef81c25849">LLVMInitializeARCTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a3d8bf90e641f417abcb5fcfe8685ecf8">LLVMInitializeARMTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmctargetdesc-cpp/#a6fbdffb36fc945879f1a767060c51e2c">LLVMInitializeAVRTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfmctargetdesc-cpp/#a57c49ae0d15b512ea03aa0c8bd297a45">LLVMInitializeBPFTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymctargetdesc-cpp/#a6f6d3c84199337a3cac544c658fe1106">LLVMInitializeCSKYTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/mctargetdesc/directxmctargetdesc-cpp/#ae2650072c61d204c8fe4bc597fdc6672">LLVMInitializeDirectXTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#a98a868de586290904766e4922d3e870b">LLVMInitializeHexagonTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/mctargetdesc/lanaimctargetdesc-cpp/#a3c16773835d3cf48abb3332a6e735de6">LLVMInitializeLanaiTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmctargetdesc-cpp/#a45bfbd633beacf42b102d7b0103a0d4c">LLVMInitializeLoongArchTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kmctargetdesc-cpp/#a60d27d11f3d31ed0356606efc80102d0">LLVMInitializeM68kTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmctargetdesc-cpp/#a32aa9aae9369c8b517be80ffecbc711c">LLVMInitializeMipsTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/mctargetdesc/msp430mctargetdesc-cpp/#ae4728e7bd5eb4cc404ac5fbbbce5cec5">LLVMInitializeMSP430TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxmctargetdesc-cpp/#a6cc0e9f51ef7d135cc855521020d9c08">LLVMInitializeNVPTXTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp/#a7355d88f591aa5dd5f1d812ea99218ec">LLVMInitializePowerPCTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmctargetdesc-cpp/#a1e93b89ed4a5f8e3974124fedfcf4b27">LLVMInitializeRISCVTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmctargetdesc-cpp/#a8c9015b70cac029d8b59b9331d506300">LLVMInitializeSparcTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvmctargetdesc-cpp/#a9615460be0935d2aab84ea024c2d821b">LLVMInitializeSPIRVTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmctargetdesc-cpp/#abbf3c4fe1fddd6f8c4afe905d4122929">LLVMInitializeSystemZTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemctargetdesc-cpp/#aa17f62e3150eef038e4a6d3fb31d2af3">LLVMInitializeVETargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-cpp/#a0f83ad11a759c56547fd4b239e605f5e">LLVMInitializeWebAssemblyTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#ab1904658c919a9d143695cabebd68f53">LLVMInitializeX86TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/mctargetdesc/xcoremctargetdesc-cpp/#a252ba3ed8208cac6aff7149891cc9c4a">LLVMInitializeXCoreTargetMC</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensamctargetdesc-cpp/#ad9def10e0f63f81dd8a4d3e2316f4795">LLVMInitializeXtensaTargetMC</a>.</p>

</div>
</div>

### RegisterMCInstrAnalysis {#a515b55c070d9124a373c062641765ed1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterMCInstrAnalysis (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#a700498ee2ebe75f1d1ed6454b8074455">Target::MCInstrAnalysisCtorFnTy</a> Fn)</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/registermcinstranalysis">RegisterMCInstrAnalysis</a> - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis">MCInstrAnalysis</a> implementation for the given target.</p>

<p>Definition at line 785 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#ac6cc590ea14328605b961daf062e51e8">LLVMInitializeAArch64TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumctargetdesc-cpp/#af6847ab00bc2a1f50ce559aaaeda2d0d">LLVMInitializeAMDGPUTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a3d8bf90e641f417abcb5fcfe8685ecf8">LLVMInitializeARMTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfmctargetdesc-cpp/#a57c49ae0d15b512ea03aa0c8bd297a45">LLVMInitializeBPFTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymctargetdesc-cpp/#a6f6d3c84199337a3cac544c658fe1106">LLVMInitializeCSKYTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#a98a868de586290904766e4922d3e870b">LLVMInitializeHexagonTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/mctargetdesc/lanaimctargetdesc-cpp/#a3c16773835d3cf48abb3332a6e735de6">LLVMInitializeLanaiTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmctargetdesc-cpp/#a45bfbd633beacf42b102d7b0103a0d4c">LLVMInitializeLoongArchTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmctargetdesc-cpp/#a32aa9aae9369c8b517be80ffecbc711c">LLVMInitializeMipsTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp/#a7355d88f591aa5dd5f1d812ea99218ec">LLVMInitializePowerPCTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmctargetdesc-cpp/#a1e93b89ed4a5f8e3974124fedfcf4b27">LLVMInitializeRISCVTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvmctargetdesc-cpp/#a9615460be0935d2aab84ea024c2d821b">LLVMInitializeSPIRVTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmctargetdesc-cpp/#abbf3c4fe1fddd6f8c4afe905d4122929">LLVMInitializeSystemZTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#ab1904658c919a9d143695cabebd68f53">LLVMInitializeX86TargetMC</a>, <a href="/web-llvm/docs/api/structs/llvm/registermcinstranalysis/#ad1f9e446fc852a74e8ff0ad5034635f0">llvm::RegisterMCInstrAnalysis&lt; MCInstrAnalysisImpl &gt;::RegisterMCInstrAnalysis</a> and <a href="/web-llvm/docs/api/structs/llvm/registermcinstranalysisfn/#a35c50dbf3c6bf48e9a28f7dcf4c73084">llvm::RegisterMCInstrAnalysisFn::RegisterMCInstrAnalysisFn</a>.</p>

</div>
</div>

### RegisterMCInstrInfo {#abea956a9e4d1526501d68bee93470e53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterMCInstrInfo (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#a7784e775d3c5b060da5dff2688a25c95">Target::MCInstrInfoCtorFnTy</a> Fn)</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/registermcinstrinfo">RegisterMCInstrInfo</a> - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> implementation for the given target.</p>


<p>Clients are responsible for ensuring that registration doesn't occur while another thread is attempting to access the registry. Typically this is done by initializing all targets at program startup.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">T</td>
<td class="doxyParamItemDescription"><p>- The target being registered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Fn</td>
<td class="doxyParamItemDescription"><p>- A function to construct a <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> for the target.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 779 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#ac6cc590ea14328605b961daf062e51e8">LLVMInitializeAArch64TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumctargetdesc-cpp/#af6847ab00bc2a1f50ce559aaaeda2d0d">LLVMInitializeAMDGPUTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcmctargetdesc-cpp/#a5a2a9b7766a908fa2b912fef81c25849">LLVMInitializeARCTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a3d8bf90e641f417abcb5fcfe8685ecf8">LLVMInitializeARMTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmctargetdesc-cpp/#a6fbdffb36fc945879f1a767060c51e2c">LLVMInitializeAVRTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfmctargetdesc-cpp/#a57c49ae0d15b512ea03aa0c8bd297a45">LLVMInitializeBPFTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymctargetdesc-cpp/#a6f6d3c84199337a3cac544c658fe1106">LLVMInitializeCSKYTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/mctargetdesc/directxmctargetdesc-cpp/#ae2650072c61d204c8fe4bc597fdc6672">LLVMInitializeDirectXTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#a98a868de586290904766e4922d3e870b">LLVMInitializeHexagonTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/mctargetdesc/lanaimctargetdesc-cpp/#a3c16773835d3cf48abb3332a6e735de6">LLVMInitializeLanaiTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmctargetdesc-cpp/#a45bfbd633beacf42b102d7b0103a0d4c">LLVMInitializeLoongArchTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kmctargetdesc-cpp/#a60d27d11f3d31ed0356606efc80102d0">LLVMInitializeM68kTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmctargetdesc-cpp/#a32aa9aae9369c8b517be80ffecbc711c">LLVMInitializeMipsTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/mctargetdesc/msp430mctargetdesc-cpp/#ae4728e7bd5eb4cc404ac5fbbbce5cec5">LLVMInitializeMSP430TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxmctargetdesc-cpp/#a6cc0e9f51ef7d135cc855521020d9c08">LLVMInitializeNVPTXTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp/#a7355d88f591aa5dd5f1d812ea99218ec">LLVMInitializePowerPCTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmctargetdesc-cpp/#a1e93b89ed4a5f8e3974124fedfcf4b27">LLVMInitializeRISCVTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmctargetdesc-cpp/#a8c9015b70cac029d8b59b9331d506300">LLVMInitializeSparcTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvmctargetdesc-cpp/#a9615460be0935d2aab84ea024c2d821b">LLVMInitializeSPIRVTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmctargetdesc-cpp/#abbf3c4fe1fddd6f8c4afe905d4122929">LLVMInitializeSystemZTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemctargetdesc-cpp/#aa17f62e3150eef038e4a6d3fb31d2af3">LLVMInitializeVETargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-cpp/#a0f83ad11a759c56547fd4b239e605f5e">LLVMInitializeWebAssemblyTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#ab1904658c919a9d143695cabebd68f53">LLVMInitializeX86TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/mctargetdesc/xcoremctargetdesc-cpp/#a252ba3ed8208cac6aff7149891cc9c4a">LLVMInitializeXCoreTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensamctargetdesc-cpp/#ad9def10e0f63f81dd8a4d3e2316f4795">LLVMInitializeXtensaTargetMC</a>, <a href="/web-llvm/docs/api/structs/llvm/registermcinstrinfo/#afb27724349d4ed9372dfac2e1582c968">llvm::RegisterMCInstrInfo&lt; MCInstrInfoImpl &gt;::RegisterMCInstrInfo</a> and <a href="/web-llvm/docs/api/structs/llvm/registermcinstrinfofn/#a649b0120e569402645b01f8e6a98d1a3">llvm::RegisterMCInstrInfoFn::RegisterMCInstrInfoFn</a>.</p>

</div>
</div>

### RegisterMCObjectFileInfo {#af3b434e41c37c5cf46a6c828c6590324}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterMCObjectFileInfo (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#a393c1c83bc743826cdf2b3175fd5f7ac">Target::MCObjectFileInfoCtorFnTy</a> Fn)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo">MCObjectFileInfo</a> implementation for the given target.</p>


<p>Clients are responsible for ensuring that registration doesn't occur while another thread is attempting to access the registry. Typically this is done by initializing all targets at program startup.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">T</td>
<td class="doxyParamItemDescription"><p>- The target being registered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Fn</td>
<td class="doxyParamItemDescription"><p>- A function to construct a <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo">MCObjectFileInfo</a> for the target.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 765 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmctargetdesc-cpp/#a1e93b89ed4a5f8e3974124fedfcf4b27">LLVMInitializeRISCVTargetMC</a>, <a href="/web-llvm/docs/api/structs/llvm/registermcobjectfileinfo/#a57f9aed5a8f464bca81515bae608e479">llvm::RegisterMCObjectFileInfo&lt; MCObjectFileInfoImpl &gt;::RegisterMCObjectFileInfo</a> and <a href="/web-llvm/docs/api/structs/llvm/registermcobjectfileinfofn/#a1a6270dc980b027fb5685359ec8191f0">llvm::RegisterMCObjectFileInfoFn::RegisterMCObjectFileInfoFn</a>.</p>

</div>
</div>

### RegisterMCRegInfo {#a0be8ffbacd90d86a1c1f27a032e2265e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterMCRegInfo (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#a75a0ab6413b8ed39da567eeb7810f9f1">Target::MCRegInfoCtorFnTy</a> Fn)</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/registermcreginfo">RegisterMCRegInfo</a> - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> implementation for the given target.</p>


<p>Clients are responsible for ensuring that registration doesn't occur while another thread is attempting to access the registry. Typically this is done by initializing all targets at program startup.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">T</td>
<td class="doxyParamItemDescription"><p>- The target being registered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Fn</td>
<td class="doxyParamItemDescription"><p>- A function to construct a <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> for the target.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 799 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#ac6cc590ea14328605b961daf062e51e8">LLVMInitializeAArch64TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumctargetdesc-cpp/#af6847ab00bc2a1f50ce559aaaeda2d0d">LLVMInitializeAMDGPUTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcmctargetdesc-cpp/#a5a2a9b7766a908fa2b912fef81c25849">LLVMInitializeARCTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a3d8bf90e641f417abcb5fcfe8685ecf8">LLVMInitializeARMTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmctargetdesc-cpp/#a6fbdffb36fc945879f1a767060c51e2c">LLVMInitializeAVRTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfmctargetdesc-cpp/#a57c49ae0d15b512ea03aa0c8bd297a45">LLVMInitializeBPFTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymctargetdesc-cpp/#a6f6d3c84199337a3cac544c658fe1106">LLVMInitializeCSKYTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/mctargetdesc/directxmctargetdesc-cpp/#ae2650072c61d204c8fe4bc597fdc6672">LLVMInitializeDirectXTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#a98a868de586290904766e4922d3e870b">LLVMInitializeHexagonTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/mctargetdesc/lanaimctargetdesc-cpp/#a3c16773835d3cf48abb3332a6e735de6">LLVMInitializeLanaiTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmctargetdesc-cpp/#a45bfbd633beacf42b102d7b0103a0d4c">LLVMInitializeLoongArchTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kmctargetdesc-cpp/#a60d27d11f3d31ed0356606efc80102d0">LLVMInitializeM68kTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmctargetdesc-cpp/#a32aa9aae9369c8b517be80ffecbc711c">LLVMInitializeMipsTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/mctargetdesc/msp430mctargetdesc-cpp/#ae4728e7bd5eb4cc404ac5fbbbce5cec5">LLVMInitializeMSP430TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxmctargetdesc-cpp/#a6cc0e9f51ef7d135cc855521020d9c08">LLVMInitializeNVPTXTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp/#a7355d88f591aa5dd5f1d812ea99218ec">LLVMInitializePowerPCTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmctargetdesc-cpp/#a1e93b89ed4a5f8e3974124fedfcf4b27">LLVMInitializeRISCVTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmctargetdesc-cpp/#a8c9015b70cac029d8b59b9331d506300">LLVMInitializeSparcTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvmctargetdesc-cpp/#a9615460be0935d2aab84ea024c2d821b">LLVMInitializeSPIRVTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmctargetdesc-cpp/#abbf3c4fe1fddd6f8c4afe905d4122929">LLVMInitializeSystemZTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemctargetdesc-cpp/#aa17f62e3150eef038e4a6d3fb31d2af3">LLVMInitializeVETargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-cpp/#a0f83ad11a759c56547fd4b239e605f5e">LLVMInitializeWebAssemblyTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#ab1904658c919a9d143695cabebd68f53">LLVMInitializeX86TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/mctargetdesc/xcoremctargetdesc-cpp/#a252ba3ed8208cac6aff7149891cc9c4a">LLVMInitializeXCoreTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensamctargetdesc-cpp/#ad9def10e0f63f81dd8a4d3e2316f4795">LLVMInitializeXtensaTargetMC</a>, <a href="/web-llvm/docs/api/structs/llvm/registermcreginfo/#afca5f376559984c3cb6fd88f54c40d55">llvm::RegisterMCRegInfo&lt; MCRegisterInfoImpl &gt;::RegisterMCRegInfo</a> and <a href="/web-llvm/docs/api/structs/llvm/registermcreginfofn/#ab40c8c3bf3b761518a7db459786d7f60">llvm::RegisterMCRegInfoFn::RegisterMCRegInfoFn</a>.</p>

</div>
</div>

### RegisterMCRelocationInfo {#afaad35464035e4f3cce37074ecb9698e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterMCRelocationInfo (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#a06a2eeff5612f9ee5509e1e2014ae52f">Target::MCRelocationInfoCtorTy</a> Fn)</td>
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

<p>RegisterMCRelocationInfo - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> an <a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo">MCRelocationInfo</a> implementation for the given target.</p>


<p>Clients are responsible for ensuring that registration doesn't occur while another thread is attempting to access the registry. Typically this is done by initializing all targets at program startup.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">T</td>
<td class="doxyParamItemDescription"><p>- The target being registered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Fn</td>
<td class="doxyParamItemDescription"><p>- A function to construct an <a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo">MCRelocationInfo</a> for the target.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 950 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a3d8bf90e641f417abcb5fcfe8685ecf8">LLVMInitializeARMTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/mctargetdesc/lanaimctargetdesc-cpp/#a3c16773835d3cf48abb3332a6e735de6">LLVMInitializeLanaiTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kmctargetdesc-cpp/#a60d27d11f3d31ed0356606efc80102d0">LLVMInitializeM68kTargetMC</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#ab1904658c919a9d143695cabebd68f53">LLVMInitializeX86TargetMC</a>.</p>

</div>
</div>

### RegisterMCSubtargetInfo {#a469331cb6070bffd3354391877547014}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterMCSubtargetInfo (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#a1056bfbe7e8c7721ae6cce94313350e3">Target::MCSubtargetInfoCtorFnTy</a> Fn)</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/registermcsubtargetinfo">RegisterMCSubtargetInfo</a> - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> implementation for the given target.</p>


<p>Clients are responsible for ensuring that registration doesn't occur while another thread is attempting to access the registry. Typically this is done by initializing all targets at program startup.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">T</td>
<td class="doxyParamItemDescription"><p>- The target being registered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Fn</td>
<td class="doxyParamItemDescription"><p>- A function to construct a <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> for the target.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 812 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#ac6cc590ea14328605b961daf062e51e8">LLVMInitializeAArch64TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumctargetdesc-cpp/#af6847ab00bc2a1f50ce559aaaeda2d0d">LLVMInitializeAMDGPUTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcmctargetdesc-cpp/#a5a2a9b7766a908fa2b912fef81c25849">LLVMInitializeARCTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a3d8bf90e641f417abcb5fcfe8685ecf8">LLVMInitializeARMTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmctargetdesc-cpp/#a6fbdffb36fc945879f1a767060c51e2c">LLVMInitializeAVRTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfmctargetdesc-cpp/#a57c49ae0d15b512ea03aa0c8bd297a45">LLVMInitializeBPFTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymctargetdesc-cpp/#a6f6d3c84199337a3cac544c658fe1106">LLVMInitializeCSKYTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/mctargetdesc/directxmctargetdesc-cpp/#ae2650072c61d204c8fe4bc597fdc6672">LLVMInitializeDirectXTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#a98a868de586290904766e4922d3e870b">LLVMInitializeHexagonTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/mctargetdesc/lanaimctargetdesc-cpp/#a3c16773835d3cf48abb3332a6e735de6">LLVMInitializeLanaiTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmctargetdesc-cpp/#a45bfbd633beacf42b102d7b0103a0d4c">LLVMInitializeLoongArchTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kmctargetdesc-cpp/#a60d27d11f3d31ed0356606efc80102d0">LLVMInitializeM68kTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmctargetdesc-cpp/#a32aa9aae9369c8b517be80ffecbc711c">LLVMInitializeMipsTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/mctargetdesc/msp430mctargetdesc-cpp/#ae4728e7bd5eb4cc404ac5fbbbce5cec5">LLVMInitializeMSP430TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxmctargetdesc-cpp/#a6cc0e9f51ef7d135cc855521020d9c08">LLVMInitializeNVPTXTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp/#a7355d88f591aa5dd5f1d812ea99218ec">LLVMInitializePowerPCTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmctargetdesc-cpp/#a1e93b89ed4a5f8e3974124fedfcf4b27">LLVMInitializeRISCVTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmctargetdesc-cpp/#a8c9015b70cac029d8b59b9331d506300">LLVMInitializeSparcTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvmctargetdesc-cpp/#a9615460be0935d2aab84ea024c2d821b">LLVMInitializeSPIRVTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmctargetdesc-cpp/#abbf3c4fe1fddd6f8c4afe905d4122929">LLVMInitializeSystemZTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemctargetdesc-cpp/#aa17f62e3150eef038e4a6d3fb31d2af3">LLVMInitializeVETargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-cpp/#a0f83ad11a759c56547fd4b239e605f5e">LLVMInitializeWebAssemblyTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#ab1904658c919a9d143695cabebd68f53">LLVMInitializeX86TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/mctargetdesc/xcoremctargetdesc-cpp/#a252ba3ed8208cac6aff7149891cc9c4a">LLVMInitializeXCoreTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensamctargetdesc-cpp/#ad9def10e0f63f81dd8a4d3e2316f4795">LLVMInitializeXtensaTargetMC</a>, <a href="/web-llvm/docs/api/structs/llvm/registermcsubtargetinfo/#a507775bfda70735863023325c56b4686">llvm::RegisterMCSubtargetInfo&lt; MCSubtargetInfoImpl &gt;::RegisterMCSubtargetInfo</a> and <a href="/web-llvm/docs/api/structs/llvm/registermcsubtargetinfofn/#af9c8f6069533f9e9497f8d08017178c5">llvm::RegisterMCSubtargetInfoFn::RegisterMCSubtargetInfoFn</a>.</p>

</div>
</div>

### RegisterMCSymbolizer {#a0a47aba9e8635c85eef8e87912e87810}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterMCSymbolizer (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#ab22797c3d4d9f28541b31bbd5999ddd1">Target::MCSymbolizerCtorTy</a> Fn)</td>
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

<p>RegisterMCSymbolizer - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> an <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer">MCSymbolizer</a> implementation for the given target.</p>


<p>Clients are responsible for ensuring that registration doesn't occur while another thread is attempting to access the registry. Typically this is done by initializing all targets at program startup.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">T</td>
<td class="doxyParamItemDescription"><p>- The target being registered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Fn</td>
<td class="doxyParamItemDescription"><p>- A function to construct an <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer">MCSymbolizer</a> for the target.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 964 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a937116e9c4a0863979038e9be05d1604">LLVMInitializeAArch64Disassembler</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#abf297f3f63ca3282686b6b725d3ca818">LLVMInitializeAMDGPUDisassembler</a>.</p>

</div>
</div>

### RegisterNullTargetStreamer {#a7829ce3a27ad6098c5997b933c8a42f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterNullTargetStreamer (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#a0943239d079f17f9648dc01f81896d72">Target::NullTargetStreamerCtorTy</a> Fn)</td>
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



<p>Definition at line 925 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#ac6cc590ea14328605b961daf062e51e8">LLVMInitializeAArch64TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumctargetdesc-cpp/#af6847ab00bc2a1f50ce559aaaeda2d0d">LLVMInitializeAMDGPUTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a3d8bf90e641f417abcb5fcfe8685ecf8">LLVMInitializeARMTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymctargetdesc-cpp/#a6f6d3c84199337a3cac544c658fe1106">LLVMInitializeCSKYTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#a98a868de586290904766e4922d3e870b">LLVMInitializeHexagonTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmctargetdesc-cpp/#a32aa9aae9369c8b517be80ffecbc711c">LLVMInitializeMipsTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxmctargetdesc-cpp/#a6cc0e9f51ef7d135cc855521020d9c08">LLVMInitializeNVPTXTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp/#a7355d88f591aa5dd5f1d812ea99218ec">LLVMInitializePowerPCTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmctargetdesc-cpp/#a1e93b89ed4a5f8e3974124fedfcf4b27">LLVMInitializeRISCVTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmctargetdesc-cpp/#a8c9015b70cac029d8b59b9331d506300">LLVMInitializeSparcTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmctargetdesc-cpp/#abbf3c4fe1fddd6f8c4afe905d4122929">LLVMInitializeSystemZTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemctargetdesc-cpp/#aa17f62e3150eef038e4a6d3fb31d2af3">LLVMInitializeVETargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-cpp/#a0f83ad11a759c56547fd4b239e605f5e">LLVMInitializeWebAssemblyTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#ab1904658c919a9d143695cabebd68f53">LLVMInitializeX86TargetMC</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/mctargetdesc/xcoremctargetdesc-cpp/#a252ba3ed8208cac6aff7149891cc9c4a">LLVMInitializeXCoreTargetMC</a>.</p>

</div>
</div>

### RegisterObjectTargetStreamer {#a4fb8d8db91a731340d7ce8dd79af8a70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterObjectTargetStreamer (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#a4e9d8a9646a89b1557207b43b6d80ad8">Target::ObjectTargetStreamerCtorTy</a> Fn)</td>
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



<p>Definition at line 936 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#ac6cc590ea14328605b961daf062e51e8">LLVMInitializeAArch64TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumctargetdesc-cpp/#af6847ab00bc2a1f50ce559aaaeda2d0d">LLVMInitializeAMDGPUTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a3d8bf90e641f417abcb5fcfe8685ecf8">LLVMInitializeARMTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmctargetdesc-cpp/#a6fbdffb36fc945879f1a767060c51e2c">LLVMInitializeAVRTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymctargetdesc-cpp/#a6f6d3c84199337a3cac544c658fe1106">LLVMInitializeCSKYTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#a98a868de586290904766e4922d3e870b">LLVMInitializeHexagonTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmctargetdesc-cpp/#a45bfbd633beacf42b102d7b0103a0d4c">LLVMInitializeLoongArchTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmctargetdesc-cpp/#a32aa9aae9369c8b517be80ffecbc711c">LLVMInitializeMipsTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/mctargetdesc/msp430mctargetdesc-cpp/#ae4728e7bd5eb4cc404ac5fbbbce5cec5">LLVMInitializeMSP430TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp/#a7355d88f591aa5dd5f1d812ea99218ec">LLVMInitializePowerPCTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmctargetdesc-cpp/#a1e93b89ed4a5f8e3974124fedfcf4b27">LLVMInitializeRISCVTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmctargetdesc-cpp/#a8c9015b70cac029d8b59b9331d506300">LLVMInitializeSparcTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmctargetdesc-cpp/#abbf3c4fe1fddd6f8c4afe905d4122929">LLVMInitializeSystemZTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemctargetdesc-cpp/#aa17f62e3150eef038e4a6d3fb31d2af3">LLVMInitializeVETargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-cpp/#a0f83ad11a759c56547fd4b239e605f5e">LLVMInitializeWebAssemblyTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#ab1904658c919a9d143695cabebd68f53">LLVMInitializeX86TargetMC</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensamctargetdesc-cpp/#ad9def10e0f63f81dd8a4d3e2316f4795">LLVMInitializeXtensaTargetMC</a>.</p>

</div>
</div>

### RegisterTarget {#abb58373a69ea039dfcce69b9d1ba9ccb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TargetRegistry::RegisterTarget (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ShortDesc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * BackendName, <a href="/web-llvm/docs/api/classes/llvm/target/#a8246d27a463d60ef213642d571744a98">Target::ArchMatchFnTy</a> ArchMatchFn, bool HasJIT=false)</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/registertarget">RegisterTarget</a> - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> the given target.</p>


<p>Attempts to register a target which has already been registered will be ignored.</p>


<p>Clients are responsible for ensuring that registration doesn't occur while another thread is attempting to access the registry. Typically this is done by initializing all targets at program startup.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">T</td>
<td class="doxyParamItemDescription"><p>- The target being registered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>- The target name. This should be a static string.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ShortDesc</td>
<td class="doxyParamItemDescription"><p>- A short target description. This should be a static string.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BackendName</td>
<td class="doxyParamItemDescription"><p>- The name of the backend. This should be a static string that is the same for all targets that share a backend implementation and must match the name used in the 'def X : <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> ...' in <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ArchMatchFn</td>
<td class="doxyParamItemDescription"><p>- The arch match checking function for this target.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">HasJIT</td>
<td class="doxyParamItemDescription"><p>- Whether the target supports JIT code generation.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 739 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>, definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/targetregistry-cpp">TargetRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/targetregistry-cpp/#a3f7b8ead5d8f67255b04b0a7b0e87405">FirstTarget</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/targetinfo/aarch64targetinfo-cpp/#a7dd86b5b88a7bceb145b4aa1db5a06e9">LLVMInitializeAArch64TargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/targetinfo/bpftargetinfo-cpp/#a7cef0584f04fa0c25d70eaed40e74287">LLVMInitializeBPFTargetInfo</a> and <a href="/web-llvm/docs/api/structs/llvm/registertarget/#af2e0222ab3c2fd66efcaee9e5fd6f187">llvm::RegisterTarget&lt; TargetArchType, HasJIT &gt;::RegisterTarget</a>.</p>

</div>
</div>

### RegisterTargetMachine {#aa7abb11d1faa188e94cbe7b8aff7ca6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterTargetMachine (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#ae50a6e34e0b78a4bd13981d9ab7b1453">Target::TargetMachineCtorTy</a> Fn)</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/registertargetmachine">RegisterTargetMachine</a> - <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> a <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> implementation for the given target.</p>


<p>Clients are responsible for ensuring that registration doesn't occur while another thread is attempting to access the registry. Typically this is done by initializing all targets at program startup.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">T</td>
<td class="doxyParamItemDescription"><p>- The target being registered.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Fn</td>
<td class="doxyParamItemDescription"><p>- A function to construct a <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> for the target.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 826 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/registertargetmachine/#af793b528b184d98a9ccc21ff3f8c552d">llvm::RegisterTargetMachine&lt; TargetMachineImpl &gt;::RegisterTargetMachine</a>.</p>

</div>
</div>

### RegisterXCOFFStreamer {#a287265bb7705e8db447164b13444c85d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TargetRegistry::RegisterXCOFFStreamer (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#a06b59c2924092e0864c7ae7d7c1ccf4d">Target::XCOFFStreamerCtorTy</a> Fn)</td>
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



<p>Definition at line 921 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp/#a7355d88f591aa5dd5f1d812ea99218ec">LLVMInitializePowerPCTargetMC</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/targetregistry-cpp">TargetRegistry.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
