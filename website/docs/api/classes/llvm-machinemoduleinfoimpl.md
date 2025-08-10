---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machinemoduleinfoimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MachineModuleInfoImpl` Class

<p>This class can be derived from and used by targets to hold private target-specific information for each <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MachineModuleInfoImpl { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">llvm/CodeGen/MachineModuleInfo.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfocoff">MachineModuleInfoCOFF</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfocoff">MachineModuleInfoCOFF</a> - This is a <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoimpl">MachineModuleInfoImpl</a> implementation for <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> targets. <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfocoff/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoelf">MachineModuleInfoELF</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoelf">MachineModuleInfoELF</a> - This is a <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoimpl">MachineModuleInfoImpl</a> implementation for <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> targets. <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoelf/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfomacho">MachineModuleInfoMachO</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfomacho">MachineModuleInfoMachO</a> - This is a <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoimpl">MachineModuleInfoImpl</a> implementation for <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> targets. <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfomacho/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfowasm">MachineModuleInfoWasm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfowasm">MachineModuleInfoWasm</a> - This is a <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoimpl">MachineModuleInfoImpl</a> implementation for Wasm targets. <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfowasm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b4a95f263fae5742d9d583d944d7fd4">StubValueTy</a> = <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, 1, bool &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57e28184abc0ddb8e29f94af5f8c2e4a">SymbolListTy</a> = std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="#a8b4a95f263fae5742d9d583d944d7fd4">StubValueTy</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82a66b348d2354ce0007ebf6c0eba921">ExprStubListTy</a> = std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A variant of <a href="#a57e28184abc0ddb8e29f94af5f8c2e4a">SymbolListTy</a> where the stub is a generalized <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a>. <a href="#a82a66b348d2354ce0007ebf6c0eba921">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab236c08575c15ccefd1f58024cf87428">~MachineModuleInfoImpl</a> ()</td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a57e28184abc0ddb8e29f94af5f8c2e4a">SymbolListTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a725119733e526e88fe5565c45bc0c574">getSortedStubs</a> (DenseMap&lt; MCSymbol *, StubValueTy &gt; &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the entries from a <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a> in a deterministic sorted orer. <a href="#a725119733e526e88fe5565c45bc0c574">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a82a66b348d2354ce0007ebf6c0eba921">ExprStubListTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0e82bea7f70af76a5beeb814d87a813">getSortedExprStubs</a> (DenseMap&lt; MCSymbol *, const MCExpr * &gt; &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the entries from a <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a> in a deterministic sorted orer. <a href="#ab0e82bea7f70af76a5beeb814d87a813">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class can be derived from and used by targets to hold private target-specific information for each <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>.</p>


<p>Objects of type are accessed/created with <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo/#a92d88d2c22a932066d294be13e2baf55">MachineModuleInfo::getObjFileInfo</a> and destroyed when the <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo">MachineModuleInfo</a> is destroyed.</p>


<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ExprStubListTy {#a82a66b348d2354ce0007ebf6c0eba921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineModuleInfoImpl::ExprStubListTy =  std::vector&lt;std::pair&lt;MCSymbol *, const MCExpr *&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A variant of <a href="#a57e28184abc0ddb8e29f94af5f8c2e4a">SymbolListTy</a> where the stub is a generalized <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a>.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>.</p>

</div>
</div>

### StubValueTy {#a8b4a95f263fae5742d9d583d944d7fd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineModuleInfoImpl::StubValueTy =  PointerIntPair&lt;MCSymbol *, 1, bool&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>.</p>

</div>
</div>

### SymbolListTy {#a57e28184abc0ddb8e29f94af5f8c2e4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineModuleInfoImpl::SymbolListTy =  std::vector&lt;std::pair&lt;MCSymbol *, StubValueTy&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MachineModuleInfoImpl() {#ab236c08575c15ccefd1f58024cf87428}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineModuleInfoImpl::~MachineModuleInfoImpl ()</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### getSortedExprStubs() {#ab0e82bea7f70af76a5beeb814d87a813}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineModuleInfoImpl::ExprStubListTy MachineModuleInfoImpl::getSortedExprStubs (<a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * &gt; &amp; ExprStubs)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the entries from a <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a> in a deterministic sorted orer.</p>


<p>Clears the map.</p>


<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>, definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleinfoimpls-cpp">MachineModuleInfoImpls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#add1eb5637dd671428b6f138ed3db6428">llvm::array_pod_sort</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a50d461a887e200e704e5157d3b21514d">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adf4e7878fc0b3b8dcde545178564190d">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleinfoimpls-cpp/#a899320212ec4d2892463ed4deb4514e6">SortAuthStubPair</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoelf/#a5622e004263323d592befe2eb1b07ed1">llvm::MachineModuleInfoELF::getAuthGVStubList</a> and <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfomacho/#a901a7b7802545df5e72e9a1c5cb7a645">llvm::MachineModuleInfoMachO::getAuthGVStubList</a>.</p>

</div>
</div>

### getSortedStubs() {#a725119733e526e88fe5565c45bc0c574}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineModuleInfoImpl::SymbolListTy MachineModuleInfoImpl::getSortedStubs (<a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="#a8b4a95f263fae5742d9d583d944d7fd4">StubValueTy</a> &gt; &amp; Map)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the entries from a <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a> in a deterministic sorted orer.</p>


<p>Clears the map.</p>


<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleinfoimpls-cpp">MachineModuleInfoImpls.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#add1eb5637dd671428b6f138ed3db6428">llvm::array_pod_sort</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleinfoimpls-cpp/#a16e7477f49dcf4a02d018c9b68d64700">SortSymbolPair</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfocoff/#a8bfda055bff9d32b40c30b25e463614e">llvm::MachineModuleInfoCOFF::GetGVStubList</a>, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoelf/#aaa4f94936a929359b14e0d70e6baaf90">llvm::MachineModuleInfoELF::GetGVStubList</a>, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfomacho/#a8f8e61da669121705fdca09643b8711b">llvm::MachineModuleInfoMachO::GetGVStubList</a> and <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfomacho/#a1ea4720388b47058057cd4d63359b060">llvm::MachineModuleInfoMachO::GetThreadLocalGVStubList</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">MachineModuleInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleinfoimpls-cpp">MachineModuleInfoImpls.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
