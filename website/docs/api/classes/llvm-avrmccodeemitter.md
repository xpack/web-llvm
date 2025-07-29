---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/avrmccodeemitter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AVRMCCodeEmitter` Class

<p>Writes <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> machine code to a stream. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AVRMCCodeEmitter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-h">Target/AVR/MCTargetDesc/AVRMCCodeEmitter.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c3227849a0b4702159a7dd31d5eba7e">AVRMCCodeEmitter</a> (const MCInstrInfo &amp;MCII, MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a783191e105aea8c841f2ae1491056d70">AVRMCCodeEmitter</a> (const AVRMCCodeEmitter &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90147719d816b666e7088d8e86eda107">operator=</a> (const AVRMCCodeEmitter &amp;)=delete</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2b044eeb8a9c6627ab1eb863b5d4ea8">loadStorePostEncoder</a> (const MCInst &amp;MI, unsigned EncodedValue, const MCSubtargetInfo &amp;STI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finishes up encoding an LD/ST instruction. <a href="#af2b044eeb8a9c6627ab1eb863b5d4ea8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;AVR::Fixups Fixup&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae7302533618c36439c1b6cdc6d9cb1e6">encodeRelCondBrTarget</a> (const MCInst &amp;MI, unsigned OpNo, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the encoding for a conditional branch target. <a href="#ae7302533618c36439c1b6cdc6d9cb1e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a535751a09a837ac9804fdec631aa01da">encodeMemri</a> (const MCInst &amp;MI, unsigned OpNo, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encodes a <span class="doxyComputerOutput">register+immediate</span> operand for <span class="doxyComputerOutput">LDD</span>/<span class="doxyComputerOutput">STD</span>. <a href="#a535751a09a837ac9804fdec631aa01da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ea0db90bc4c3bde7483cd326cfce765">encodeComplement</a> (const MCInst &amp;MI, unsigned OpNo, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Takes the complement of a number (~0 - val). <a href="#a2ea0db90bc4c3bde7483cd326cfce765">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;AVR::Fixups Fixup, unsigned Offset&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0a2f1804a66aebb3fc50395a997bffbb">encodeImm</a> (const MCInst &amp;MI, unsigned OpNo, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encodes an immediate value with a given fixup. <a href="#a0a2f1804a66aebb3fc50395a997bffbb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9862985de10a13d1c0f2887e3574df0">encodeCallTarget</a> (const MCInst &amp;MI, unsigned OpNo, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the encoding of the target for the <span class="doxyComputerOutput">CALL k</span> instruction. <a href="#ae9862985de10a13d1c0f2887e3574df0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b82aab04fc2fbaea3c0e0673836854a">getBinaryCodeForInstr</a> (const MCInst &amp;MI, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a>'ed function to get the binary encoding for an instruction. <a href="#a2b82aab04fc2fbaea3c0e0673836854a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d15b30175e4ffd082760fd1a6542402">getExprOpValue</a> (const MCExpr *Expr, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac561c265a8eb5f9d734d0dfd964e7a34">getMachineOpValue</a> (const MCInst &amp;MI, const MCOperand &amp;MO, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the binary encoding of operand. <a href="#ac561c265a8eb5f9d734d0dfd964e7a34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1356decfcdbb99dd3cf79893b85d767">encodeInstruction</a> (const MCInst &amp;MI, SmallVectorImpl&lt; char &gt; &amp;CB, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encode the given <span class="doxyComputerOutput">Inst</span> to bytes and append to <span class="doxyComputerOutput">CB</span>. <a href="#ae1356decfcdbb99dd3cf79893b85d767">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4567262f76293737ac8cec9a9a32bd28">MCII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba64c6bee17601364d3122e974cb718f">Ctx</a></td>
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

## Description {#details}

<p>Writes <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> machine code to a stream.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-h">AVRMCCodeEmitter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AVRMCCodeEmitter() {#a3c3227849a0b4702159a7dd31d5eba7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AVRMCCodeEmitter::AVRMCCodeEmitter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-h">AVRMCCodeEmitter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### AVRMCCodeEmitter() {#a783191e105aea8c841f2ae1491056d70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AVRMCCodeEmitter::AVRMCCodeEmitter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/avrmccodeemitter">AVRMCCodeEmitter</a> &amp;)</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-h">AVRMCCodeEmitter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Operators

### operator=() {#a90147719d816b666e7088d8e86eda107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AVRMCCodeEmitter::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/avrmccodeemitter">AVRMCCodeEmitter</a> &amp;)</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-h">AVRMCCodeEmitter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### encodeCallTarget() {#ae9862985de10a13d1c0f2887e3574df0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AVRMCCodeEmitter::encodeCallTarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets the encoding of the target for the <span class="doxyComputerOutput">CALL k</span> instruction.</p>

<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-h">AVRMCCodeEmitter.h</a>, definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-cpp">AVRMCCodeEmitter.cpp</a>.</p>

</div>
</div>

### encodeComplement() {#a2ea0db90bc4c3bde7483cd326cfce765}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AVRMCCodeEmitter::encodeComplement (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Takes the complement of a number (~0 - val).</p>

<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-h">AVRMCCodeEmitter.h</a>, definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-cpp">AVRMCCodeEmitter.cpp</a>.</p>

</div>
</div>

### encodeImm() {#a0a2f1804a66aebb3fc50395a997bffbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;AVR::Fixups Fixup, unsigned Offset&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AVRMCCodeEmitter::encodeImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Encodes an immediate value with a given fixup.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Template Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Offset</td>
<td class="doxyParamItemDescription"><p>The offset into the instruction for the fixup.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-h">AVRMCCodeEmitter.h</a>, definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-cpp">AVRMCCodeEmitter.cpp</a>.</p>

</div>
</div>

### encodeInstruction() {#ae1356decfcdbb99dd3cf79893b85d767}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AVRMCCodeEmitter::encodeInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-h">AVRMCCodeEmitter.h</a>, definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-cpp">AVRMCCodeEmitter.cpp</a>.</p>

</div>
</div>

### encodeMemri() {#a535751a09a837ac9804fdec631aa01da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AVRMCCodeEmitter::encodeMemri (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Encodes a <span class="doxyComputerOutput">register+immediate</span> operand for <span class="doxyComputerOutput">LDD</span>/<span class="doxyComputerOutput">STD</span>.</p>


<p>Performs a post-encoding step on a <span class="doxyComputerOutput">LD</span> or <span class="doxyComputerOutput">ST</span> instruction.</p>


<p>The encoding of the LD/ST family of instructions is inconsistent w.r.t the pointer register and the addressing mode.</p>


<p>The permutations of the format are as followed: ld Rd, X <span class="doxyComputerOutput">1001 000d dddd 1100</span> ld Rd, X+ <span class="doxyComputerOutput">1001 000d dddd 1101</span> ld Rd, -X <span class="doxyComputerOutput">1001 000d dddd 1110</span></p>


<p>ld Rd, Y <span class="doxyComputerOutput">1000 000d dddd 1000</span> ld Rd, Y+ <span class="doxyComputerOutput">1001 000d dddd 1001</span> ld Rd, -Y <span class="doxyComputerOutput">1001 000d dddd 1010</span></p>


<p>ld Rd, Z <span class="doxyComputerOutput">1000 000d dddd 0000</span> ld Rd, Z+ <span class="doxyComputerOutput">1001 000d dddd 0001</span> ld Rd, -Z <span class="doxyComputerOutput">1001 000d dddd 0010</span> ^ | Note this one inconsistent bit - it is 1 sometimes and 0 at other times. There is no logical pattern. Looking at a truth table, the following formula can be derived to fit the pattern:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">inconsistent_bit = is_predec <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">OR</a> is_postinc <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">OR</a> is_reg_x</span></span></div>

</div>


<p>// We manually set this bit in this post encoder method. */ unsigned AVRMCCodeEmitter::loadStorePostEncoder(const MCInst &amp;MI, unsigned EncodedValue,
                                       const MCSubtargetInfo &amp;STI) const {</p>


<p>assert(MI.getOperand(0).<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg()</a> &amp;&amp; MI.getOperand(1).<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg()</a> &amp;&amp; "the load/store operands must be registers");</p>


<p>unsigned Opcode = MI.getOpcode();</p>


<p>Get the index of the pointer register operand. unsigned Idx = 0; if (Opcode == AVR::LDRdPtrPd || Opcode == AVR::LDRdPtrPi || Opcode == AVR::LDRdPtr) Idx = 1;</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if we need to set the inconsistent bit bool IsPredec = Opcode == AVR::LDRdPtrPd || Opcode == AVR::STPtrPdRr; bool IsPostinc = Opcode == AVR::LDRdPtrPi || Opcode == AVR::STPtrPiRr; if (MI.getOperand(Idx).<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg()</a> == AVR::R27R26 || IsPredec || IsPostinc) EncodedValue |= (1 &lt;&lt; 12);</p>


<p>Encode the pointer register. switch (MI.getOperand(Idx).<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg()</a>) { case AVR::R27R26: EncodedValue |= 0xc; break; case AVR::R29R28: EncodedValue |= 0x8; break; case AVR::R31R30: break; default: llvm_unreachable("invalid pointer register"); break; }</p>


<p>return EncodedValue; }</p>


<p>template &lt;<a href="/web-llvm/docs/api/namespaces/llvm/avr/#ae093893769f0a31accd70fbf3fd419b1">AVR::Fixups</a> Fixup&gt; unsigned AVRMCCodeEmitter::encodeRelCondBrTarget(const MCInst &amp;MI, unsigned OpNo,
                                        SmallVectorImpl&lt;MCFixup&gt; &amp;Fixups,
                                        const MCSubtargetInfo &amp;STI) const { const <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp;MO = MI.getOperand(OpNo);</p>


<p>if (MO.isExpr()) { Fixups.push_back( <a href="/web-llvm/docs/api/classes/llvm/mcfixup/#abdf37854fa6eb68017b96486df443a32">MCFixup::create</a>(0, MO.getExpr(), <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58">MCFixupKind(Fixup)</a>, MI.getLoc())); return 0; }</p>


<p>assert(MO.isImm());</p>


<p>Take the size of the current instruction away. With labels, this is implicitly done. auto target = MO.getImm(); AVR::fixups::adjustBranchTarget(target); return target; }</p>


<p>/** Encodes a <span class="doxyComputerOutput">memri</span> operand. The operand is 7-bits.</p>


<ul class="doxyList ">
<li>The lower 6 bits is the immediate</li>
<li>The upper bit is the pointer register bit (Z=0,Y=1)</li>
</ul>

<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-h">AVRMCCodeEmitter.h</a>, definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-cpp">AVRMCCodeEmitter.cpp</a>.</p>

</div>
</div>

### encodeRelCondBrTarget() {#ae7302533618c36439c1b6cdc6d9cb1e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;AVR::Fixups Fixup&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AVRMCCodeEmitter::encodeRelCondBrTarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets the encoding for a conditional branch target.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-h">AVRMCCodeEmitter.h</a>.</p>

</div>
</div>

### getBinaryCodeForInstr() {#a2b82aab04fc2fbaea3c0e0673836854a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::AVRMCCodeEmitter::getBinaryCodeForInstr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a>'ed function to get the binary encoding for an instruction.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-h">AVRMCCodeEmitter.h</a>.</p>

</div>
</div>

### getExprOpValue() {#a5d15b30175e4ffd082760fd1a6542402}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AVRMCCodeEmitter::getExprOpValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-h">AVRMCCodeEmitter.h</a>, definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-cpp">AVRMCCodeEmitter.cpp</a>.</p>

</div>
</div>

### getMachineOpValue() {#ac561c265a8eb5f9d734d0dfd964e7a34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AVRMCCodeEmitter::getMachineOpValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; MO, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the binary encoding of operand.</p>


<p>If the machine operand requires relocation, the relocation is recorded and zero is returned.</p>


<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-h">AVRMCCodeEmitter.h</a>, definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-cpp">AVRMCCodeEmitter.cpp</a>.</p>

</div>
</div>

### loadStorePostEncoder() {#af2b044eeb8a9c6627ab1eb863b5d4ea8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AVRMCCodeEmitter::loadStorePostEncoder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, unsigned EncodedValue, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finishes up encoding an LD/ST instruction.</p>


<p>The purpose of this function is to set an bit in the instruction which follows no logical pattern. See the implementation for details.</p>


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-h">AVRMCCodeEmitter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Ctx {#aba64c6bee17601364d3122e974cb718f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext&amp; llvm::AVRMCCodeEmitter::Ctx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-h">AVRMCCodeEmitter.h</a>.</p>

</div>
</div>

### MCII {#a4567262f76293737ac8cec9a9a32bd28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCInstrInfo&amp; llvm::AVRMCCodeEmitter::MCII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-h">AVRMCCodeEmitter.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-cpp">AVRMCCodeEmitter.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmccodeemitter-h">AVRMCCodeEmitter.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
