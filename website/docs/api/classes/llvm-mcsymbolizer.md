---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcsymbolizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MCSymbolizer` Class

<p>Symbolize and annotate disassembled instructions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCSymbolizer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcsymbolizer-h">llvm/MC/MCDisassembler/MCSymbolizer.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpusymbolizer">AMDGPUSymbolizer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer">MCExternalSymbolizer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Symbolize using user-provided, C API, callbacks. <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00aa95cc168a100bdcaed4030479a064">MCSymbolizer</a> (MCContext &amp;Ctx, std::unique_ptr&lt; MCRelocationInfo &gt; RelInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer">MCSymbolizer</a>, taking ownership of <span class="doxyComputerOutput">RelInfo</span>. <a href="#a00aa95cc168a100bdcaed4030479a064">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4d3568a8e152aea7d097968b7795928">MCSymbolizer</a> (const MCSymbolizer &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3aed29e95874a781030e7041069fdd6">~MCSymbolizer</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer">MCSymbolizer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9602b13c6a3bcda6ee076454b38aef94">operator=</a> (const MCSymbolizer &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adac4188cce487f7706a299575df4f684">tryAddingSymbolicOperand</a> (MCInst &amp;Inst, raw_ostream &amp;cStream, int64_t Value, uint64_t Address, bool IsBranch, uint64_t Offset, uint64_t OpSize, uint64_t InstSize)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to add a symbolic operand instead of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> to the <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>. <a href="#adac4188cce487f7706a299575df4f684">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa88d2b02364ed21ffd55212185593c30">tryAddingPcLoadReferenceComment</a> (raw_ostream &amp;cStream, int64_t Value, uint64_t Address)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to add a comment on the PC-relative load. <a href="#aa88d2b02364ed21ffd55212185593c30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff22a92530c025154e8c3aa07d887b2c">getReferencedAddresses</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer">MCSymbolizer</a>'s list of addresses that were referenced by symbolizable operands but not resolved to a symbol. <a href="#aff22a92530c025154e8c3aa07d887b2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7ae949c9f9c53c3e6e8c29799753c01">Ctx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo">MCRelocationInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65399cf3fad4593f48477a0962ddd074">RelInfo</a></td>
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

<p>Symbolize and annotate disassembled instructions.</p>


<p>For now this mimics the old symbolization logic (from both <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> and x86), that relied on user-provided (C API) callbacks to do the actual symbol lookup in the object file. This was moved to <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer">MCExternalSymbolizer</a>. A better API would not rely on actually calling the two methods here from inside each disassembler, but would use the instr info to determine what operands are actually symbolizable, and in what way. I don't think this information exists right now.</p>


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcsymbolizer-h">MCSymbolizer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCSymbolizer() {#a00aa95cc168a100bdcaed4030479a064}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCSymbolizer::MCSymbolizer (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo">MCRelocationInfo</a> &gt; RelInfo)</td>
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

<p>Construct an <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer">MCSymbolizer</a>, taking ownership of <span class="doxyComputerOutput">RelInfo</span>.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcsymbolizer-h">MCSymbolizer.h</a>.</p>


<p>References <a href="#ae7ae949c9f9c53c3e6e8c29799753c01">Ctx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#a65399cf3fad4593f48477a0962ddd074">RelInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpusymbolizer/#a70de8ee85411894e7911e34e0d8020d0">llvm::AMDGPUSymbolizer::AMDGPUSymbolizer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#a33721a5176a9422407d47a78e6bbfe82">llvm::MCExternalSymbolizer::MCExternalSymbolizer</a>, <a href="#ab4d3568a8e152aea7d097968b7795928">MCSymbolizer</a> and <a href="#a9602b13c6a3bcda6ee076454b38aef94">operator=</a>.</p>

</div>
</div>

### MCSymbolizer() {#ab4d3568a8e152aea7d097968b7795928}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCSymbolizer::MCSymbolizer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer">MCSymbolizer</a> &amp;)</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcsymbolizer-h">MCSymbolizer.h</a>.</p>


<p>Reference <a href="#a00aa95cc168a100bdcaed4030479a064">MCSymbolizer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MCSymbolizer() {#aa3aed29e95874a781030e7041069fdd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbolizer::~MCSymbolizer ()</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcsymbolizer-h">MCSymbolizer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a9602b13c6a3bcda6ee076454b38aef94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbolizer &amp; llvm::MCSymbolizer::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer">MCSymbolizer</a> &amp;)</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcsymbolizer-h">MCSymbolizer.h</a>.</p>


<p>Reference <a href="#a00aa95cc168a100bdcaed4030479a064">MCSymbolizer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getReferencedAddresses() {#aff22a92530c025154e8c3aa07d887b2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ArrayRef&lt; uint64_t &gt; llvm::MCSymbolizer::getReferencedAddresses ()</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer">MCSymbolizer</a>'s list of addresses that were referenced by symbolizable operands but not resolved to a symbol.</p>


<p>The caller (some code that is disassembling a section or other chunk of code) would typically create a synthetic label at each address and add them to its list of symbols in the section, before creating a new <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer">MCSymbolizer</a> with the enhanced symbol list and retrying disassembling the section. The returned array is unordered and may have duplicates. The returned <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> stops being valid on any call to or destruction of the <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer">MCSymbolizer</a> object.</p>


<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcsymbolizer-h">MCSymbolizer.h</a>.</p>

</div>
</div>

### tryAddingPcLoadReferenceComment() {#aa88d2b02364ed21ffd55212185593c30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCSymbolizer::tryAddingPcLoadReferenceComment (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; cStream, int64_t Value, uint64_t Address)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to add a comment on the PC-relative load.</p>


<p>For instance, in Mach-O, this is used to add annotations to instructions that use C string literals, as found in __cstring.</p>


<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcsymbolizer-h">MCSymbolizer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>.</p>

</div>
</div>

### tryAddingSymbolicOperand() {#adac4188cce487f7706a299575df4f684}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCSymbolizer::tryAddingSymbolicOperand (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; cStream, int64_t Value, uint64_t Address, bool IsBranch, uint64_t Offset, uint64_t OpSize, uint64_t InstSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to add a symbolic operand instead of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> to the <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>.</p>


<p>Instead of having a difficult to read immediate, a symbolic operand would represent this immediate in a more understandable way, for instance as a symbol or an offset from a symbol. Relocations can also be used to enrich the symbolic expression.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Inst</td>
<td class="doxyParamItemDescription"><p>- The <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> where to insert the symbolic operand.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">cStream</td>
<td class="doxyParamItemDescription"><p>- Stream to print comments and annotations on.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/llvm/value"&gt;Value&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>- Operand value, pc-adjusted by the caller if necessary.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Address</td>
<td class="doxyParamItemDescription"><p>- Load address of the instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsBranch</td>
<td class="doxyParamItemDescription"><p>- Is the instruction a branch?</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Offset</td>
<td class="doxyParamItemDescription"><p>- Byte offset of the operand inside the inst.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OpSize</td>
<td class="doxyParamItemDescription"><p>- Size of the operand in bytes.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InstSize</td>
<td class="doxyParamItemDescription"><p>- Size of the instruction in bytes.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Whether a symbolic operand was added.</p></dd>
</dl>


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcsymbolizer-h">MCSymbolizer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Ctx {#ae7ae949c9f9c53c3e6e8c29799753c01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext&amp; llvm::MCSymbolizer::Ctx</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcsymbolizer-h">MCSymbolizer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#a1d968b4e0193154acbbe41c3604f7f20">llvm::AArch64ExternalSymbolizer::AArch64ExternalSymbolizer</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusymbolizer/#a70de8ee85411894e7911e34e0d8020d0">llvm::AMDGPUSymbolizer::AMDGPUSymbolizer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#a33721a5176a9422407d47a78e6bbfe82">llvm::MCExternalSymbolizer::MCExternalSymbolizer</a>, <a href="#a00aa95cc168a100bdcaed4030479a064">MCSymbolizer</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusymbolizer/#a6c8e8592c8a9a236312224fb457fc834">llvm::AMDGPUSymbolizer::tryAddingSymbolicOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#aa4807aa3571299368e6d9b5c3d39893a">llvm::MCExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### RelInfo {#a65399cf3fad4593f48477a0962ddd074}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MCRelocationInfo&gt; llvm::MCSymbolizer::RelInfo</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcsymbolizer-h">MCSymbolizer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#a1d968b4e0193154acbbe41c3604f7f20">llvm::AArch64ExternalSymbolizer::AArch64ExternalSymbolizer</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusymbolizer/#a70de8ee85411894e7911e34e0d8020d0">llvm::AMDGPUSymbolizer::AMDGPUSymbolizer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#a33721a5176a9422407d47a78e6bbfe82">llvm::MCExternalSymbolizer::MCExternalSymbolizer</a>, <a href="#a00aa95cc168a100bdcaed4030479a064">MCSymbolizer</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#aa4807aa3571299368e6d9b5c3d39893a">llvm::MCExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcsymbolizer-h">MCSymbolizer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
