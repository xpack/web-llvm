---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ppcelfmcasminfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PPCELFMCAsmInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::PPCELFMCAsmInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmcasminfo-h">Target/PowerPC/MCTargetDesc/PPCMCAsmInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasminfoelf">MCAsmInfoELF</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a463a7c03ba11e950bd438542028a2a20">PPCELFMCAsmInfo</a> (bool is64Bit, const Triple &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dcb2b87443070961a52b825dea0b067">anchor</a> () override</td>
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


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmcasminfo-h">PPCMCAsmInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PPCELFMCAsmInfo() {#a463a7c03ba11e950bd438542028a2a20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPCELFMCAsmInfo::PPCELFMCAsmInfo (bool is64Bit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T)</td>
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



<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmcasminfo-h">PPCMCAsmInfo.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmcasminfo-cpp">PPCMCAsmInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ac150f03927bf41531f945b3bc5b315e4">llvm::MCAsmInfo::AlignmentIsInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#aaab4eaa2f4de9c0d12606c176dd9d738">llvm::MCAsmInfo::AssemblerDialect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lcomm/#aae933cd10a930a5312da96502035e331a310fe8dc05086ce23b6826ccb3c37fc7">llvm::LCOMM::ByteAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#aeb608789bae103384e251c302a2215f9">llvm::MCAsmInfo::CalleeSaveStackSlotSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ae243a845fe9d46ed2cb7403700921e4a">llvm::MCAsmInfo::CodePointerSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#af30c385b021a371a04bacd22cef94c7b">llvm::MCAsmInfo::CommentString</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a3c136967a2fc9489724bcd8706a16fed">llvm::MCAsmInfo::Data64bitsDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a40bb8a0475f841d023b30c6449595d83">llvm::MCAsmInfo::DollarIsPC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84ab4fe87e4046ecd1f9f3d96bbf63822b3">llvm::DwarfCFI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a500ba2b2c0203d1d53b83a649551a6b5">llvm::MCAsmInfo::ExceptionsType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a652270ec0bdb03b5a7f934524412aa7f">is64Bit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#adfd724f11ba125f30c3bb516be0bb06f">llvm::MCAsmInfo::IsLittleEndian</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a6f7c7ae850927432e251d9a5f8bb0537">llvm::MCAsmInfo::LCOMMDirectiveAlignmentType</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a139e22bc2c357349563ce30a503d13fd">llvm::MCAsmInfo::MinInstAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a4deabb10a57806073dc4681158f628f8">llvm::MCAsmInfo::NeedsLocalForSize</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a4c6fec6469969e44d4af328ef7782c46">llvm::Triple::ppc64le</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a440d963f2b5dc6b1268643771492a905">llvm::Triple::ppcle</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a98f40236cfff7278d4b57633fad2245d">llvm::MCAsmInfo::SupportsDebugInformation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a9209a7aeb154de066a5f7ed6087892cc">llvm::MCAsmInfo::UsesELFSectionDirectiveForBSS</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#acf84c6bd03a785a251784cad666d9ee1">llvm::MCAsmInfo::ZeroDirective</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a9dcb2b87443070961a52b825dea0b067}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCELFMCAsmInfo::anchor ()</td>
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



<p>Declaration at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmcasminfo-h">PPCMCAsmInfo.h</a>, definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmcasminfo-cpp">PPCMCAsmInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmcasminfo-cpp">PPCMCAsmInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmcasminfo-h">PPCMCAsmInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
