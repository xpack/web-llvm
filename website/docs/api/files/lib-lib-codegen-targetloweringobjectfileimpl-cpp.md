---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `TargetLoweringObjectFileImpl.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">llvm/CodeGen/TargetLoweringObjectFileImpl.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/coff-h">llvm/BinaryFormat/COFF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">llvm/BinaryFormat/Dwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/elf-h">llvm/BinaryFormat/ELF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">llvm/BinaryFormat/MachO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/wasm-h">llvm/BinaryFormat/Wasm.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicblocksectionutils-h">llvm/CodeGen/BasicBlockSectionUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">llvm/CodeGen/MachineModuleInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfoimpls-h">llvm/CodeGen/MachineModuleInfoImpls.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">llvm/IR/Comdat.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">llvm/IR/DiagnosticInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticprinter-h">llvm/IR/DiagnosticPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">llvm/IR/GlobalAlias.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalobject-h">llvm/IR/GlobalObject.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">llvm/IR/GlobalValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">llvm/IR/GlobalVariable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mangler-h">llvm/IR/Mangler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/pseudoprobe-h">llvm/IR/PseudoProbe.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfodarwin-h">llvm/MC/MCAsmInfoDarwin.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectioncoff-h">llvm/MC/MCSectionCOFF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionelf-h">llvm/MC/MCSectionELF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectiongoff-h">llvm/MC/MCSectionGOFF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionmacho-h">llvm/MC/MCSectionMachO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionwasm-h">llvm/MC/MCSectionWasm.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsectionxcoff-h">llvm/MC/MCSectionXCOFF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">llvm/MC/MCStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">llvm/MC/MCSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbolelf-h">llvm/MC/MCSymbolELF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcvalue-h">llvm/MC/MCValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/sectionkind-h">llvm/MC/SectionKind.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">llvm/ProfileData/InstrProf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/base64-h">llvm/Support/Base64.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegen-h">llvm/Support/CodeGen.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">llvm/Support/Format.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include &lt;cassert&gt;
#include &lt;string&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-targetloweringobjectfileimpl-cpp-">anonymous{TargetLoweringObjectFileImpl.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-targetloweringobjectfileimpl-cpp-/loweringdiagnosticinfo">LoweringDiagnosticInfo</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cf0a64393382f9a3115486212dfddda">GetObjCImageInfo</a> (Module &amp;M, unsigned &amp;Version, unsigned &amp;Flags, StringRef &amp;Section)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a728a93afb3dc13272034c0f59100f0ea">getELFKindForNamedSection</a> (StringRef Name, SectionKind K)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5861f5573d2e4cb48d685699e882695d">hasPrefix</a> (StringRef SectionName, StringRef Prefix)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55fa090d8ab1244df164135a4611ffe3">getELFSectionType</a> (StringRef Name, SectionKind K)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdbb74e69ffa28259967758299afad6a">getELFSectionFlags</a> (SectionKind K)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2fad8392c4cfa8ead6bce638f70bbf5">getELFComdat</a> (const GlobalValue *GV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf">MCSymbolELF</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ea34b9a1f566e473a3a2e35f4d58c17">getLinkedToSymbol</a> (const GlobalObject *GO, const TargetMachine &amp;TM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ca956d55a99b92d586bbfbe4d9eb620">getEntrySizeForKind</a> (SectionKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7bd2c042f102e350b6663b7fc9b1641">getSectionPrefixForGlobal</a> (SectionKind Kind, bool IsLarge)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the section prefix name used by options FunctionsSections and DataSections. <a href="#ad7bd2c042f102e350b6663b7fc9b1641">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 128 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade886f9a8ca0106ed64320647cbc1646">getELFSectionNameForGlobal</a> (const GlobalObject *GO, SectionKind Kind, Mangler &amp;Mang, const TargetMachine &amp;TM, unsigned EntrySize, bool UniqueSectionName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ff5b7a3a331a125bf3c5c70c9b3e686">calcUniqueIDUpdateFlagsAndSize</a> (const GlobalObject *GO, StringRef SectionName, SectionKind Kind, const TargetMachine &amp;TM, MCContext &amp;Ctx, Mangler &amp;Mang, unsigned &amp;Flags, unsigned &amp;EntrySize, unsigned &amp;NextUniqueID, const bool Retain, const bool ForceUnique)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate an appropriate unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for a section, and update Flags, EntrySize and NextUniqueID where appropriate. <a href="#a5ff5b7a3a331a125bf3c5c70c9b3e686">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, bool, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa0bbd687c795e07836fce23f49ebdd0">getGlobalObjectInfo</a> (const GlobalObject *GO, const TargetMachine &amp;TM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53445d1abe416390025be3ba8262a719">handlePragmaClangSection</a> (const GlobalObject *GO, SectionKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ad010e488dcef9a629eb57ccd67d32d">selectExplicitSectionGlobal</a> (const GlobalObject *GO, SectionKind Kind, const TargetMachine &amp;TM, MCContext &amp;Ctx, Mangler &amp;Mang, unsigned &amp;NextUniqueID, bool Retain, bool ForceUnique)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add2f0f91363dc8f915f182708b863919">selectELFSectionForGlobal</a> (MCContext &amp;Ctx, const GlobalObject *GO, SectionKind Kind, Mangler &amp;Mang, const TargetMachine &amp;TM, bool EmitUniqueSection, unsigned Flags, unsigned *NextUniqueID, const MCSymbolELF *AssociatedSymbol)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04cde3b10a14084e6358f46a241ac55e">selectELFSectionForGlobal</a> (MCContext &amp;Ctx, const GlobalObject *GO, SectionKind Kind, Mangler &amp;Mang, const TargetMachine &amp;TM, bool Retain, bool EmitUniqueSection, unsigned Flags, unsigned *NextUniqueID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cf6220e005c692b687fb495317b2d70">getStaticStructorSection</a> (MCContext &amp;Ctx, bool UseInitArray, bool IsCtor, unsigned Priority, const MCSymbol *KeySym)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab80457ac1eada6ec15c0492e30e5d6e4">checkMachOComdat</a> (const GlobalValue *GV)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11774bb915f7a73132b7dcbd43c5c18d">canUsePrivateLabel</a> (const MCAsmInfo &amp;AsmInfo, const MCSection &amp;Section)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f16beafed60f8ff4da8d921a4827e2c">getCOFFSectionFlags</a> (SectionKind K, const TargetMachine &amp;TM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a19103e69c6cb0ad95809d01b7b60cf">getComdatGVForCOFF</a> (const GlobalValue *GV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21e02ce6503c32d68315d841724b9385">getSelectionForCOFF</a> (const GlobalValue *GV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae079b3947f018c426db097508b93c678">getCOFFSectionNameForUniqueGlobal</a> (SectionKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcsectioncoff">MCSectionCOFF</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ad88e2a91bd25d33e1c21e854dced94">getCOFFStaticStructorSection</a> (MCContext &amp;Ctx, const Triple &amp;T, bool IsCtor, unsigned Priority, const MCSymbol *KeySym, MCSectionCOFF *Default)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb62d40db98a4479c864881fc06ce82a">APIntToHexString</a> (const APInt &amp;AI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae03364150b1bad2075c2d8db2bb87b92">scalarConstantToHexString</a> (const Constant *C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b7427173624577aaeb3201edcbd09b0">getWasmComdat</a> (const GlobalValue *GV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab351474e259e150dc8c1f28b5e482231">getWasmSectionFlags</a> (SectionKind K, bool Retain)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcsectionwasm">MCSectionWasm</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bfdd88bac067b42c86732805b14788b">selectWasmSectionForGlobal</a> (MCContext &amp;Ctx, const GlobalObject *GO, SectionKind Kind, Mangler &amp;Mang, const TargetMachine &amp;TM, bool EmitUniqueSection, unsigned *NextUniqueID, bool Retain)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdf58dbb5abc97dc544dfa3b8f0cecc4">JumpTableInFunctionSection</a>("jumptable-in-function-section", cl::Hidden, cl::init(false), cl::desc("Putting Jump Table in function section"))</td>
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

### APIntToHexString() {#abb62d40db98a4479c864881fc06ce82a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string APIntToHexString (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; AI)</td>
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



<p>Definition at line 2049 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a615619b0b2879029152b9a20e96624bc">llvm::transform</a>.</p>


<p>Referenced by <a href="#ae03364150b1bad2075c2d8db2bb87b92">scalarConstantToHexString</a>.</p>

</div>
</div>

### calcUniqueIDUpdateFlagsAndSize() {#a5ff5b7a3a331a125bf3c5c70c9b3e686}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned calcUniqueIDUpdateFlagsAndSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> * GO, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/mangler">Mangler</a> &amp; Mang, unsigned &amp; Flags, unsigned &amp; EntrySize, unsigned &amp; NextUniqueID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool Retain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool ForceUnique)</td>
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

<p>Calculate an appropriate unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for a section, and update Flags, EntrySize and NextUniqueID where appropriate.</p>

<p>Definition at line 703 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aa96980c44bc03ccd7b7b1fde53bc1f7da62fb23a196d73b6c068b55048cc02008">llvm::MCContext::GenericSectionID</a>, <a href="#ade886f9a8ca0106ed64320647cbc1646">getELFSectionNameForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#aef569d822dbf572ae71954d6831ce8a9">llvm::GlobalObject::getMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015ad0920ec9832b008457b48ba85712a111">llvm::ELF::SHF_GNU_RETAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a9284ee71917fdddaa2eeaba1bfe17e2b">llvm::ELF::SHF_LINK_ORDER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a0e54850eb2f8e74ae549f6dd70926723">llvm::ELF::SHF_MERGE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015aa92c276373fb0485e9930f76e69fe4cb">llvm::ELF::SHF_SUNW_NODISCARD</a>.</p>


<p>Referenced by <a href="#a1ad010e488dcef9a629eb57ccd67d32d">selectExplicitSectionGlobal</a>.</p>

</div>
</div>

### canUsePrivateLabel() {#a11774bb915f7a73132b7dcbd43c5c18d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool canUsePrivateLabel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &amp; AsmInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> &amp; Section)</td>
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



<p>Definition at line 1567 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcasminfodarwin/#ab4ef3ac1427687f11d30de588a790122">llvm::MCAsmInfoDarwin::isSectionAtomizableBySymbols</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a2aa25f7f2b406e074ebced65fa3dd531">llvm::TargetLoweringObjectFileMachO::getNameWithPrefix</a>.</p>

</div>
</div>

### checkMachOComdat() {#ab80457ac1eada6ec15c0492e30e5d6e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void checkMachOComdat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
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



<p>Definition at line 1299 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a43721e1e88567116e8fca545125d86bf">llvm::GlobalValue::getComdat</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a5e9dfc1cc5890ea9fb55b1dedcc2bd27">llvm::TargetLoweringObjectFileMachO::getExplicitSectionGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4309c75962c713f4a9a3e95468fd2cfa">llvm::TargetLoweringObjectFileMachO::SelectSectionForGlobal</a>.</p>

</div>
</div>

### getCOFFSectionFlags() {#a3f16beafed60f8ff4da8d921a4827e2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getCOFFSectionFlags (<a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> K, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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



<p>Definition at line 1597 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa2b3dbe611464bb08a83985d56d7bc67b">llvm::COFF::IMAGE_SCN_CNT_CODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa6a1c5fd37f3374c2e8e233d9e19bd205">llvm::COFF::IMAGE_SCN_CNT_INITIALIZED_DATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa4e1f40f2bdf9b194d4156c7707d047ba">llvm::COFF::IMAGE_SCN_CNT_UNINITIALIZED_DATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa24ac1300caa85825d3526b8baaec159f">llvm::COFF::IMAGE_SCN_LNK_REMOVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa64a6c00401f530708fa161270b0b8177">llvm::COFF::IMAGE_SCN_MEM_16BIT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa5c5ea9353e663af52c356d43798701a1">llvm::COFF::IMAGE_SCN_MEM_DISCARDABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa447cfc2eddd86f9f90a054d3e111c6d9">llvm::COFF::IMAGE_SCN_MEM_EXECUTE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa3c5ce7207c84ca0e6a03fd08ab4831ba">llvm::COFF::IMAGE_SCN_MEM_READ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aac1dfcdc9a17df9b148557d4c01759767">llvm::COFF::IMAGE_SCN_MEM_WRITE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#ac74d5e6c2cf6e4a41c5cd533e7f88fad">isThumb</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab456eadbc2378864e9aa9e2a545a1e65">llvm::Triple::thumb</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a1d07788150d8bd44cbba78db405f1574">llvm::TargetLoweringObjectFileCOFF::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#ad75e2aa4d67c101594e1f7448588c8d3">llvm::TargetLoweringObjectFileCOFF::getSectionForJumpTable</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a5835f5de3b78527c3348c7346c197b69">llvm::TargetLoweringObjectFileCOFF::SelectSectionForGlobal</a>.</p>

</div>
</div>

### getCOFFSectionNameForUniqueGlobal() {#ae079b3947f018c426db097508b93c678}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getCOFFSectionNameForUniqueGlobal (<a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> Kind)</td>
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



<p>Definition at line 1714 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#ad75e2aa4d67c101594e1f7448588c8d3">llvm::TargetLoweringObjectFileCOFF::getSectionForJumpTable</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a5835f5de3b78527c3348c7346c197b69">llvm::TargetLoweringObjectFileCOFF::SelectSectionForGlobal</a>.</p>

</div>
</div>

### getCOFFStaticStructorSection() {#a2ad88e2a91bd25d33e1c21e854dced94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionCOFF * getCOFFStaticStructorSection (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T, bool IsCtor, unsigned Priority, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * KeySym, <a href="/web-llvm/docs/api/classes/llvm/mcsectioncoff">MCSectionCOFF</a> * Default)</td>
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



<p>Definition at line 1955 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#aaf2a32c0f2738e57cac623b73b2c88aba79935518a3889663d8688b6b01fff051">Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa6a1c5fd37f3374c2e8e233d9e19bd205">llvm::COFF::IMAGE_SCN_CNT_INITIALIZED_DATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa3c5ce7207c84ca0e6a03fd08ab4831ba">llvm::COFF::IMAGE_SCN_MEM_READ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aac1dfcdc9a17df9b148557d4c01759767">llvm::COFF::IMAGE_SCN_MEM_WRITE</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a5b24916c9e1d8dd6e832abff33c763a8">llvm::TargetLoweringObjectFileCOFF::getStaticCtorSection</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#ad08c27804856dd188e679696e0a0343b">llvm::TargetLoweringObjectFileCOFF::getStaticDtorSection</a>.</p>

</div>
</div>

### getComdatGVForCOFF() {#a3a19103e69c6cb0ad95809d01b7b60cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GlobalValue * getComdatGVForCOFF (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
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



<p>Definition at line 1636 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a43721e1e88567116e8fca545125d86bf">llvm::GlobalValue::getComdat</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#ab1e6423b61f37584900fbdcadeedafb6">llvm::Module::getNamedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a1d07788150d8bd44cbba78db405f1574">llvm::TargetLoweringObjectFileCOFF::getExplicitSectionGlobal</a>, <a href="#a21e02ce6503c32d68315d841724b9385">getSelectionForCOFF</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a5835f5de3b78527c3348c7346c197b69">llvm::TargetLoweringObjectFileCOFF::SelectSectionForGlobal</a>.</p>

</div>
</div>

### getELFComdat() {#ae2fad8392c4cfa8ead6bce638f70bbf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Comdat * getELFComdat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
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



<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035a8c4ae4df3d085db275a58182612ff3be">llvm::Comdat::Any</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a43721e1e88567116e8fca545125d86bf">llvm::GlobalValue::getComdat</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035ab2d0d4bc9ba11b7324f5ffc20a9dc37a">llvm::Comdat::NoDeduplicate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="#afa0bbd687c795e07836fce23f49ebdd0">getGlobalObjectInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#ac8b6405ee0ca88cdcd7aea5d129551c4">llvm::TargetLoweringObjectFileELF::getSectionForLSDA</a>.</p>

</div>
</div>

### getELFKindForNamedSection() {#a728a93afb3dc13272034c0f59100f0ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionKind getELFKindForNamedSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> K)</td>
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



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a456b64e26b8bcdbd8294689615d8a055">llvm::Triple::ELF</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a97d95412f17878de8c47a9d13fd91871">llvm::SectionKind::getBSS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a50e3b943e26ec60c2aa24a7ff43a2d17">llvm::getInstrProfSectionName</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a13a2c76a48665ee3f4782fba7ddd72e1">llvm::SectionKind::getMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a9ca4fd7df1d9dc2cf7c4a1046d5b6957">llvm::SectionKind::getThreadBSS</a> and <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a047ddbdfed14ef00dfd7d11718be4cc1">llvm::SectionKind::getThreadData</a>.</p>


<p>Referenced by <a href="#a1ad010e488dcef9a629eb57ccd67d32d">selectExplicitSectionGlobal</a>.</p>

</div>
</div>

### getELFSectionFlags() {#afdbb74e69ffa28259967758299afad6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getELFSectionFlags (<a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> K)</td>
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



<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015af7f7df9a78253e9e24438eb30861bc23">llvm::ELF::SHF_ARM_PURECODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a4ed5db5129e0b0fe70bf59b691698a72">llvm::ELF::SHF_EXCLUDE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015affae0e6af56cc351c85d9c208e27af02">llvm::ELF::SHF_EXECINSTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a0e54850eb2f8e74ae549f6dd70926723">llvm::ELF::SHF_MERGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a1997ac83cc5cdf3e9ccc1e2de7bb8d45">llvm::ELF::SHF_STRINGS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015af09f8799cc15fd856ff2284c7519d6d8">llvm::ELF::SHF_TLS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015ae4bcae1b3b4fa53eba0886cbd799f0a8">llvm::ELF::SHF_WRITE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a050de8d61f37b8c99a85fe4a0f8deaf2">llvm::TargetLoweringObjectFileELF::getUniqueSectionForFunction</a>, <a href="#a1ad010e488dcef9a629eb57ccd67d32d">selectExplicitSectionGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a7c532f94d6bb9c4aba4190b81a7f8dbf">llvm::TargetLoweringObjectFileELF::SelectSectionForGlobal</a>.</p>

</div>
</div>

### getELFSectionNameForGlobal() {#ade886f9a8ca0106ed64320647cbc1646}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt; 128 &gt; getELFSectionNameForGlobal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> * GO, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/mangler">Mangler</a> &amp; Mang, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, unsigned EntrySize, bool UniqueSectionName)</td>
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



<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aa5d2c67dadc073dac78224224ee89350">llvm::GlobalValue::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#abc7937248226859bf5a5d64a28c8269f">llvm::DataLayout::getPreferredAlign</a>, <a href="#ad7bd2c042f102e350b6663b7fc9b1641">getSectionPrefixForGlobal</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#a5ff5b7a3a331a125bf3c5c70c9b3e686">calcUniqueIDUpdateFlagsAndSize</a> and <a href="#add2f0f91363dc8f915f182708b863919">selectELFSectionForGlobal</a>.</p>

</div>
</div>

### getELFSectionType() {#a55fa090d8ab1244df164135a4611ffe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getELFSectionType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> K)</td>
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



<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="#a5861f5573d2e4cb48d685699e882695d">hasPrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcafffa193cb0a9dae557d42e1e9d946298">llvm::ELF::SHT_FINI_ARRAY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcad0b0776fdeb0b583dfd2f0230b2e0bcd">llvm::ELF::SHT_INIT_ARRAY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca8d1430e480e40a4011259ae657b58e96">llvm::ELF::SHT_LLVM_LTO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca74f197262c720223d22a582814c4482d">llvm::ELF::SHT_LLVM_OFFLOADING</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca45212cec20bcd4ca3449dcd8654010ac">llvm::ELF::SHT_NOBITS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcad8d748e7ddd6a4fa31b32710bdd5aae2">llvm::ELF::SHT_NOTE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcabd6afa66a5f0e569e9066124b5d692b8">llvm::ELF::SHT_PREINIT_ARRAY</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca18ae5a64ac74a4265698b956bc797b32">llvm::ELF::SHT_PROGBITS</a>.</p>


<p>Referenced by <a href="#add2f0f91363dc8f915f182708b863919">selectELFSectionForGlobal</a> and <a href="#a1ad010e488dcef9a629eb57ccd67d32d">selectExplicitSectionGlobal</a>.</p>

</div>
</div>

### getEntrySizeForKind() {#a2ca956d55a99b92d586bbfbe4d9eb620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getEntrySizeForKind (<a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> Kind)</td>
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



<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#add2f0f91363dc8f915f182708b863919">selectELFSectionForGlobal</a> and <a href="#a1ad010e488dcef9a629eb57ccd67d32d">selectExplicitSectionGlobal</a>.</p>

</div>
</div>

### getGlobalObjectInfo() {#afa0bbd687c795e07836fce23f49ebdd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; StringRef, bool, unsigned &gt; getGlobalObjectInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> * GO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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



<p>Definition at line 783 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035a8c4ae4df3d085db275a58182612ff3be">llvm::Comdat::Any</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#ae2fad8392c4cfa8ead6bce638f70bbf5">getELFComdat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015aa4128c7283d8e6e763e8810a91c2dc1e">llvm::ELF::SHF_GROUP</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015ac3670b9f8f377801e941e3d341c51800">llvm::ELF::SHF_X86_64_LARGE</a>.</p>


<p>Referenced by <a href="#add2f0f91363dc8f915f182708b863919">selectELFSectionForGlobal</a> and <a href="#a1ad010e488dcef9a629eb57ccd67d32d">selectExplicitSectionGlobal</a>.</p>

</div>
</div>

### getLinkedToSymbol() {#a5ea34b9a1f566e473a3a2e35f4d58c17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbolELF * getLinkedToSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> * GO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
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



<p>Definition at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mdoperand/#ac5d52549f5e52702a331fbc4bd7eb512">llvm::MDOperand::get</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#aef569d822dbf572ae71954d6831ce8a9">llvm::GlobalObject::getMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>.</p>


<p>Referenced by <a href="#a04cde3b10a14084e6358f46a241ac55e">selectELFSectionForGlobal</a> and <a href="#a1ad010e488dcef9a629eb57ccd67d32d">selectExplicitSectionGlobal</a>.</p>

</div>
</div>

### GetObjCImageInfo() {#a2cf0a64393382f9a3115486212dfddda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GetObjCImageInfo (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, unsigned &amp; Version, unsigned &amp; Flags, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Section)</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad938857d6c6603847adf3a8cbe403d17">llvm::mdconst::extract</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a0a5c55e12c97b80021330fe82b642293aec0586c2f89c73dcc00841aa000141bb">llvm::Module::Require</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a467c9de76e4b351317463d4c803cebc4">llvm::TargetLoweringObjectFileCOFF::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a3a90d46a868772348b417ed1a94b3a94">llvm::TargetLoweringObjectFileELF::emitModuleMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a7bdbc0657e52a4bffa675c290b32840f">llvm::TargetLoweringObjectFileMachO::emitModuleMetadata</a>.</p>

</div>
</div>

### getSectionPrefixForGlobal() {#ad7bd2c042f102e350b6663b7fc9b1641}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getSectionPrefixForGlobal (<a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> Kind, bool IsLarge)</td>
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

<p>Return the section prefix name used by options FunctionsSections and DataSections.</p>

<p>Definition at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#ade886f9a8ca0106ed64320647cbc1646">getELFSectionNameForGlobal</a> and <a href="#a5bfdd88bac067b42c86732805b14788b">selectWasmSectionForGlobal</a>.</p>

</div>
</div>

### getSelectionForCOFF() {#a21e02ce6503c32d68315d841724b9385}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getSelectionForCOFF (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
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



<p>Definition at line 1653 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035a8c4ae4df3d085db275a58182612ff3be">llvm::Comdat::Any</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035acceb065ea69a5e06e80bd6ceddd7b9a7">llvm::Comdat::ExactMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a788ede5201dc9b44e419e9fd2fbb38bf">llvm::GlobalValue::getAliaseeObject</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a43721e1e88567116e8fca545125d86bf">llvm::GlobalValue::getComdat</a>, <a href="#a3a19103e69c6cb0ad95809d01b7b60cf">getComdatGVForCOFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#abb2a5b3cc2301597c2ffed2e4b04f45ead3941c7129f5525831b86bad485c5c84">llvm::COFF::IMAGE_COMDAT_SELECT_ANY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#abb2a5b3cc2301597c2ffed2e4b04f45ea85161daa9965cdbe86d035f42c2c65ed">llvm::COFF::IMAGE_COMDAT_SELECT_ASSOCIATIVE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#abb2a5b3cc2301597c2ffed2e4b04f45eacd78638706a3064a4e45338ff1e7bf27">llvm::COFF::IMAGE_COMDAT_SELECT_EXACT_MATCH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#abb2a5b3cc2301597c2ffed2e4b04f45ea17ba874a692efa7078523c01aa3fee7d">llvm::COFF::IMAGE_COMDAT_SELECT_LARGEST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#abb2a5b3cc2301597c2ffed2e4b04f45ea0377869950971d165e9d51c507a0d660">llvm::COFF::IMAGE_COMDAT_SELECT_NODUPLICATES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#abb2a5b3cc2301597c2ffed2e4b04f45ea4995c77f273d7f348b698ca069dc778a">llvm::COFF::IMAGE_COMDAT_SELECT_SAME_SIZE</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035a2444b05a47619decc80c2ce0cc224dc8">llvm::Comdat::Largest</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035ab2d0d4bc9ba11b7324f5ffc20a9dc37a">llvm::Comdat::NoDeduplicate</a> and <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035a8b148d3d05688ddb23b7abb81527b7ce">llvm::Comdat::SameSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a1d07788150d8bd44cbba78db405f1574">llvm::TargetLoweringObjectFileCOFF::getExplicitSectionGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a5835f5de3b78527c3348c7346c197b69">llvm::TargetLoweringObjectFileCOFF::SelectSectionForGlobal</a>.</p>

</div>
</div>

### getStaticStructorSection() {#a8cf6220e005c692b687fb495317b2d70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionELF * getStaticStructorSection (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, bool UseInitArray, bool IsCtor, unsigned Priority, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * KeySym)</td>
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



<p>Definition at line 1097 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015aa4128c7283d8e6e763e8810a91c2dc1e">llvm::ELF::SHF_GROUP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015ae4bcae1b3b4fa53eba0886cbd799f0a8">llvm::ELF::SHF_WRITE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcafffa193cb0a9dae557d42e1e9d946298">llvm::ELF::SHT_FINI_ARRAY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcad0b0776fdeb0b583dfd2f0230b2e0bcd">llvm::ELF::SHT_INIT_ARRAY</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca18ae5a64ac74a4265698b956bc797b32">llvm::ELF::SHT_PROGBITS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a2db5f2d616786cd3aeab03d0d5115fca">llvm::TargetLoweringObjectFileELF::getStaticCtorSection</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a4d95ba93070cf6ac583ce923884ee5da">llvm::TargetLoweringObjectFileELF::getStaticDtorSection</a>.</p>

</div>
</div>

### getWasmComdat() {#a8b7427173624577aaeb3201edcbd09b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Comdat * getWasmComdat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
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



<p>Definition at line 2131 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035a8c4ae4df3d085db275a58182612ff3be">llvm::Comdat::Any</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a43721e1e88567116e8fca545125d86bf">llvm::GlobalValue::getComdat</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilewasm/#ad7fddd197449964ffb791c5a7e1900ec">llvm::TargetLoweringObjectFileWasm::getExplicitSectionGlobal</a> and <a href="#a5bfdd88bac067b42c86732805b14788b">selectWasmSectionForGlobal</a>.</p>

</div>
</div>

### getWasmSectionFlags() {#ab351474e259e150dc8c1f28b5e482231}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getWasmSectionFlags (<a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> K, bool Retain)</td>
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



<p>Definition at line 2144 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#ab59521677a1bb67738764d89f9cb0429a05cd6cd324ddab7f919b11f3422ec610">llvm::wasm::WASM_SEG_FLAG_RETAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#ab59521677a1bb67738764d89f9cb0429ac340817f607f61c4413f9e89b0acab03">llvm::wasm::WASM_SEG_FLAG_STRINGS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#ab59521677a1bb67738764d89f9cb0429a829d95d74beace7ff3449f6715cbaec7">llvm::wasm::WASM_SEG_FLAG_TLS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilewasm/#ad7fddd197449964ffb791c5a7e1900ec">llvm::TargetLoweringObjectFileWasm::getExplicitSectionGlobal</a> and <a href="#a5bfdd88bac067b42c86732805b14788b">selectWasmSectionForGlobal</a>.</p>

</div>
</div>

### handlePragmaClangSection() {#a53445d1abe416390025be3ba8262a719}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef handlePragmaClangSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> * GO, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> Kind)</td>
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



<p>Definition at line 797 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a2e5805d3565801dc32ec696d17624c6e">llvm::GlobalVariable::getAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a0b2e3fb45c4435c29abebf7768a77cd6">llvm::GlobalObject::getSection</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a794d6b65a466293b4ce971189b2e9ab1">llvm::GlobalVariable::hasImplicitSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a1d07788150d8bd44cbba78db405f1574">llvm::TargetLoweringObjectFileCOFF::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a5e9dfc1cc5890ea9fb55b1dedcc2bd27">llvm::TargetLoweringObjectFileMachO::getExplicitSectionGlobal</a> and <a href="#a1ad010e488dcef9a629eb57ccd67d32d">selectExplicitSectionGlobal</a>.</p>

</div>
</div>

### hasPrefix() {#a5861f5573d2e4cb48d685699e882695d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasPrefix (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix)</td>
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



<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>Referenced by <a href="#a55fa090d8ab1244df164135a4611ffe3">getELFSectionType</a>.</p>

</div>
</div>

### scalarConstantToHexString() {#ae03364150b1bad2075c2d8db2bb87b92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string scalarConstantToHexString (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C)</td>
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



<p>Definition at line 2060 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="#abb62d40db98a4479c864881fc06ce82a">APIntToHexString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#ae03364150b1bad2075c2d8db2bb87b92">scalarConstantToHexString</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a300546d54aa331d7615052bd9ba5883d">llvm::TargetLoweringObjectFileCOFF::getSectionForConstant</a> and <a href="#ae03364150b1bad2075c2d8db2bb87b92">scalarConstantToHexString</a>.</p>

</div>
</div>

### selectELFSectionForGlobal() {#add2f0f91363dc8f915f182708b863919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionELF * selectELFSectionForGlobal (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> * GO, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/mangler">Mangler</a> &amp; Mang, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, bool EmitUniqueSection, unsigned Flags, unsigned * NextUniqueID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf">MCSymbolELF</a> * AssociatedSymbol)</td>
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



<p>Definition at line 874 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aa96980c44bc03ccd7b7b1fde53bc1f7da62fb23a196d73b6c068b55048cc02008">llvm::MCContext::GenericSectionID</a>, <a href="#ade886f9a8ca0106ed64320647cbc1646">getELFSectionNameForGlobal</a>, <a href="#a55fa090d8ab1244df164135a4611ffe3">getELFSectionType</a>, <a href="#a2ca956d55a99b92d586bbfbe4d9eb620">getEntrySizeForKind</a> and <a href="#afa0bbd687c795e07836fce23f49ebdd0">getGlobalObjectInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a38d2d101b244807c73327e57f705ef7e">llvm::TargetLoweringObjectFileELF::getSectionForJumpTable</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a050de8d61f37b8c99a85fe4a0f8deaf2">llvm::TargetLoweringObjectFileELF::getUniqueSectionForFunction</a>, <a href="#a04cde3b10a14084e6358f46a241ac55e">selectELFSectionForGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a7c532f94d6bb9c4aba4190b81a7f8dbf">llvm::TargetLoweringObjectFileELF::SelectSectionForGlobal</a>.</p>

</div>
</div>

### selectELFSectionForGlobal() {#a04cde3b10a14084e6358f46a241ac55e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * selectELFSectionForGlobal (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> * GO, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/mangler">Mangler</a> &amp; Mang, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, bool Retain, bool EmitUniqueSection, unsigned Flags, unsigned * NextUniqueID)</td>
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



<p>Definition at line 906 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5ea34b9a1f566e473a3a2e35f4d58c17">getLinkedToSymbol</a>, <a href="#add2f0f91363dc8f915f182708b863919">selectELFSectionForGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015ad0920ec9832b008457b48ba85712a111">llvm::ELF::SHF_GNU_RETAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a9284ee71917fdddaa2eeaba1bfe17e2b">llvm::ELF::SHF_LINK_ORDER</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015aa92c276373fb0485e9930f76e69fe4cb">llvm::ELF::SHF_SUNW_NODISCARD</a>.</p>

</div>
</div>

### selectExplicitSectionGlobal() {#a1ad010e488dcef9a629eb57ccd67d32d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection * selectExplicitSectionGlobal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> * GO, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/mangler">Mangler</a> &amp; Mang, unsigned &amp; NextUniqueID, bool Retain, bool ForceUnique)</td>
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



<p>Definition at line 818 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5ff5b7a3a331a125bf3c5c70c9b3e686">calcUniqueIDUpdateFlagsAndSize</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#aad03ef5cfbe6e7cad076d9e45ba06592">llvm::LLVMContext::diagnose</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="#a728a93afb3dc13272034c0f59100f0ea">getELFKindForNamedSection</a>, <a href="#afdbb74e69ffa28259967758299afad6a">getELFSectionFlags</a>, <a href="#a55fa090d8ab1244df164135a4611ffe3">getELFSectionType</a>, <a href="#a2ca956d55a99b92d586bbfbe4d9eb620">getEntrySizeForKind</a>, <a href="#afa0bbd687c795e07836fce23f49ebdd0">getGlobalObjectInfo</a>, <a href="#a5ea34b9a1f566e473a3a2e35f4d58c17">getLinkedToSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a4fb981ce623b68eea5cd781ee0ae8ddf">llvm::Module::getSourceFileName</a>, <a href="#a53445d1abe416390025be3ba8262a719">handlePragmaClangSection</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a0e54850eb2f8e74ae549f6dd70926723">llvm::ELF::SHF_MERGE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#af043f3b43eb6797a702c062b9a3d54fe">llvm::TargetLoweringObjectFileELF::getExplicitSectionGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a050de8d61f37b8c99a85fe4a0f8deaf2">llvm::TargetLoweringObjectFileELF::getUniqueSectionForFunction</a>.</p>

</div>
</div>

### selectWasmSectionForGlobal() {#a5bfdd88bac067b42c86732805b14788b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionWasm * selectWasmSectionForGlobal (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> * GO, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/mangler">Mangler</a> &amp; Mang, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, bool EmitUniqueSection, unsigned * NextUniqueID, bool Retain)</td>
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



<p>Definition at line 2204 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aa96980c44bc03ccd7b7b1fde53bc1f7da62fb23a196d73b6c068b55048cc02008">llvm::MCContext::GenericSectionID</a>, <a href="#ad7bd2c042f102e350b6663b7fc9b1641">getSectionPrefixForGlobal</a>, <a href="#a8b7427173624577aaeb3201edcbd09b0">getWasmComdat</a> and <a href="#ab351474e259e150dc8c1f28b5e482231">getWasmSectionFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilewasm/#ae9c61f87f856e9bf0341b4d68136c3ab">llvm::TargetLoweringObjectFileWasm::SelectSectionForGlobal</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### JumpTableInFunctionSection {#acdf58dbb5abc97dc544dfa3b8f0cecc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; JumpTableInFunctionSection("jumptable-in-function-section", cl::Hidden, cl::init(false), cl::desc("Putting Jump Table in function section"))</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp">TargetLoweringObjectFileImpl.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a900d73462c4eb7e568ff0e8fa1883898">llvm::TargetLoweringObjectFileCOFF::shouldPutJumpTableInFunctionSection</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
