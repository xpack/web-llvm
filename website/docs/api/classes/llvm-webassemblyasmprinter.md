---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/webassemblyasmprinter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `WebAssemblyAsmPrinter` Class



## Declaration

<div class="doxyDeclaration">
class llvm::WebAssemblyAsmPrinter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">Target/WebAssembly/WebAssemblyAsmPrinter.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class is intended to be used as a driving class for all asm writers. <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75225c64245214556dda42b8d778eca9">WebAssemblyAsmPrinter</a> (TargetMachine &amp;TM, std::unique_ptr&lt; MCStreamer &gt; Streamer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05033ee0700043d8631ea334b3cb8170">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a05033ee0700043d8631ea334b3cb8170">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/webassemblysubtarget">WebAssemblySubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bdc58ed97a30a3aa2c8b78ea08f04b2">getSubtarget</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a897bd48044b4c136754a489e5e9c0967">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the specified function out to the OutStreamer. <a href="#a897bd48044b4c136754a489e5e9c0967">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0cbac92300c3074e6bb81d58e92a86b">emitEndOfAsmFile</a> (Module &amp;M) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This virtual method can be overridden by targets that want to emit something at the end of their file. <a href="#af0cbac92300c3074e6bb81d58e92a86b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a013467bb98e0c35a48763e22de49cc75">EmitProducerInfo</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06dab5b53d53c65a118f25ea11570352">EmitTargetFeatures</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedbc3a6b1ed39b77650edac4239774cf">EmitFunctionAttributes</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d155a589e83947673539f155aa88172">emitSymbolType</a> (const MCSymbolWasm *Sym)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0202522d1384c2ad88417c496ae62068">emitGlobalVariable</a> (const GlobalVariable *GV) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the specified global variable to the .s file. <a href="#a0202522d1384c2ad88417c496ae62068">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00c3b9300cf6108db77e784317aec777">emitJumpTableInfo</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print assembly representations of the jump tables used by the current function to the current output stream. <a href="#a00c3b9300cf6108db77e784317aec777">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b28e8554e69354731d399f7d68129ce">emitConstantPool</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print to the current output stream assembly representations of the constants in the constant pool MCP. <a href="#a5b28e8554e69354731d399f7d68129ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2ead336a250ceb168df7c3cefc1988e">emitFunctionBodyStart</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets can override this to emit stuff before the first basic block in the function. <a href="#aa2ead336a250ceb168df7c3cefc1988e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42cd82bf5091d26adbbfb2eb56026b43">emitInstruction</a> (const MachineInstr *MI) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets should implement this to emit instructions. <a href="#a42cd82bf5091d26adbbfb2eb56026b43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3b56dc8749765fe615f325594493167">PrintAsmOperand</a> (const MachineInstr *MI, unsigned OpNo, const char *ExtraCode, raw_ostream &amp;OS) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the specified operand of MI, an INLINEASM instruction, using the specified assembler variant. <a href="#ab3b56dc8749765fe615f325594493167">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16563560b6ca95512cfdcd6595221db2">PrintAsmMemoryOperand</a> (const MachineInstr *MI, unsigned OpNo, const char *ExtraCode, raw_ostream &amp;OS) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the specified operand of MI, an INLINEASM instruction, using the specified assembler variant as an address. <a href="#a16563560b6ca95512cfdcd6595221db2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b134d4df9353786cf749d861b77b792">getRegType</a> (unsigned RegNo) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c5b93703bfd35ff033b6fd30c2b8ee7">regToString</a> (const MachineOperand &amp;MO)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/webassemblytargetstreamer">WebAssemblyTargetStreamer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42b2a805173bc1cc36a6a59861107fe3">getTargetStreamer</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm">MCSymbolWasm</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfb93588e65e2c1c3e35ba88168478c5">getMCSymbolForFunction</a> (const Function *F, bool EnableEmEH, wasm::WasmSignature *Sig, bool &amp;InvokeDetected)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d95a71faaca9c18ee44f1942b77c716">getOrCreateWasmSymbol</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa29ca0ef805870463b1abf3171c5cf1c">emitDecls</a> (const Module &amp;M)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/webassemblysubtarget">WebAssemblySubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6ec45a0a952c7ac58bdd1fb427fb066">Subtarget</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3263a8a988940518ce85187bf87c75e">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/webassemblyfunctioninfo">WebAssemblyFunctionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3788a9c4a8a0b2b11ada8494135cca97">MFI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a236ac34be0935d8c821bf35699065a88">signaturesEmitted</a> = false</td>
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


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WebAssemblyAsmPrinter() {#a75225c64245214556dda42b8d778eca9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::WebAssemblyAsmPrinter::WebAssemblyAsmPrinter (<a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &gt; Streamer)</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#afcfe4636c15aaef711e33ecc8638f9b4">llvm::AsmPrinter::AsmPrinter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitConstantPool() {#a5b28e8554e69354731d399f7d68129ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WebAssemblyAsmPrinter::emitConstantPool ()</td>
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

<p>Print to the current output stream assembly representations of the constants in the constant pool MCP.</p>


<p>EmitConstantPool - Print to the current output stream assembly representations of the constants in the constant pool MCP.</p>


<p>This is used to print out constants which have been "spilled to memory" by the code generator.</p>


<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>, definition at line 601 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-cpp">WebAssemblyAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa29ca0ef805870463b1abf3171c5cf1c">emitDecls</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa1316da87e093c08b6657877572b19a4">llvm::AsmPrinter::MMI</a>.</p>

</div>
</div>

### emitDecls() {#aa29ca0ef805870463b1abf3171c5cf1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WebAssemblyAsmPrinter::emitDecls (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>, definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-cpp">WebAssemblyAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e263b9cd2bdbbbaf3d78a2caba5cbf5">llvm::computeSignatureVTs</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetstreamer/#a570c02e3766c7ab80637f2afe5e2b2c1">llvm::WebAssemblyTargetStreamer::emitExportName</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetstreamer/#a014bfcdfadf6202d9bc16fae201ddfe3">llvm::WebAssemblyTargetStreamer::emitFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetstreamer/#a99f9c999cb4aef66ed2984c4c133ba2e">llvm::WebAssemblyTargetStreamer::emitImportModule</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetstreamer/#ab48941bfdd610d540b536cae837cc142">llvm::WebAssemblyTargetStreamer::emitImportName</a>, <a href="#a4d155a589e83947673539f155aa88172">emitSymbolType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#acfb93588e65e2c1c3e35ba88168478c5">getMCSymbolForFunction</a>, <a href="#a4d95a71faaca9c18ee44f1942b77c716">getOrCreateWasmSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a07b368631b4c3217eacc9d0d93001d76">llvm::AsmPrinter::getSymbol</a>, <a href="#a42b2a805173bc1cc36a6a59861107fe3">getTargetStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfowasm/#ac5aa57db9835c70f4de98ecc5100ab2f">llvm::MachineModuleInfoWasm::MachineSymbolsUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa1316da87e093c08b6657877572b19a4">llvm::AsmPrinter::MMI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a7e344cff0feadf0b02223fee63cc7475">Results</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ace31823ee67c59988aaf81127a235372">llvm::signatureFromMVTs</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529ae2d3246e8f9451c96b200707078c83d9">llvm::wasm::WASM_SYMBOL_TYPE_FUNCTION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a9d507b0cb1cf288e6fe831666a8b8668">llvm::WebAssembly::WasmEnableEmEH</a> and <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#aab16d00c5762ae8f5a89ce045b44b07e">llvm::WebAssembly::WasmEnableEmSjLj</a>.</p>


<p>Referenced by <a href="#a5b28e8554e69354731d399f7d68129ce">emitConstantPool</a> and <a href="#af0cbac92300c3074e6bb81d58e92a86b">emitEndOfAsmFile</a>.</p>

</div>
</div>

### emitEndOfAsmFile() {#af0cbac92300c3074e6bb81d58e92a86b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WebAssemblyAsmPrinter::emitEndOfAsmFile (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;)</td>
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

<p>This virtual method can be overridden by targets that want to emit something at the end of their file.</p>

<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>, definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-cpp">WebAssemblyAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#aa29ca0ef805870463b1abf3171c5cf1c">emitDecls</a>, <a href="#aedbc3a6b1ed39b77650edac4239774cf">EmitFunctionAttributes</a>, <a href="#a013467bb98e0c35a48763e22de49cc75">EmitProducerInfo</a>, <a href="#a06dab5b53d53c65a118f25ea11570352">EmitTargetFeatures</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a13a2c76a48665ee3f4782fba7ddd72e1">llvm::SectionKind::getMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a33df8ca13cb8bb9e37d1f43b202aef7f">llvm::WebAssembly::getOrCreateFunctionTableSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mdstring/#ae44259d9edd71181ea8b89d18f27a967">llvm::MDString::getString</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a07b368631b4c3217eacc9d0d93001d76">llvm::AsmPrinter::getSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#af45a1b676eb96b330c6a5bb5dab029ae">llvm::WebAssembly::isWasmVarAddressSpace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243afb34d5700d536c3f8f8a5004985d1f57">llvm::MCSA_NoDeadStrip</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### EmitFunctionAttributes() {#aedbc3a6b1ed39b77650edac4239774cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WebAssemblyAsmPrinter::EmitFunctionAttributes (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>, definition at line 559 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-cpp">WebAssemblyAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2bcd261c0da622d37e1c5aeb02496e12">llvm::getConstantStringInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a13a2c76a48665ee3f4782fba7ddd72e1">llvm::SectionKind::getMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a07b368631b4c3217eacc9d0d93001d76">llvm::AsmPrinter::getSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a0b931781aa589c6ebe64a76c1447e5b2">llvm::User::operands</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a966eb231e7d4e572874d2cb49b18faea">llvm::Value::stripPointerCasts</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a62dd0aeb9839db4490d0e271b00123f5">llvm::MCSymbolRefExpr::VK_WASM_FUNCINDEX</a>.</p>


<p>Referenced by <a href="#af0cbac92300c3074e6bb81d58e92a86b">emitEndOfAsmFile</a>.</p>

</div>
</div>

### emitFunctionBodyStart() {#aa2ead336a250ceb168df7c3cefc1988e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WebAssemblyAsmPrinter::emitFunctionBodyStart ()</td>
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

<p>Targets can override this to emit stuff before the first basic block in the function.</p>

<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>, definition at line 611 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-cpp">WebAssemblyAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e263b9cd2bdbbbaf3d78a2caba5cbf5">llvm::computeSignatureVTs</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa06f7388d0cc9b44ece08cdf56c0ecf0">llvm::AsmPrinter::CurrentFnSym</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a70f18d2f240208cd99fc70db9b39eb7a">llvm::AsmPrinter::emitFunctionBodyStart</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetstreamer/#a014bfcdfadf6202d9bc16fae201ddfe3">llvm::WebAssemblyTargetStreamer::emitFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetstreamer/#adcba3ab060f2f002eb00092b3dd14ee3">llvm::WebAssemblyTargetStreamer::emitIndIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetstreamer/#a3c8ad738608a5bbb704322730ad6b678">llvm::WebAssemblyTargetStreamer::emitLocal</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a42b2a805173bc1cc36a6a59861107fe3">getTargetStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac2b1c517d194a6bdd00f66bce97f52c3">llvm::AsmPrinter::lowerConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ace31823ee67c59988aaf81127a235372">llvm::signatureFromMVTs</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25657a51f99b0a2819bdc54d3e31b813">llvm::AsmPrinter::TM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf8d332ecf62a0b283e3795bdbd45d79">llvm::valTypesFromMVTs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529ae2d3246e8f9451c96b200707078c83d9">llvm::wasm::WASM_SYMBOL_TYPE_FUNCTION</a>.</p>

</div>
</div>

### emitGlobalVariable() {#a0202522d1384c2ad88417c496ae62068}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WebAssemblyAsmPrinter::emitGlobalVariable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV)</td>
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

<p>Emit the specified global variable to the .s file.</p>


<p>EmitGlobalVariable - Emit the specified global variable to the .s file.</p>


<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>, definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-cpp">WebAssemblyAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ada9b9cff9a1f422b5426595ae603e681">llvm::computeLegalValueVTs</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a83aca905c88deb0a7598e92f4f6558b0">llvm::AsmPrinter::emitLinkage</a>, <a href="#a4d155a589e83947673539f155aa88172">emitSymbolType</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#abd205e7b05bd8d8bb0d6f01a216a53ee">llvm::AsmPrinter::emitVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a702d4986803a1782ba305b1c7a0f1c21">llvm::GlobalValue::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a0beddb53641a541e2238617c5fac4be7">llvm::Module::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aa5d2c67dadc073dac78224224ee89350">llvm::GlobalValue::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a07b368631b4c3217eacc9d0d93001d76">llvm::AsmPrinter::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a9a1560129bcae4e7e2456326461a8aa6">llvm::AsmPrinter::getSymbolPreferLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#af3dcaf743b04a6ee2c241b2259959b4a">llvm::MCSymbolWasm::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a28b9561d9ef3d237ef894023187fa26c">llvm::GlobalValue::getVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a1c66d4eff947253e7610a66379974d63">llvm::GlobalVariable::hasInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a32e606ac4c88f71f14212e42b808e7f4">llvm::GlobalValue::isDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a239427c2c3a01e23bd15b29633696536">llvm::GlobalValue::isThreadLocal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#af45a1b676eb96b330c6a5bb5dab029ae">llvm::WebAssembly::isWasmVarAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a711350a8af2fb95f4f1ca8cb7fa79374">llvm::WebAssembly::wasmSymbolSetType</a>.</p>

</div>
</div>

### emitInstruction() {#a42cd82bf5091d26adbbfb2eb56026b43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WebAssemblyAsmPrinter::emitInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *)</td>
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

<p>Targets should implement this to emit instructions.</p>

<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>, definition at line 639 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-cpp">WebAssemblyAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1b02eda9bb97934fbcc3d7f29219b931">llvm::AsmPrinter::EmitToStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ad50f5d7186d7a17abb53860320a2a5b1">llvm::AsmPrinter::isVerbose</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblymcinstlower/#a62aefd0bed5ed9cd5a154bf4d4074a22">llvm::WebAssemblyMCInstLower::lower</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>.</p>

</div>
</div>

### emitJumpTableInfo() {#a00c3b9300cf6108db77e784317aec777}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WebAssemblyAsmPrinter::emitJumpTableInfo ()</td>
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

<p>Print assembly representations of the jump tables used by the current function to the current output stream.</p>

<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>, definition at line 607 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-cpp">WebAssemblyAsmPrinter.cpp</a>.</p>

</div>
</div>

### EmitProducerInfo() {#a013467bb98e0c35a48763e22de49cc75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WebAssemblyAsmPrinter::EmitProducerInfo (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>, definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-cpp">WebAssemblyAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#af13923757ac4e6379f33a942c8e57295aa603905470e2a5b8c13e96b579ef0dba">llvm::AsmPrinter::Debug</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a13a2c76a48665ee3f4782fba7ddd72e1">llvm::SectionKind::getMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga6040ef7c99341269e7c3ffe8347f72b3">llvm::dwarf::LanguageString</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>


<p>Referenced by <a href="#af0cbac92300c3074e6bb81d58e92a86b">emitEndOfAsmFile</a>.</p>

</div>
</div>

### emitSymbolType() {#a4d155a589e83947673539f155aa88172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WebAssemblyAsmPrinter::emitSymbolType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm">MCSymbolWasm</a> * Sym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>, definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-cpp">WebAssemblyAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetstreamer/#a72e444cf89b61ea6d36b20c6163ce69b">llvm::WebAssemblyTargetStreamer::emitGlobalType</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetstreamer/#a9d5cf9e506b47d1b988ea8acf3ac41db">llvm::WebAssemblyTargetStreamer::emitTableType</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetstreamer/#a42a11579f7f2ae9543856a25cac48a44">llvm::WebAssemblyTargetStreamer::emitTagType</a>, <a href="#a42b2a805173bc1cc36a6a59861107fe3">getTargetStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#af3dcaf743b04a6ee2c241b2259959b4a">llvm::MCSymbolWasm::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a36f3d68b8025222c9f73a586aee5932f">llvm::wasm::WASM_SYMBOL_TYPE_GLOBAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a7e6d4cfa5233363b413a1b9997c98d7c">llvm::wasm::WASM_SYMBOL_TYPE_TABLE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a47169d0c34c301e7580280da4dc576a6">llvm::wasm::WASM_SYMBOL_TYPE_TAG</a>.</p>


<p>Referenced by <a href="#aa29ca0ef805870463b1abf3171c5cf1c">emitDecls</a> and <a href="#a0202522d1384c2ad88417c496ae62068">emitGlobalVariable</a>.</p>

</div>
</div>

### EmitTargetFeatures() {#a06dab5b53d53c65a118f25ea11570352}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WebAssemblyAsmPrinter::EmitTargetFeatures (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>, definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-cpp">WebAssemblyAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a13a2c76a48665ee3f4782fba7ddd72e1">llvm::SectionKind::getMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6930b5cc89dc0d84d4e96776acd477e1aafc5c5d2970fdd289dc771afef420e99">llvm::wasm::WASM_FEATURE_PREFIX_DISALLOWED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6930b5cc89dc0d84d4e96776acd477e1a08aa52c6ef848bafb5206058227544e5">llvm::wasm::WASM_FEATURE_PREFIX_USED</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1cd80a76d76bf507862c05650c5b16e9">llvm::WebAssemblyFeatureKV</a>.</p>


<p>Referenced by <a href="#af0cbac92300c3074e6bb81d58e92a86b">emitEndOfAsmFile</a>.</p>

</div>
</div>

### getMCSymbolForFunction() {#acfb93588e65e2c1c3e35ba88168478c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbolWasm * WebAssemblyAsmPrinter::getMCSymbolForFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, bool EnableEmEH, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmsignature">wasm::WasmSignature</a> * Sig, bool &amp; InvokeDetected)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>, definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-cpp">WebAssemblyAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-cpp/#a0a97488075cd2fcd03613374a36af571">getEmscriptenInvokeSymbolName</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aaac6d709ea6a14a69a632a3685936c92">llvm::AsmPrinter::GetExternalSymbolSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a07b368631b4c3217eacc9d0d93001d76">llvm::AsmPrinter::getSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-cpp/#a5e43ab7ef24290031d9eb2c23738f509">isEmscriptenInvokeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmsignature/#ab9eed93a9142e4a73b647f0eacbd0698">llvm::wasm::WasmSignature::Returns</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#ab777621cd8cd052180667366c7191456">llvm::WebAssembly::signatureToString</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#aa29ca0ef805870463b1abf3171c5cf1c">emitDecls</a>.</p>

</div>
</div>

### getOrCreateWasmSymbol() {#a4d95a71faaca9c18ee44f1942b77c716}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * WebAssemblyAsmPrinter::getOrCreateWasmSymbol (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>, definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-cpp">WebAssemblyAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aaac6d709ea6a14a69a632a3685936c92">llvm::AsmPrinter::GetExternalSymbolSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#ae94b800d0b8c1e3423be89c87d447c9c">llvm::WebAssembly::getLibcallSignature</a>, <a href="#a1bdc58ed97a30a3aa2c8b78ea08f04b2">getSubtarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8ad878ea6016bfe01729548bf442de5a8b">llvm::wasm::I32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a0ef8084534e2fa2859faac16914a7ff8ae7e62f6928f76df671b5a0379793fab6">llvm::wasm::I64</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ab2fdacf803a7a00c831b1e3c068a5ce8">llvm::AsmPrinter::isPositionIndependent</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa7625af893e242d33b9f182066f59310">llvm::AsmPrinter::OutContext</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a3bf8c7186acf1ffbf50c1f7c915554bb">llvm::wasm::WASM_SYMBOL_TYPE_DATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529ae2d3246e8f9451c96b200707078c83d9">llvm::wasm::WASM_SYMBOL_TYPE_FUNCTION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a36f3d68b8025222c9f73a586aee5932f">llvm::wasm::WASM_SYMBOL_TYPE_GLOBAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529a47169d0c34c301e7580280da4dc576a6">llvm::wasm::WASM_SYMBOL_TYPE_TAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a126deb4cb22aa8806e714b8e42b2647eabde54aa45b9d6b85fb4c37fc5cca29f5">llvm::wasm::WASM_TYPE_I32</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a126deb4cb22aa8806e714b8e42b2647ea2b4b3bdb67bcba743db32a1c0684ccff">llvm::wasm::WASM_TYPE_I64</a>.</p>


<p>Referenced by <a href="#aa29ca0ef805870463b1abf3171c5cf1c">emitDecls</a>.</p>

</div>
</div>

### getPassName() {#a05033ee0700043d8631ea334b3cb8170}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::WebAssemblyAsmPrinter::getPassName ()</td>
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

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>.</p>

</div>
</div>

### getRegType() {#a9b134d4df9353786cf749d861b77b792}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT WebAssemblyAsmPrinter::getRegType (unsigned RegNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-cpp">WebAssemblyAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### getSubtarget() {#a1bdc58ed97a30a3aa2c8b78ea08f04b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const WebAssemblySubtarget &amp; llvm::WebAssemblyAsmPrinter::getSubtarget ()</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>.</p>


<p>Referenced by <a href="#a4d95a71faaca9c18ee44f1942b77c716">getOrCreateWasmSymbol</a>.</p>

</div>
</div>

### getTargetStreamer() {#a42b2a805173bc1cc36a6a59861107fe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WebAssemblyTargetStreamer * WebAssemblyAsmPrinter::getTargetStreamer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-cpp">WebAssemblyAsmPrinter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ac189a157a6aab76ea837c13ec615dbc9">llvm::AsmPrinter::OutStreamer</a>.</p>


<p>Referenced by <a href="#aa29ca0ef805870463b1abf3171c5cf1c">emitDecls</a>, <a href="#aa2ead336a250ceb168df7c3cefc1988e">emitFunctionBodyStart</a> and <a href="#a4d155a589e83947673539f155aa88172">emitSymbolType</a>.</p>

</div>
</div>

### PrintAsmMemoryOperand() {#a16563560b6ca95512cfdcd6595221db2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WebAssemblyAsmPrinter::PrintAsmMemoryOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ExtraCode, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Print the specified operand of MI, an INLINEASM instruction, using the specified assembler variant as an address.</p>


<p>Targets should override this to format as appropriate. This method can return true if the operand is erroneous.</p>


<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>, definition at line 742 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-cpp">WebAssemblyAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#acc23f9f04e6b3bb38b1fdc1dffe47ac5">llvm::AsmPrinter::PrintAsmMemoryOperand</a>.</p>

</div>
</div>

### PrintAsmOperand() {#ab3b56dc8749765fe615f325594493167}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WebAssemblyAsmPrinter::PrintAsmOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned OpNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ExtraCode, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
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

<p>Print the specified operand of MI, an INLINEASM instruction, using the specified assembler variant.</p>


<p>PrintAsmOperand - Print the specified operand of MI, an INLINEASM instruction, using the specified assembler variant.</p>


<p>Targets should override this to format as appropriate. This method can return true if the operand is erroneous.</p>


<p>Targets should override this to format as appropriate for machine specific ExtraCodes or when the arch-independent handling would be too complex otherwise.</p>


<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>, definition at line 704 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-cpp">WebAssemblyAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aaac6d709ea6a14a69a632a3685936c92">llvm::AsmPrinter::GetExternalSymbolSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a57e64b633278df75c699e6b98ce15031">llvm::MachineOperand::getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af624ff47eaa512dbe23866accb3837c1">llvm::MachineOperand::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a1cc134bd22a318835dc929323da70ea4">llvm::MachineBasicBlock::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab59b255f78cd503133d032152a41d105">llvm::MachineOperand::getSymbolName</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab313591ae4ea1e3a4ab59121a7dc2a2b">llvm::MachineOperand::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a47692fd7344d1adc2916ad4cc31d26c8">llvm::AsmPrinter::MAI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba9d22ed12eec3e14283ed6a3617d12119">llvm::MachineOperand::MO_ExternalSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba3f1f6bfc5aa57cf388201bf6b8fee7d3">llvm::MachineOperand::MO_GlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba066f84460d9f7b61d54b187555756ef6">llvm::MachineOperand::MO_Immediate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba95566cb4525dab82db8cbbed3d634c23">llvm::MachineOperand::MO_MachineBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af269b990800f72c7cf535c407e8e639ba99b874c6560305fd292d20f6a06da166">llvm::MachineOperand::MO_Register</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a27f7a23e572edb7b1bc46d9639c3204a">llvm::MCSymbol::print</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#af865b91965a6c4e1082d1510228db5b5">llvm::AsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a9267c5a5f78e26424afb66b404d44d8b">llvm::AsmPrinter::printOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a34e471aa6f0a6f1975d57f3aafc7b2e0">llvm::AsmPrinter::PrintSymbolOperand</a> and <a href="#a4c5b93703bfd35ff033b6fd30c2b8ee7">regToString</a>.</p>

</div>
</div>

### regToString() {#a4c5b93703bfd35ff033b6fd30c2b8ee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string WebAssemblyAsmPrinter::regToString (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-cpp">WebAssemblyAsmPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a> and <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a77bfe2fcd74307eb34fab682645aea2a">llvm::WebAssembly::UnusedReg</a>.</p>


<p>Referenced by <a href="#ab3b56dc8749765fe615f325594493167">PrintAsmOperand</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a897bd48044b4c136754a489e5e9c0967}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssemblyAsmPrinter::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Emit the specified function out to the OutStreamer.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a4ddb4afaf5e4a6bca81ececd63f516da">llvm::AsmPrinter::MF</a> and <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#abdebe99024a5c0aac2587659ba60a581">llvm::AsmPrinter::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MFI {#a3788a9c4a8a0b2b11ada8494135cca97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WebAssemblyFunctionInfo* llvm::WebAssemblyAsmPrinter::MFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>.</p>

</div>
</div>

### MRI {#ac3263a8a988940518ce85187bf87c75e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineRegisterInfo* llvm::WebAssemblyAsmPrinter::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>.</p>

</div>
</div>

### signaturesEmitted {#a236ac34be0935d8c821bf35699065a88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssemblyAsmPrinter::signaturesEmitted = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>.</p>

</div>
</div>

### Subtarget {#aa6ec45a0a952c7ac58bdd1fb427fb066}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const WebAssemblySubtarget* llvm::WebAssemblyAsmPrinter::Subtarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-cpp">WebAssemblyAsmPrinter.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-h">WebAssemblyAsmPrinter.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
