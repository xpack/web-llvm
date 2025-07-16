---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/llvmcdisassembler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The Disassembler Reference



## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvmopinfosymbol1">LLVMOpInfoSymbol1</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The initial support in LLVM MC for the most general form of a relocatable expression is "AddSymbol - SubtractSymbol + Offset". <a href="/web-llvm/docs/api/structs/llvmopinfosymbol1/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvmopinfo1">LLVMOpInfo1</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">void * <a href="#gae903996143e88ff186c738f81122094e">LLVMDisasmContextRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An opaque reference to a disassembler context. <a href="#gae903996143e88ff186c738f81122094e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">int(* <a href="#gaa8eb7ea1e53fd6e7a11b6aa4749c6e60">LLVMOpInfoCallback</a>)(void *DisInfo, uint64_t PC, uint64_t Offset, uint64_t OpSize, uint64_t InstSize, int TagType, void *TagBuf)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type for the operand information call back function. <a href="#gaa8eb7ea1e53fd6e7a11b6aa4749c6e60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *(* <a href="#ga05ffa603beb390898904a06b14ee5537">LLVMSymbolLookupCallback</a>)(void *DisInfo, uint64_t ReferenceValue, uint64_t *ReferenceType, uint64_t ReferencePC, const char **ReferenceName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type for the symbol lookup function. <a href="#ga05ffa603beb390898904a06b14ee5537">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm-c/externc-h/#a4789aaabaa5bf3b7a549171b47cc4d4a">LLVM_C_EXTERN_C_BEGIN</a> <a href="#gae903996143e88ff186c738f81122094e">LLVMDisasmContextRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab2235be6ece819e49dbde7cd52c3a2d8">LLVMCreateDisasm</a> (const char *TripleName, void *DisInfo, int TagType, LLVMOpInfoCallback GetOpInfo, LLVMSymbolLookupCallback SymbolLookUp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a disassembler for the TripleName. <a href="#gab2235be6ece819e49dbde7cd52c3a2d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#gae903996143e88ff186c738f81122094e">LLVMDisasmContextRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga906d56cff22d17c94cae0c91fa36f6e2">LLVMCreateDisasmCPU</a> (const char *Triple, const char *CPU, void *DisInfo, int TagType, LLVMOpInfoCallback GetOpInfo, LLVMSymbolLookupCallback SymbolLookUp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a disassembler for the TripleName and a specific CPU. <a href="#ga906d56cff22d17c94cae0c91fa36f6e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#gae903996143e88ff186c738f81122094e">LLVMDisasmContextRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga0ed319f9f853493c0b38e551ec2adfc5">LLVMCreateDisasmCPUFeatures</a> (const char *Triple, const char *CPU, const char *Features, void *DisInfo, int TagType, LLVMOpInfoCallback GetOpInfo, LLVMSymbolLookupCallback SymbolLookUp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a disassembler for the TripleName, a specific CPU and specific feature string. <a href="#ga0ed319f9f853493c0b38e551ec2adfc5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gad1cbbd5aa7b51f04687926e8f9e4aebb">LLVMSetDisasmOptions</a> (LLVMDisasmContextRef DC, uint64_t Options)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the disassembler's options. <a href="#gad1cbbd5aa7b51f04687926e8f9e4aebb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga15b630b4a386bee86ad5a10ff7592af0">LLVMDisasmDispose</a> (LLVMDisasmContextRef DC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dispose of a disassembler context. <a href="#ga15b630b4a386bee86ad5a10ff7592af0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4ab4dad1fdcb9e651fa60f6059ab09b4">LLVMDisasmInstruction</a> (LLVMDisasmContextRef DC, uint8_t *Bytes, uint64_t BytesSize, uint64_t PC, char *OutString, size_t OutStringSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disassemble a single instruction using the disassembler context specified in the parameter DC. <a href="#ga4ab4dad1fdcb9e651fa60f6059ab09b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga2e77b3aa2a7502be2350e34cfdbbe957">LLVMDisassembler_Option_UseMarkup</a>&nbsp;&nbsp;&nbsp;1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga17abcf26af53ca0ef4d8902e9abdfbdf">LLVMDisassembler_Option_PrintImmHex</a>&nbsp;&nbsp;&nbsp;2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gae0ce9f25acf18f03656aebcd8b99f807">LLVMDisassembler_Option_AsmPrinterVariant</a>&nbsp;&nbsp;&nbsp;4</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga7da58a469e24dca8c6cd1b644f57e5d7">LLVMDisassembler_Option_SetInstrComments</a>&nbsp;&nbsp;&nbsp;8</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga51495370fd44cea5cb0c7696139457d9">LLVMDisassembler_Option_PrintLatency</a>&nbsp;&nbsp;&nbsp;16</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaa21f8b4663cd086facd275f6286138e3">LLVMDisassembler_Option_Color</a>&nbsp;&nbsp;&nbsp;32</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaeb7b3311097fd803536f89c1fd8a5f15">LLVMDisassembler_VariantKind_None</a>&nbsp;&nbsp;&nbsp;0 /* all targets */</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The operand VariantKinds for symbolic disassembly. <a href="#gaeb7b3311097fd803536f89c1fd8a5f15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga18c0e1aa1f200a0154c9301841a4d7ba">LLVMDisassembler_VariantKind_ARM_HI16</a>&nbsp;&nbsp;&nbsp;1 /* :upper16: */</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The ARM target VariantKinds. <a href="#ga18c0e1aa1f200a0154c9301841a4d7ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga518d82ae8838203f9aa0f8566a5ca51c">LLVMDisassembler_VariantKind_ARM_LO16</a>&nbsp;&nbsp;&nbsp;2 /* :lower16: */</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaac17762c72a25f63faf21df57e16176e">LLVMDisassembler_VariantKind_ARM64_PAGE</a>&nbsp;&nbsp;&nbsp;1 /* @page */</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The ARM64 target VariantKinds. <a href="#gaac17762c72a25f63faf21df57e16176e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gacd4b54131faf848e92ea232693077151">LLVMDisassembler_VariantKind_ARM64_PAGEOFF</a>&nbsp;&nbsp;&nbsp;2 /* @pageoff */</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gad25fcaca7790acb9f3678686219daecc">LLVMDisassembler_VariantKind_ARM64_GOTPAGE</a>&nbsp;&nbsp;&nbsp;3 /* @gotpage */</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga1babeeed365fdc3d716a52ebf3d5b315">LLVMDisassembler_VariantKind_ARM64_GOTPAGEOFF</a>&nbsp;&nbsp;&nbsp;4 /* @gotpageoff */</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga34ffa9d914aa8d4d7f0c70f409ff0d2f">LLVMDisassembler_VariantKind_ARM64_TLVP</a>&nbsp;&nbsp;&nbsp;5 /* @tvlppage */</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga0c26f64bd2eaca9d9d4c21e14ea93f93">LLVMDisassembler_VariantKind_ARM64_TLVOFF</a>&nbsp;&nbsp;&nbsp;6 /* @tvlppageoff */</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaa6b926b61f2d59191c806d31bb94c894">LLVMDisassembler_ReferenceType_InOut_None</a>&nbsp;&nbsp;&nbsp;0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The reference types on input and output. <a href="#gaa6b926b61f2d59191c806d31bb94c894">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga82fca9d886616e829b203276c80afabf">LLVMDisassembler_ReferenceType_In_Branch</a>&nbsp;&nbsp;&nbsp;1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4d14397b83038d9f432101b60d28afcd">LLVMDisassembler_ReferenceType_In_PCrel_Load</a>&nbsp;&nbsp;&nbsp;2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga73395d6a90fefa202ec94dd103440106">LLVMDisassembler_ReferenceType_In_ARM64_ADRP</a>&nbsp;&nbsp;&nbsp;4294967297</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga3e62ce52a54791ea0b2098eb8adc840f">LLVMDisassembler_ReferenceType_In_ARM64_ADDXri</a>&nbsp;&nbsp;&nbsp;4294967298</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf7375fccf8efe1277a941cb3cff28966">LLVMDisassembler_ReferenceType_In_ARM64_LDRXui</a>&nbsp;&nbsp;&nbsp;4294967299</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gad81c0ae2e8ee538e833bb6e6c2ac0676">LLVMDisassembler_ReferenceType_In_ARM64_LDRXl</a>&nbsp;&nbsp;&nbsp;4294967300</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga1141f7abd5221b48b97c927b57234e33">LLVMDisassembler_ReferenceType_In_ARM64_ADR</a>&nbsp;&nbsp;&nbsp;4294967301</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga43cc63fe7d58d8379d06b31cf92d620b">LLVMDisassembler_ReferenceType_Out_SymbolStub</a>&nbsp;&nbsp;&nbsp;1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga9ddf8b97918a69a6a513225d2f26c91f">LLVMDisassembler_ReferenceType_Out_LitPool_SymAddr</a>&nbsp;&nbsp;&nbsp;2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga81e5011868131b85e2fe428b5de9165b">LLVMDisassembler_ReferenceType_Out_LitPool_CstrAddr</a>&nbsp;&nbsp;&nbsp;3</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4e7df42625f59e6870f6aaa04fd8e112">LLVMDisassembler_ReferenceType_Out_Objc_CFString_Ref</a>&nbsp;&nbsp;&nbsp;4</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaa07c4db36282f91d8f9da2f1c74ffc4c">LLVMDisassembler_ReferenceType_Out_Objc_Message</a>&nbsp;&nbsp;&nbsp;5</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaceddd31c06c7ca91bb4747dd008a7bfb">LLVMDisassembler_ReferenceType_Out_Objc_Message_Ref</a>&nbsp;&nbsp;&nbsp;6</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab234f9f0c243edf081dcbee6400c320a">LLVMDisassembler_ReferenceType_Out_Objc_Selector_Ref</a>&nbsp;&nbsp;&nbsp;7</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga32181431bb3d71b1218b596eb3252b3f">LLVMDisassembler_ReferenceType_Out_Objc_Class_Ref</a>&nbsp;&nbsp;&nbsp;8</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gae11bd2845e00fc1aed8223da0793bf4b">LLVMDisassembler_ReferenceType_DeMangled_Name</a>&nbsp;&nbsp;&nbsp;9</td>
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


