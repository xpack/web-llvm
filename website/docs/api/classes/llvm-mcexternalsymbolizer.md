---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcexternalsymbolizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MCExternalSymbolizer` Class

<p>Symbolize using user-provided, C API, callbacks. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCExternalSymbolizer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcexternalsymbolizer-h">llvm/MC/MCDisassembler/MCExternalSymbolizer.h</a>"
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer">AArch64ExternalSymbolizer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33721a5176a9422407d47a78e6bbfe82">MCExternalSymbolizer</a> (MCContext &amp;Ctx, std::unique_ptr&lt; MCRelocationInfo &gt; RelInfo, LLVMOpInfoCallback getOpInfo, LLVMSymbolLookupCallback symbolLookUp, void *disInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4807aa3571299368e6d9b5c3d39893a">tryAddingSymbolicOperand</a> (MCInst &amp;MI, raw_ostream &amp;CommentStream, int64_t Value, uint64_t Address, bool IsBranch, uint64_t Offset, uint64_t OpSize, uint64_t InstSize) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to add a symbolic operand instead of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span> to the <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>. <a href="#aa4807aa3571299368e6d9b5c3d39893a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a932da00ce99b1018afdbc02579239ff1">tryAddingPcLoadReferenceComment</a> (raw_ostream &amp;CommentStream, int64_t Value, uint64_t Address) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to add a comment on the PC-relative load. <a href="#a932da00ce99b1018afdbc02579239ff1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Hooks for symbolic disassembly via the public 'C' interface. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gaa8eb7ea1e53fd6e7a11b6aa4749c6e60">LLVMOpInfoCallback</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2307af972a75c070da7242a59df69859">GetOpInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga05ffa603beb390898904a06b14ee5537">LLVMSymbolLookupCallback</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43bb0a0aab29f9a9dbdee6a2e2d3264f">SymbolLookUp</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The function to lookup a symbol name. <a href="#a43bb0a0aab29f9a9dbdee6a2e2d3264f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08e6d3c9e137726ed3c3729b61d8bed0">DisInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The pointer to the block of symbolic information for above call back. <a href="#a08e6d3c9e137726ed3c3729b61d8bed0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Symbolize using user-provided, C API, callbacks.</p>


<p>See <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassembler-h">llvm-c/Disassembler.h</a>.</p>


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcexternalsymbolizer-h">MCExternalSymbolizer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCExternalSymbolizer() {#a33721a5176a9422407d47a78e6bbfe82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCExternalSymbolizer::MCExternalSymbolizer (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo">MCRelocationInfo</a> &gt; RelInfo, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gaa8eb7ea1e53fd6e7a11b6aa4749c6e60">LLVMOpInfoCallback</a> getOpInfo, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga05ffa603beb390898904a06b14ee5537">LLVMSymbolLookupCallback</a> symbolLookUp, void * disInfo)</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcexternalsymbolizer-h">MCExternalSymbolizer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer/#ae7ae949c9f9c53c3e6e8c29799753c01">llvm::MCSymbolizer::Ctx</a>, <a href="#a08e6d3c9e137726ed3c3729b61d8bed0">DisInfo</a>, <a href="#a2307af972a75c070da7242a59df69859">GetOpInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer/#a00aa95cc168a100bdcaed4030479a064">llvm::MCSymbolizer::MCSymbolizer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer/#a65399cf3fad4593f48477a0962ddd074">llvm::MCSymbolizer::RelInfo</a> and <a href="#a43bb0a0aab29f9a9dbdee6a2e2d3264f">SymbolLookUp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#a1d968b4e0193154acbbe41c3604f7f20">llvm::AArch64ExternalSymbolizer::AArch64ExternalSymbolizer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### tryAddingPcLoadReferenceComment() {#a932da00ce99b1018afdbc02579239ff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCExternalSymbolizer::tryAddingPcLoadReferenceComment (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; cStream, int64_t Value, uint64_t Address)</td>
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


<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcexternalsymbolizer-h">MCExternalSymbolizer.h</a>, definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/mcexternalsymbolizer-cpp">MCExternalSymbolizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="#a08e6d3c9e137726ed3c3729b61d8bed0">DisInfo</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga4d14397b83038d9f432101b60d28afcd">LLVMDisassembler_ReferenceType_In_PCrel_Load</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga81e5011868131b85e2fe428b5de9165b">LLVMDisassembler_ReferenceType_Out_LitPool_CstrAddr</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga9ddf8b97918a69a6a513225d2f26c91f">LLVMDisassembler_ReferenceType_Out_LitPool_SymAddr</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga4e7df42625f59e6870f6aaa04fd8e112">LLVMDisassembler_ReferenceType_Out_Objc_CFString_Ref</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga32181431bb3d71b1218b596eb3252b3f">LLVMDisassembler_ReferenceType_Out_Objc_Class_Ref</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gaa07c4db36282f91d8f9da2f1c74ffc4c">LLVMDisassembler_ReferenceType_Out_Objc_Message</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gaceddd31c06c7ca91bb4747dd008a7bfb">LLVMDisassembler_ReferenceType_Out_Objc_Message_Ref</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gab234f9f0c243edf081dcbee6400c320a">LLVMDisassembler_ReferenceType_Out_Objc_Selector_Ref</a>, <a href="#a43bb0a0aab29f9a9dbdee6a2e2d3264f">SymbolLookUp</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a5ba2ece4b959bae02752c34b784ba087">llvm::raw_ostream::write_escaped</a>.</p>

</div>
</div>

### tryAddingSymbolicOperand() {#aa4807aa3571299368e6d9b5c3d39893a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCExternalSymbolizer::tryAddingSymbolicOperand (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; cStream, int64_t Value, uint64_t Address, bool IsBranch, uint64_t Offset, uint64_t OpSize, uint64_t InstSize)</td>
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


<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcexternalsymbolizer-h">MCExternalSymbolizer.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/mcexternalsymbolizer-cpp">MCExternalSymbolizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/structs/llvmopinfo1/#a5ac48adba22aa66db9bed16f0d492705">LLVMOpInfo1::AddSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a3cbe1086ebf00680e8dc374e07305cfb">llvm::MCBinaryExpr::createAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#aff718d95a5738283e9049bc93fa9abe2">llvm::MCUnaryExpr::createMinus</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer/#ae7ae949c9f9c53c3e6e8c29799753c01">llvm::MCSymbolizer::Ctx</a>, <a href="#a08e6d3c9e137726ed3c3729b61d8bed0">DisInfo</a>, <a href="#a2307af972a75c070da7242a59df69859">GetOpInfo</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gae11bd2845e00fc1aed8223da0793bf4b">LLVMDisassembler_ReferenceType_DeMangled_Name</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga82fca9d886616e829b203276c80afabf">LLVMDisassembler_ReferenceType_In_Branch</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gaa6b926b61f2d59191c806d31bb94c894">LLVMDisassembler_ReferenceType_InOut_None</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gaa07c4db36282f91d8f9da2f1c74ffc4c">LLVMDisassembler_ReferenceType_Out_Objc_Message</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga43cc63fe7d58d8379d06b31cf92d620b">LLVMDisassembler_ReferenceType_Out_SymbolStub</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/llvmopinfosymbol1/#a60a11f3a829fd9bbeb3071bf372bcef0">LLVMOpInfoSymbol1::Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/structs/llvmopinfosymbol1/#a03a90bff1e766901579a900fd4f870a1">LLVMOpInfoSymbol1::Present</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer/#a65399cf3fad4593f48477a0962ddd074">llvm::MCSymbolizer::RelInfo</a>, <a href="/web-llvm/docs/api/structs/llvmopinfo1/#a5a683606e957f62746726cab5935d165">LLVMOpInfo1::SubtractSymbol</a>, <a href="#a43bb0a0aab29f9a9dbdee6a2e2d3264f">SymbolLookUp</a>, <a href="/web-llvm/docs/api/structs/llvmopinfo1/#ada34b99f968a6dbdd52619e812eb7d9a">LLVMOpInfo1::Value</a>, <a href="/web-llvm/docs/api/structs/llvmopinfosymbol1/#ada98ba08ab672b331d230197a788e625">LLVMOpInfoSymbol1::Value</a> and <a href="/web-llvm/docs/api/structs/llvmopinfo1/#ab73fd79b7db7a7c855f644fb952b519b">LLVMOpInfo1::VariantKind</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Hooks for symbolic disassembly via the public 'C' interface.



<p>The function to get the symbolic information for operands.</p>


### DisInfo {#a08e6d3c9e137726ed3c3729b61d8bed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::MCExternalSymbolizer::DisInfo</td>
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

<p>The pointer to the block of symbolic information for above call back.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcexternalsymbolizer-h">MCExternalSymbolizer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#a1d968b4e0193154acbbe41c3604f7f20">llvm::AArch64ExternalSymbolizer::AArch64ExternalSymbolizer</a>, <a href="#a33721a5176a9422407d47a78e6bbfe82">MCExternalSymbolizer</a>, <a href="#a932da00ce99b1018afdbc02579239ff1">tryAddingPcLoadReferenceComment</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a> and <a href="#aa4807aa3571299368e6d9b5c3d39893a">tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### GetOpInfo {#a2307af972a75c070da7242a59df69859}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOpInfoCallback llvm::MCExternalSymbolizer::GetOpInfo</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcexternalsymbolizer-h">MCExternalSymbolizer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#a1d968b4e0193154acbbe41c3604f7f20">llvm::AArch64ExternalSymbolizer::AArch64ExternalSymbolizer</a>, <a href="#a33721a5176a9422407d47a78e6bbfe82">MCExternalSymbolizer</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a> and <a href="#aa4807aa3571299368e6d9b5c3d39893a">tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### SymbolLookUp {#a43bb0a0aab29f9a9dbdee6a2e2d3264f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMSymbolLookupCallback llvm::MCExternalSymbolizer::SymbolLookUp</td>
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

<p>The function to lookup a symbol name.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcexternalsymbolizer-h">MCExternalSymbolizer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#a1d968b4e0193154acbbe41c3604f7f20">llvm::AArch64ExternalSymbolizer::AArch64ExternalSymbolizer</a>, <a href="#a33721a5176a9422407d47a78e6bbfe82">MCExternalSymbolizer</a>, <a href="#a932da00ce99b1018afdbc02579239ff1">tryAddingPcLoadReferenceComment</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a> and <a href="#aa4807aa3571299368e6d9b5c3d39893a">tryAddingSymbolicOperand</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/include/llvm/mc/mcdisassembler/mcexternalsymbolizer-h">MCExternalSymbolizer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/mcexternalsymbolizer-cpp">MCExternalSymbolizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
