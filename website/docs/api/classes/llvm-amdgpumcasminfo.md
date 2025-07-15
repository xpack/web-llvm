---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgpumcasminfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AMDGPUMCAsmInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPUMCAsmInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcasminfo-h">Target/AMDGPU/MCTargetDesc/AMDGPUMCAsmInfo.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19016cbffc3d1438e542dba773f5a9bd">AMDGPUMCAsmInfo</a> (const Triple &amp;TT, const MCTargetOptions &amp;Options)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf19d3b66e114232ade937d6a7e9c654">shouldOmitSectionDirective</a> (StringRef SectionName) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the .section directive should be omitted when emitting <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/sectionname">SectionName</a></span>. <a href="#adf19d3b66e114232ade937d6a7e9c654">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a081e0d017dbcb21393b0e55d70d4550c">getMaxInstLength</a> (const MCSubtargetInfo *STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the maximum possible encoded instruction size in bytes. <a href="#a081e0d017dbcb21393b0e55d70d4550c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcasminfo-h">AMDGPUMCAsmInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AMDGPUMCAsmInfo() {#a19016cbffc3d1438e542dba773f5a9bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPUMCAsmInfo::AMDGPUMCAsmInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> &amp; Options)</td>
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



<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcasminfo-h">AMDGPUMCAsmInfo.h</a>, definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcasminfo-cpp">AMDGPUMCAsmInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a387d88fc1b536facc13f5a41170250b0">llvm::Triple::amdgcn</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ae243a845fe9d46ed2cb7403700921e4a">llvm::MCAsmInfo::CodePointerSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ac0079bf3834ce7ee765d437aae0a8a69">llvm::MCAsmInfo::COMMDirectiveAlignmentIsInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#af30c385b021a371a04bacd22cef94c7b">llvm::MCAsmInfo::CommentString</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#adcdd548ad577bc7c4c2e43f2f38cb1b4">llvm::MCAsmInfo::DwarfRegNumForCFI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a15bacf592302115a438444da1b9517e4">llvm::MCAsmInfo::HasNoDeadStrip</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ab74c767922c89f683dec73c5b9a7b87a">llvm::MCAsmInfo::HasSingleParameterDotFile</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#aa238b30c1afd57422b374a9cb2edc4df">llvm::MCAsmInfo::InlineAsmEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a87ec076e2f46691b519f60545904269c">llvm::MCAsmInfo::InlineAsmStart</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a824f02b302d147245dc0f553c63428db">llvm::MCAsmInfo::MaxInstLength</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a139e22bc2c357349563ce30a503d13fd">llvm::MCAsmInfo::MinInstAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#aabcffa0fe7b36126687bc1f1ea65fa91">llvm::MCAsmInfo::SeparatorString</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a9e5942554aaf9a1c2dbde04c503c11b2">llvm::MCAsmInfo::StackGrowsUp</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a98f40236cfff7278d4b57633fad2245d">llvm::MCAsmInfo::SupportsDebugInformation</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a624dfc3c9dd72db826eca195ed423535">llvm::MCAsmInfo::UseIntegratedAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ab1ef887b0a356cedf933a5f3e7cc40d9">llvm::MCAsmInfo::UsesCFIWithoutEH</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a9209a7aeb154de066a5f7ed6087892cc">llvm::MCAsmInfo::UsesELFSectionDirectiveForBSS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getMaxInstLength() {#a081e0d017dbcb21393b0e55d70d4550c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPUMCAsmInfo::getMaxInstLength (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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

<p>Returns the maximum possible encoded instruction size in bytes.</p>


<p>If <span class="doxyComputerOutput">STI</span> is null, this should be the maximum size for any subtarget.</p>


<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcasminfo-h">AMDGPUMCAsmInfo.h</a>, definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcasminfo-cpp">AMDGPUMCAsmInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a5fc23559f17bbe5ff83ec0fed0a5fdcf">llvm::Triple::getArch</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a1ef6ef4ff039e873e9f66e21e3e55e26">llvm::MCSubtargetInfo::getTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a824f02b302d147245dc0f553c63428db">llvm::MCAsmInfo::MaxInstLength</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a060ea888d89f5d59a5743118e429296f">llvm::Triple::r600</a>.</p>

</div>
</div>

### shouldOmitSectionDirective() {#adf19d3b66e114232ade937d6a7e9c654}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUMCAsmInfo::shouldOmitSectionDirective (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName)</td>
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

<p>Return true if the .section directive should be omitted when emitting <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/sectionname">SectionName</a></span>.</p>


<p>For example:</p>


<p>shouldOmitSectionDirective(".text")</p>


<p>returns false =&gt; .section .text,#alloc,#execinstr returns true =&gt; .text</p>


<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcasminfo-h">AMDGPUMCAsmInfo.h</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcasminfo-cpp">AMDGPUMCAsmInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#aac7daa6624215575aaf2642545bfd9bf">llvm::MCAsmInfo::shouldOmitSectionDirective</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcasminfo-cpp">AMDGPUMCAsmInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcasminfo-h">AMDGPUMCAsmInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
