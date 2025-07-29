---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-bpfmccodeemitter-cpp-/bpfmccodeemitter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BPFMCCodeEmitter` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{BPFMCCodeEmitter.cpp}::BPFMCCodeEmitter { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c750c3c8d8702d470f732462b02c28f">BPFMCCodeEmitter</a> (const MCInstrInfo &amp;, const MCRegisterInfo &amp;mri, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0958eed2765421c5b151c78c77cea3a5">BPFMCCodeEmitter</a> (const BPFMCCodeEmitter &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f750bd90e93177594c068fed213716d">~BPFMCCodeEmitter</a> () override=default</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64ecfefe58dae16fff59ce631798317e">operator=</a> (const BPFMCCodeEmitter &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e8d7e1be8a5d016d0ccc1fbf1c2cd0b">getBinaryCodeForInstr</a> (const MCInst &amp;MI, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a955c8163dbb18d99c96c57d1c4b273f0">getMachineOpValue</a> (const MCInst &amp;MI, const MCOperand &amp;MO, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7ac978614ae5b57e3282b89b16ab3c1">getMemoryOpValue</a> (const MCInst &amp;MI, unsigned Op, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76f5410dcaece835e30459df0a57c16c">encodeInstruction</a> (const MCInst &amp;MI, SmallVectorImpl&lt; char &gt; &amp;CB, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encode the given <span class="doxyComputerOutput">Inst</span> to bytes and append to <span class="doxyComputerOutput">CB</span>. <a href="#a76f5410dcaece835e30459df0a57c16c">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a238451365348f39a8cb512ff44155252">MRI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ced18e70aa1af4cb4bfa5c58bfdacc9">IsLittleEndian</a></td>
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


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfmccodeemitter-cpp">BPFMCCodeEmitter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BPFMCCodeEmitter() {#a3c750c3c8d8702d470f732462b02c28f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{BPFMCCodeEmitter.cpp}::BPFMCCodeEmitter::BPFMCCodeEmitter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp; mri, bool IsLittleEndian)</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfmccodeemitter-cpp">BPFMCCodeEmitter.cpp</a>.</p>


<p>Referenced by <a href="#a0958eed2765421c5b151c78c77cea3a5">BPFMCCodeEmitter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5c3c6cb1614778fbb5c205ca4c79837">llvm::createBPFbeMCCodeEmitter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afa8652744acd380b593fd80c6678c0f4">llvm::createBPFMCCodeEmitter</a> and <a href="#a64ecfefe58dae16fff59ce631798317e">operator=</a>.</p>

</div>
</div>

### BPFMCCodeEmitter() {#a0958eed2765421c5b151c78c77cea3a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{BPFMCCodeEmitter.cpp}::BPFMCCodeEmitter::BPFMCCodeEmitter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-bpfmccodeemitter-cpp-/bpfmccodeemitter">BPFMCCodeEmitter</a> &amp;)</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfmccodeemitter-cpp">BPFMCCodeEmitter.cpp</a>.</p>


<p>Reference <a href="#a3c750c3c8d8702d470f732462b02c28f">BPFMCCodeEmitter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~BPFMCCodeEmitter() {#a4f750bd90e93177594c068fed213716d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{BPFMCCodeEmitter.cpp}::BPFMCCodeEmitter::~BPFMCCodeEmitter ()</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfmccodeemitter-cpp">BPFMCCodeEmitter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a64ecfefe58dae16fff59ce631798317e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{BPFMCCodeEmitter.cpp}::BPFMCCodeEmitter::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-bpfmccodeemitter-cpp-/bpfmccodeemitter">BPFMCCodeEmitter</a> &amp;)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfmccodeemitter-cpp">BPFMCCodeEmitter.cpp</a>.</p>


<p>Reference <a href="#a3c750c3c8d8702d470f732462b02c28f">BPFMCCodeEmitter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### encodeInstruction() {#a76f5410dcaece835e30459df0a57c16c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BPFMCCodeEmitter::encodeInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfmccodeemitter-cpp">BPFMCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbad861877da56b8b4ceb35c8cbfdf65bb4">llvm::big</a>, <a href="#a8e8d7e1be8a5d016d0ccc1fbf1c2cd0b">getBinaryCodeForInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfmccodeemitter-cpp/#a719974b514bdad6c002cf5416f968e0f">SwapBits</a> and <a href="/web-llvm/docs/api/structs/llvm/support/endian/writer/#a16a69d4248bb11c84536099421ea833b">llvm::support::endian::Writer::write</a>.</p>


<p>Referenced by <a href="#a8e8d7e1be8a5d016d0ccc1fbf1c2cd0b">getBinaryCodeForInstr</a>.</p>

</div>
</div>

### getBinaryCodeForInstr() {#a8e8d7e1be8a5d016d0ccc1fbf1c2cd0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{BPFMCCodeEmitter.cpp}::BPFMCCodeEmitter::getBinaryCodeForInstr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfmccodeemitter-cpp">BPFMCCodeEmitter.cpp</a>.</p>


<p>References <a href="#a76f5410dcaece835e30459df0a57c16c">encodeInstruction</a>, <a href="#a955c8163dbb18d99c96c57d1c4b273f0">getMachineOpValue</a>, <a href="#af7ac978614ae5b57e3282b89b16ab3c1">getMemoryOpValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a76f5410dcaece835e30459df0a57c16c">encodeInstruction</a>.</p>

</div>
</div>

### getMachineOpValue() {#a955c8163dbb18d99c96c57d1c4b273f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned BPFMCCodeEmitter::getMachineOpValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; MO, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfmccodeemitter-cpp">BPFMCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfixup/#abdf37854fa6eb68017b96486df443a32">llvm::MCFixup::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bpf/#aae3746000e14e086696c5e63aa810812a7d2fd911c9275dbfc182765904ce1bdc">llvm::BPF::FK_BPF_PCRel_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a11803cd0814af72a9d078ac0f7a33137">llvm::FK_PCRel_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a0f7a8485c2c761bc5e870fe2b6466372">llvm::FK_PCRel_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a751b491a3c8dd06f9b616ee717dbdbae">llvm::FK_SecRel_8</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ac9408fbc60922d24b01c1efcbd4ba52b">llvm::MCOperand::getExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#af5d6e67c11188675c1309e098afac194">llvm::MCExpr::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a94abf618eb8001b802910ab872a7d1d9">llvm::MCOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ae23b2e8269fe15dbe5ebb3394438960c">llvm::MCOperand::isExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a5f639fdcd3fc673fcbdb47f2e88b2b41">llvm::MCOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a7a8c7eea0aa4890f25a4b83e1f0a0b6f">llvm::MCOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606fa8cbc19c1660252a30c030fa945999a91">llvm::MCExpr::SymbolRef</a>.</p>


<p>Referenced by <a href="#a8e8d7e1be8a5d016d0ccc1fbf1c2cd0b">getBinaryCodeForInstr</a>.</p>

</div>
</div>

### getMemoryOpValue() {#af7ac978614ae5b57e3282b89b16ab3c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t BPFMCCodeEmitter::getMemoryOpValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, unsigned Op, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfmccodeemitter-cpp">BPFMCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a94abf618eb8001b802910ab872a7d1d9">llvm::MCOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a5f639fdcd3fc673fcbdb47f2e88b2b41">llvm::MCOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a7a8c7eea0aa4890f25a4b83e1f0a0b6f">llvm::MCOperand::isReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a8e8d7e1be8a5d016d0ccc1fbf1c2cd0b">getBinaryCodeForInstr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IsLittleEndian {#a0ced18e70aa1af4cb4bfa5c58bfdacc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{BPFMCCodeEmitter.cpp}::BPFMCCodeEmitter::IsLittleEndian</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfmccodeemitter-cpp">BPFMCCodeEmitter.cpp</a>.</p>

</div>
</div>

### MRI {#a238451365348f39a8cb512ff44155252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCRegisterInfo&amp; anonymous{BPFMCCodeEmitter.cpp}::BPFMCCodeEmitter::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfmccodeemitter-cpp">BPFMCCodeEmitter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfmccodeemitter-cpp">BPFMCCodeEmitter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