<div class="doxySectionDef">

## Typedefs

### LLVMDisasmContextRef {#gae903996143e88ff186c738f81122094e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef void* LLVMDisasmContextRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An opaque reference to a disassembler context.</p>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>

</div>
</div>

### LLVMOpInfoCallback {#gaa8eb7ea1e53fd6e7a11b6aa4749c6e60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef int(* LLVMOpInfoCallback) (void *DisInfo, uint64_t PC, uint64_t Offset, uint64_t OpSize, uint64_t InstSize, int TagType, void *TagBuf)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type for the operand information call back function.</p>


<p>This is called to get the symbolic information for an operand of an instruction. Typically this is from the relocation information, symbol table, etc. That block of information is saved when the disassembler context is created and passed to the call back in the DisInfo parameter. The instruction containing operand is at the PC parameter. For some instruction sets, there can be more than one operand with symbolic information. To determine the symbolic operand information for each operand, the bytes for the specific operand in the instruction are specified by the Offset parameter and its byte widith is the OpSize parameter. For instructions sets with fixed widths and one symbolic operand per instruction, the Offset parameter will be zero and InstSize parameter will be the instruction width. The information is returned in TagBuf and is Triple specific with its specific information defined by the value of TagType for that Triple. If symbolic information is returned the function * returns 1, otherwise it returns 0.</p>


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>

