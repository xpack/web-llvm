---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-aarch64asmbackend-cpp-/darwinaarch64asmbackend
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DarwinAArch64AsmBackend` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{AArch64AsmBackend.cpp}::DarwinAArch64AsmBackend { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-aarch64asmbackend-cpp-/aarch64asmbackend">AArch64AsmBackend</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac945b0d8be66879fb12fd546993c8a12">DarwinAArch64AsmBackend</a> (const Target &amp;T, const Triple &amp;TT, const MCRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e8a36df4b823e1054141017b4a9b7bc">createObjectTargetWriter</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26e5b6731c22761e5c4e7abe1dc13a21">generateCompactUnwindEncoding</a> (const MCDwarfFrameInfo *FI, const MCContext *Ctxt) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate the compact unwind encoding from the CFI directives. <a href="#a26e5b6731c22761e5c4e7abe1dc13a21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9f5d60b72d8d6be83b972dbcf25b013">encodeStackAdjustment</a> (uint32_t StackSize) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encode compact unwind stack adjustment for frameless functions. <a href="#ac9f5d60b72d8d6be83b972dbcf25b013">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1b749e05c43ce4566b37d31170d51be">MRI</a></td>
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


<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64asmbackend-cpp">AArch64AsmBackend.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DarwinAArch64AsmBackend() {#ac945b0d8be66879fb12fd546993c8a12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AArch64AsmBackend.cpp}::DarwinAArch64AsmBackend::DarwinAArch64AsmBackend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp; MRI)</td>
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



<p>Definition at line 598 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64asmbackend-cpp">AArch64AsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmbackend-cpp-/aarch64asmbackend/#a526a0b9f260fd4abd86775c9b069b04f">anonymous{AArch64AsmBackend.cpp}::AArch64AsmBackend::AArch64AsmBackend</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a676b531bfbeddd2a9614c12d21ad4c88">llvm::createAArch64leAsmBackend</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createObjectTargetWriter() {#a1e8a36df4b823e1054141017b4a9b7bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MCObjectTargetWriter &gt; anonymous{AArch64AsmBackend.cpp}::DarwinAArch64AsmBackend::createObjectTargetWriter ()</td>
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



<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64asmbackend-cpp">AArch64AsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc40b81be773102b1e6cf2af7d5300ea">llvm::createAArch64MachObjectWriter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a3f499fbedb1116d9243b169e32f12367">llvm::MachO::getCPUSubType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ada5bfd87ed7d3e85e1447626b2692055">llvm::MachO::getCPUType</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmbackend-cpp-/aarch64asmbackend/#ac8b3e70938bf2accfb94fb994e33eebb">anonymous{AArch64AsmBackend.cpp}::AArch64AsmBackend::TheTriple</a>.</p>

</div>
</div>

### generateCompactUnwindEncoding() {#a26e5b6731c22761e5c4e7abe1dc13a21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{AArch64AsmBackend.cpp}::DarwinAArch64AsmBackend::generateCompactUnwindEncoding (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo">MCDwarfFrameInfo</a> * FI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> * Ctxt)</td>
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

<p>Generate the compact unwind encoding from the CFI directives.</p>

<p>Definition at line 611 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64asmbackend-cpp">AArch64AsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a7374fa80c820bab9544f60931b8ca408">llvm::MCContext::emitCompactUnwindNonCanonical</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a1dd46e82704007e1b3b83ee229ffa79f">FPReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adbf6afc10ae6b65838f21620477623aa">llvm::getDRegFromBReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aef30e8b2caf06dd1513a1c9aacf45097">llvm::MCCFIInstruction::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a9d7ee9c6eaabde95dd9695326a77f253">llvm::MCCFIInstruction::getOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a57846002cda511da6585cb417cf9d392">llvm::MCCFIInstruction::getRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5690bb8ba0b629acff71bb5b4f2e5b4">llvm::getXRegFromWReg</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad678a6927d2876e9eb5fba111da70584">llvm::MCDwarfFrameInfo::Instructions</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a919e61fbc03b7b8a1660337897db7094">llvm::MCAsmBackend::isDarwinCanonicalPersonality</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6ecacbbd41f459c6cea155b66a7ba10f1058">llvm::MCCFIInstruction::OpDefCfa</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca5822faf65b27795cd48bd44712d48927">llvm::MCCFIInstruction::OpDefCfaOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca74ec33979cec7221719caa137b50da3f">llvm::MCCFIInstruction::OpOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#a3c371b9d29a2da49e836e29ac73b359b">llvm::MCDwarfFrameInfo::Personality</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmbackend-cpp-/cu/#a16405a544a6b03e51579487ecb9e37f6adac808bcc3f35561b42dee2cd280c1ef">anonymous{AArch64AsmBackend.cpp}::CU::UNWIND_ARM64_FRAME_D10_D11_PAIR</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmbackend-cpp-/cu/#a16405a544a6b03e51579487ecb9e37f6a0af2a34b6a8638fcc6b17f368f145ed0">anonymous{AArch64AsmBackend.cpp}::CU::UNWIND_ARM64_FRAME_D12_D13_PAIR</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmbackend-cpp-/cu/#a16405a544a6b03e51579487ecb9e37f6ad83c76554f0a5b2335d1d1fa329c3744">anonymous{AArch64AsmBackend.cpp}::CU::UNWIND_ARM64_FRAME_D14_D15_PAIR</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmbackend-cpp-/cu/#a16405a544a6b03e51579487ecb9e37f6a6ad85562e2e0bdfe6b0d7087f0be3219">anonymous{AArch64AsmBackend.cpp}::CU::UNWIND_ARM64_FRAME_D8_D9_PAIR</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmbackend-cpp-/cu/#a16405a544a6b03e51579487ecb9e37f6aba9c409a7664833e2847bb1ccf07419c">anonymous{AArch64AsmBackend.cpp}::CU::UNWIND_ARM64_FRAME_X19_X20_PAIR</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmbackend-cpp-/cu/#a16405a544a6b03e51579487ecb9e37f6a79bdc6acbe6e112f61db72f4957d099c">anonymous{AArch64AsmBackend.cpp}::CU::UNWIND_ARM64_FRAME_X21_X22_PAIR</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmbackend-cpp-/cu/#a16405a544a6b03e51579487ecb9e37f6a04b731c3240e635e185ccd51b4bdf6f3">anonymous{AArch64AsmBackend.cpp}::CU::UNWIND_ARM64_FRAME_X23_X24_PAIR</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmbackend-cpp-/cu/#a16405a544a6b03e51579487ecb9e37f6a4f25a0a71f42af3084ec8b5e1b0f6bd1">anonymous{AArch64AsmBackend.cpp}::CU::UNWIND_ARM64_FRAME_X25_X26_PAIR</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmbackend-cpp-/cu/#a16405a544a6b03e51579487ecb9e37f6a68942402a85c709fe1f44d789311372a">anonymous{AArch64AsmBackend.cpp}::CU::UNWIND_ARM64_FRAME_X27_X28_PAIR</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmbackend-cpp-/cu/#a16405a544a6b03e51579487ecb9e37f6aa773994800d86f27b3280d8b97fc7576">anonymous{AArch64AsmBackend.cpp}::CU::UNWIND_ARM64_MODE_DWARF</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmbackend-cpp-/cu/#a16405a544a6b03e51579487ecb9e37f6abd0383c872b2d87cf76523b8b4886101">anonymous{AArch64AsmBackend.cpp}::CU::UNWIND_ARM64_MODE_FRAME</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64asmbackend-cpp-/cu/#a16405a544a6b03e51579487ecb9e37f6a05eeb1b0006cfbee46a3ac9fb0d5a96c">anonymous{AArch64AsmBackend.cpp}::CU::UNWIND_ARM64_MODE_FRAMELESS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### encodeStackAdjustment() {#ac9f5d60b72d8d6be83b972dbcf25b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t anonymous{AArch64AsmBackend.cpp}::DarwinAArch64AsmBackend::encodeStackAdjustment (uint32_t StackSize)</td>
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

<p>Encode compact unwind stack adjustment for frameless functions.</p>


<p>See UNWIND_ARM64_FRAMELESS_STACK_SIZE_MASK in compact_unwind_encoding.h. The stack size always needs to be 16 byte aligned.</p>


<p>Definition at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64asmbackend-cpp">AArch64AsmBackend.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MRI {#ac1b749e05c43ce4566b37d31170d51be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCRegisterInfo&amp; anonymous{AArch64AsmBackend.cpp}::DarwinAArch64AsmBackend::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64asmbackend-cpp">AArch64AsmBackend.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64asmbackend-cpp">AArch64AsmBackend.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
