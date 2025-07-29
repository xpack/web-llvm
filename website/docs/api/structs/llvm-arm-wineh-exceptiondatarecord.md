---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/arm/wineh/exceptiondatarecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ExceptionDataRecord` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::ARM::WinEH::ExceptionDataRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">llvm/Support/ARMWinEH.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae11800e5d9f412809983f9c1b858416e">ExceptionDataRecord</a> (const support::ulittle32_t *Data, bool isAArch64)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77a6ae45ab4922d452d8d24b1d45f41d">FunctionLength</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac287729c52962d9600b114705e19324f">FunctionLengthInBytesARM</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23d38eba4adf8ffe9fe345775b7b8336">FunctionLengthInBytesAArch64</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19f0fe6836d58eb2ced7fbb51de75c61">Vers</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49311f42d61cd53273df87340355edb6">X</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f20f15ab24999f2e5ad420701116236">E</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aeafaf4e47772d209df8b5bb310d613">F</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae37170ac9b2a64d82b601622e6817737">EpilogueCount</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add11c2ad7367043eecc4aa89befa7903">CodeWords</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e8a8cac27eee7b6b082dd6af3c42846">EpilogueScopes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a024a668705032c00996b65aeaa0f6183">UnwindByteCode</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fe82d94f803c204e29f093949dd7bbf">ExceptionHandlerRVA</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab54645df04406348e514f5cd61f236da">ExceptionHandlerParameter</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4666cdfaaae2aabc3c84cf83a3a6838d">Data</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a233df223bb2d0c05a94506b1cd866e0a">isAArch64</a></td>
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


<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ExceptionDataRecord() {#ae11800e5d9f412809983f9c1b858416e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ARM::WinEH::ExceptionDataRecord::ExceptionDataRecord (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a> * Data, bool isAArch64)</td>
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



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="#a4666cdfaaae2aabc3c84cf83a3a6838d">Data</a> and <a href="#a233df223bb2d0c05a94506b1cd866e0a">isAArch64</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### CodeWords() {#add11c2ad7367043eecc4aa89befa7903}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::ARM::WinEH::ExceptionDataRecord::CodeWords ()</td>
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



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="#a4666cdfaaae2aabc3c84cf83a3a6838d">Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#aca4bf94569d7af05df6be821c0d19f00">llvm::ARM::WinEH::HeaderWords</a> and <a href="#a233df223bb2d0c05a94506b1cd866e0a">isAArch64</a>.</p>


<p>Referenced by <a href="#ab54645df04406348e514f5cd61f236da">ExceptionHandlerParameter</a>, <a href="#a2fe82d94f803c204e29f093949dd7bbf">ExceptionHandlerRVA</a> and <a href="#a024a668705032c00996b65aeaa0f6183">UnwindByteCode</a>.</p>

</div>
</div>

### E() {#a0f20f15ab24999f2e5ad420701116236}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARM::WinEH::ExceptionDataRecord::E ()</td>
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



<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>Reference <a href="#a4666cdfaaae2aabc3c84cf83a3a6838d">Data</a>.</p>


<p>Referenced by <a href="#a9e8a8cac27eee7b6b082dd6af3c42846">EpilogueScopes</a>, <a href="#ab54645df04406348e514f5cd61f236da">ExceptionHandlerParameter</a>, <a href="#a2fe82d94f803c204e29f093949dd7bbf">ExceptionHandlerRVA</a> and <a href="#a024a668705032c00996b65aeaa0f6183">UnwindByteCode</a>.</p>

</div>
</div>

### EpilogueCount() {#ae37170ac9b2a64d82b601622e6817737}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::ARM::WinEH::ExceptionDataRecord::EpilogueCount ()</td>
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



<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="#a4666cdfaaae2aabc3c84cf83a3a6838d">Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#aca4bf94569d7af05df6be821c0d19f00">llvm::ARM::WinEH::HeaderWords</a> and <a href="#a233df223bb2d0c05a94506b1cd866e0a">isAArch64</a>.</p>


<p>Referenced by <a href="#a9e8a8cac27eee7b6b082dd6af3c42846">EpilogueScopes</a>, <a href="#ab54645df04406348e514f5cd61f236da">ExceptionHandlerParameter</a>, <a href="#a2fe82d94f803c204e29f093949dd7bbf">ExceptionHandlerRVA</a> and <a href="#a024a668705032c00996b65aeaa0f6183">UnwindByteCode</a>.</p>

</div>
</div>

### EpilogueScopes() {#a9e8a8cac27eee7b6b082dd6af3c42846}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; support::ulittle32_t &gt; llvm::ARM::WinEH::ExceptionDataRecord::EpilogueScopes ()</td>
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



<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4666cdfaaae2aabc3c84cf83a3a6838d">Data</a>, <a href="#a0f20f15ab24999f2e5ad420701116236">E</a>, <a href="#ae37170ac9b2a64d82b601622e6817737">EpilogueCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#aca4bf94569d7af05df6be821c0d19f00">llvm::ARM::WinEH::HeaderWords</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### ExceptionHandlerParameter() {#ab54645df04406348e514f5cd61f236da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ARM::WinEH::ExceptionDataRecord::ExceptionHandlerParameter ()</td>
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



<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#add11c2ad7367043eecc4aa89befa7903">CodeWords</a>, <a href="#a4666cdfaaae2aabc3c84cf83a3a6838d">Data</a>, <a href="#a0f20f15ab24999f2e5ad420701116236">E</a>, <a href="#ae37170ac9b2a64d82b601622e6817737">EpilogueCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#aca4bf94569d7af05df6be821c0d19f00">llvm::ARM::WinEH::HeaderWords</a> and <a href="#a49311f42d61cd53273df87340355edb6">X</a>.</p>

</div>
</div>

### ExceptionHandlerRVA() {#a2fe82d94f803c204e29f093949dd7bbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ARM::WinEH::ExceptionDataRecord::ExceptionHandlerRVA ()</td>
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



<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#add11c2ad7367043eecc4aa89befa7903">CodeWords</a>, <a href="#a4666cdfaaae2aabc3c84cf83a3a6838d">Data</a>, <a href="#a0f20f15ab24999f2e5ad420701116236">E</a>, <a href="#ae37170ac9b2a64d82b601622e6817737">EpilogueCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#aca4bf94569d7af05df6be821c0d19f00">llvm::ARM::WinEH::HeaderWords</a> and <a href="#a49311f42d61cd53273df87340355edb6">X</a>.</p>

</div>
</div>

### F() {#a2aeafaf4e47772d209df8b5bb310d613}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARM::WinEH::ExceptionDataRecord::F ()</td>
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



<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4666cdfaaae2aabc3c84cf83a3a6838d">Data</a> and <a href="#a233df223bb2d0c05a94506b1cd866e0a">isAArch64</a>.</p>

</div>
</div>

### FunctionLength() {#a77a6ae45ab4922d452d8d24b1d45f41d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ARM::WinEH::ExceptionDataRecord::FunctionLength ()</td>
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



<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>Reference <a href="#a4666cdfaaae2aabc3c84cf83a3a6838d">Data</a>.</p>


<p>Referenced by <a href="#a23d38eba4adf8ffe9fe345775b7b8336">FunctionLengthInBytesAArch64</a> and <a href="#ac287729c52962d9600b114705e19324f">FunctionLengthInBytesARM</a>.</p>

</div>
</div>

### FunctionLengthInBytesAArch64() {#a23d38eba4adf8ffe9fe345775b7b8336}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ARM::WinEH::ExceptionDataRecord::FunctionLengthInBytesAArch64 ()</td>
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



<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>Reference <a href="#a77a6ae45ab4922d452d8d24b1d45f41d">FunctionLength</a>.</p>

</div>
</div>

### FunctionLengthInBytesARM() {#ac287729c52962d9600b114705e19324f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ARM::WinEH::ExceptionDataRecord::FunctionLengthInBytesARM ()</td>
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



<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>Reference <a href="#a77a6ae45ab4922d452d8d24b1d45f41d">FunctionLength</a>.</p>

</div>
</div>

### UnwindByteCode() {#a024a668705032c00996b65aeaa0f6183}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uint8_t &gt; llvm::ARM::WinEH::ExceptionDataRecord::UnwindByteCode ()</td>
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



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="#add11c2ad7367043eecc4aa89befa7903">CodeWords</a>, <a href="#a4666cdfaaae2aabc3c84cf83a3a6838d">Data</a>, <a href="#a0f20f15ab24999f2e5ad420701116236">E</a>, <a href="#ae37170ac9b2a64d82b601622e6817737">EpilogueCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#aca4bf94569d7af05df6be821c0d19f00">llvm::ARM::WinEH::HeaderWords</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### Vers() {#a19f0fe6836d58eb2ced7fbb51de75c61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::ARM::WinEH::ExceptionDataRecord::Vers ()</td>
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



<p>Definition at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>Reference <a href="#a4666cdfaaae2aabc3c84cf83a3a6838d">Data</a>.</p>

</div>
</div>

### X() {#a49311f42d61cd53273df87340355edb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARM::WinEH::ExceptionDataRecord::X ()</td>
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



<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>Reference <a href="#a4666cdfaaae2aabc3c84cf83a3a6838d">Data</a>.</p>


<p>Referenced by <a href="#ab54645df04406348e514f5cd61f236da">ExceptionHandlerParameter</a> and <a href="#a2fe82d94f803c204e29f093949dd7bbf">ExceptionHandlerRVA</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Data {#a4666cdfaaae2aabc3c84cf83a3a6838d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const support::ulittle32_t* llvm::ARM::WinEH::ExceptionDataRecord::Data</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>Referenced by <a href="#add11c2ad7367043eecc4aa89befa7903">CodeWords</a>, <a href="#a0f20f15ab24999f2e5ad420701116236">E</a>, <a href="#ae37170ac9b2a64d82b601622e6817737">EpilogueCount</a>, <a href="#a9e8a8cac27eee7b6b082dd6af3c42846">EpilogueScopes</a>, <a href="#ae11800e5d9f412809983f9c1b858416e">ExceptionDataRecord</a>, <a href="#ab54645df04406348e514f5cd61f236da">ExceptionHandlerParameter</a>, <a href="#a2fe82d94f803c204e29f093949dd7bbf">ExceptionHandlerRVA</a>, <a href="#a2aeafaf4e47772d209df8b5bb310d613">F</a>, <a href="#a77a6ae45ab4922d452d8d24b1d45f41d">FunctionLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#aca4bf94569d7af05df6be821c0d19f00">llvm::ARM::WinEH::HeaderWords</a>, <a href="#a024a668705032c00996b65aeaa0f6183">UnwindByteCode</a>, <a href="#a19f0fe6836d58eb2ced7fbb51de75c61">Vers</a> and <a href="#a49311f42d61cd53273df87340355edb6">X</a>.</p>

</div>
</div>

### isAArch64 {#a233df223bb2d0c05a94506b1cd866e0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARM::WinEH::ExceptionDataRecord::isAArch64</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>Referenced by <a href="#add11c2ad7367043eecc4aa89befa7903">CodeWords</a>, <a href="#ae37170ac9b2a64d82b601622e6817737">EpilogueCount</a>, <a href="#ae11800e5d9f412809983f9c1b858416e">ExceptionDataRecord</a>, <a href="#a2aeafaf4e47772d209df8b5bb310d613">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#aca4bf94569d7af05df6be821c0d19f00">llvm::ARM::WinEH::HeaderWords</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