</div>
</div>

### LLVMSymbolLookupCallback {#ga05ffa603beb390898904a06b14ee5537}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef const char *(* LLVMSymbolLookupCallback) (void *DisInfo, uint64_t ReferenceValue, uint64_t *ReferenceType, uint64_t ReferencePC, const char **ReferenceName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type for the symbol lookup function.</p>


<p>This may be called by the disassembler for things like adding a comment for a PC plus a constant offset load instruction to use a symbol name instead of a load address value. It is passed the block information is saved when the disassembler context is created and the ReferenceValue to look up as a symbol. If no symbol is found for the ReferenceValue NULL is returned. The <a href="/web-llvm/docs/api/classes/referencetype">ReferenceType</a> of the instruction is passed indirectly as is the PC of the instruction in ReferencePC. If the output reference can be determined its type is returned indirectly in <a href="/web-llvm/docs/api/classes/referencetype">ReferenceType</a> along with ReferenceName if any, or that is set to NULL.</p>


<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### LLVMCreateDisasm() {#gab2235be6ece819e49dbde7cd52c3a2d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_C_EXTERN_C_BEGIN LLVMDisasmContextRef LLVMCreateDisasm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * TripleName, void * DisInfo, int TagType, <a href="#gaa8eb7ea1e53fd6e7a11b6aa4749c6e60">LLVMOpInfoCallback</a> GetOpInfo, <a href="#ga05ffa603beb390898904a06b14ee5537">LLVMSymbolLookupCallback</a> SymbolLookUp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a disassembler for the TripleName.</p>


