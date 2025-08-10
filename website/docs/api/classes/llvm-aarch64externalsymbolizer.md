---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/aarch64externalsymbolizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AArch64ExternalSymbolizer` Class



## Declaration

<div class="doxyDeclaration">
class llvm::AArch64ExternalSymbolizer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64externalsymbolizer-h">Target/AArch64/Disassembler/AArch64ExternalSymbolizer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d968b4e0193154acbbe41c3604f7f20">AArch64ExternalSymbolizer</a> (MCContext &amp;Ctx, std::unique_ptr&lt; MCRelocationInfo &gt; RelInfo, LLVMOpInfoCallback GetOpInfo, LLVMSymbolLookupCallback SymbolLookUp, void *DisInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadc518cf2b179163c8eca58f17e333b2">tryAddingSymbolicOperand</a> (MCInst &amp;MI, raw_ostream &amp;CommentStream, int64_t Value, uint64_t Address, bool IsBranch, uint64_t Offset, uint64_t OpSize, uint64_t InstSize) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>tryAddingSymbolicOperand - tryAddingSymbolicOperand trys to add a symbolic operand in place of the immediate <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> in the <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>. <a href="#aadc518cf2b179163c8eca58f17e333b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64externalsymbolizer-h">AArch64ExternalSymbolizer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AArch64ExternalSymbolizer() {#a1d968b4e0193154acbbe41c3604f7f20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AArch64ExternalSymbolizer::AArch64ExternalSymbolizer (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo">MCRelocationInfo</a> &gt; RelInfo, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gaa8eb7ea1e53fd6e7a11b6aa4749c6e60">LLVMOpInfoCallback</a> GetOpInfo, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga05ffa603beb390898904a06b14ee5537">LLVMSymbolLookupCallback</a> SymbolLookUp, void * DisInfo)</td>
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



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64externalsymbolizer-h">AArch64ExternalSymbolizer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer/#ae7ae949c9f9c53c3e6e8c29799753c01">llvm::MCSymbolizer::Ctx</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#a08e6d3c9e137726ed3c3729b61d8bed0">llvm::MCExternalSymbolizer::DisInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#a2307af972a75c070da7242a59df69859">llvm::MCExternalSymbolizer::GetOpInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#a33721a5176a9422407d47a78e6bbfe82">llvm::MCExternalSymbolizer::MCExternalSymbolizer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer/#a65399cf3fad4593f48477a0962ddd074">llvm::MCSymbolizer::RelInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#a43bb0a0aab29f9a9dbdee6a2e2d3264f">llvm::MCExternalSymbolizer::SymbolLookUp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### tryAddingSymbolicOperand() {#aadc518cf2b179163c8eca58f17e333b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64ExternalSymbolizer::tryAddingSymbolicOperand (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; CommentStream, int64_t Value, uint64_t Address, bool IsBranch, uint64_t Offset, uint64_t OpSize, uint64_t InstSize)</td>
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

<p>tryAddingSymbolicOperand - tryAddingSymbolicOperand trys to add a symbolic operand in place of the immediate <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> in the <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>.</p>


<p>The immediate <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> has not had any PC adjustment made by the caller. If the instruction is a branch that adds the PC to the immediate <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> then isBranch is Success, else Fail. If GetOpInfo is non-null, then it is called to get any symbolic information at the Address for this instrution. If that returns non-zero then the symbolic information it returns is used to create an <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> and that is added as an operand to the <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>. If <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#a2307af972a75c070da7242a59df69859">GetOpInfo()</a> returns zero and isBranch is Success then a symbol look up for Address + <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is done and if a symbol is found an <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> is created with that, else an <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> with Address + <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is created. If <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#a2307af972a75c070da7242a59df69859">GetOpInfo()</a> returns zero and isBranch is Fail then the Opcode of the <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> is tested and for ADRP an other instructions that help to load of pointers a symbol look up is done to see it is returns a specific reference type to add to the comment stream. This function returns Success if it adds an operand to the <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> and Fail otherwise.</p>


<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64externalsymbolizer-h">AArch64ExternalSymbolizer.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64externalsymbolizer-cpp">AArch64ExternalSymbolizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/structs/llvmopinfo1/#a5ac48adba22aa66db9bed16f0d492705">LLVMOpInfo1::AddSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#a3cbe1086ebf00680e8dc374e07305cfb">llvm::MCBinaryExpr::createAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcunaryexpr/#aff718d95a5738283e9049bc93fa9abe2">llvm::MCUnaryExpr::createMinus</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer/#ae7ae949c9f9c53c3e6e8c29799753c01">llvm::MCSymbolizer::Ctx</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#a08e6d3c9e137726ed3c3729b61d8bed0">llvm::MCExternalSymbolizer::DisInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo/#a88977138a65e44f5f302342e4a00b501">llvm::MCRegisterInfo::getEncodingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#a2307af972a75c070da7242a59df69859">llvm::MCExternalSymbolizer::GetOpInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64externalsymbolizer-cpp/#a514d7e297481327255217939292ae114">getVariant</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga3e62ce52a54791ea0b2098eb8adc840f">LLVMDisassembler_ReferenceType_In_ARM64_ADDXri</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga1141f7abd5221b48b97c927b57234e33">LLVMDisassembler_ReferenceType_In_ARM64_ADR</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga73395d6a90fefa202ec94dd103440106">LLVMDisassembler_ReferenceType_In_ARM64_ADRP</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gad81c0ae2e8ee538e833bb6e6c2ac0676">LLVMDisassembler_ReferenceType_In_ARM64_LDRXl</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gaf7375fccf8efe1277a941cb3cff28966">LLVMDisassembler_ReferenceType_In_ARM64_LDRXui</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga82fca9d886616e829b203276c80afabf">LLVMDisassembler_ReferenceType_In_Branch</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga81e5011868131b85e2fe428b5de9165b">LLVMDisassembler_ReferenceType_Out_LitPool_CstrAddr</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga9ddf8b97918a69a6a513225d2f26c91f">LLVMDisassembler_ReferenceType_Out_LitPool_SymAddr</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga4e7df42625f59e6870f6aaa04fd8e112">LLVMDisassembler_ReferenceType_Out_Objc_CFString_Ref</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga32181431bb3d71b1218b596eb3252b3f">LLVMDisassembler_ReferenceType_Out_Objc_Class_Ref</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gaa07c4db36282f91d8f9da2f1c74ffc4c">LLVMDisassembler_ReferenceType_Out_Objc_Message</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gaceddd31c06c7ca91bb4747dd008a7bfb">LLVMDisassembler_ReferenceType_Out_Objc_Message_Ref</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gab234f9f0c243edf081dcbee6400c320a">LLVMDisassembler_ReferenceType_Out_Objc_Selector_Ref</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga43cc63fe7d58d8379d06b31cf92d620b">LLVMDisassembler_ReferenceType_Out_SymbolStub</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/llvmopinfosymbol1/#a60a11f3a829fd9bbeb3071bf372bcef0">LLVMOpInfoSymbol1::Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/structs/llvmopinfosymbol1/#a03a90bff1e766901579a900fd4f870a1">LLVMOpInfoSymbol1::Present</a>, <a href="/web-llvm/docs/api/structs/llvmopinfo1/#a5a683606e957f62746726cab5935d165">LLVMOpInfo1::SubtractSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#a43bb0a0aab29f9a9dbdee6a2e2d3264f">llvm::MCExternalSymbolizer::SymbolLookUp</a>, <a href="/web-llvm/docs/api/structs/llvmopinfo1/#ada34b99f968a6dbdd52619e812eb7d9a">LLVMOpInfo1::Value</a>, <a href="/web-llvm/docs/api/structs/llvmopinfosymbol1/#ada98ba08ab672b331d230197a788e625">LLVMOpInfoSymbol1::Value</a>, <a href="/web-llvm/docs/api/structs/llvmopinfo1/#ab73fd79b7db7a7c855f644fb952b519b">LLVMOpInfo1::VariantKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a5ba2ece4b959bae02752c34b784ba087">llvm::raw_ostream::write_escaped</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64externalsymbolizer-cpp">AArch64ExternalSymbolizer.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64externalsymbolizer-h">AArch64ExternalSymbolizer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
