---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/webassemblymcasminfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `WebAssemblyMCAsmInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::WebAssemblyMCAsmInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymcasminfo-h">Target/WebAssembly/MCTargetDesc/WebAssemblyMCAsmInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasminfowasm">MCAsmInfoWasm</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeedabbbedf55686897e99e0f50249f66">WebAssemblyMCAsmInfo</a> (const Triple &amp;T, const MCTargetOptions &amp;Options)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecc6f4c5ef0bdacc58d323d9d9df697e">~WebAssemblyMCAsmInfo</a> () override</td>
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


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymcasminfo-h">WebAssemblyMCAsmInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WebAssemblyMCAsmInfo() {#aeedabbbedf55686897e99e0f50249f66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WebAssemblyMCAsmInfo::WebAssemblyMCAsmInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> &amp; Options)</td>
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



<p>Declaration at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymcasminfo-h">WebAssemblyMCAsmInfo.h</a>, definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymcasminfo-cpp">WebAssemblyMCAsmInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ac150f03927bf41531f945b3bc5b315e4">llvm::MCAsmInfo::AlignmentIsInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#aeb608789bae103384e251c302a2215f9">llvm::MCAsmInfo::CalleeSaveStackSlotSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ae243a845fe9d46ed2cb7403700921e4a">llvm::MCAsmInfo::CodePointerSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ac0079bf3834ce7ee765d437aae0a8a69">llvm::MCAsmInfo::COMMDirectiveAlignmentIsInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a035c98c0423e6dd21ec2ea039f762440">llvm::MCAsmInfo::Data16bitsDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a620b2ebe9e68a34106b7bdcc4220c6b2">llvm::MCAsmInfo::Data32bitsDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a3c136967a2fc9489724bcd8706a16fed">llvm::MCAsmInfo::Data64bitsDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a3aabcaa0b460b2ea508314bf21c2ffd9">llvm::MCAsmInfo::Data8bitsDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a500ba2b2c0203d1d53b83a649551a6b5">llvm::MCAsmInfo::ExceptionsType</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a6f7c7ae850927432e251d9a5f8bb0537">llvm::MCAsmInfo::LCOMMDirectiveAlignmentType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lcomm/#aae933cd10a930a5312da96502035e331adce83244e971c1aeafe5840c91d9be0b">llvm::LCOMM::Log2Alignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a98f40236cfff7278d4b57633fad2245d">llvm::MCAsmInfo::SupportsDebugInformation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ad8ce9bafbf33806b98fec165f653a72b">llvm::MCAsmInfo::UseDataRegionDirectives</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84af93da81fd23e2eeaf8de29b04bb2399f">llvm::Wasm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a83d68f56b86e580ac9d156b47af53c2c">llvm::WebAssembly::WasmEnableEH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a877b8fcf196f226d4f2289ebdb1f276b">llvm::WebAssembly::WasmEnableSjLj</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#acf84c6bd03a785a251784cad666d9ee1">llvm::MCAsmInfo::ZeroDirective</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~WebAssemblyMCAsmInfo() {#aecc6f4c5ef0bdacc58d323d9d9df697e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WebAssemblyMCAsmInfo::~WebAssemblyMCAsmInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymcasminfo-h">WebAssemblyMCAsmInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymcasminfo-cpp">WebAssemblyMCAsmInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymcasminfo-h">WebAssemblyMCAsmInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