<p>Symbolic disassembly is supported by passing a block of information in the DisInfo parameter and specifying the TagType and callback functions as described above. These can all be passed as NULL. If successful, this returns a disassembler context. If not, it returns NULL. This function is equivalent to calling <a href="#ga0ed319f9f853493c0b38e551ec2adfc5">LLVMCreateDisasmCPUFeatures()</a> with an empty CPU name and feature set.</p>


<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassembler-h">Disassembler.h</a>, definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-cpp">Disassembler.cpp</a>.</p>


<p>Reference <a href="#ga0ed319f9f853493c0b38e551ec2adfc5">LLVMCreateDisasmCPUFeatures</a>.</p>

</div>
</div>

### LLVMCreateDisasmCPU() {#ga906d56cff22d17c94cae0c91fa36f6e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMDisasmContextRef LLVMCreateDisasmCPU (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Triple, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * CPU, void * DisInfo, int TagType, <a href="#gaa8eb7ea1e53fd6e7a11b6aa4749c6e60">LLVMOpInfoCallback</a> GetOpInfo, <a href="#ga05ffa603beb390898904a06b14ee5537">LLVMSymbolLookupCallback</a> SymbolLookUp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a disassembler for the TripleName and a specific CPU.</p>


<p>Symbolic disassembly is supported by passing a block of information in the DisInfo parameter and specifying the TagType and callback functions as described above. These can all be passed * as NULL. If successful, this returns a disassembler context. If not, it returns NULL. This function is equivalent to calling <a href="#ga0ed319f9f853493c0b38e551ec2adfc5">LLVMCreateDisasmCPUFeatures()</a> with an empty feature set.</p>


<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassembler-h">Disassembler.h</a>, definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-cpp">Disassembler.cpp</a>.</p>


<p>Reference <a href="#ga0ed319f9f853493c0b38e551ec2adfc5">LLVMCreateDisasmCPUFeatures</a>.</p>

</div>
</div>

### LLVMCreateDisasmCPUFeatures() {#ga0ed319f9f853493c0b38e551ec2adfc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMDisasmContextRef LLVMCreateDisasmCPUFeatures (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Triple, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * CPU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Features, void * DisInfo, int TagType, <a href="#gaa8eb7ea1e53fd6e7a11b6aa4749c6e60">LLVMOpInfoCallback</a> GetOpInfo, <a href="#ga05ffa603beb390898904a06b14ee5537">LLVMSymbolLookupCallback</a> SymbolLookUp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a disassembler for the TripleName, a specific CPU and specific feature string.</p>


<p>Symbolic disassembly is supported by passing a block of information in the DisInfo parameter and specifying the TagType and callback functions as described above. These can all be passed * as NULL. If successful, this returns a disassembler context. If not, it returns NULL.</p>


<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassembler-h">Disassembler.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-cpp">Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/target/#a9a65dcb8a1d47b55360f95a575dedb62">llvm::Target::createMCAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a9453c999bd3483858dec967aa3b8fca2">llvm::Target::createMCDisassembler</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a9aecbb4df7336a0a60255508e24e93d3">llvm::Target::createMCInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#afbeb195717f888bfc2ba9f54e9623bae">llvm::Target::createMCInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a7291082412f4df3356f434aac4685911">llvm::Target::createMCRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a6130eb3698f30c46e09f6f1b826c8e50">llvm::Target::createMCRelocationInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a3b11020c76ae0245d4aee684528e8a73">llvm::Target::createMCSubtargetInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a41d5b78272429261ccbbc0581e7e5a97">llvm::Target::createMCSymbolizer</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a85a69009ec328d5835241f56fb62cc6d">llvm::TargetRegistry::lookupTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmdisasmcontext/#a043768d184e14c6c14e4db9389e6218a">llvm::LLVMDisasmContext::setCPU</a>.</p>


<p>Referenced by <a href="#gab2235be6ece819e49dbde7cd52c3a2d8">LLVMCreateDisasm</a> and <a href="#ga906d56cff22d17c94cae0c91fa36f6e2">LLVMCreateDisasmCPU</a>.</p>

</div>
</div>

### LLVMDisasmDispose() {#ga15b630b4a386bee86ad5a10ff7592af0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMDisasmDispose (<a href="#gae903996143e88ff186c738f81122094e">LLVMDisasmContextRef</a> DC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dispose of a disassembler context.</p>

<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassembler-h">Disassembler.h</a>, definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-cpp">Disassembler.cpp</a>.</p>

</div>
</div>

