---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcasminfodarwin
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCAsmInfoDarwin` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MCAsmInfoDarwin { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfodarwin-h">llvm/MC/MCAsmInfoDarwin.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class is intended to be used as a base class for asm properties and features specific to the target. <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aarch64mcasminfodarwin">AArch64MCAsmInfoDarwin</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/armmcasminfodarwin">ARMMCAsmInfoDarwin</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/x86mcasminfodarwin">X86MCAsmInfoDarwin</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ababa8db9a500a01d8969d2bdc55ec981">MCAsmInfoDarwin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4ef3ac1427687f11d30de588a790122">isSectionAtomizableBySymbols</a> (const MCSection &amp;Section)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the section is atomized using the symbols in it. <a href="#ab4ef3ac1427687f11d30de588a790122">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfodarwin-h">MCAsmInfoDarwin.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCAsmInfoDarwin() {#ababa8db9a500a01d8969d2bdc55ec981}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmInfoDarwin::MCAsmInfoDarwin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfodarwin-h">MCAsmInfoDarwin.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasminfodarwin-cpp">MCAsmInfoDarwin.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ac150f03927bf41531f945b3bc5b315e4">llvm::MCAsmInfo::AlignmentIsInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ac0079bf3834ce7ee765d437aae0a8a69">llvm::MCAsmInfo::COMMDirectiveAlignmentIsInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ab5b8b23af9e578cebad7bb0ed9113924">llvm::MCAsmInfo::DwarfUsesRelocationsAcrossSections</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a7c3b8692b75d4808f7c888e61f01e1c8">llvm::MCAsmInfo::HasDotTypeDotSizeDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a15bacf592302115a438444da1b9517e4">llvm::MCAsmInfo::HasNoDeadStrip</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ab74c767922c89f683dec73c5b9a7b87a">llvm::MCAsmInfo::HasSingleParameterDotFile</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a35179e4c975f4619c9e55af83bb23bee">llvm::MCAsmInfo::HasSubsectionsViaSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a8369a33761758d3fd9114e46795851ea">llvm::MCAsmInfo::HasWeakDefCanBeHiddenDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#aaccbddd4af6a81c7bf3a53e30289bb17">llvm::MCAsmInfo::HiddenDeclarationVisibilityAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#aef1537a18c53520abe7cb7026e10cb92">llvm::MCAsmInfo::HiddenVisibilityAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#aa238b30c1afd57422b374a9cb2edc4df">llvm::MCAsmInfo::InlineAsmEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a87ec076e2f46691b519f60545904269c">llvm::MCAsmInfo::InlineAsmStart</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a6f7c7ae850927432e251d9a5f8bb0537">llvm::MCAsmInfo::LCOMMDirectiveAlignmentType</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a952dc5034e99e797c493900cf8c9f299">llvm::MCAsmInfo::LinkerPrivateGlobalPrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lcomm/#aae933cd10a930a5312da96502035e331adce83244e971c1aeafe5840c91d9be0b">llvm::LCOMM::Log2Alignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243af3367f8319e21bf0779da14146221c55">llvm::MCSA_Invalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a39ad38d82f889bf4c82e539beb859d05">llvm::MCSA_PrivateExtern</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a1de3b3906f70f4952617056881437120">llvm::MCAsmInfo::ProtectedVisibilityAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a5e56692562ead63a7721268341efd118">llvm::MCAsmInfo::SetDirectiveSuppressesReloc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a72118878aeadcae71da2d5d179aebb81">llvm::MCAsmInfo::WeakRefDirective</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#acf84c6bd03a785a251784cad666d9ee1">llvm::MCAsmInfo::ZeroDirective</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isSectionAtomizableBySymbols() {#ab4ef3ac1427687f11d30de588a790122}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCAsmInfoDarwin::isSectionAtomizableBySymbols (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> &amp; Section)</td>
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

<p>True if the section is atomized using the symbols in it.</p>


<p>This is false if the section is atomized based on its contents (<a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a>' __TEXT,__cstring for example).</p>


<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfodarwin-h">MCAsmInfoDarwin.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcasminfodarwin-cpp">MCAsmInfoDarwin.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsection/#aac4366cca0c8d3cd472a02a71f4aa34c">llvm::MCSection::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho/#a3daa3b8dd38ee3a426a6f83bb3cac0d2">llvm::MCSectionMachO::getSegmentName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho/#a2f530d6116df447fdadb8ef67239cd4e">llvm::MCSectionMachO::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a22ad6417ce1c6d4ecad57a09abbc8e78">llvm::MachO::S_16BYTE_LITERALS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a96a823d462214dfff581d9471ec646e2">llvm::MachO::S_4BYTE_LITERALS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409abf30d8c4dee516771947b057cde186c4">llvm::MachO::S_8BYTE_LITERALS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a857886b2cccfd23c2445e9912addf150">llvm::MachO::S_CSTRING_LITERALS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a148f0bafb3d61c0182d05638075c7de1">llvm::MachO::S_INTERPOSING</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a4735e4e9043352fd4e19057bf95ea28a">llvm::MachO::S_LAZY_SYMBOL_POINTERS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409aa906bb55cd8e457ca1ffce51741d055e">llvm::MachO::S_LITERAL_POINTERS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a61e394fcd6d71346ac33aad0f551459b">llvm::MachO::S_MOD_INIT_FUNC_POINTERS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a5933976355da08874b6a186342dbadd1">llvm::MachO::S_MOD_TERM_FUNC_POINTERS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a93912b05b13268a5cbd717f4a5fab8c9">llvm::MachO::S_NON_LAZY_SYMBOL_POINTERS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a48b52b2439385a6f96a6e50defb27409a0b4240e38bf4066a8378e3a0450555ef">llvm::MachO::S_THREAD_LOCAL_VARIABLE_POINTERS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#a11774bb915f7a73132b7dcbd43c5c18d">canUsePrivateLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#ab3fd02f1d1b3eeeec275c2485ba8af0a">llvm::MachObjectWriter::getAtom</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64machobjectwriter-cpp-/aarch64machobjectwriter/#ab0bd2f62658fdbaf0b7206e161932596">anonymous{AArch64MachObjectWriter.cpp}::AArch64MachObjectWriter::recordRelocation</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfodarwin-h">MCAsmInfoDarwin.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcasminfodarwin-cpp">MCAsmInfoDarwin.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
