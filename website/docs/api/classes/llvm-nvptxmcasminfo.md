---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/nvptxmcasminfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `NVPTXMCAsmInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::NVPTXMCAsmInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxmcasminfo-h">Target/NVPTX/MCTargetDesc/NVPTXMCAsmInfo.h</a>"
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a198606773a0fd35284257608ba615fa5">NVPTXMCAsmInfo</a> (const Triple &amp;TheTriple, const MCTargetOptions &amp;Options)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61fc81fb9125f5e5c7184ea3609c4a46">shouldOmitSectionDirective</a> (StringRef SectionName) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the .section directive should be omitted when emitting <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/sectionname">SectionName</a></span>. <a href="#a61fc81fb9125f5e5c7184ea3609c4a46">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b793f445a3f1491c00272f915f305fe">anchor</a> ()</td>
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


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxmcasminfo-h">NVPTXMCAsmInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NVPTXMCAsmInfo() {#a198606773a0fd35284257608ba615fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NVPTXMCAsmInfo::NVPTXMCAsmInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TheTriple, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> &amp; Options)</td>
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



<p>Declaration at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxmcasminfo-h">NVPTXMCAsmInfo.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxmcasminfo-cpp">NVPTXMCAsmInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a20ecadae9aa8ee83587c9fcaedf6578a">llvm::MCAsmInfo::AsciiDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ad8520723e634e656d2a8219e0cf19ba7">llvm::MCAsmInfo::AscizDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#aeb608789bae103384e251c302a2215f9">llvm::MCAsmInfo::CalleeSaveStackSlotSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ae243a845fe9d46ed2cb7403700921e4a">llvm::MCAsmInfo::CodePointerSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#af30c385b021a371a04bacd22cef94c7b">llvm::MCAsmInfo::CommentString</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a035c98c0423e6dd21ec2ea039f762440">llvm::MCAsmInfo::Data16bitsDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a620b2ebe9e68a34106b7bdcc4220c6b2">llvm::MCAsmInfo::Data32bitsDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a3c136967a2fc9489724bcd8706a16fed">llvm::MCAsmInfo::Data64bitsDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a3aabcaa0b460b2ea508314bf21c2ffd9">llvm::MCAsmInfo::Data8bitsDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a93a6345f8b8953e784329ce22797ddbc">llvm::MCAsmInfo::EnableDwarfFileDirectoryDefault</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5fc23559f17bbe5ff83ec0fed0a5fdcf">llvm::Triple::getArch</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a6c6ae04133910ce4d3a494a44258bad3">llvm::MCAsmInfo::GlobalDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a7c3b8692b75d4808f7c888e61f01e1c8">llvm::MCAsmInfo::HasDotTypeDotSizeDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a1fa6b719130b38e60e6d562d0f07ec1e">llvm::MCAsmInfo::HasFunctionAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ab74c767922c89f683dec73c5b9a7b87a">llvm::MCAsmInfo::HasSingleParameterDotFile</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#aaccbddd4af6a81c7bf3a53e30289bb17">llvm::MCAsmInfo::HiddenDeclarationVisibilityAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#aef1537a18c53520abe7cb7026e10cb92">llvm::MCAsmInfo::HiddenVisibilityAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#aa238b30c1afd57422b374a9cb2edc4df">llvm::MCAsmInfo::InlineAsmEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a87ec076e2f46691b519f60545904269c">llvm::MCAsmInfo::InlineAsmStart</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243af3367f8319e21bf0779da14146221c55">llvm::MCSA_Invalid</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a92ac53f0fca7e6c3f4e56a2d4903b9ae">llvm::Triple::nvptx64</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a5384e7b6526e6d9c7744c07e1136b7b8">llvm::MCAsmInfo::PrivateGlobalPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a721901796262520ac70998c9323686cb">llvm::MCAsmInfo::PrivateLabelPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a1de3b3906f70f4952617056881437120">llvm::MCAsmInfo::ProtectedVisibilityAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a98f40236cfff7278d4b57633fad2245d">llvm::MCAsmInfo::SupportsDebugInformation</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ac8e3a97a3e21326e8ed0026bed0e7188">llvm::MCAsmInfo::SupportsExtendedDwarfLocDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ad6636ff34629b06e7f639d338c81bdf5">llvm::MCAsmInfo::SupportsQuotedNames</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#aa415e0a1dab862fe76c07809b74ee3b1">llvm::MCAsmInfo::SupportsSignedData</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a624dfc3c9dd72db826eca195ed423535">llvm::MCAsmInfo::UseIntegratedAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ab594ccd316e4f97380e00dcd595a5c36">llvm::MCAsmInfo::UseParensForDollarSignNames</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#af76361f7a7974added3f9774fbf0ce09">llvm::MCAsmInfo::WeakDirective</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#acf84c6bd03a785a251784cad666d9ee1">llvm::MCAsmInfo::ZeroDirective</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### shouldOmitSectionDirective() {#a61fc81fb9125f5e5c7184ea3609c4a46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::NVPTXMCAsmInfo::shouldOmitSectionDirective (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the .section directive should be omitted when emitting <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/sectionname">SectionName</a></span>.</p>


<p>For example:</p>


<p>shouldOmitSectionDirective(".text")</p>


<p>returns false =&gt; .section .text,#alloc,#execinstr returns true =&gt; .text</p>


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxmcasminfo-h">NVPTXMCAsmInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a0b793f445a3f1491c00272f915f305fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NVPTXMCAsmInfo::anchor ()</td>
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



<p>Declaration at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxmcasminfo-h">NVPTXMCAsmInfo.h</a>, definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxmcasminfo-cpp">NVPTXMCAsmInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxmcasminfo-cpp">NVPTXMCAsmInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxmcasminfo-h">NVPTXMCAsmInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
