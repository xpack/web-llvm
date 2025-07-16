---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RISCVMCCodeEmitter` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> - Generic instruction encoding interface. <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21c6ba71675846b8a6c8d5de62ec3e4c">RISCVMCCodeEmitter</a> (MCContext &amp;ctx, MCInstrInfo const &amp;MCII)</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a194e84a8f53d9c2244a9f2042e984811">RISCVMCCodeEmitter</a> (const RISCVMCCodeEmitter &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9f757cedc19ffba639173a7cd6dabbe">~RISCVMCCodeEmitter</a> () override=default</td>
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

## Private Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f9245959d81fe53717ce09bb8d63b39">operator=</a> (const RISCVMCCodeEmitter &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef4f1647d634efffc620679419aa92e8">encodeInstruction</a> (const MCInst &amp;MI, SmallVectorImpl&lt; char &gt; &amp;CB, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encode the given <span class="doxyComputerOutput">Inst</span> to bytes and append to <span class="doxyComputerOutput">CB</span>. <a href="#aef4f1647d634efffc620679419aa92e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb7cbfc91aec970d7d9b935b81f8db66">expandFunctionCall</a> (const MCInst &amp;MI, SmallVectorImpl&lt; char &gt; &amp;CB, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a949f92840302b18bc451d406ddeb09a9">expandTLSDESCCall</a> (const MCInst &amp;MI, SmallVectorImpl&lt; char &gt; &amp;CB, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa2b2e58e0859c0608b6f10a8ad1c79f">expandAddTPRel</a> (const MCInst &amp;MI, SmallVectorImpl&lt; char &gt; &amp;CB, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9f55bb589105b8751fa61098690db0b">expandLongCondBr</a> (const MCInst &amp;MI, SmallVectorImpl&lt; char &gt; &amp;CB, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a890f4d0cc528cbddaa4232e43608858b">getBinaryCodeForInstr</a> (const MCInst &amp;MI, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a>'erated function for getting the binary encoding for an instruction. <a href="#a890f4d0cc528cbddaa4232e43608858b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4a1a1b8458cb5d562bdeb5dfdbe7ba0">getMachineOpValue</a> (const MCInst &amp;MI, const MCOperand &amp;MO, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return binary encoding of operand. <a href="#af4a1a1b8458cb5d562bdeb5dfdbe7ba0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a896ba7bca325a888cbd951f6a9f3f844">getImmOpValueAsr1</a> (const MCInst &amp;MI, unsigned OpNo, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a847e5bb4507e49e9af8582df2cb12f50">getImmOpValue</a> (const MCInst &amp;MI, unsigned OpNo, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a619df47e547666871c57c8ce635d427f">getVMaskReg</a> (const MCInst &amp;MI, unsigned OpNo, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a9b42842a9f4205634bb55ca6aa940b">getRlistOpValue</a> (const MCInst &amp;MI, unsigned OpNo, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe8f8f923b30170e95ed310904339766">getRegReg</a> (const MCInst &amp;MI, unsigned OpNo, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6514d7a479a55e03f70980735e0298b4">Ctx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>  &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a892db552e21f21729518bb8f6369e3db">MCII</a></td>
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


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmccodeemitter-cpp">RISCVMCCodeEmitter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RISCVMCCodeEmitter() {#a21c6ba71675846b8a6c8d5de62ec3e4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::RISCVMCCodeEmitter (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; ctx, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII)</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmccodeemitter-cpp">RISCVMCCodeEmitter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### RISCVMCCodeEmitter() {#a194e84a8f53d9c2244a9f2042e984811}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::RISCVMCCodeEmitter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter">RISCVMCCodeEmitter</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmccodeemitter-cpp">RISCVMCCodeEmitter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~RISCVMCCodeEmitter() {#ac9f757cedc19ffba639173a7cd6dabbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::~RISCVMCCodeEmitter ()</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmccodeemitter-cpp">RISCVMCCodeEmitter.cpp</a>.</p>


<p>References <a href="#aef4f1647d634efffc620679419aa92e8">encodeInstruction</a>, <a href="#afa2b2e58e0859c0608b6f10a8ad1c79f">expandAddTPRel</a>, <a href="#abb7cbfc91aec970d7d9b935b81f8db66">expandFunctionCall</a>, <a href="#aa9f55bb589105b8751fa61098690db0b">expandLongCondBr</a>, <a href="#a949f92840302b18bc451d406ddeb09a9">expandTLSDESCCall</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Operators

### operator=() {#a5f9245959d81fe53717ce09bb8d63b39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-riscvmccodeemitter-cpp-/riscvmccodeemitter">RISCVMCCodeEmitter</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmccodeemitter-cpp">RISCVMCCodeEmitter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### encodeInstruction() {#aef4f1647d634efffc620679419aa92e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVMCCodeEmitter::encodeInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p>Encode the given <span class="doxyComputerOutput">Inst</span> to bytes and append to <span class="doxyComputerOutput">CB</span>.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmccodeemitter-cpp">RISCVMCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afa2b2e58e0859c0608b6f10a8ad1c79f">expandAddTPRel</a>, <a href="#abb7cbfc91aec970d7d9b935b81f8db66">expandFunctionCall</a>, <a href="#aa9f55bb589105b8751fa61098690db0b">expandLongCondBr</a>, <a href="#a949f92840302b18bc451d406ddeb09a9">expandTLSDESCCall</a>, <a href="#a890f4d0cc528cbddaa4232e43608858b">getBinaryCodeForInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aae26f659b722d1d053b93b5f1735f52f">llvm::SmallVectorImpl&lt; T &gt;::truncate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>.</p>


<p>Referenced by <a href="#ac9f757cedc19ffba639173a7cd6dabbe">~RISCVMCCodeEmitter</a>.</p>

</div>
</div>

### expandAddTPRel() {#afa2b2e58e0859c0608b6f10a8ad1c79f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVMCCodeEmitter::expandAddTPRel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmccodeemitter-cpp">RISCVMCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder/#a6990ced5e71387ca4e8aaa1c4f96b380">llvm::MCInstBuilder::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfixup/#abdf37854fa6eb68017b96486df443a32">llvm::MCFixup::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a3a04590e7d054034a15f0c7c64180129">llvm::RISCV::fixup_riscv_relax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a8a4b86f25fcb0c3c748f0e70066b9f7a">llvm::RISCV::fixup_riscv_tprel_add</a>, <a href="#a890f4d0cc528cbddaa4232e43608858b">getBinaryCodeForInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ac9408fbc60922d24b01c1efcbd4ba52b">llvm::MCOperand::getExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a00877c778cc9f75bf1682233e36930d9">llvm::RISCVMCExpr::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a94abf618eb8001b802910ab872a7d1d9">llvm::MCOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ae23b2e8269fe15dbe5ebb3394438960c">llvm::MCOperand::isExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a7a8c7eea0aa4890f25a4b83e1f0a0b6f">llvm::MCOperand::isReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a9396ec898399370b727b35de80497248">llvm::RISCVMCExpr::VK_RISCV_TPREL_ADD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>.</p>


<p>Referenced by <a href="#aef4f1647d634efffc620679419aa92e8">encodeInstruction</a> and <a href="#ac9f757cedc19ffba639173a7cd6dabbe">~RISCVMCCodeEmitter</a>.</p>

</div>
</div>

### expandFunctionCall() {#abb7cbfc91aec970d7d9b935b81f8db66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVMCCodeEmitter::expandFunctionCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmccodeemitter-cpp">RISCVMCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder/#ad824e6c64e2015a9fbaba9a4c9d0a7b9">llvm::MCInstBuilder::addExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder/#ac6bfc040ddca811a88a95e1f6d6b3747">llvm::MCInstBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder/#a2b9700052102985a61c9cf62b71d68f0">llvm::MCInstBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a890f4d0cc528cbddaa4232e43608858b">getBinaryCodeForInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a53afee158973a8af8c60263ddb5b2d07">llvm::MCSubtargetInfo::getFeatureBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#ae0de300bc79ed06538e3c4ef611ae27d">llvm::RISCVII::getTailExpandUseRegNo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>.</p>


<p>Referenced by <a href="#aef4f1647d634efffc620679419aa92e8">encodeInstruction</a> and <a href="#ac9f757cedc19ffba639173a7cd6dabbe">~RISCVMCCodeEmitter</a>.</p>

</div>
</div>

### expandLongCondBr() {#aa9f55bb589105b8751fa61098690db0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVMCCodeEmitter::expandLongCondBr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmccodeemitter-cpp">RISCVMCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder/#ac6bfc040ddca811a88a95e1f6d6b3747">llvm::MCInstBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder/#a6990ced5e71387ca4e8aaa1c4f96b380">llvm::MCInstBuilder::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder/#a2b9700052102985a61c9cf62b71d68f0">llvm::MCInstBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfixup/#abdf37854fa6eb68017b96486df443a32">llvm::MCFixup::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149af5d53b8db9782487831bb12e66c9061c">llvm::RISCV::fixup_riscv_jal</a>, <a href="#a890f4d0cc528cbddaa4232e43608858b">getBinaryCodeForInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ac9408fbc60922d24b01c1efcbd4ba52b">llvm::MCOperand::getExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmccodeemitter-cpp/#af95c96928e1ea721e99c30d087b46fc2">getInvertedBranchOp</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregister/#af8403cc977c65b910e618ebcb6a12c32">llvm::MCRegister::id</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ae23b2e8269fe15dbe5ebb3394438960c">llvm::MCOperand::isExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>.</p>


<p>Referenced by <a href="#aef4f1647d634efffc620679419aa92e8">encodeInstruction</a> and <a href="#ac9f757cedc19ffba639173a7cd6dabbe">~RISCVMCCodeEmitter</a>.</p>

</div>
</div>

### expandTLSDESCCall() {#a949f92840302b18bc451d406ddeb09a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RISCVMCCodeEmitter::expandTLSDESCCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmccodeemitter-cpp">RISCVMCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder/#ac6bfc040ddca811a88a95e1f6d6b3747">llvm::MCInstBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder/#a2b9700052102985a61c9cf62b71d68f0">llvm::MCInstBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfixup/#abdf37854fa6eb68017b96486df443a32">llvm::MCFixup::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a2ea2f585dbae2849029cab18c49893fd">llvm::RISCV::fixup_riscv_tlsdesc_call</a>, <a href="#a890f4d0cc528cbddaa4232e43608858b">getBinaryCodeForInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ac9408fbc60922d24b01c1efcbd4ba52b">llvm::MCOperand::getExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ae23b2e8269fe15dbe5ebb3394438960c">llvm::MCOperand::isExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>.</p>


<p>Referenced by <a href="#aef4f1647d634efffc620679419aa92e8">encodeInstruction</a> and <a href="#ac9f757cedc19ffba639173a7cd6dabbe">~RISCVMCCodeEmitter</a>.</p>

</div>
</div>

### getBinaryCodeForInstr() {#a890f4d0cc528cbddaa4232e43608858b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::getBinaryCodeForInstr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a>'erated function for getting the binary encoding for an instruction.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmccodeemitter-cpp">RISCVMCCodeEmitter.cpp</a>.</p>


<p>References <a href="#a847e5bb4507e49e9af8582df2cb12f50">getImmOpValue</a>, <a href="#a896ba7bca325a888cbd951f6a9f3f844">getImmOpValueAsr1</a>, <a href="#af4a1a1b8458cb5d562bdeb5dfdbe7ba0">getMachineOpValue</a>, <a href="#afe8f8f923b30170e95ed310904339766">getRegReg</a>, <a href="#a2a9b42842a9f4205634bb55ca6aa940b">getRlistOpValue</a>, <a href="#a619df47e547666871c57c8ce635d427f">getVMaskReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#aef4f1647d634efffc620679419aa92e8">encodeInstruction</a>, <a href="#afa2b2e58e0859c0608b6f10a8ad1c79f">expandAddTPRel</a>, <a href="#abb7cbfc91aec970d7d9b935b81f8db66">expandFunctionCall</a>, <a href="#aa9f55bb589105b8751fa61098690db0b">expandLongCondBr</a> and <a href="#a949f92840302b18bc451d406ddeb09a9">expandTLSDESCCall</a>.</p>

</div>
</div>

### getImmOpValue() {#a847e5bb4507e49e9af8582df2cb12f50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t RISCVMCCodeEmitter::getImmOpValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmccodeemitter-cpp">RISCVMCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606fad39c4375f2de701a811385670a699a51">llvm::MCExpr::Binary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfixup/#abdf37854fa6eb68017b96486df443a32">llvm::MCFixup::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a21852a2668ad26c40c78267682662908">llvm::RISCV::fixup_riscv_12_i</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149ad266f94de8002bb828840b8f22972ea8">llvm::RISCV::fixup_riscv_branch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a88ebf98dfcb9792c5ff93e1aaeae2795">llvm::RISCV::fixup_riscv_call</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a173779bb566468845e601a108fdd0ad4">llvm::RISCV::fixup_riscv_call_plt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a4ff796b91dfd8a1d885eed8bf90d7cf7">llvm::RISCV::fixup_riscv_got_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a1ebb3c0abab31295b4d2eb846560a7bb">llvm::RISCV::fixup_riscv_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a012738aab307f8753a834e12a5551890">llvm::RISCV::fixup_riscv_invalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149af5d53b8db9782487831bb12e66c9061c">llvm::RISCV::fixup_riscv_jal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a8a2e61994b3021df5ad535363254b705">llvm::RISCV::fixup_riscv_lo12_i</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149ab67201b0aad523fe1a9cdcfa3996cd8a">llvm::RISCV::fixup_riscv_lo12_s</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149ad37e08bb2772b97fd5c82cc64b92b8c9">llvm::RISCV::fixup_riscv_pcrel_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a25f04a3aac7dcd8105cd6199add50589">llvm::RISCV::fixup_riscv_pcrel_lo12_i</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a352fb7bc558f75c5d77993daf797ea1c">llvm::RISCV::fixup_riscv_pcrel_lo12_s</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a3a04590e7d054034a15f0c7c64180129">llvm::RISCV::fixup_riscv_relax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149ad0ebbd5ab44960cdc83796e80006aaaa">llvm::RISCV::fixup_riscv_rvc_branch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a9f4ce31fb99c4613c6f173ce268f9725">llvm::RISCV::fixup_riscv_rvc_jump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a1dcfb88aadd66136c03e2620a6ff91dd">llvm::RISCV::fixup_riscv_tls_gd_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a13b9024d713be1b06a31431a40316038">llvm::RISCV::fixup_riscv_tls_got_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149ada53b713dc586f277c29064f2f37204d">llvm::RISCV::fixup_riscv_tlsdesc_add_lo12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a2ea2f585dbae2849029cab18c49893fd">llvm::RISCV::fixup_riscv_tlsdesc_call</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149ac480fe24e2a9fc38e09382467a80c8e5">llvm::RISCV::fixup_riscv_tlsdesc_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a74ba417e94a716ab604d0ca6b34bb95c">llvm::RISCV::fixup_riscv_tlsdesc_load_lo12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a2f31aaf6d6645f72b9b48260e7297112">llvm::RISCV::fixup_riscv_tprel_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a649d0d8789e34184b131eec00e540e39">llvm::RISCV::fixup_riscv_tprel_lo12_i</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a31a39f52d66a5973e6b2a499fc567149a0c02afb112894ac62bc5f4d4ce99f0ee">llvm::RISCV::fixup_riscv_tprel_lo12_s</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d3d3a355228d2f64fa312abbd7abfbf">llvm::FixupKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ac9408fbc60922d24b01c1efcbd4ba52b">llvm::MCOperand::getExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a7d2868e2bfce3a05c68294f371804304">llvm::RISCVII::getFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#af5d6e67c11188675c1309e098afac194">llvm::MCExpr::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a00877c778cc9f75bf1682233e36930d9">llvm::RISCVMCExpr::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a3de5a33eebb79cedfddd2e7db025095eab75729e10c92b52d7b02f3bc3f0a0dc0">llvm::RISCVII::InstFormatB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a3de5a33eebb79cedfddd2e7db025095ea1fa709b805667423a5c0967763263bb6">llvm::RISCVII::InstFormatCB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a3de5a33eebb79cedfddd2e7db025095ea7e4cb41f015ce8adf3d41f682c3960dc">llvm::RISCVII::InstFormatCJ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a3de5a33eebb79cedfddd2e7db025095ea46b70cca748a3756c44a134ee2ecf207">llvm::RISCVII::InstFormatI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a3de5a33eebb79cedfddd2e7db025095ea362305b12b71a0801a40ff9a48435e78">llvm::RISCVII::InstFormatJ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvii/#a3de5a33eebb79cedfddd2e7db025095ea2be0b30da2b9552e5e242d04c89d54e3">llvm::RISCVII::InstFormatS</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ae23b2e8269fe15dbe5ebb3394438960c">llvm::MCOperand::isExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a5f639fdcd3fc673fcbdb47f2e88b2b41">llvm::MCOperand::isImm</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606fa8cbc19c1660252a30c030fa945999a91">llvm::MCExpr::SymbolRef</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606faa65560b8224a92e80f422df090f07c55">llvm::MCExpr::Target</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a604e28a9a3d857c263b22b49ba9b19f6">llvm::RISCVMCExpr::VK_RISCV_32_PCREL</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6aa4478c3f29a4ad6e0fe8e721c821c476">llvm::RISCVMCExpr::VK_RISCV_CALL</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a7f0a2ade0160be4082351dd594bfab25">llvm::RISCVMCExpr::VK_RISCV_CALL_PLT</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6af53e7457e88370f76455f7cf9c525a8f">llvm::RISCVMCExpr::VK_RISCV_GOT_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6ab5c3ca301e449ab85f42444601bba378">llvm::RISCVMCExpr::VK_RISCV_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6ac04a0920cd401e8c1ed55264c9d1ae7d">llvm::RISCVMCExpr::VK_RISCV_Invalid</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a3c930f90b860b3ff02df7bd420c1f89e">llvm::RISCVMCExpr::VK_RISCV_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a05180d523d3d284b05bddea7102bfd7d">llvm::RISCVMCExpr::VK_RISCV_None</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a380387ebfe7e093c92941ec73b8a2557">llvm::RISCVMCExpr::VK_RISCV_PCREL_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a4b697ccb4bf41db17dc4422189098f55">llvm::RISCVMCExpr::VK_RISCV_PCREL_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a739b9795700df7ae19816f89508f1b49">llvm::RISCVMCExpr::VK_RISCV_TLS_GD_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a17c514839d8a0aca51f132e5dae74967">llvm::RISCVMCExpr::VK_RISCV_TLS_GOT_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a563b259281b6f3e45a89bb1784036aec">llvm::RISCVMCExpr::VK_RISCV_TLSDESC_ADD_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6ae5770558120b3a15fc80a83e0532dc22">llvm::RISCVMCExpr::VK_RISCV_TLSDESC_CALL</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6aada38a4713e0b102bd6c05f34926f896">llvm::RISCVMCExpr::VK_RISCV_TLSDESC_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a5e718279c4aba4b5032b0e4ae1435db7">llvm::RISCVMCExpr::VK_RISCV_TLSDESC_LOAD_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a9396ec898399370b727b35de80497248">llvm::RISCVMCExpr::VK_RISCV_TPREL_ADD</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a28a380cf34cda5c68bbe50aa22378bb1">llvm::RISCVMCExpr::VK_RISCV_TPREL_HI</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#a6be127bc7f810a3f4dc182aff79943e6a1cfe2bb904199433c2ef567b6227db8c">llvm::RISCVMCExpr::VK_RISCV_TPREL_LO</a>.</p>


<p>Referenced by <a href="#a890f4d0cc528cbddaa4232e43608858b">getBinaryCodeForInstr</a> and <a href="#a896ba7bca325a888cbd951f6a9f3f844">getImmOpValueAsr1</a>.</p>

</div>
</div>

### getImmOpValueAsr1() {#a896ba7bca325a888cbd951f6a9f3f844}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t RISCVMCCodeEmitter::getImmOpValueAsr1 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmccodeemitter-cpp">RISCVMCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="#a847e5bb4507e49e9af8582df2cb12f50">getImmOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a5f639fdcd3fc673fcbdb47f2e88b2b41">llvm::MCOperand::isImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a890f4d0cc528cbddaa4232e43608858b">getBinaryCodeForInstr</a>.</p>

</div>
</div>

### getMachineOpValue() {#af4a1a1b8458cb5d562bdeb5dfdbe7ba0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t RISCVMCCodeEmitter::getMachineOpValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; MO, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return binary encoding of operand.</p>


<p>If the machine operand requires relocation, record the relocation and return zero.</p>


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmccodeemitter-cpp">RISCVMCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a94abf618eb8001b802910ab872a7d1d9">llvm::MCOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a5f639fdcd3fc673fcbdb47f2e88b2b41">llvm::MCOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a7a8c7eea0aa4890f25a4b83e1f0a0b6f">llvm::MCOperand::isReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a890f4d0cc528cbddaa4232e43608858b">getBinaryCodeForInstr</a>.</p>

</div>
</div>

### getRegReg() {#afe8f8f923b30170e95ed310904339766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned RISCVMCCodeEmitter::getRegReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmccodeemitter-cpp">RISCVMCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a94abf618eb8001b802910ab872a7d1d9">llvm::MCOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a7a8c7eea0aa4890f25a4b83e1f0a0b6f">llvm::MCOperand::isReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a890f4d0cc528cbddaa4232e43608858b">getBinaryCodeForInstr</a>.</p>

</div>
</div>

### getRlistOpValue() {#a2a9b42842a9f4205634bb55ca6aa940b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned RISCVMCCodeEmitter::getRlistOpValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmccodeemitter-cpp">RISCVMCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a5f639fdcd3fc673fcbdb47f2e88b2b41">llvm::MCOperand::isImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a890f4d0cc528cbddaa4232e43608858b">getBinaryCodeForInstr</a>.</p>

</div>
</div>

### getVMaskReg() {#a619df47e547666871c57c8ce635d427f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned RISCVMCCodeEmitter::getVMaskReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmccodeemitter-cpp">RISCVMCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a94abf618eb8001b802910ab872a7d1d9">llvm::MCOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a7a8c7eea0aa4890f25a4b83e1f0a0b6f">llvm::MCOperand::isReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a890f4d0cc528cbddaa4232e43608858b">getBinaryCodeForInstr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Ctx {#a6514d7a479a55e03f70980735e0298b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext&amp; anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::Ctx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmccodeemitter-cpp">RISCVMCCodeEmitter.cpp</a>.</p>

</div>
</div>

### MCII {#a892db552e21f21729518bb8f6369e3db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstrInfo const&amp; anonymous{RISCVMCCodeEmitter.cpp}::RISCVMCCodeEmitter::MCII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmccodeemitter-cpp">RISCVMCCodeEmitter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmccodeemitter-cpp">RISCVMCCodeEmitter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
