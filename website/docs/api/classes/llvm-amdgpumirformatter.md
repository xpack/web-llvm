---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgpumirformatter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AMDGPUMIRFormatter` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPUMIRFormatter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumirformatter-h">Target/AMDGPU/AMDGPUMIRFormatter.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mirformatter">MIRFormatter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MIRFormater - Interface to format MIR operand based on target. <a href="/web-llvm/docs/api/classes/llvm/mirformatter/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8c9d594c7f1654478ed349265ce1ee8">AMDGPUMIRFormatter</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24bb0971ba1766373c362ca64335f5ad">~AMDGPUMIRFormatter</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7b088af8e8d9bff6f48072ca3f03114">printImm</a> (raw_ostream &amp;OS, const MachineInstr &amp;MI, std::optional&lt; unsigned &gt; OpIdx, int64_t Imm) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement target specific printing for machine operand immediate value, so that we can have more meaningful mnemonic than a 64-bit integer. <a href="#aa7b088af8e8d9bff6f48072ca3f03114">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab82c73940b96a0a03b4f99acf2f77614">parseImmMnemonic</a> (const unsigned OpCode, const unsigned OpIdx, StringRef Src, int64_t &amp;Imm, ErrorCallbackType ErrorCallback) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement target specific parsing of immediate mnemonics. <a href="#ab82c73940b96a0a03b4f99acf2f77614">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95b74b885b1071adb9355810140524f2">parseCustomPseudoSourceValue</a> (StringRef Src, MachineFunction &amp;MF, PerFunctionMIParsingState &amp;PFS, const PseudoSourceValue *&amp;PSV, ErrorCallbackType ErrorCallback) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement target specific parsing of target custom pseudo source value. <a href="#a95b74b885b1071adb9355810140524f2">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0ceab2b96e729f21702ca8e08b57bbe">printSDelayAluImm</a> (int64_t Imm, llvm::raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the string to represent s_delay_alu immediate value. <a href="#ab0ceab2b96e729f21702ca8e08b57bbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd0758feef517f688700d327fefc483d">parseSDelayAluImmMnemonic</a> (const unsigned int OpIdx, int64_t &amp;Imm, llvm::StringRef &amp;Src, llvm::MIRFormatter::ErrorCallbackType &amp;ErrorCallback) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the immediate pseudo literal for s_delay_alu. <a href="#abd0758feef517f688700d327fefc483d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumirformatter-h">AMDGPUMIRFormatter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AMDGPUMIRFormatter() {#ae8c9d594c7f1654478ed349265ce1ee8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPUMIRFormatter::AMDGPUMIRFormatter ()</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumirformatter-h">AMDGPUMIRFormatter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AMDGPUMIRFormatter() {#a24bb0971ba1766373c362ca64335f5ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::AMDGPUMIRFormatter::~AMDGPUMIRFormatter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumirformatter-h">AMDGPUMIRFormatter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### parseCustomPseudoSourceValue() {#a95b74b885b1071adb9355810140524f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUMIRFormatter::parseCustomPseudoSourceValue (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Src, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate">PerFunctionMIParsingState</a> &amp; PFS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> *&amp; PSV, <a href="/web-llvm/docs/api/classes/llvm/mirformatter/#a3cf0479d0a1b76b416c3ca482bf19936">ErrorCallbackType</a> ErrorCallback)</td>
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

<p>Implement target specific parsing of target custom pseudo source value.</p>

<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumirformatter-h">AMDGPUMIRFormatter.h</a>, definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumirformatter-cpp">AMDGPUMIRFormatter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#af7fdaf467c5003b564b5079708ce5254">llvm::SIMachineFunctionInfo::getGWSPSV</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### parseImmMnemonic() {#ab82c73940b96a0a03b4f99acf2f77614}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUMIRFormatter::parseImmMnemonic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned OpCode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned OpIdx, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Src, int64_t &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/mirformatter/#a3cf0479d0a1b76b416c3ca482bf19936">ErrorCallbackType</a> ErrorCallback)</td>
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

<p>Implement target specific parsing of immediate mnemonics.</p>


<p>The mnemonic is a string with a leading dot.</p>


<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumirformatter-h">AMDGPUMIRFormatter.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumirformatter-cpp">AMDGPUMIRFormatter.cpp</a>.</p>

</div>
</div>

### printImm() {#aa7b088af8e8d9bff6f48072ca3f03114}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUMIRFormatter::printImm (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, std::optional&lt; unsigned &gt; OpIdx, int64_t Imm)</td>
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

<p>Implement target specific printing for machine operand immediate value, so that we can have more meaningful mnemonic than a 64-bit integer.</p>


<p>Passing None to OpIdx means the index is unknown.</p>


<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumirformatter-h">AMDGPUMIRFormatter.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumirformatter-cpp">AMDGPUMIRFormatter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/mirformatter/#aab0de54b603828aac17031e3d6c8ce17">llvm::MIRFormatter::printImm</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### parseSDelayAluImmMnemonic() {#abd0758feef517f688700d327fefc483d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUMIRFormatter::parseSDelayAluImmMnemonic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned int OpIdx, int64_t &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> &amp; Src, <a href="/web-llvm/docs/api/classes/llvm/mirformatter/#a3cf0479d0a1b76b416c3ca482bf19936">llvm::MIRFormatter::ErrorCallbackType</a> &amp; ErrorCallback)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the immediate pseudo literal for s_delay_alu.</p>

<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumirformatter-h">AMDGPUMIRFormatter.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumirformatter-cpp">AMDGPUMIRFormatter.cpp</a>.</p>

</div>
</div>

### printSDelayAluImm() {#ab0ceab2b96e729f21702ca8e08b57bbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUMIRFormatter::printSDelayAluImm (int64_t Imm, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">llvm::raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the string to represent s_delay_alu immediate value.</p>

<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumirformatter-h">AMDGPUMIRFormatter.h</a>, definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumirformatter-cpp">AMDGPUMIRFormatter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumirformatter-cpp">AMDGPUMIRFormatter.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumirformatter-h">AMDGPUMIRFormatter.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