### LLVMDisasmInstruction() {#ga4ab4dad1fdcb9e651fa60f6059ab09b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t LLVMDisasmInstruction (<a href="#gae903996143e88ff186c738f81122094e">LLVMDisasmContextRef</a> DC, uint8_t * Bytes, uint64_t BytesSize, uint64_t PC, char * OutString, size_t OutStringSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Disassemble a single instruction using the disassembler context specified in the parameter DC.</p>


<p>The bytes of the instruction are specified in the parameter Bytes, and contains at least BytesSize number of bytes. The instruction is at the address specified by the PC parameter. If a valid instruction can be disassembled, its string is returned indirectly in OutString whose size is specified in the parameter OutStringSize. This function returns the number of bytes in the instruction or zero if there was no valid instruction.</p>


<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassembler-h">Disassembler.h</a>, definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-cpp">Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a7b68be12c974b6b70bc86062f221a344">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::data</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-cpp/#a0e50dc982f01eab3eeb5eef624e25f03">emitComments</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-cpp/#ad7331753737602bb545def2c960c209d">emitLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#abb9477fc02ae36079df14aa77d8789c3">llvm::raw_ostream::enable_colors</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmdisasmcontext/#a025b4cae7b0009c9b81088eec80d4bdd">llvm::LLVMDisasmContext::getDisAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a938eec53ce08249709acf1b3ec7f4035">llvm::MCDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmdisasmcontext/#acd7a5e2ee33e79a76e07153242061fc3">llvm::LLVMDisasmContext::getIP</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmdisasmcontext/#a8cf18895a5ca03704be21ce808e03c83">llvm::LLVMDisasmContext::getOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmdisasmcontext/#a38cda99e294483fa025f4eb57f6544b9">llvm::LLVMDisasmContext::getSubtargetInfo</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#gaa21f8b4663cd086facd275f6286138e3">LLVMDisassembler_Option_Color</a>, <a href="#ga51495370fd44cea5cb0c7696139457d9">LLVMDisassembler_Option_PrintLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#ac297f3bc74269d7fe98eaf7300cba9fa">llvm::MCInstPrinter::printInst</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a3aa0680085158cfb0c14163a07ce9515">llvm::MCInstPrinter::setUseColor</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa9d693b8e530a7fa3457dece6f8951e6c">llvm::MCDisassembler::SoftFail</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aaabe09036b442fff9aa63ce1e844fdf60">llvm::MCDisassembler::Success</a>.</p>

</div>
</div>

### LLVMSetDisasmOptions() {#gad1cbbd5aa7b51f04687926e8f9e4aebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LLVMSetDisasmOptions (<a href="#gae903996143e88ff186c738f81122094e">LLVMDisasmContextRef</a> DC, uint64_t Options)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the disassembler's options.</p>


<p>Returns 1 if it can set the Options and 0 otherwise.</p>


<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassembler-h">Disassembler.h</a>, definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-cpp">Disassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llvmdisasmcontext/#a242ff66f07dcc065b46e07959edf6e4d">llvm::LLVMDisasmContext::addOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmdisasmcontext/#a26ae4b99e4c6cd8620f8603354572a33">llvm::LLVMDisasmContext::CommentStream</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a9aecbb4df7336a0a60255508e24e93d3">llvm::Target::createMCInstPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmdisasmcontext/#a4aaa235a27bfb38f0a782db0e5945176">llvm::LLVMDisasmContext::getAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a403352e1bd073ad5ea775fa48b598d60">llvm::MCAsmInfo::getAssemblerDialect</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmdisasmcontext/#ad1b025fe9218ff51f65b8d0be826e3db">llvm::LLVMDisasmContext::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmdisasmcontext/#acd7a5e2ee33e79a76e07153242061fc3">llvm::LLVMDisasmContext::getIP</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmdisasmcontext/#aa6a4fae6275aca4dfeb6d0e2618482ba">llvm::LLVMDisasmContext::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmdisasmcontext/#aebf9ddd5b499d9fe5c3a5e8374ec6a73">llvm::LLVMDisasmContext::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmdisasmcontext/#af6472ad3902ecbb48480e46eb60217b9">llvm::LLVMDisasmContext::getTripleName</a>, <a href="#gae0ce9f25acf18f03656aebcd8b99f807">LLVMDisassembler_Option_AsmPrinterVariant</a>, <a href="#gaa21f8b4663cd086facd275f6286138e3">LLVMDisassembler_Option_Color</a>, <a href="#ga17abcf26af53ca0ef4d8902e9abdfbdf">LLVMDisassembler_Option_PrintImmHex</a>, <a href="#ga51495370fd44cea5cb0c7696139457d9">LLVMDisassembler_Option_PrintLatency</a>, <a href="#ga7da58a469e24dca8c6cd1b644f57e5d7">LLVMDisassembler_Option_SetInstrComments</a>, <a href="#ga2e77b3aa2a7502be2350e34cfdbbe957">LLVMDisassembler_Option_UseMarkup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a3216205cbe92e7720a22058cf2d57676">llvm::MCInstPrinter::setCommentStream</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmdisasmcontext/#a36eaceae57946055f0f9439da556700c">llvm::LLVMDisasmContext::setIP</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a5315ee213d2bb70bfb0d581369c8bd47">llvm::MCInstPrinter::setPrintImmHex</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/#a93ea46134ac48f273fb38c88c4edde07">llvm::MCInstPrinter::setUseMarkup</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### LLVMDisassembler\_Option\_AsmPrinterVariant {#gae0ce9f25acf18f03656aebcd8b99f807}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_Option_AsmPrinterVariant&nbsp;&nbsp;&nbsp;4</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassembler-h">Disassembler.h</a>.</p>


