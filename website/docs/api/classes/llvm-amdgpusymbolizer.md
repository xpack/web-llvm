---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgpusymbolizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AMDGPUSymbolizer` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPUSymbolizer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">Target/AMDGPU/Disassembler/AMDGPUDisassembler.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer">MCSymbolizer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Symbolize and annotate disassembled instructions. <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70de8ee85411894e7911e34e0d8020d0">AMDGPUSymbolizer</a> (MCContext &amp;Ctx, std::unique_ptr&lt; MCRelocationInfo &gt; &amp;&amp;RelInfo, void *disInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c8e8592c8a9a236312224fb457fc834">tryAddingSymbolicOperand</a> (MCInst &amp;Inst, raw_ostream &amp;cStream, int64_t Value, uint64_t Address, bool IsBranch, uint64_t Offset, uint64_t OpSize, uint64_t InstSize) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to add a symbolic operand instead of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> to the <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>. <a href="#a6c8e8592c8a9a236312224fb457fc834">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a768aa0c6497b97983622dfda59705b95">tryAddingPcLoadReferenceComment</a> (raw_ostream &amp;cStream, int64_t Value, uint64_t Address) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to add a comment on the PC-relative load. <a href="#a768aa0c6497b97983622dfda59705b95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3716e8d35ed9e76daa734f04befa0b92">getReferencedAddresses</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer">MCSymbolizer</a>'s list of addresses that were referenced by symbolizable operands but not resolved to a symbol. <a href="#a3716e8d35ed9e76daa734f04befa0b92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c3e6f04b38ec8f540800a67881ae514">DisInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88603de9e9cf882b2489872ed46970d9">ReferencedAddresses</a></td>
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


<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AMDGPUSymbolizer() {#a70de8ee85411894e7911e34e0d8020d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AMDGPUSymbolizer::AMDGPUSymbolizer (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo">MCRelocationInfo</a> &gt; &amp;&amp; RelInfo, void * disInfo)</td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer/#ae7ae949c9f9c53c3e6e8c29799753c01">llvm::MCSymbolizer::Ctx</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer/#a00aa95cc168a100bdcaed4030479a064">llvm::MCSymbolizer::MCSymbolizer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer/#a65399cf3fad4593f48477a0962ddd074">llvm::MCSymbolizer::RelInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getReferencedAddresses() {#a3716e8d35ed9e76daa734f04befa0b92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uint64_t &gt; llvm::AMDGPUSymbolizer::getReferencedAddresses ()</td>
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


<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>.</p>

</div>
</div>

### tryAddingPcLoadReferenceComment() {#a768aa0c6497b97983622dfda59705b95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUSymbolizer::tryAddingPcLoadReferenceComment (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; cStream, int64_t Value, uint64_t Address)</td>
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

<p>Try to add a comment on the PC-relative load.</p>


<p>For instance, in Mach-O, this is used to add annotations to instructions that use C string literals, as found in __cstring.</p>


<p>Declaration at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 2584 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### tryAddingSymbolicOperand() {#a6c8e8592c8a9a236312224fb457fc834}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUSymbolizer::tryAddingSymbolicOperand (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; cStream, int64_t Value, uint64_t Address, bool IsBranch, uint64_t Offset, uint64_t OpSize, uint64_t InstSize)</td>
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


<p>Declaration at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>, definition at line 2556 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/symbolinfoty/#afbab73489bf1a6bd2d3d605b87267528">llvm::SymbolInfoTy::Addr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer/#ae7ae949c9f9c53c3e6e8c29799753c01">llvm::MCSymbolizer::Ctx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a2addd3222711e927ec6604bc65bccb2c">llvm::ELF::STT_NOTYPE</a> and <a href="/web-llvm/docs/api/structs/llvm/symbolinfoty/#af21a9bc17551fea2afa647a2db3cbcdb">llvm::SymbolInfoTy::Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DisInfo {#a7c3e6f04b38ec8f540800a67881ae514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::AMDGPUSymbolizer::DisInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>.</p>

</div>
</div>

### ReferencedAddresses {#a88603de9e9cf882b2489872ed46970d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint64_t&gt; llvm::AMDGPUSymbolizer::ReferencedAddresses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp">AMDGPUDisassembler.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-h">AMDGPUDisassembler.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
