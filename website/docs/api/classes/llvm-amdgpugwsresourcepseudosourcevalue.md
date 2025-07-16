---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgpugwsresourcepseudosourcevalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AMDGPUGWSResourcePseudoSourceValue` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPUGWSResourcePseudoSourceValue { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">Target/AMDGPU/SIMachineFunctionInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpupseudosourcevalue">AMDGPUPseudoSourceValue</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74dd494eb5ad3484b0bbc6aeaea396e6">AMDGPUGWSResourcePseudoSourceValue</a> (const AMDGPUTargetMachine &amp;TM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0c9dd661a9232174cc9df932e6c5ef1">isAliased</a> (const MachineFrameInfo *) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the memory pointed to by this <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> may also be pointed to by an LLVM IR <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="#ab0c9dd661a9232174cc9df932e6c5ef1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac61f96cb055eb6c11442cdba748dbd9">mayAlias</a> (const MachineFrameInfo *) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the memory pointed to by this <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> can ever alias an LLVM IR <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="#aac61f96cb055eb6c11442cdba748dbd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a0657756114b42300c74c24e47fbba8">printCustom</a> (raw_ostream &amp;OS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement printing for <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a>. <a href="#a0a0657756114b42300c74c24e47fbba8">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a4e5e9f0ab04343a9c16d93a7d7871c">classof</a> (const PseudoSourceValue *V)</td>
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


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AMDGPUGWSResourcePseudoSourceValue() {#a74dd494eb5ad3484b0bbc6aeaea396e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPUGWSResourcePseudoSourceValue::AMDGPUGWSResourcePseudoSourceValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine">AMDGPUTargetMachine</a> &amp; TM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/amdgpupseudosourcevalue/#a360cad3f092e5c503eff88c5b6ef82f0">llvm::AMDGPUPseudoSourceValue::AMDGPUPseudoSourceValue</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpupseudosourcevalue/#ac1988f325ca94dd7396982b41348737aa614f353bb83d312a7967338d90a99997">llvm::AMDGPUPseudoSourceValue::GWSResource</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isAliased() {#ab0c9dd661a9232174cc9df932e6c5ef1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUGWSResourcePseudoSourceValue::isAliased (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> *)</td>
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

<p>Test whether the memory pointed to by this <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> may also be pointed to by an LLVM IR <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>

</div>
</div>

### mayAlias() {#aac61f96cb055eb6c11442cdba748dbd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUGWSResourcePseudoSourceValue::mayAlias (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> *)</td>
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

<p>Return true if the memory pointed to by this <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> can ever alias an LLVM IR <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>

</div>
</div>

### printCustom() {#a0a0657756114b42300c74c24e47fbba8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AMDGPUGWSResourcePseudoSourceValue::printCustom (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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

<p>Implement printing for <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a>.</p>


<p>This is called from <a href="/web-llvm/docs/api/classes/llvm/value/#a1e56c814d11206720cc23059b871128d">Value::print</a> or <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>'s operator&lt;&lt;.</p>


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a1a4e5e9f0ab04343a9c16d93a7d7871c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUGWSResourcePseudoSourceValue::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pseudosourcevalue">PseudoSourceValue</a> * V)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/amdgpupseudosourcevalue/#ac1988f325ca94dd7396982b41348737aa614f353bb83d312a7967338d90a99997">llvm::AMDGPUPseudoSourceValue::GWSResource</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