<p>Referenced by <a href="#gad1cbbd5aa7b51f04687926e8f9e4aebb">LLVMSetDisasmOptions</a>.</p>

</div>
</div>

### LLVMDisassembler\_Option\_Color {#gaa21f8b4663cd086facd275f6286138e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_Option_Color&nbsp;&nbsp;&nbsp;32</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassembler-h">Disassembler.h</a>.</p>


<p>Referenced by <a href="#ga4ab4dad1fdcb9e651fa60f6059ab09b4">LLVMDisasmInstruction</a> and <a href="#gad1cbbd5aa7b51f04687926e8f9e4aebb">LLVMSetDisasmOptions</a>.</p>

</div>
</div>

### LLVMDisassembler\_Option\_PrintImmHex {#ga17abcf26af53ca0ef4d8902e9abdfbdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_Option_PrintImmHex&nbsp;&nbsp;&nbsp;2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassembler-h">Disassembler.h</a>.</p>


<p>Referenced by <a href="#gad1cbbd5aa7b51f04687926e8f9e4aebb">LLVMSetDisasmOptions</a>.</p>

</div>
</div>

### LLVMDisassembler\_Option\_PrintLatency {#ga51495370fd44cea5cb0c7696139457d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_Option_PrintLatency&nbsp;&nbsp;&nbsp;16</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassembler-h">Disassembler.h</a>.</p>


<p>Referenced by <a href="#ga4ab4dad1fdcb9e651fa60f6059ab09b4">LLVMDisasmInstruction</a> and <a href="#gad1cbbd5aa7b51f04687926e8f9e4aebb">LLVMSetDisasmOptions</a>.</p>

</div>
</div>

### LLVMDisassembler\_Option\_SetInstrComments {#ga7da58a469e24dca8c6cd1b644f57e5d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_Option_SetInstrComments&nbsp;&nbsp;&nbsp;8</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassembler-h">Disassembler.h</a>.</p>


<p>Referenced by <a href="#gad1cbbd5aa7b51f04687926e8f9e4aebb">LLVMSetDisasmOptions</a>.</p>

</div>
</div>

### LLVMDisassembler\_Option\_UseMarkup {#ga2e77b3aa2a7502be2350e34cfdbbe957}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_Option_UseMarkup&nbsp;&nbsp;&nbsp;1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassembler-h">Disassembler.h</a>.</p>


<p>Referenced by <a href="#gad1cbbd5aa7b51f04687926e8f9e4aebb">LLVMSetDisasmOptions</a>.</p>

</div>
</div>

