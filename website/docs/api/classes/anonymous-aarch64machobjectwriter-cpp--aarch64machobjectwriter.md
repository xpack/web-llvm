---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-aarch64machobjectwriter-cpp-/aarch64machobjectwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AArch64MachObjectWriter` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{AArch64MachObjectWriter.cpp}::AArch64MachObjectWriter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcmachobjecttargetwriter">MCMachObjectTargetWriter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ed961a70254a62667fa5944977cd375">AArch64MachObjectWriter</a> (uint32_t CPUType, uint32_t CPUSubtype, bool IsILP32)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0bd2f62658fdbaf0b7206e161932596">recordRelocation</a> (MachObjectWriter *Writer, MCAssembler &amp;Asm, const MCFragment *Fragment, const MCFixup &amp;Fixup, MCValue Target, uint64_t &amp;FixedValue) override</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a027f54496f82f987b0eef952da6abc6b">getAArch64FixupKindMachOInfo</a> (const MCFixup &amp;Fixup, unsigned &amp;RelocType, const MCSymbolRefExpr *Sym, unsigned &amp;Log2Size, const MCAssembler &amp;Asm)</td>
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


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64machobjectwriter-cpp">AArch64MachObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AArch64MachObjectWriter() {#a2ed961a70254a62667fa5944977cd375}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AArch64MachObjectWriter.cpp}::AArch64MachObjectWriter::AArch64MachObjectWriter (uint32_t CPUType, uint32_t CPUSubtype, bool IsILP32)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64machobjectwriter-cpp">AArch64MachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcmachobjecttargetwriter/#a585fed60885001bfbcb03bdb998bc6e0">llvm::MCMachObjectTargetWriter::CPUSubtype</a> and <a href="/web-llvm/docs/api/classes/llvm/mcmachobjecttargetwriter/#ab5600ec5363bb5d1b3c62b55f8363a99">llvm::MCMachObjectTargetWriter::MCMachObjectTargetWriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### recordRelocation() {#ab0bd2f62658fdbaf0b7206e161932596}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64MachObjectWriter::recordRelocation (<a href="/web-llvm/docs/api/classes/llvm/machobjectwriter">MachObjectWriter</a> * Writer, <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> * Fragment, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> Target, uint64_t &amp; FixedValue)</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64machobjectwriter-cpp">AArch64MachObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a40b113871f6a7036554ee273f6c989fe">llvm::MachObjectWriter::addRelocation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa91ead49defe15a5f34e4e0f4a2365d09">llvm::MachO::ARM64_RELOC_ADDEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa49adb9548fb89cb6cd971e8afa28edea">llvm::MachO::ARM64_RELOC_AUTHENTICATED_POINTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfaffc9c125707f9893dde566edfc79d656">llvm::MachO::ARM64_RELOC_BRANCH26</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfad557674652722e3e339b58dc9895df5a">llvm::MachO::ARM64_RELOC_PAGE21</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa2498a9e498c85f7eec3117d24c409ad3">llvm::MachO::ARM64_RELOC_PAGEOFF12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa2f0c5edc91e3359ff834e95607773f31">llvm::MachO::ARM64_RELOC_POINTER_TO_GOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa78b1160279497250f62c414267853f1f">llvm::MachO::ARM64_RELOC_SUBTRACTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad23021ed657c8b0f302154585b0fd3bfa948650248b0f0c167e5effe9dd552f2c">llvm::MachO::ARM64_RELOC_UNSIGNED</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64machobjectwriter-cpp/#a4bdfc7678b89f0959870e072aaf0d036">canUseLocalRelocation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9ad31b24bfe1fb4471f899fbfa37d240f7">llvm::AArch64::fixup_aarch64_pcrel_adrp_imm21</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9a9cfa836f3def950d2b4a9cc69a5de67c">llvm::AArch64::fixup_aarch64_pcrel_branch14</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a5c816ea23ece51a78a235f57ffb177a9a87e08dcaf47dcab2f388f1d348002f3f">llvm::AArch64::fixup_aarch64_pcrel_branch19</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#ab3fd02f1d1b3eeeec275c2485ba8af0a">llvm::MachObjectWriter::getAtom</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#afe11aa50f8890a5eeda1fadf7e2f576e">llvm::MCSymbol::getFragment</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a2be2c8edb4b559c7d47cfa0ec881739f">llvm::MachObjectWriter::getFragmentAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a30cdafd656830b62aa8070242810c405">llvm::Target::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a04990a85b6279a802df811663e2852f5">llvm::MCSection::getOrdinal</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#a7b98ffc5ede97acf84a20b7476d3ffff">llvm::MCFragment::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a9c098d5087a761f4ff5d1862ae8dfcbe">llvm::MachObjectWriter::getSymbolAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a56f972d8aca0c842218ea5b0fd4559a8">llvm::MachObjectWriter::isFixupKindPCRel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfodarwin/#ab4ef3ac1427687f11d30de588a790122">llvm::MCAsmInfoDarwin::isSectionAtomizableBySymbols</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info/#a2c1c46bbe4b0ef3065fe91d3e9ca806e">llvm::MachO::any_relocation_info::r_word0</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info/#aff97edf4109298178b12aca5621bd6ec">llvm::MachO::any_relocation_info::r_word1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae48d3339087b2fd4771ddadae550b334a194b9b14fac1e84995be68484867a709">llvm::MachO::S_ATTR_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfa0121933247ec3c2a0477b4e9142fcdc9">llvm::AArch64MCExpr::VK_AUTH</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcexpr/#abec9c1dd43489b968c9780860bad71bfaa8bd8587ab7bb2c4e6db67d515b0d83e">llvm::AArch64MCExpr::VK_AUTHADDR</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985aa780672c4378b10a1ef6094a4c46de10">llvm::MCSymbolRefExpr::VK_GOT</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getAArch64FixupKindMachOInfo() {#a027f54496f82f987b0eef952da6abc6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64MachObjectWriter::getAArch64FixupKindMachOInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, unsigned &amp; RelocType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr">MCSymbolRefExpr</a> * Sym, unsigned &amp; Log2Size, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64machobjectwriter-cpp">AArch64MachObjectWriter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64machobjectwriter-cpp">AArch64MachObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
