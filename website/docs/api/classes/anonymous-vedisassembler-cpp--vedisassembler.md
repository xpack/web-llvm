---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-vedisassembler-cpp-/vedisassembler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `VEDisassembler` Class Reference

<p>A disassembler class for <a href="/web-llvm/docs/api/namespaces/llvm/ve">VE</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{VEDisassembler.cpp}::VEDisassembler { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Superclass for all disassemblers. <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f3375e11a9577cdac832a11a6c0d28b">VEDisassembler</a> (const MCSubtargetInfo &amp;STI, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a554e2369c8f276e2b171578887742f37">~VEDisassembler</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73f28e529d7fea5bf343716c3f6c12ba">getInstruction</a> (MCInst &amp;Instr, uint64_t &amp;Size, ArrayRef&lt; uint8_t &gt; Bytes, uint64_t Address, raw_ostream &amp;CStream) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the disassembly of a single instruction. <a href="#a73f28e529d7fea5bf343716c3f6c12ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A disassembler class for <a href="/web-llvm/docs/api/namespaces/llvm/ve">VE</a>.</p>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp">VEDisassembler.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VEDisassembler() {#a1f3375e11a9577cdac832a11a6c0d28b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{VEDisassembler.cpp}::VEDisassembler::VEDisassembler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp">VEDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a07639073d0bfe2f90b94ced7f2944596">llvm::MCDisassembler::MCDisassembler</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp/#aede8def5ce26e9dde4fc490d24bf9996">createVEDisassembler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~VEDisassembler() {#a554e2369c8f276e2b171578887742f37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual anonymous{VEDisassembler.cpp}::VEDisassembler::~VEDisassembler ()</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp">VEDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="#a73f28e529d7fea5bf343716c3f6c12ba">getInstruction</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getInstruction() {#a73f28e529d7fea5bf343716c3f6c12ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus VEDisassembler::getInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Instr, uint64_t &amp; Size, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Bytes, uint64_t Address, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; CStream)</td>
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

<p>Returns the disassembly of a single instruction.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Instr</td>
<td class="doxyParamItemDescription"><p>- An MCInst to populate with the contents of the instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>- A value to populate with the size of the instruction, or the number of bytes consumed while attempting to decode an invalid instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Address</td>
<td class="doxyParamItemDescription"><p>- The address, in the memory space of region, of the first byte of the instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Bytes</td>
<td class="doxyParamItemDescription"><p>- A reference to the actual bytes of the instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CStream</td>
<td class="doxyParamItemDescription"><p>- The stream to print comments and annotations on.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- MCDisassembler::Success if the instruction is valid, MCDisassembler::SoftFail if the instruction was disassemblable but invalid, MCDisassembler::Fail if the instruction was invalid.</p></dd>
</dl>


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp">VEDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a3faa10cafd0be721018fc1b9bc2c5488">llvm::MCDisassembler::getContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp/#a3fcc2328b16aab5f5620750b7e9b4c41">readInstruction64</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>


<p>Referenced by <a href="#a554e2369c8f276e2b171578887742f37">~VEDisassembler</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp">VEDisassembler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