### LLVMDisassembler\_ReferenceType\_DeMangled\_Name {#gae11bd2845e00fc1aed8223da0793bf4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_ReferenceType_DeMangled_Name&nbsp;&nbsp;&nbsp;9</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#aa4807aa3571299368e6d9b5c3d39893a">llvm::MCExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### LLVMDisassembler\_ReferenceType\_In\_ARM64\_ADDXri {#ga3e62ce52a54791ea0b2098eb8adc840f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_ReferenceType_In_ARM64_ADDXri&nbsp;&nbsp;&nbsp;4294967298</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### LLVMDisassembler\_ReferenceType\_In\_ARM64\_ADR {#ga1141f7abd5221b48b97c927b57234e33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_ReferenceType_In_ARM64_ADR&nbsp;&nbsp;&nbsp;4294967301</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### LLVMDisassembler\_ReferenceType\_In\_ARM64\_ADRP {#ga73395d6a90fefa202ec94dd103440106}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_ReferenceType_In_ARM64_ADRP&nbsp;&nbsp;&nbsp;4294967297</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### LLVMDisassembler\_ReferenceType\_In\_ARM64\_LDRXl {#gad81c0ae2e8ee538e833bb6e6c2ac0676}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_ReferenceType_In_ARM64_LDRXl&nbsp;&nbsp;&nbsp;4294967300</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### LLVMDisassembler\_ReferenceType\_In\_ARM64\_LDRXui {#gaf7375fccf8efe1277a941cb3cff28966}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_ReferenceType_In_ARM64_LDRXui&nbsp;&nbsp;&nbsp;4294967299</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### LLVMDisassembler\_ReferenceType\_In\_Branch {#ga82fca9d886616e829b203276c80afabf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_ReferenceType_In_Branch&nbsp;&nbsp;&nbsp;1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#aa4807aa3571299368e6d9b5c3d39893a">llvm::MCExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### LLVMDisassembler\_ReferenceType\_In\_PCrel\_Load {#ga4d14397b83038d9f432101b60d28afcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_ReferenceType_In_PCrel_Load&nbsp;&nbsp;&nbsp;2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#a932da00ce99b1018afdbc02579239ff1">llvm::MCExternalSymbolizer::tryAddingPcLoadReferenceComment</a>.</p>

</div>
</div>

### LLVMDisassembler\_ReferenceType\_InOut\_None {#gaa6b926b61f2d59191c806d31bb94c894}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_ReferenceType_InOut_None&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The reference types on input and output.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#aa4807aa3571299368e6d9b5c3d39893a">llvm::MCExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### LLVMDisassembler\_ReferenceType\_Out\_LitPool\_CstrAddr {#ga81e5011868131b85e2fe428b5de9165b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_ReferenceType_Out_LitPool_CstrAddr&nbsp;&nbsp;&nbsp;3</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#a932da00ce99b1018afdbc02579239ff1">llvm::MCExternalSymbolizer::tryAddingPcLoadReferenceComment</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### LLVMDisassembler\_ReferenceType\_Out\_LitPool\_SymAddr {#ga9ddf8b97918a69a6a513225d2f26c91f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_ReferenceType_Out_LitPool_SymAddr&nbsp;&nbsp;&nbsp;2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#a932da00ce99b1018afdbc02579239ff1">llvm::MCExternalSymbolizer::tryAddingPcLoadReferenceComment</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### LLVMDisassembler\_ReferenceType\_Out\_Objc\_CFString\_Ref {#ga4e7df42625f59e6870f6aaa04fd8e112}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_ReferenceType_Out_Objc_CFString_Ref&nbsp;&nbsp;&nbsp;4</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#a932da00ce99b1018afdbc02579239ff1">llvm::MCExternalSymbolizer::tryAddingPcLoadReferenceComment</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### LLVMDisassembler\_ReferenceType\_Out\_Objc\_Class\_Ref {#ga32181431bb3d71b1218b596eb3252b3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_ReferenceType_Out_Objc_Class_Ref&nbsp;&nbsp;&nbsp;8</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#a932da00ce99b1018afdbc02579239ff1">llvm::MCExternalSymbolizer::tryAddingPcLoadReferenceComment</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### LLVMDisassembler\_ReferenceType\_Out\_Objc\_Message {#gaa07c4db36282f91d8f9da2f1c74ffc4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_ReferenceType_Out_Objc_Message&nbsp;&nbsp;&nbsp;5</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#a932da00ce99b1018afdbc02579239ff1">llvm::MCExternalSymbolizer::tryAddingPcLoadReferenceComment</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#aa4807aa3571299368e6d9b5c3d39893a">llvm::MCExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### LLVMDisassembler\_ReferenceType\_Out\_Objc\_Message\_Ref {#gaceddd31c06c7ca91bb4747dd008a7bfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_ReferenceType_Out_Objc_Message_Ref&nbsp;&nbsp;&nbsp;6</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#a932da00ce99b1018afdbc02579239ff1">llvm::MCExternalSymbolizer::tryAddingPcLoadReferenceComment</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### LLVMDisassembler\_ReferenceType\_Out\_Objc\_Selector\_Ref {#gab234f9f0c243edf081dcbee6400c320a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_ReferenceType_Out_Objc_Selector_Ref&nbsp;&nbsp;&nbsp;7</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#a932da00ce99b1018afdbc02579239ff1">llvm::MCExternalSymbolizer::tryAddingPcLoadReferenceComment</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### LLVMDisassembler\_ReferenceType\_Out\_SymbolStub {#ga43cc63fe7d58d8379d06b31cf92d620b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_ReferenceType_Out_SymbolStub&nbsp;&nbsp;&nbsp;1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#aa4807aa3571299368e6d9b5c3d39893a">llvm::MCExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### LLVMDisassembler\_VariantKind\_ARM\_HI16 {#ga18c0e1aa1f200a0154c9301841a4d7ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_VariantKind_ARM_HI16&nbsp;&nbsp;&nbsp;1 /* :upper16: */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The ARM target VariantKinds.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armmachorelocationinfo-cpp-/armmachorelocationinfo/#acf3e0563ec30bb753fe338dc8be818b6">anonymous{ARMMachORelocationInfo.cpp}::ARMMachORelocationInfo::createExprForCAPIVariantKind</a>.</p>

