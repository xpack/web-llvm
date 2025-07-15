---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machinemoduleinfoelf
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MachineModuleInfoELF` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoelf">MachineModuleInfoELF</a> - This is a <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoimpl">MachineModuleInfoImpl</a> implementation for <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> targets. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MachineModuleInfoELF { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfoimpls-h">llvm/CodeGen/MachineModuleInfoImpls.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoimpl">MachineModuleInfoImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class can be derived from and used by targets to hold private target-specific information for each <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>. <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoimpl/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpumachinemoduleinfo">AMDGPUMachineModuleInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10fcc9cad3c4fe08af16f7ca8c14110d">MachineModuleInfoELF</a> (const MachineModuleInfo &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoimpl/#a8b4a95f263fae5742d9d583d944d7fd4">StubValueTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b1fd7fefb6e992c5b7097eb82d87142">getGVStubEntry</a> (MCSymbol *Sym)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27791becbf2d4443838db00f370df0a4">getAuthPtrStubEntry</a> (MCSymbol *Sym)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoimpl/#a57e28184abc0ddb8e29f94af5f8c2e4a">SymbolListTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa4f94936a929359b14e0d70e6baaf90">GetGVStubList</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Accessor methods to return the set of stubs in sorted order. <a href="#aaa4f94936a929359b14e0d70e6baaf90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoimpl/#a82a66b348d2354ce0007ebf6c0eba921">ExprStubListTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5622e004263323d592befe2eb1b07ed1">getAuthGVStubList</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ed90bfbfc1ad64f7fce9458287b79cc">hasSignedPersonality</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa565a171330c72f26e511b731476f18d">anchor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoimpl/#a8b4a95f263fae5742d9d583d944d7fd4">StubValueTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a104b9fa8d00ecc287fca5c34c2128ec2">GVStubs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GVStubs - These stubs are used to materialize global addresses in PIC mode. <a href="#a104b9fa8d00ecc287fca5c34c2128ec2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb8dd4be2c1735bed8899746a58b5b03">AuthPtrStubs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AuthPtrStubs - These stubs are used to materialize signed addresses for extern_weak symbols. <a href="#abb8dd4be2c1735bed8899746a58b5b03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5fa1246db10a13b975f92cda0b328a3">HasSignedPersonality</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HasSignedPersonality is true if the corresponding IR module has the "ptrauth-sign-personality" flag set to 1. <a href="#ad5fa1246db10a13b975f92cda0b328a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoelf">MachineModuleInfoELF</a> - This is a <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoimpl">MachineModuleInfoImpl</a> implementation for <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> targets.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfoimpls-h">MachineModuleInfoImpls.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MachineModuleInfoELF() {#a10fcc9cad3c4fe08af16f7ca8c14110d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineModuleInfoELF::MachineModuleInfoELF (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> &amp; MMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfoimpls-h">MachineModuleInfoImpls.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleinfoimpls-cpp">MachineModuleInfoImpls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#a86397deb1d9d25f7a17ce22c4d66482f">llvm::mdconst::extract_or_null</a> and <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo/#a6a05f73ad80e58a532ea879ccc166b66">llvm::MachineModuleInfo::getModule</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpumachinemoduleinfo/#ae8cd76b599873138cddf10f91e7bcad0">llvm::AMDGPUMachineModuleInfo::AMDGPUMachineModuleInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAuthGVStubList() {#a5622e004263323d592befe2eb1b07ed1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExprStubListTy llvm::MachineModuleInfoELF::getAuthGVStubList ()</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfoimpls-h">MachineModuleInfoImpls.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoimpl/#ab0e82bea7f70af76a5beeb814d87a813">llvm::MachineModuleInfoImpl::getSortedExprStubs</a>.</p>

</div>
</div>

### getAuthPtrStubEntry() {#a27791becbf2d4443838db00f370df0a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr *&amp; llvm::MachineModuleInfoELF::getAuthPtrStubEntry (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfoimpls-h">MachineModuleInfoImpls.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getGVStubEntry() {#a9b1fd7fefb6e992c5b7097eb82d87142}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StubValueTy &amp; llvm::MachineModuleInfoELF::getGVStubEntry (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym)</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfoimpls-h">MachineModuleInfoImpls.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sparcelftargetobjectfile/#a953050dfdd0d33bc59eb08438aa5d88c">llvm::SparcELFTargetObjectFile::getTTypeGlobalReference</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a726934c33655de3d8c59b38d0e946a62">llvm::TargetLoweringObjectFileELF::getTTypeGlobalReference</a>.</p>

</div>
</div>

### GetGVStubList() {#aaa4f94936a929359b14e0d70e6baaf90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolListTy llvm::MachineModuleInfoELF::GetGVStubList ()</td>
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

<p>Accessor methods to return the set of stubs in sorted order.</p>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfoimpls-h">MachineModuleInfoImpls.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoimpl/#a725119733e526e88fe5565c45bc0c574">llvm::MachineModuleInfoImpl::getSortedStubs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa9a2aed0d26a4fca41f8fc0986a3f12b">llvm::AsmPrinter::doFinalization</a>.</p>

</div>
</div>

### hasSignedPersonality() {#a8ed90bfbfc1ad64f7fce9458287b79cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineModuleInfoELF::hasSignedPersonality ()</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfoimpls-h">MachineModuleInfoImpls.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64-elftargetobjectfile/#a50239bad1326b962fc58f1b311e7e255">llvm::AArch64_ELFTargetObjectFile::emitPersonalityValueImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#aa565a171330c72f26e511b731476f18d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineModuleInfoELF::anchor ()</td>
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



<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfoimpls-h">MachineModuleInfoImpls.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleinfoimpls-cpp">MachineModuleInfoImpls.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AuthPtrStubs {#abb8dd4be2c1735bed8899746a58b5b03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MCSymbol *, const MCExpr *&gt; llvm::MachineModuleInfoELF::AuthPtrStubs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AuthPtrStubs - These stubs are used to materialize signed addresses for extern_weak symbols.</p>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfoimpls-h">MachineModuleInfoImpls.h</a>.</p>

</div>
</div>

### GVStubs {#a104b9fa8d00ecc287fca5c34c2128ec2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MCSymbol *, StubValueTy&gt; llvm::MachineModuleInfoELF::GVStubs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GVStubs - These stubs are used to materialize global addresses in PIC mode.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfoimpls-h">MachineModuleInfoImpls.h</a>.</p>

</div>
</div>

### HasSignedPersonality {#ad5fa1246db10a13b975f92cda0b328a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineModuleInfoELF::HasSignedPersonality = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>HasSignedPersonality is true if the corresponding IR module has the "ptrauth-sign-personality" flag set to 1.</p>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfoimpls-h">MachineModuleInfoImpls.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfoimpls-h">MachineModuleInfoImpls.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleinfoimpls-cpp">MachineModuleInfoImpls.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
