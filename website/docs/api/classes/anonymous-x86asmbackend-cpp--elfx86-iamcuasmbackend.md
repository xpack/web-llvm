---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-x86asmbackend-cpp-/elfx86-iamcuasmbackend
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ELFX86_IAMCUAsmBackend` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{X86AsmBackend.cpp}::ELFX86_IAMCUAsmBackend { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/elfx86asmbackend">ELFX86AsmBackend</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4342b77a350dd1fbe795770f19bfdf9">ELFX86_IAMCUAsmBackend</a> (const Target &amp;T, uint8_t OSABI, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcobjecttargetwriter">MCObjectTargetWriter</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab06fb55f23a939d7383582d3acebb77c">createObjectTargetWriter</a> () const override</td>
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


<p>Definition at line 1092 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ELFX86\_IAMCUAsmBackend() {#ac4342b77a350dd1fbe795770f19bfdf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86AsmBackend.cpp}::ELFX86_IAMCUAsmBackend::ELFX86_IAMCUAsmBackend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, uint8_t OSABI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 1094 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/elfx86asmbackend/#a0cb189d00d8c497e861a7e2eb84eb87a">anonymous{X86AsmBackend.cpp}::ELFX86AsmBackend::ELFX86AsmBackend</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/elfx86asmbackend/#a46072da6a2a8ba555dc255c823e660ef">anonymous{X86AsmBackend.cpp}::ELFX86AsmBackend::OSABI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae35ef2e57b2c31572d967cb78484ffaa">llvm::createX86_32AsmBackend</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createObjectTargetWriter() {#ab06fb55f23a939d7383582d3acebb77c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MCObjectTargetWriter &gt; anonymous{X86AsmBackend.cpp}::ELFX86_IAMCUAsmBackend::createObjectTargetWriter ()</td>
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



<p>Definition at line 1099 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acb451d6d9cdcbf17e68e77abdf013ba5">llvm::createX86ELFObjectWriter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a523afcfc41d80d0b04a8eebf7b18030daf94f3540cf7f0fac3c8cf0cdde4e7b46">llvm::ELF::EM_IAMCU</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/elfx86asmbackend/#a46072da6a2a8ba555dc255c823e660ef">anonymous{X86AsmBackend.cpp}::ELFX86AsmBackend::OSABI</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp">X86AsmBackend.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