</div>
</div>

### LLVMDisassembler\_VariantKind\_ARM\_LO16 {#ga518d82ae8838203f9aa0f8566a5ca51c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_VariantKind_ARM_LO16&nbsp;&nbsp;&nbsp;2 /* :lower16: */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armmachorelocationinfo-cpp-/armmachorelocationinfo/#acf3e0563ec30bb753fe338dc8be818b6">anonymous{ARMMachORelocationInfo.cpp}::ARMMachORelocationInfo::createExprForCAPIVariantKind</a>.</p>

</div>
</div>

### LLVMDisassembler\_VariantKind\_ARM64\_GOTPAGE {#gad25fcaca7790acb9f3678686219daecc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_VariantKind_ARM64_GOTPAGE&nbsp;&nbsp;&nbsp;3 /* @gotpage */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64externalsymbolizer-cpp/#a514d7e297481327255217939292ae114">getVariant</a>.</p>

</div>
</div>

### LLVMDisassembler\_VariantKind\_ARM64\_GOTPAGEOFF {#ga1babeeed365fdc3d716a52ebf3d5b315}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_VariantKind_ARM64_GOTPAGEOFF&nbsp;&nbsp;&nbsp;4 /* @gotpageoff */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64externalsymbolizer-cpp/#a514d7e297481327255217939292ae114">getVariant</a>.</p>

</div>
</div>

### LLVMDisassembler\_VariantKind\_ARM64\_PAGE {#gaac17762c72a25f63faf21df57e16176e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_VariantKind_ARM64_PAGE&nbsp;&nbsp;&nbsp;1 /* @page */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The ARM64 target VariantKinds.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64externalsymbolizer-cpp/#a514d7e297481327255217939292ae114">getVariant</a>.</p>

</div>
</div>

### LLVMDisassembler\_VariantKind\_ARM64\_PAGEOFF {#gacd4b54131faf848e92ea232693077151}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_VariantKind_ARM64_PAGEOFF&nbsp;&nbsp;&nbsp;2 /* @pageoff */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64externalsymbolizer-cpp/#a514d7e297481327255217939292ae114">getVariant</a>.</p>

</div>
</div>

### LLVMDisassembler\_VariantKind\_ARM64\_TLVOFF {#ga0c26f64bd2eaca9d9d4c21e14ea93f93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_VariantKind_ARM64_TLVOFF&nbsp;&nbsp;&nbsp;6 /* @tvlppageoff */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64externalsymbolizer-cpp/#a514d7e297481327255217939292ae114">getVariant</a>.</p>

</div>
</div>

### LLVMDisassembler\_VariantKind\_ARM64\_TLVP {#ga34ffa9d914aa8d4d7f0c70f409ff0d2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_VariantKind_ARM64_TLVP&nbsp;&nbsp;&nbsp;5 /* @tvlppage */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64externalsymbolizer-cpp/#a514d7e297481327255217939292ae114">getVariant</a>.</p>

</div>
</div>

### LLVMDisassembler\_VariantKind\_None {#gaeb7b3311097fd803536f89c1fd8a5f15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMDisassembler_VariantKind_None&nbsp;&nbsp;&nbsp;0 /* all targets */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The operand VariantKinds for symbolic disassembly.</p>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/disassemblertypes-h">DisassemblerTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo/#a4636659aa6c1ac582dedcdd046795f98">llvm::MCRelocationInfo::createExprForCAPIVariantKind</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64externalsymbolizer-cpp/#a514d7e297481327255217939292ae114">getVariant</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
