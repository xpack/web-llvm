---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-loongarchmccodeemitter-cpp-/loongarchmccodeemitter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LoongArchMCCodeEmitter` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62e67667ee8e8fd1063db7f1abe921e4">LoongArchMCCodeEmitter</a> (MCContext &amp;ctx, MCInstrInfo const &amp;MCII)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a5a31df4f5b238352977c30fde81998">LoongArchMCCodeEmitter</a> (const LoongArchMCCodeEmitter &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aeef2a20b390f09151e000308215c1b">~LoongArchMCCodeEmitter</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95155b93bafa3d31b0480fe808662ed3">operator=</a> (const LoongArchMCCodeEmitter &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79052c2401f49c8daef2440833b8f624">encodeInstruction</a> (const MCInst &amp;MI, SmallVectorImpl&lt; char &gt; &amp;CB, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encode the given <span class="doxyComputerOutput">Inst</span> to bytes and append to <span class="doxyComputerOutput">CB</span>. <a href="#a79052c2401f49c8daef2440833b8f624">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned Opc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3985c640bde224e8ef6b275f9a1e3be7">expandToVectorLDI</a> (const MCInst &amp;MI, SmallVectorImpl&lt; char &gt; &amp;CB, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6740cbf8bbdd52574f85db63500cd25">expandAddTPRel</a> (const MCInst &amp;MI, SmallVectorImpl&lt; char &gt; &amp;CB, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40b62ffa25ac1dbeeff7bfd23ad5ce11">getBinaryCodeForInstr</a> (const MCInst &amp;MI, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a>'erated function for getting the binary encoding for an instruction. <a href="#a40b62ffa25ac1dbeeff7bfd23ad5ce11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92b2c2e6e237469e463e5a402954447b">getMachineOpValue</a> (const MCInst &amp;MI, const MCOperand &amp;MO, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return binary encoding of operand. <a href="#a92b2c2e6e237469e463e5a402954447b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd8fc9de4306c356df340ec49acd6a38">getImmOpValueSub1</a> (const MCInst &amp;MI, unsigned OpNo, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return binary encoding of an immediate operand specified by OpNo. <a href="#acd8fc9de4306c356df340ec49acd6a38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af641c8f0bf20235b08fc10826724dc8a">getImmOpValueAsr</a> (const MCInst &amp;MI, unsigned OpNo, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return binary encoding of an immediate operand specified by OpNo. <a href="#af641c8f0bf20235b08fc10826724dc8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a496a589a4ca89aafae1db05782b62cde">getExprOpValue</a> (const MCInst &amp;MI, const MCOperand &amp;MO, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned Opc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3985c640bde224e8ef6b275f9a1e3be7">expandToVectorLDI</a> (const MCInst &amp;MI, SmallVectorImpl&lt; char &gt; &amp;CB, SmallVectorImpl&lt; MCFixup &gt; &amp;Fixups, const MCSubtargetInfo &amp;STI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd36cd4b765447557b169a71d6aeaca1">Ctx</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28caaa2c86152dd0a3a55781381b3113">MCII</a></td>
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


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmccodeemitter-cpp">LoongArchMCCodeEmitter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoongArchMCCodeEmitter() {#a62e67667ee8e8fd1063db7f1abe921e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::LoongArchMCCodeEmitter (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; ctx, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII)</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmccodeemitter-cpp">LoongArchMCCodeEmitter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### LoongArchMCCodeEmitter() {#a1a5a31df4f5b238352977c30fde81998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::LoongArchMCCodeEmitter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-loongarchmccodeemitter-cpp-/loongarchmccodeemitter">LoongArchMCCodeEmitter</a> &amp;)</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmccodeemitter-cpp">LoongArchMCCodeEmitter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LoongArchMCCodeEmitter() {#a2aeef2a20b390f09151e000308215c1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::~LoongArchMCCodeEmitter ()</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmccodeemitter-cpp">LoongArchMCCodeEmitter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Operators

### operator=() {#a95155b93bafa3d31b0480fe808662ed3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-loongarchmccodeemitter-cpp-/loongarchmccodeemitter">LoongArchMCCodeEmitter</a> &amp;)</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmccodeemitter-cpp">LoongArchMCCodeEmitter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### encodeInstruction() {#a79052c2401f49c8daef2440833b8f624}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoongArchMCCodeEmitter::encodeInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmccodeemitter-cpp">LoongArchMCCodeEmitter.cpp</a>.</p>


<p>References <a href="#ac6740cbf8bbdd52574f85db63500cd25">expandAddTPRel</a>, <a href="#a3985c640bde224e8ef6b275f9a1e3be7">expandToVectorLDI</a>, <a href="#a40b62ffa25ac1dbeeff7bfd23ad5ce11">getBinaryCodeForInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>.</p>

</div>
</div>

### expandAddTPRel() {#ac6740cbf8bbdd52574f85db63500cd25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoongArchMCCodeEmitter::expandAddTPRel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmccodeemitter-cpp">LoongArchMCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder/#a6990ced5e71387ca4e8aaa1c4f96b380">llvm::MCInstBuilder::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfixup/#abdf37854fa6eb68017b96486df443a32">llvm::MCFixup::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a5fca7ef96b80eeb5fd1b6a3163efa7c8">llvm::LoongArch::fixup_loongarch_relax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a2b7b0cf591b58d1f5b6e12555947ca8f">llvm::LoongArch::fixup_loongarch_tls_le_add_r</a>, <a href="#a40b62ffa25ac1dbeeff7bfd23ad5ce11">getBinaryCodeForInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a4bf4b498b59667ac2ef8028f56fe51e1">llvm::LoongArchMCExpr::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fac93f74665b151febca74a33966c42f24">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LE_ADD_R</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>.</p>


<p>Referenced by <a href="#a79052c2401f49c8daef2440833b8f624">encodeInstruction</a> and <a href="#a3985c640bde224e8ef6b275f9a1e3be7">expandToVectorLDI</a>.</p>

</div>
</div>

### expandToVectorLDI() {#a3985c640bde224e8ef6b275f9a1e3be7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned Opc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::expandToVectorLDI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmccodeemitter-cpp">LoongArchMCCodeEmitter.cpp</a>.</p>


<p>References <a href="#ac6740cbf8bbdd52574f85db63500cd25">expandAddTPRel</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a79052c2401f49c8daef2440833b8f624">encodeInstruction</a>.</p>

</div>
</div>

### expandToVectorLDI() {#a3985c640bde224e8ef6b275f9a1e3be7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned Opc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::expandToVectorLDI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; CB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmccodeemitter-cpp">LoongArchMCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder/#ac6bfc040ddca811a88a95e1f6d6b3747">llvm::MCInstBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstbuilder/#a6990ced5e71387ca4e8aaa1c4f96b380">llvm::MCInstBuilder::addOperand</a>, <a href="#a40b62ffa25ac1dbeeff7bfd23ad5ce11">getBinaryCodeForInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>.</p>

</div>
</div>

### getBinaryCodeForInstr() {#a40b62ffa25ac1dbeeff7bfd23ad5ce11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::getBinaryCodeForInstr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a>'erated function for getting the binary encoding for an instruction.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmccodeemitter-cpp">LoongArchMCCodeEmitter.cpp</a>.</p>


<p>References <a href="#acd8fc9de4306c356df340ec49acd6a38">getImmOpValueSub1</a>, <a href="#a92b2c2e6e237469e463e5a402954447b">getMachineOpValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a79052c2401f49c8daef2440833b8f624">encodeInstruction</a>, <a href="#ac6740cbf8bbdd52574f85db63500cd25">expandAddTPRel</a> and <a href="#a3985c640bde224e8ef6b275f9a1e3be7">expandToVectorLDI</a>.</p>

</div>
</div>

### getExprOpValue() {#a496a589a4ca89aafae1db05782b62cde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LoongArchMCCodeEmitter::getExprOpValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; MO, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmccodeemitter-cpp">LoongArchMCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfixup/#abdf37854fa6eb68017b96486df443a32">llvm::MCFixup::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a182008c1f6c332cb2cfd8c3d3ffada3e">llvm::LoongArch::fixup_loongarch_abs64_hi12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a5781daab526ee6f78c11cef621710a2d">llvm::LoongArch::fixup_loongarch_abs64_lo20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a21687a5a7d599a51082b61a1d0a6460b">llvm::LoongArch::fixup_loongarch_abs_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a343c4c51960b95f6932cb1ba63ed48cf">llvm::LoongArch::fixup_loongarch_abs_lo12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a3f224f26aafd12d872689f8eb64ca9ff">llvm::LoongArch::fixup_loongarch_b16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a6a204b67935b35bfa83298c90529c8a5">llvm::LoongArch::fixup_loongarch_b21</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a392f7ae3052bbb64a2fe93f149406d91">llvm::LoongArch::fixup_loongarch_b26</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a59970f56c58d60df377c56b5e91a0bdc">llvm::LoongArch::fixup_loongarch_call36</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a27effc7fabddb827c97fe12c08b4b4ed">llvm::LoongArch::fixup_loongarch_got64_hi12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a76186316b79421b904e5616dd40a77f4">llvm::LoongArch::fixup_loongarch_got64_lo20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a4e73d9c87b6ea7808c96d97684a5921e">llvm::LoongArch::fixup_loongarch_got64_pc_hi12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a816bc68679fd92ee1d3bc24d616734b3">llvm::LoongArch::fixup_loongarch_got64_pc_lo20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442ad9c7cbe9f5b23dc2c8573bb0eb65281c">llvm::LoongArch::fixup_loongarch_got_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442aacce8aaa2283b7aab1c717c12737b55c">llvm::LoongArch::fixup_loongarch_got_lo12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442ace2a6b39eee23db158b0de4cbd417a0d">llvm::LoongArch::fixup_loongarch_got_pc_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a84ae204828658f7a4ddb6d3d2aef7d9d">llvm::LoongArch::fixup_loongarch_got_pc_lo12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a3ec696ff217c26a3f7cdc6cde57036be">llvm::LoongArch::fixup_loongarch_invalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a2629a2a4eda3b73a2194529d8c62a01f">llvm::LoongArch::fixup_loongarch_pcala64_hi12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a598695ee31d24c927a625ba43991764b">llvm::LoongArch::fixup_loongarch_pcala64_lo20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a30f70c1a75b3d1f90a90bad77d1f9552">llvm::LoongArch::fixup_loongarch_pcala_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442aaacb6594915668631b88a1a9dd82a1a8">llvm::LoongArch::fixup_loongarch_pcala_lo12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442aa97ef6bb067a0826e482475f0d2c58c1">llvm::LoongArch::fixup_loongarch_pcrel20_s2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a5fca7ef96b80eeb5fd1b6a3163efa7c8">llvm::LoongArch::fixup_loongarch_relax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a29ef5f049dc0156695b4612536454b75">llvm::LoongArch::fixup_loongarch_tls_desc64_hi12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a44def7e9e81969a7cdaa063b216b255b">llvm::LoongArch::fixup_loongarch_tls_desc64_lo20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442aa95aaec8bb8dad453efc686fda1867b6">llvm::LoongArch::fixup_loongarch_tls_desc64_pc_hi12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a0b331a509be207369a4345fdb7570e5d">llvm::LoongArch::fixup_loongarch_tls_desc64_pc_lo20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a836a1f04695534ec8427ce5fa2dd23ca">llvm::LoongArch::fixup_loongarch_tls_desc_call</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a5cfe57ceb00f912383559bcf32db7acf">llvm::LoongArch::fixup_loongarch_tls_desc_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a90e25d7d9eab9d83d73eaae639e3efc9">llvm::LoongArch::fixup_loongarch_tls_desc_ld</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a9ba95db567e06dacb0dc7942d2e83f93">llvm::LoongArch::fixup_loongarch_tls_desc_lo12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442ab93d415801aac281c02a45251b7afd2c">llvm::LoongArch::fixup_loongarch_tls_desc_pc_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442af9c08e61060803ae06cfdef3ee6539e1">llvm::LoongArch::fixup_loongarch_tls_desc_pc_lo12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a0bc1b42c2d43687b84f88de20cb7c28a">llvm::LoongArch::fixup_loongarch_tls_desc_pcrel20_s2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a277e092845e4152ebaca04dff5c1b1f6">llvm::LoongArch::fixup_loongarch_tls_gd_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a8cc1177a4f234ac06143b5e5f071d570">llvm::LoongArch::fixup_loongarch_tls_gd_pc_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a8767028752c41efd2842421e1dce2bae">llvm::LoongArch::fixup_loongarch_tls_gd_pcrel20_s2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442ae25636abc93c8f21a22e8663f0f3829e">llvm::LoongArch::fixup_loongarch_tls_ie64_hi12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442adf22d94f89325c70d09b96b5d876724d">llvm::LoongArch::fixup_loongarch_tls_ie64_lo20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442aca0d1ed529bed5ad80294b4464a6788b">llvm::LoongArch::fixup_loongarch_tls_ie64_pc_hi12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442ad0dddc75ccc9b5194ec36fc1d694c578">llvm::LoongArch::fixup_loongarch_tls_ie64_pc_lo20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a25a46a6951286c5aba59fbe61a330d3f">llvm::LoongArch::fixup_loongarch_tls_ie_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a18f18ff993ffd17a6d47f8918dd438e4">llvm::LoongArch::fixup_loongarch_tls_ie_lo12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442aff8b5461923257f1d8082bb3ee4a3900">llvm::LoongArch::fixup_loongarch_tls_ie_pc_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a2f5a1b60ab4716802c2f13dc01bbddc2">llvm::LoongArch::fixup_loongarch_tls_ie_pc_lo12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442aaa8a760d2c964e5fdab184eb7d1d4181">llvm::LoongArch::fixup_loongarch_tls_ld_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a0bc4de676222971fe2f939c4793c52ec">llvm::LoongArch::fixup_loongarch_tls_ld_pc_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442ac5ba68eb7f333ccda09e3f458b8d2b8c">llvm::LoongArch::fixup_loongarch_tls_ld_pcrel20_s2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a70bee6eb9030175a97edc63e692efdf1">llvm::LoongArch::fixup_loongarch_tls_le64_hi12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a814739c18efc36fceba5e291301c7c68">llvm::LoongArch::fixup_loongarch_tls_le64_lo20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442ada76942b1c8dba41d75a85b4fc7c5008">llvm::LoongArch::fixup_loongarch_tls_le_hi20</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442aef434a0aa4c47da8b4fea92d745ad4da">llvm::LoongArch::fixup_loongarch_tls_le_hi20_r</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a212dc9b5723f913647b5fdfede3f81d6">llvm::LoongArch::fixup_loongarch_tls_le_lo12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarch/#a570edf0f57d14f265cdb232c05912442a4c552db3ca835a6d0f5777810e8371d2">llvm::LoongArch::fixup_loongarch_tls_le_lo12_r</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d3d3a355228d2f64fa312abbd7abfbf">llvm::FixupKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ac9408fbc60922d24b01c1efcbd4ba52b">llvm::MCOperand::getExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a4bf4b498b59667ac2ef8028f56fe51e1">llvm::LoongArchMCExpr::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#af5d6e67c11188675c1309e098afac194">llvm::MCExpr::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#ae4dfc23aafdbe1c23d8dfd2d883ea412">llvm::LoongArchMCExpr::getRelaxHint</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ae23b2e8269fe15dbe5ebb3394438960c">llvm::MCOperand::isExpr</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606fa8cbc19c1660252a30c030fa945999a91">llvm::MCExpr::SymbolRef</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606faa65560b8224a92e80f422df090f07c55">llvm::MCExpr::Target</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa5a1b61e6eda817ed9e2b3cd6056990b1">llvm::LoongArchMCExpr::VK_LoongArch_ABS64_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fafa717809c42ea7a735c4ba7cd7cc9b0d">llvm::LoongArchMCExpr::VK_LoongArch_ABS64_LO20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa203b677b6d91643eee403c74f5370303">llvm::LoongArchMCExpr::VK_LoongArch_ABS_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa4b6341fa13f1dc1e47baacdcf69e8c41">llvm::LoongArchMCExpr::VK_LoongArch_ABS_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa9d404502c90b9f06080fc97fe12110ae">llvm::LoongArchMCExpr::VK_LoongArch_B16</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa898fbeff95eaf12a8ea019722e6d0d3e">llvm::LoongArchMCExpr::VK_LoongArch_B21</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa013d74af246487fe165cb00b45c3a09d">llvm::LoongArchMCExpr::VK_LoongArch_B26</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa1966ed6149cfdacca4a00fe4c47c84b2">llvm::LoongArchMCExpr::VK_LoongArch_CALL</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fad6c8d6e7d5e229e681e7d585f69faaab">llvm::LoongArchMCExpr::VK_LoongArch_CALL36</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa7eb27ee3028b06cba41393d751fe1fb5">llvm::LoongArchMCExpr::VK_LoongArch_CALL_PLT</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa311598ad7d07257815082808e9ac1fdf">llvm::LoongArchMCExpr::VK_LoongArch_GOT64_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fac47fcc37d78a9b3eec4e00531ab622a7">llvm::LoongArchMCExpr::VK_LoongArch_GOT64_LO20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa942bf7e81e85ddb89b17479502489554">llvm::LoongArchMCExpr::VK_LoongArch_GOT64_PC_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3facfb29225eda9c946dfa6a9cd6319bd2a">llvm::LoongArchMCExpr::VK_LoongArch_GOT64_PC_LO20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa2968ccf12fee2fe568d6673d83632eba">llvm::LoongArchMCExpr::VK_LoongArch_GOT_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa88122daedcca01675ef8906b58578b5c">llvm::LoongArchMCExpr::VK_LoongArch_GOT_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa657565a0ac647cc547c2ac36f3f72a55">llvm::LoongArchMCExpr::VK_LoongArch_GOT_PC_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3faa5a27ca526e9322089661bd5d5765acf">llvm::LoongArchMCExpr::VK_LoongArch_GOT_PC_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa00135481912986d64bbd2a939fd40f53">llvm::LoongArchMCExpr::VK_LoongArch_Invalid</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa33224fdcfcc9926c8a61f21eb57e1df7">llvm::LoongArchMCExpr::VK_LoongArch_None</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fadb040d152ed1e4e61470d230855861e6">llvm::LoongArchMCExpr::VK_LoongArch_PCALA64_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3faa1e2680ca0caa8430901cf1c4cac7904">llvm::LoongArchMCExpr::VK_LoongArch_PCALA64_LO20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa09957a91a71c9ef48220738c683a6664">llvm::LoongArchMCExpr::VK_LoongArch_PCALA_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa317df8b349d62bcc6b0f2f714cf4e3f2">llvm::LoongArchMCExpr::VK_LoongArch_PCALA_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa1c6d9ba2e4a6e6a8fff0f16a0e390cbb">llvm::LoongArchMCExpr::VK_LoongArch_PCREL20_S2</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa33f37781402f6b86afbef475c4161894">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC64_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fac54f5d108b9b10b10dbde7fcc8360a27">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC64_LO20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3faca511db33a132c4018d5125fbfecf380">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC64_PC_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa889c7dda330f4512b92b10d6037ae968">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC64_PC_LO20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa213239ed6908fdf8c514ee7b9fde83c7">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC_CALL</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa53d1c9f539eb44d3f293cd3d40931e62">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa83c43c389321317ab727415951d89d3b">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC_LD</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa8f6f6db2e883c43aeade25c0437dbed0">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fae6e3232ea5ed35bcff53b2870ab91caa">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC_PC_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fac40aea5222f770df6bef19887ff6e95f">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC_PC_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa27fb2e3f2b14071e67978225162fc6ef">llvm::LoongArchMCExpr::VK_LoongArch_TLS_DESC_PCREL20_S2</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa3c1cd75405441118fd8be8c2193532b1">llvm::LoongArchMCExpr::VK_LoongArch_TLS_GD_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fac8447557b79aea88da30a7924a415a4d">llvm::LoongArchMCExpr::VK_LoongArch_TLS_GD_PC_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa99900bd2b4f973f1a5267ab4fccf1ffb">llvm::LoongArchMCExpr::VK_LoongArch_TLS_GD_PCREL20_S2</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa5ed5ac4f2e54048bf799310defa548ba">llvm::LoongArchMCExpr::VK_LoongArch_TLS_IE64_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa6d762b588d0bfd42e24afb9b4943c710">llvm::LoongArchMCExpr::VK_LoongArch_TLS_IE64_LO20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3faeef04231f1e5fdc1e0422183470183f1">llvm::LoongArchMCExpr::VK_LoongArch_TLS_IE64_PC_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa69ddebf16c8e84b6872be8e80989431b">llvm::LoongArchMCExpr::VK_LoongArch_TLS_IE64_PC_LO20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa389a7ab7f07286be92f09eecb6d16e1c">llvm::LoongArchMCExpr::VK_LoongArch_TLS_IE_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3faa4ed58231825db10243f5d7200bf8d09">llvm::LoongArchMCExpr::VK_LoongArch_TLS_IE_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa9578c303dbb56ea59546a31685a7e7b4">llvm::LoongArchMCExpr::VK_LoongArch_TLS_IE_PC_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa7999ca8a77cee84f4ab594113d188745">llvm::LoongArchMCExpr::VK_LoongArch_TLS_IE_PC_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa20401cf1e3c1c674bc022e8a039770a3">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LD_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa112bf038550f50622ec2a2fae1597a1b">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LD_PC_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fae135875cdc076b203e8930a288d51547">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LD_PCREL20_S2</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa11590762cd7e097ca71309aea2b89768">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LE64_HI12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3faa0e31177c652aeaa8dc62b3692c15f10">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LE64_LO20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fac93f74665b151febca74a33966c42f24">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LE_ADD_R</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3faaf90da3f79d9695756216166cfcce205">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LE_HI20</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa36359bd9320b3a5a9d7c042872cc31ff">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LE_HI20_R</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fa5ad2126dc889178bc845a3243170a252">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LE_LO12</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a86a435759a1b631e4b292966be3bed3fabd4f5bd7211c4e6ab85c3e964360b290">llvm::LoongArchMCExpr::VK_LoongArch_TLS_LE_LO12_R</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>


<p>Referenced by <a href="#af641c8f0bf20235b08fc10826724dc8a">getImmOpValueAsr</a> and <a href="#a92b2c2e6e237469e463e5a402954447b">getMachineOpValue</a>.</p>

</div>
</div>

### getImmOpValueAsr() {#af641c8f0bf20235b08fc10826724dc8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::getImmOpValueAsr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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

<p>Return binary encoding of an immediate operand specified by OpNo.</p>


<p>The value returned is the value of the immediate shifted right Note that this function is dedicated to specific immediate types, e.g. simm14_lsl2, simm16_lsl2, simm21_lsl2 and simm26_lsl2.</p>


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmccodeemitter-cpp">LoongArchMCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a496a589a4ca89aafae1db05782b62cde">getExprOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a5f639fdcd3fc673fcbdb47f2e88b2b41">llvm::MCOperand::isImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getImmOpValueSub1() {#acd8fc9de4306c356df340ec49acd6a38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LoongArchMCCodeEmitter::getImmOpValueSub1 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, unsigned OpNo, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return binary encoding of an immediate operand specified by OpNo.</p>


<p>The value returned is the value of the immediate minus 1. Note that this function is dedicated to specific immediate types, e.g. uimm2_plus1.</p>


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmccodeemitter-cpp">LoongArchMCCodeEmitter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a40b62ffa25ac1dbeeff7bfd23ad5ce11">getBinaryCodeForInstr</a>.</p>

</div>
</div>

### getMachineOpValue() {#a92b2c2e6e237469e463e5a402954447b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LoongArchMCCodeEmitter::getMachineOpValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcoperand">MCOperand</a> &amp; MO, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &gt; &amp; Fixups, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return binary encoding of operand.</p>


<p>If the machine operand requires relocation, record the relocation and return zero.</p>


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmccodeemitter-cpp">LoongArchMCCodeEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a496a589a4ca89aafae1db05782b62cde">getExprOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a94abf618eb8001b802910ab872a7d1d9">llvm::MCOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ae23b2e8269fe15dbe5ebb3394438960c">llvm::MCOperand::isExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a5f639fdcd3fc673fcbdb47f2e88b2b41">llvm::MCOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a7a8c7eea0aa4890f25a4b83e1f0a0b6f">llvm::MCOperand::isReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a40b62ffa25ac1dbeeff7bfd23ad5ce11">getBinaryCodeForInstr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Ctx {#abd36cd4b765447557b169a71d6aeaca1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext&amp; anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::Ctx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmccodeemitter-cpp">LoongArchMCCodeEmitter.cpp</a>.</p>

</div>
</div>

### MCII {#a28caaa2c86152dd0a3a55781381b3113}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstrInfo const&amp; anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::MCII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmccodeemitter-cpp">LoongArchMCCodeEmitter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmccodeemitter-cpp">LoongArchMCCodeEmitter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
