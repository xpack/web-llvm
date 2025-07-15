---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcinstbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCInstBuilder` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MCInstBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstbuilder-h">llvm/MC/MCInstBuilder.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9de8dd26280fe4aa3bf0dbc3d59eb1a9">MCInstBuilder</a> (unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new <a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder">MCInstBuilder</a> for an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> with a specific opcode. <a href="#a9de8dd26280fe4aa3bf0dbc3d59eb1a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c72877f39b7f30a22e17b6653b71991">operator MCInst &amp;</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder">MCInstBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a003cdc56c0ea0f09a25e034d65e44215">setLoc</a> (SMLoc SM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the location. <a href="#a003cdc56c0ea0f09a25e034d65e44215">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder">MCInstBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b9700052102985a61c9cf62b71d68f0">addReg</a> (MCRegister Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new register operand. <a href="#a2b9700052102985a61c9cf62b71d68f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder">MCInstBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6bfc040ddca811a88a95e1f6d6b3747">addImm</a> (int64_t Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new integer immediate operand. <a href="#ac6bfc040ddca811a88a95e1f6d6b3747">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder">MCInstBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54eb54113b3e3294c9239b4926c5593e">addSFPImm</a> (uint32_t Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new single floating point immediate operand. <a href="#a54eb54113b3e3294c9239b4926c5593e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder">MCInstBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abad64db289073fd52a0bb0f20f4f3e82">addDFPImm</a> (uint64_t Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new floating point immediate operand. <a href="#abad64db289073fd52a0bb0f20f4f3e82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder">MCInstBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad824e6c64e2015a9fbaba9a4c9d0a7b9">addExpr</a> (const MCExpr *Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> operand. <a href="#ad824e6c64e2015a9fbaba9a4c9d0a7b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder">MCInstBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ba00db86c29454bb2964094906ca88b">addInst</a> (const MCInst *Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a new <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> operand. <a href="#a1ba00db86c29454bb2964094906ca88b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder">MCInstBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6990ced5e71387ca4e8aaa1c4f96b380">addOperand</a> (const MCOperand &amp;Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an operand. <a href="#a6990ced5e71387ca4e8aaa1c4f96b380">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a234d1f32da2ef86b83bd11f07b1cf631">Inst</a></td>
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


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstbuilder-h">MCInstBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCInstBuilder() {#a9de8dd26280fe4aa3bf0dbc3d59eb1a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCInstBuilder::MCInstBuilder (unsigned Opcode)</td>
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

<p>Create a new <a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder">MCInstBuilder</a> for an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> with a specific opcode.</p>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstbuilder-h">MCInstBuilder.h</a>.</p>


<p>Referenced by <a href="#abad64db289073fd52a0bb0f20f4f3e82">addDFPImm</a>, <a href="#ad824e6c64e2015a9fbaba9a4c9d0a7b9">addExpr</a>, <a href="#ac6bfc040ddca811a88a95e1f6d6b3747">addImm</a>, <a href="#a1ba00db86c29454bb2964094906ca88b">addInst</a>, <a href="#a6990ced5e71387ca4e8aaa1c4f96b380">addOperand</a>, <a href="#a2b9700052102985a61c9cf62b71d68f0">addReg</a>, <a href="#a54eb54113b3e3294c9239b4926c5593e">addSFPImm</a> and <a href="#a003cdc56c0ea0f09a25e034d65e44215">setLoc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator MCInst &amp;() {#a6c72877f39b7f30a22e17b6653b71991}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCInstBuilder::operator MCInst &amp; ()</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstbuilder-h">MCInstBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addDFPImm() {#abad64db289073fd52a0bb0f20f4f3e82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstBuilder &amp; llvm::MCInstBuilder::addDFPImm (uint64_t Val)</td>
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

<p>Add a new floating point immediate operand.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstbuilder-h">MCInstBuilder.h</a>.</p>


<p>References <a href="#a6990ced5e71387ca4e8aaa1c4f96b380">addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ad813d2ab5c4ffc7d5f6172735b44ca1a">llvm::MCOperand::createDFPImm</a> and <a href="#a9de8dd26280fe4aa3bf0dbc3d59eb1a9">MCInstBuilder</a>.</p>

</div>
</div>

### addExpr() {#ad824e6c64e2015a9fbaba9a4c9d0a7b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstBuilder &amp; llvm::MCInstBuilder::addExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Val)</td>
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

<p>Add a new <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> operand.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstbuilder-h">MCInstBuilder.h</a>.</p>


<p>References <a href="#a6990ced5e71387ca4e8aaa1c4f96b380">addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a> and <a href="#a9de8dd26280fe4aa3bf0dbc3d59eb1a9">MCInstBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a8dce3e9284d907db3457ebbfc74909f7">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#a4123a254ab36bc97c087331e6cb38665">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzasmprinter/#a25956df5af6db1ef928aa17999d28727">llvm::SystemZAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/x86asmprinter/#a1959523b897eac43ed99525fd9849be1">llvm::X86AsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a0c5eda02c50a11f3dde025afe0675b6e">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::EmitTlsCall</a> and <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#abb7cbfc91aec970d7d9b935b81f8db66">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::expandFunctionCall</a>.</p>

</div>
</div>

### addImm() {#ac6bfc040ddca811a88a95e1f6d6b3747}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstBuilder &amp; llvm::MCInstBuilder::addImm (int64_t Val)</td>
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

<p>Add a new integer immediate operand.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstbuilder-h">MCInstBuilder.h</a>.</p>


<p>References <a href="#a6990ced5e71387ca4e8aaa1c4f96b380">addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a> and <a href="#a9de8dd26280fe4aa3bf0dbc3d59eb1a9">MCInstBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a8dce3e9284d907db3457ebbfc74909f7">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzasmprinter/#a25956df5af6db1ef928aa17999d28727">llvm::SystemZAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymccodeemitter/#adaafdf331200e6510034c6a3680f5a34">llvm::CSKYMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#abb7cbfc91aec970d7d9b935b81f8db66">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::expandFunctionCall</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymccodeemitter/#a4a7ca70410938579ebcd69725c1abab0">llvm::CSKYMCCodeEmitter::expandJBTF</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#aa9f55bb589105b8751fa61098690db0b">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::expandLongCondBr</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymccodeemitter/#aad532d3d4fbb58bd93d97bdfeee21dcf">llvm::CSKYMCCodeEmitter::expandNEG</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymccodeemitter/#aabea40b68294ad7754d882cad63b5298">llvm::CSKYMCCodeEmitter::expandRSUBI</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#a949f92840302b18bc451d406ddeb09a9">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::expandTLSDESCCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmccodeemitter-cpp-/loongarchmccodeemitter/#a3985c640bde224e8ef6b275f9a1e3be7">anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::expandToVectorLDI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvmatint/#a829402a713d109eae3d7945c88f33255">llvm::RISCVMatInt::generateMCInstSeq</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#af373607877e9c76b500c1942c86e8da2">llvm::AArch64InstrInfo::getNop</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a408601da70bde1bd6239443476c13d6f">llvm::HexagonInstrInfo::getNop</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a65cef9ee9bfa5c5549b3b3758b6247f6">llvm::LoongArchInstrInfo::getNop</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a8e9da3ff990db8ea36450b9ba4f892b3">llvm::RISCVInstrInfo::getNop</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a9f3014dd5d395d0e11fd2efedde63ac7">llvm::Thumb1InstrInfo::getNop</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#ade22dde6e6e9e21d725f2d8f92258eab">llvm::Thumb2InstrInfo::getNop</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a4b5ab0b13d0a554ac6b9db1ef8a988bd">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::LowerKCFI_CHECK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#aff8749491e795a239d50e5073d9c6c3d">lowerRIEfLow</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#aa35546976f2247d92d87b67efb61b529">lowerRIHigh</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#a80b4a8ba65789bdb6aa8e88a36a0d752">lowerRILow</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#af8d4cfe6b93149556d17ef6b8fe8713f">lowerSubvectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#acd38c0e4fda856c62c4cead791a9285f">lowerSubvectorStore</a> and <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a2bf52a4c2353e5edda7215415b608d12">llvm::ARMAsmPrinter::runOnMachineFunction</a>.</p>

</div>
</div>

### addInst() {#a1ba00db86c29454bb2964094906ca88b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstBuilder &amp; llvm::MCInstBuilder::addInst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> * Val)</td>
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

<p>Add a new <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> operand.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstbuilder-h">MCInstBuilder.h</a>.</p>


<p>References <a href="#a6990ced5e71387ca4e8aaa1c4f96b380">addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ae86bea5bf6fe3c0a2a9f09f5fdc4a310">llvm::MCOperand::createInst</a> and <a href="#a9de8dd26280fe4aa3bf0dbc3d59eb1a9">MCInstBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a408601da70bde1bd6239443476c13d6f">llvm::HexagonInstrInfo::getNop</a>.</p>

</div>
</div>

### addOperand() {#a6990ced5e71387ca4e8aaa1c4f96b380}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstBuilder &amp; llvm::MCInstBuilder::addOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; Op)</td>
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

<p>Add an operand.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstbuilder-h">MCInstBuilder.h</a>.</p>


<p>References <a href="#a6990ced5e71387ca4e8aaa1c4f96b380">addOperand</a> and <a href="#a9de8dd26280fe4aa3bf0dbc3d59eb1a9">MCInstBuilder</a>.</p>


<p>Referenced by <a href="#abad64db289073fd52a0bb0f20f4f3e82">addDFPImm</a>, <a href="#ad824e6c64e2015a9fbaba9a4c9d0a7b9">addExpr</a>, <a href="#ac6bfc040ddca811a88a95e1f6d6b3747">addImm</a>, <a href="#a1ba00db86c29454bb2964094906ca88b">addInst</a>, <a href="#a6990ced5e71387ca4e8aaa1c4f96b380">addOperand</a>, <a href="#a2b9700052102985a61c9cf62b71d68f0">addReg</a>, <a href="#a54eb54113b3e3294c9239b4926c5593e">addSFPImm</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymccodeemitter/#adaafdf331200e6510034c6a3680f5a34">llvm::CSKYMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmccodeemitter-cpp-/loongarchmccodeemitter/#ac6740cbf8bbdd52574f85db63500cd25">anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::expandAddTPRel</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#afa2b2e58e0859c0608b6f10a8ad1c79f">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::expandAddTPRel</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymccodeemitter/#a4a7ca70410938579ebcd69725c1abab0">llvm::CSKYMCCodeEmitter::expandJBTF</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#aa9f55bb589105b8751fa61098690db0b">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::expandLongCondBr</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymccodeemitter/#aad532d3d4fbb58bd93d97bdfeee21dcf">llvm::CSKYMCCodeEmitter::expandNEG</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymccodeemitter/#aabea40b68294ad7754d882cad63b5298">llvm::CSKYMCCodeEmitter::expandRSUBI</a> and <a href="/web-llvm/docs/api/classes/anonymous-loongarchmccodeemitter-cpp-/loongarchmccodeemitter/#a3985c640bde224e8ef6b275f9a1e3be7">anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::expandToVectorLDI</a>.</p>

</div>
</div>

### addReg() {#a2b9700052102985a61c9cf62b71d68f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstBuilder &amp; llvm::MCInstBuilder::addReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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

<p>Add a new register operand.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstbuilder-h">MCInstBuilder.h</a>.</p>


<p>References <a href="#a6990ced5e71387ca4e8aaa1c4f96b380">addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a9de8dd26280fe4aa3bf0dbc3d59eb1a9">MCInstBuilder</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a8dce3e9284d907db3457ebbfc74909f7">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppclinuxasmprinter/#a4123a254ab36bc97c087331e6cb38665">anonymous{PPCAsmPrinter.cpp}::PPCLinuxAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#ac09670e222cb6d4948119b60fd4f3e6e">llvm::ARMAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzasmprinter/#a25956df5af6db1ef928aa17999d28727">llvm::SystemZAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/x86asmprinter/#a1959523b897eac43ed99525fd9849be1">llvm::X86AsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#abb7cbfc91aec970d7d9b935b81f8db66">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::expandFunctionCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#aa9f55bb589105b8751fa61098690db0b">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::expandLongCondBr</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter/#a949f92840302b18bc451d406ddeb09a9">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::expandTLSDESCCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvmatint/#a829402a713d109eae3d7945c88f33255">llvm::RISCVMatInt::generateMCInstSeq</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a65cef9ee9bfa5c5549b3b3758b6247f6">llvm::LoongArchInstrInfo::getNop</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a8e9da3ff990db8ea36450b9ba4f892b3">llvm::RISCVInstrInfo::getNop</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a9f3014dd5d395d0e11fd2efedde63ac7">llvm::Thumb1InstrInfo::getNop</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#ade22dde6e6e9e21d725f2d8f92258eab">llvm::Thumb2InstrInfo::getNop</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a4b5ab0b13d0a554ac6b9db1ef8a988bd">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::LowerKCFI_CHECK</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a22c90a0d582e484ad655a9f337002b05">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerMOVaddrPAC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#aff8749491e795a239d50e5073d9c6c3d">lowerRIEfLow</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#aa35546976f2247d92d87b67efb61b529">lowerRIHigh</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#a80b4a8ba65789bdb6aa8e88a36a0d752">lowerRILow</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#af8d4cfe6b93149556d17ef6b8fe8713f">lowerSubvectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#acd38c0e4fda856c62c4cead791a9285f">lowerSubvectorStore</a> and <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a2bf52a4c2353e5edda7215415b608d12">llvm::ARMAsmPrinter::runOnMachineFunction</a>.</p>

</div>
</div>

### addSFPImm() {#a54eb54113b3e3294c9239b4926c5593e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstBuilder &amp; llvm::MCInstBuilder::addSFPImm (uint32_t Val)</td>
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

<p>Add a new single floating point immediate operand.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstbuilder-h">MCInstBuilder.h</a>.</p>


<p>References <a href="#a6990ced5e71387ca4e8aaa1c4f96b380">addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a28d125e6f6bba87ccb0032ddceeb6c47">llvm::MCOperand::createSFPImm</a> and <a href="#a9de8dd26280fe4aa3bf0dbc3d59eb1a9">MCInstBuilder</a>.</p>

</div>
</div>

### setLoc() {#a003cdc56c0ea0f09a25e034d65e44215}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstBuilder &amp; llvm::MCInstBuilder::setLoc (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> SM)</td>
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

<p>Set the location.</p>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstbuilder-h">MCInstBuilder.h</a>.</p>


<p>References <a href="#a9de8dd26280fe4aa3bf0dbc3d59eb1a9">MCInstBuilder</a> and <a href="#a003cdc56c0ea0f09a25e034d65e44215">setLoc</a>.</p>


<p>Referenced by <a href="#a003cdc56c0ea0f09a25e034d65e44215">setLoc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Inst {#a234d1f32da2ef86b83bd11f07b1cf631}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInst llvm::MCInstBuilder::Inst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstbuilder-h">MCInstBuilder.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstbuilder-h">MCInstBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
