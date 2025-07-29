---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/x86ii
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `X86II` Namespace

<p><a href="/web-llvm/docs/api/namespaces/llvm/x86ii">X86II</a> - This namespace holds all of the target specific flags that instruction info tracks. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::X86II { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TOF { <a href="#a45cdfdabb3963ec52b198ce5d3aabc84">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Operand Flag enum. <a href="#a45cdfdabb3963ec52b198ce5d3aabc84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : uint64_t { <a href="#a74027296f130de8cbbe7bc543dc4285e">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b188aa442133e25413fa69e3a0223b8">isPrefix</a> (uint64_t TSFlags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8da88ee0688eaec097d62d33fff86992">isPseudo</a> (uint64_t TSFlags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5e00b79e046b7edec72a31f9398ea75">getBaseOpcodeFor</a> (uint64_t TSFlags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b8bc7d5e78603d3c61a536fd4217eba">hasImm</a> (uint64_t TSFlags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab80f6be5c11059e150772326c6a5e293">getSizeOfImm</a> (uint64_t TSFlags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decode the "size of immediate" field from the TSFlags field of the specified instruction. <a href="#ab80f6be5c11059e150772326c6a5e293">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0654eb4aaf0d4dae00f58a0b176c114">isImmPCRel</a> (uint64_t TSFlags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe8aadc3acd1babeaaa102408ac9973b">isImmSigned</a> (uint64_t TSFlags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0baab1b1dfea49cbffeb8727aebd429">getOperandBias</a> (const MCInstrDesc &amp;Desc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute whether all of the def operands are repeated in the uses and therefore should be skipped. <a href="#af0baab1b1dfea49cbffeb8727aebd429">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bab7f646d8804292fe0561f29f0c9c0">hasNewDataDest</a> (uint64_t TSFlags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad571a5a542b484586224d3a8df631646">getMemoryOperandNo</a> (uint64_t TSFlags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9fd738474c4c822202e6d73a9509904">isXMMReg</a> (MCRegister Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc7da017f8afea15479e578fcc10a2e2">isYMMReg</a> (MCRegister Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a301d6276fae739378e945ebbe0c8dd9b">isZMMReg</a> (MCRegister Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed3a5dba6b8da462e693c4965ec7c911">isApxExtendedReg</a> (MCRegister Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae63be8b012497f28a863be8cfa255a87">isX86_64ExtendedReg</a> (MCRegister Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bdd2254738314285aa56112068b2407">canUseApxExtendedReg</a> (const MCInstrDesc &amp;Desc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ccb37bba2965d7b115cbcbbb196b088">is32ExtendedReg</a> (MCRegister Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f97093f1f56f60672b73a8285ce9c96">isX86_64NonExtLowByteReg</a> (MCRegister Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5feea989366c35ad4b85148a305f116">isKMasked</a> (uint64_t TSFlags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07b28b4355ad8daca32f6087453982a0">isKMergeMasked</a> (uint64_t TSFlags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9df9a1addf48641771cbae1137661aa">needSIB</a> (MCRegister BaseReg, MCRegister IndexReg, bool In64BitMode)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/x86ii">X86II</a> - This namespace holds all of the target specific flags that instruction info tracks.</p>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a74027296f130de8cbbe7bc543dc4285e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : uint64_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pseudo<a id="a74027296f130de8cbbe7bc543dc4285eac147ba1bbcbb4cbda038e4fbd6e5bb31"></a></td>
<td class="doxyEnumItemDescription">PseudoFrm - This represents an instruction that is a pseudo instruction or one that has not been implemented yet (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RawFrm<a id="a74027296f130de8cbbe7bc543dc4285ea0418cac03c72116432f2161ba81a9477"></a></td>
<td class="doxyEnumItemDescription">Raw - This form is for instructions that don't have any operands, so they are just a fixed opcode value, like 'leave' (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddRegFrm<a id="a74027296f130de8cbbe7bc543dc4285ea5cd1bb6ca4bb8d7b507c98b61a19ae77"></a></td>
<td class="doxyEnumItemDescription">AddRegFrm - This form is used for instructions like 'push r32' that have their one register operand added to their opcode (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RawFrmMemOffs<a id="a74027296f130de8cbbe7bc543dc4285eaf45ee1f86f45fd23ef8e084b0069aa17"></a></td>
<td class="doxyEnumItemDescription">RawFrmMemOffs - This form is for instructions that store an absolute memory offset as an immediate with a possible segment override (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RawFrmSrc<a id="a74027296f130de8cbbe7bc543dc4285eab93edaca89956bd35deb0830c0a83c32"></a></td>
<td class="doxyEnumItemDescription">RawFrmSrc - This form is for instructions that use the source index register SI/ESI/RSI with a possible segment override (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RawFrmDst<a id="a74027296f130de8cbbe7bc543dc4285ea336cd3807e9712aee813c92ab1cbd3c7"></a></td>
<td class="doxyEnumItemDescription">RawFrmDst - This form is for instructions that use the destination index register DI/EDI/RDI (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RawFrmDstSrc<a id="a74027296f130de8cbbe7bc543dc4285ea0ebbf8b9bdbf40355e1786a06fe3ebdb"></a></td>
<td class="doxyEnumItemDescription">RawFrmDstSrc - This form is for instructions that use the source index register SI/ESI/RSI with a possible segment override, and also the destination index register DI/EDI/RDI (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RawFrmImm8<a id="a74027296f130de8cbbe7bc543dc4285ea682f4bde7ea50ebb5d09cfc9f8283d87"></a></td>
<td class="doxyEnumItemDescription">RawFrmImm8 - This is used for the ENTER instruction, which has two immediates, the first of which is a 16-bit immediate (specified by the imm encoding) and the second is a 8-bit fixed value (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RawFrmImm16<a id="a74027296f130de8cbbe7bc543dc4285eab246efb880b0f5ea54ddf3879bced8e3"></a></td>
<td class="doxyEnumItemDescription">RawFrmImm16 - This is used for CALL FAR instructions, which have two immediates, the first of which is a 16 or 32-bit immediate (specified by the imm encoding) and the second is a 16-bit fixed value (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddCCFrm<a id="a74027296f130de8cbbe7bc543dc4285ea3db5b7855daab5b642f29a4f8743d1a9"></a></td>
<td class="doxyEnumItemDescription">AddCCFrm - This form is used for Jcc that encode the condition code in the lower 4 bits of the opcode (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PrefixByte<a id="a74027296f130de8cbbe7bc543dc4285ea3f6747b02d6858c6b951b760c4117325"></a></td>
<td class="doxyEnumItemDescription">PrefixByte - This form is used for instructions that represent a prefix byte like data16 or rep (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRMDestRegCC<a id="a74027296f130de8cbbe7bc543dc4285ea7ea417afb58cc07fa2cfcae87905361c"></a></td>
<td class="doxyEnumItemDescription">MRMDestRegCC - This form is used for the cfcmov instructions, which use the Mod/RM byte to specify the operands reg(r/m) and reg(reg) and also encodes a condition code (= 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRMDestMemCC<a id="a74027296f130de8cbbe7bc543dc4285eaa9e2dd541cca69dae4eb2b19c12a920a"></a></td>
<td class="doxyEnumItemDescription">MRMDestMemCC - This form is used for the cfcmov instructions, which use the Mod/RM byte to specify the operands mem(r/m) and reg(reg) and also encodes a condition code (= 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRMDestMem4VOp3CC<a id="a74027296f130de8cbbe7bc543dc4285ea39ff7e3b87758fceb290c859e5525b92"></a></td>
<td class="doxyEnumItemDescription">MRMDestMem4VOp3CC - This form is used for instructions that use the Mod/RM byte to specify a destination which in this case is memory and operand 3 with VEX.VVVV, and also encodes a condition code (= 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRMr0<a id="a74027296f130de8cbbe7bc543dc4285ea47511fb3305bca93e2f5a8b5c06cd434"></a></td>
<td class="doxyEnumItemDescription">Instructions operate on a register Reg/Opcode operand not the r/m field (= 21)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRMSrcMemFSIB<a id="a74027296f130de8cbbe7bc543dc4285ea912fe30bf2fb6db485900f399a0f6919"></a></td>
<td class="doxyEnumItemDescription">MRMSrcMem - But force to use the SIB field (= 22)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRMDestMemFSIB<a id="a74027296f130de8cbbe7bc543dc4285ea5a693dd88d31ce75ba797dca591201dc"></a></td>
<td class="doxyEnumItemDescription">MRMDestMem - But force to use the SIB field (= 23)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRMDestMem<a id="a74027296f130de8cbbe7bc543dc4285ea8de627e0b4d8f49621aaffaf22768ccf"></a></td>
<td class="doxyEnumItemDescription">MRMDestMem - This form is used for instructions that use the Mod/RM byte to specify a destination, which in this case is memory (= 24)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRMSrcMem<a id="a74027296f130de8cbbe7bc543dc4285eabeb3b7e6c5b8fde8b53c453b462f0aae"></a></td>
<td class="doxyEnumItemDescription">MRMSrcMem - This form is used for instructions that use the Mod/RM byte to specify a source, which in this case is memory (= 25)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRMSrcMem4VOp3<a id="a74027296f130de8cbbe7bc543dc4285ea71ff3202ae1a689c037fdde29b3ef3d2"></a></td>
<td class="doxyEnumItemDescription">MRMSrcMem4VOp3 - This form is used for instructions that encode operand 3 with VEX.VVVV and load from memory (= 26)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRMSrcMemOp4<a id="a74027296f130de8cbbe7bc543dc4285eabfcb56e85f0547829052a6f31803159b"></a></td>
<td class="doxyEnumItemDescription">MRMSrcMemOp4 - This form is used for instructions that use the Mod/RM byte to specify the fourth source, which in this case is memory (= 27)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRMSrcMemCC<a id="a74027296f130de8cbbe7bc543dc4285ea1ba28eab105e932f7173e256119df199"></a></td>
<td class="doxyEnumItemDescription">MRMSrcMemCC - This form is used for instructions that use the Mod/RM byte to specify the operands and also encodes a condition code (= 28)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRMXmCC<a id="a74027296f130de8cbbe7bc543dc4285eaae046536d1fe7157266801c5446581f1"></a></td>
<td class="doxyEnumItemDescription">MRMXm - This form is used for instructions that use the Mod/RM byte to specify a memory source, but doesn't use the middle field (= 30)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRMXm<a id="a74027296f130de8cbbe7bc543dc4285ea580f946ce0c61ee2cb39a53181487908"></a></td>
<td class="doxyEnumItemDescription">MRMXm - This form is used for instructions that use the Mod/RM byte to specify a memory source, but doesn't use the middle field (= 31)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM0m<a id="a74027296f130de8cbbe7bc543dc4285eac9be8e1d01f704feb05bd77f9454d9c4"></a></td>
<td class="doxyEnumItemDescription">MRM0m-MRM7m - Instructions that operate on a memory r/m operand and use reg field to hold extended opcode, which is represented as /0, /1, .. (= 32)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM1m<a id="a74027296f130de8cbbe7bc543dc4285ea2907aae414f1869eede11975c90ca55e"></a></td>
<td class="doxyEnumItemDescription"> (= 33)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM2m<a id="a74027296f130de8cbbe7bc543dc4285eab2b54a959754806bbcc10c7d415869b4"></a></td>
<td class="doxyEnumItemDescription"> (= 34)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM3m<a id="a74027296f130de8cbbe7bc543dc4285eae6c25fb53fc239290474f16af2896017"></a></td>
<td class="doxyEnumItemDescription"> (= 35)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM4m<a id="a74027296f130de8cbbe7bc543dc4285ea3b73d9e91703e440c64df61ab7cc1997"></a></td>
<td class="doxyEnumItemDescription"> (= 36)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM5m<a id="a74027296f130de8cbbe7bc543dc4285ea0420bc5bdfc993b20046f32d50fa0753"></a></td>
<td class="doxyEnumItemDescription"> (= 37)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM6m<a id="a74027296f130de8cbbe7bc543dc4285eaf1e55f460320e2a89ccd653477a81909"></a></td>
<td class="doxyEnumItemDescription"> (= 38)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM7m<a id="a74027296f130de8cbbe7bc543dc4285ea792ba63c3af3d1eed02519bbc1f883c2"></a></td>
<td class="doxyEnumItemDescription"> (= 39)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRMDestReg<a id="a74027296f130de8cbbe7bc543dc4285eabe42ba2fb12010736a3d91ff51c00f91"></a></td>
<td class="doxyEnumItemDescription">MRMDestReg - This form is used for instructions that use the Mod/RM byte to specify a destination, which in this case is a register (= 40)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRMSrcReg<a id="a74027296f130de8cbbe7bc543dc4285eab5eb1a156b44a8263348720cefb0f078"></a></td>
<td class="doxyEnumItemDescription">MRMSrcReg - This form is used for instructions that use the Mod/RM byte to specify a source, which in this case is a register (= 41)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRMSrcReg4VOp3<a id="a74027296f130de8cbbe7bc543dc4285eaec9007fc8d5e45ac8c8ca70cbc20527c"></a></td>
<td class="doxyEnumItemDescription">MRMSrcReg4VOp3 - This form is used for instructions that encode operand 3 with VEX.VVVV and do not load from memory (= 42)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRMSrcRegOp4<a id="a74027296f130de8cbbe7bc543dc4285eaa5752d9fbf4eaf48924623fb22345d78"></a></td>
<td class="doxyEnumItemDescription">MRMSrcRegOp4 - This form is used for instructions that use the Mod/RM byte to specify the fourth source, which in this case is a register (= 43)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRMSrcRegCC<a id="a74027296f130de8cbbe7bc543dc4285eac7457861e859e2d45b248505b1ce4d64"></a></td>
<td class="doxyEnumItemDescription">MRMSrcRegCC - This form is used for instructions that use the Mod/RM byte to specify the operands and also encodes a condition code (= 44)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRMXrCC<a id="a74027296f130de8cbbe7bc543dc4285eaa674367c0dc04c60557b71d6cb873cc0"></a></td>
<td class="doxyEnumItemDescription">MRMXCCr - This form is used for instructions that use the Mod/RM byte to specify a register source, but doesn't use the middle field (= 46)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRMXr<a id="a74027296f130de8cbbe7bc543dc4285ea6d334921612f3043e206d194dc882494"></a></td>
<td class="doxyEnumItemDescription">MRMXr - This form is used for instructions that use the Mod/RM byte to specify a register source, but doesn't use the middle field (= 47)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM0r<a id="a74027296f130de8cbbe7bc543dc4285ea594ebf9b65f24cace8a6ed6cc4c188dc"></a></td>
<td class="doxyEnumItemDescription">MRM0r-MRM7r - Instructions that operate on a register r/m operand and use reg field to hold extended opcode, which is represented as /0, /1, .. (= 48)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM1r<a id="a74027296f130de8cbbe7bc543dc4285eaf4593f298ffcbd9b56cccee8c9b08f4f"></a></td>
<td class="doxyEnumItemDescription"> (= 49)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM2r<a id="a74027296f130de8cbbe7bc543dc4285ea50b127ece65d9d64ecff049972c908a7"></a></td>
<td class="doxyEnumItemDescription"> (= 50)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM3r<a id="a74027296f130de8cbbe7bc543dc4285eae3f4d0f3323d02cfb646af18c329dcc1"></a></td>
<td class="doxyEnumItemDescription"> (= 51)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM4r<a id="a74027296f130de8cbbe7bc543dc4285eaf2b510dd27c823fbcb97dccc422165dc"></a></td>
<td class="doxyEnumItemDescription"> (= 52)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM5r<a id="a74027296f130de8cbbe7bc543dc4285ea1ccd60dae6f567df2362f05b10053f2c"></a></td>
<td class="doxyEnumItemDescription"> (= 53)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM6r<a id="a74027296f130de8cbbe7bc543dc4285eafe4134fe8da389ed6dbaddff7d04e924"></a></td>
<td class="doxyEnumItemDescription"> (= 54)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM7r<a id="a74027296f130de8cbbe7bc543dc4285ea48bbc6e11eab7158eca421cdbefb4300"></a></td>
<td class="doxyEnumItemDescription"> (= 55)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM0X<a id="a74027296f130de8cbbe7bc543dc4285ea0107a9570489e513aeb2c457c1bc4ea7"></a></td>
<td class="doxyEnumItemDescription">MRM0X-MRM7X - Instructions that operate that have mod=11 and an opcode but ignore r/m (= 56)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM1X<a id="a74027296f130de8cbbe7bc543dc4285ea38b0803128a680769157e24858a8fcec"></a></td>
<td class="doxyEnumItemDescription"> (= 57)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM2X<a id="a74027296f130de8cbbe7bc543dc4285ea8ffd3410ef34800d44d089d1204ab80a"></a></td>
<td class="doxyEnumItemDescription"> (= 58)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM3X<a id="a74027296f130de8cbbe7bc543dc4285ea8cd6a8196a06c9a17ef03ad258199b56"></a></td>
<td class="doxyEnumItemDescription"> (= 59)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM4X<a id="a74027296f130de8cbbe7bc543dc4285eaa594aa3985a0795387aa7af8947b1e36"></a></td>
<td class="doxyEnumItemDescription"> (= 60)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM5X<a id="a74027296f130de8cbbe7bc543dc4285eab383ad975c3b9092939504e4cfe2ae1b"></a></td>
<td class="doxyEnumItemDescription"> (= 61)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM6X<a id="a74027296f130de8cbbe7bc543dc4285ea8b62cf7e7b7cd325706f22acc7a534d6"></a></td>
<td class="doxyEnumItemDescription"> (= 62)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM7X<a id="a74027296f130de8cbbe7bc543dc4285ea7f05c49c45f8901eb86ef2cae982fb87"></a></td>
<td class="doxyEnumItemDescription"> (= 63)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_C0<a id="a74027296f130de8cbbe7bc543dc4285ea2af966e37189622a1946ce35593a47c1"></a></td>
<td class="doxyEnumItemDescription">MRM_XX (XX: C0-FF)- A mod/rm byte of exactly 0xXX (= 64)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_C1<a id="a74027296f130de8cbbe7bc543dc4285eadf13526f9c198e6d3c44b18fade1cdaa"></a></td>
<td class="doxyEnumItemDescription"> (= 65)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_C2<a id="a74027296f130de8cbbe7bc543dc4285ea189edb0057c77e393b6cd48c6a57844f"></a></td>
<td class="doxyEnumItemDescription"> (= 66)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_C3<a id="a74027296f130de8cbbe7bc543dc4285ea0b8663d52f6013c3c4c44ee6b3e4c221"></a></td>
<td class="doxyEnumItemDescription"> (= 67)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_C4<a id="a74027296f130de8cbbe7bc543dc4285eaec272046d5dd90472121b5a374c10c13"></a></td>
<td class="doxyEnumItemDescription"> (= 68)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_C5<a id="a74027296f130de8cbbe7bc543dc4285ea2a6bc67c716424a75afd98493ce44ca7"></a></td>
<td class="doxyEnumItemDescription"> (= 69)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_C6<a id="a74027296f130de8cbbe7bc543dc4285ea1511d6f7eff51b12b38d9f86c132b3a5"></a></td>
<td class="doxyEnumItemDescription"> (= 70)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_C7<a id="a74027296f130de8cbbe7bc543dc4285ea20fa7bc944e07c156d78ee9f5ee4c04c"></a></td>
<td class="doxyEnumItemDescription"> (= 71)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_C8<a id="a74027296f130de8cbbe7bc543dc4285ea37445de2099407dfca0ec37ff35fe5d5"></a></td>
<td class="doxyEnumItemDescription"> (= 72)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_C9<a id="a74027296f130de8cbbe7bc543dc4285ea0125d0cd4af4273d1367a6c462839199"></a></td>
<td class="doxyEnumItemDescription"> (= 73)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_CA<a id="a74027296f130de8cbbe7bc543dc4285ea5b915593c95df3a2d84c96327151320d"></a></td>
<td class="doxyEnumItemDescription"> (= 74)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_CB<a id="a74027296f130de8cbbe7bc543dc4285ea395918f662de770c178e7f7e544934ba"></a></td>
<td class="doxyEnumItemDescription"> (= 75)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_CC<a id="a74027296f130de8cbbe7bc543dc4285ea8fbd1ccdaf11ee40122c547614c78a10"></a></td>
<td class="doxyEnumItemDescription"> (= 76)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_CD<a id="a74027296f130de8cbbe7bc543dc4285ea776deddd1d12c851740c6c5a42da0fd0"></a></td>
<td class="doxyEnumItemDescription"> (= 77)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_CE<a id="a74027296f130de8cbbe7bc543dc4285ea7a707f8b06bf47ba3bfe19ddd4a4de26"></a></td>
<td class="doxyEnumItemDescription"> (= 78)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_CF<a id="a74027296f130de8cbbe7bc543dc4285ea4f3138e38a1ffc21e8e279506282fdc4"></a></td>
<td class="doxyEnumItemDescription"> (= 79)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_D0<a id="a74027296f130de8cbbe7bc543dc4285eaa9cc16d23eb1dbbd266f08d5b72c9d3b"></a></td>
<td class="doxyEnumItemDescription"> (= 80)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_D1<a id="a74027296f130de8cbbe7bc543dc4285ea3bcf50adb50e141c86c2207c2665a914"></a></td>
<td class="doxyEnumItemDescription"> (= 81)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_D2<a id="a74027296f130de8cbbe7bc543dc4285ea19e5fd422fa45df8331f702e30a3b23d"></a></td>
<td class="doxyEnumItemDescription"> (= 82)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_D3<a id="a74027296f130de8cbbe7bc543dc4285eacf475f7fa1990d9771867a43a5cb85b2"></a></td>
<td class="doxyEnumItemDescription"> (= 83)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_D4<a id="a74027296f130de8cbbe7bc543dc4285eaeaa884b20defdb5c6e68fad5b0292c5e"></a></td>
<td class="doxyEnumItemDescription"> (= 84)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_D5<a id="a74027296f130de8cbbe7bc543dc4285ea0463837736d6ed75cc0575e546ad9769"></a></td>
<td class="doxyEnumItemDescription"> (= 85)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_D6<a id="a74027296f130de8cbbe7bc543dc4285ea272fc77667a050402a169a058b0a4743"></a></td>
<td class="doxyEnumItemDescription"> (= 86)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_D7<a id="a74027296f130de8cbbe7bc543dc4285ea3bd2db5d167f57e231a3cbda8b47328b"></a></td>
<td class="doxyEnumItemDescription"> (= 87)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_D8<a id="a74027296f130de8cbbe7bc543dc4285ea7a240d439831945855485d9f668be73d"></a></td>
<td class="doxyEnumItemDescription"> (= 88)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_D9<a id="a74027296f130de8cbbe7bc543dc4285ea5502e099f8608464260941952d44efd6"></a></td>
<td class="doxyEnumItemDescription"> (= 89)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_DA<a id="a74027296f130de8cbbe7bc543dc4285eab93028e02236b5c4c5d824a31d68805d"></a></td>
<td class="doxyEnumItemDescription"> (= 90)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_DB<a id="a74027296f130de8cbbe7bc543dc4285ea9a3b74dbd24dd89ad5cdca90b5fd868f"></a></td>
<td class="doxyEnumItemDescription"> (= 91)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_DC<a id="a74027296f130de8cbbe7bc543dc4285ea16edad2aa61ba14cb331d3741526c0bc"></a></td>
<td class="doxyEnumItemDescription"> (= 92)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_DD<a id="a74027296f130de8cbbe7bc543dc4285ea571898bf7abbdc75ca1da8810cde5e0f"></a></td>
<td class="doxyEnumItemDescription"> (= 93)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_DE<a id="a74027296f130de8cbbe7bc543dc4285ea248e1fc19cfe5ff9230b7ed6dbf9cd72"></a></td>
<td class="doxyEnumItemDescription"> (= 94)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_DF<a id="a74027296f130de8cbbe7bc543dc4285eaccca1bfb3adb4527dfd581b8d68540a6"></a></td>
<td class="doxyEnumItemDescription"> (= 95)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_E0<a id="a74027296f130de8cbbe7bc543dc4285ea3063db197181757a6cd1e36cede73a30"></a></td>
<td class="doxyEnumItemDescription"> (= 96)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_E1<a id="a74027296f130de8cbbe7bc543dc4285ea3ab2637fb82524a013ea7c723f8c8f63"></a></td>
<td class="doxyEnumItemDescription"> (= 97)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_E2<a id="a74027296f130de8cbbe7bc543dc4285ea75edf85ddb193d591093ce26d7767e4f"></a></td>
<td class="doxyEnumItemDescription"> (= 98)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_E3<a id="a74027296f130de8cbbe7bc543dc4285eabd41e93afa5098b8fbdc4283a4715554"></a></td>
<td class="doxyEnumItemDescription"> (= 99)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_E4<a id="a74027296f130de8cbbe7bc543dc4285eaeeac690144cf1f43a36406182ad141ee"></a></td>
<td class="doxyEnumItemDescription"> (= 100)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_E5<a id="a74027296f130de8cbbe7bc543dc4285ea2bad450ca1a94ce69ae415089410766c"></a></td>
<td class="doxyEnumItemDescription"> (= 101)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_E6<a id="a74027296f130de8cbbe7bc543dc4285ea252613e02ec044540f82c75f89f36eef"></a></td>
<td class="doxyEnumItemDescription"> (= 102)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_E7<a id="a74027296f130de8cbbe7bc543dc4285ea00d46302e861a9c7fd9fecff66f57d43"></a></td>
<td class="doxyEnumItemDescription"> (= 103)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_E8<a id="a74027296f130de8cbbe7bc543dc4285ea5d145c66ae6d756f9e9ad6ca5679fc30"></a></td>
<td class="doxyEnumItemDescription"> (= 104)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_E9<a id="a74027296f130de8cbbe7bc543dc4285ea2926981e23657a2d17b45aa1e8deeb32"></a></td>
<td class="doxyEnumItemDescription"> (= 105)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_EA<a id="a74027296f130de8cbbe7bc543dc4285eaf0e0ba20c47f32af24167f89de05ea2b"></a></td>
<td class="doxyEnumItemDescription"> (= 106)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_EB<a id="a74027296f130de8cbbe7bc543dc4285ea5e1a684c375625f7e37e9fe1e51e8b11"></a></td>
<td class="doxyEnumItemDescription"> (= 107)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_EC<a id="a74027296f130de8cbbe7bc543dc4285ea404988f54ad3626aa9083dffa10af417"></a></td>
<td class="doxyEnumItemDescription"> (= 108)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_ED<a id="a74027296f130de8cbbe7bc543dc4285ea6d741c96d1bb53548d70ba69e64dd87f"></a></td>
<td class="doxyEnumItemDescription"> (= 109)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_EE<a id="a74027296f130de8cbbe7bc543dc4285eadfb7936fa0afa17e28a206fcdbc56f0c"></a></td>
<td class="doxyEnumItemDescription"> (= 110)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_EF<a id="a74027296f130de8cbbe7bc543dc4285eae82cd5ecc861d5194f989105b9b1a703"></a></td>
<td class="doxyEnumItemDescription"> (= 111)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_F0<a id="a74027296f130de8cbbe7bc543dc4285ea936de17cbfd634fac5595a37a533f95f"></a></td>
<td class="doxyEnumItemDescription"> (= 112)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_F1<a id="a74027296f130de8cbbe7bc543dc4285ead6e835cdd73242accfc715f15582d01d"></a></td>
<td class="doxyEnumItemDescription"> (= 113)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_F2<a id="a74027296f130de8cbbe7bc543dc4285ead97baea9720ca2d954726b6740b7809d"></a></td>
<td class="doxyEnumItemDescription"> (= 114)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_F3<a id="a74027296f130de8cbbe7bc543dc4285ea1956e66a1c51c45ba25231fcb34a6aaa"></a></td>
<td class="doxyEnumItemDescription"> (= 115)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_F4<a id="a74027296f130de8cbbe7bc543dc4285eabc0b630f1cb9d56814a374cc7c8e70c7"></a></td>
<td class="doxyEnumItemDescription"> (= 116)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_F5<a id="a74027296f130de8cbbe7bc543dc4285ea88119e0502acf1a1ec6650f4435f9924"></a></td>
<td class="doxyEnumItemDescription"> (= 117)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_F6<a id="a74027296f130de8cbbe7bc543dc4285ea421213d9262af8d681a60931da2ea361"></a></td>
<td class="doxyEnumItemDescription"> (= 118)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_F7<a id="a74027296f130de8cbbe7bc543dc4285ea599cbf1248343a8255a40b76010a699f"></a></td>
<td class="doxyEnumItemDescription"> (= 119)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_F8<a id="a74027296f130de8cbbe7bc543dc4285eaaf1c2bcbf66b594cb5ef0710023eaa2a"></a></td>
<td class="doxyEnumItemDescription"> (= 120)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_F9<a id="a74027296f130de8cbbe7bc543dc4285ea44d10b054bc67d9b6f1a07b9dc0d18ee"></a></td>
<td class="doxyEnumItemDescription"> (= 121)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_FA<a id="a74027296f130de8cbbe7bc543dc4285ea2d11d20093f76b091589d4ef0eaceae4"></a></td>
<td class="doxyEnumItemDescription"> (= 122)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_FB<a id="a74027296f130de8cbbe7bc543dc4285ea6f05cf3244440c8e67134b48bc940c36"></a></td>
<td class="doxyEnumItemDescription"> (= 123)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_FC<a id="a74027296f130de8cbbe7bc543dc4285eac2a2c7a6e424ee9aa0011460a4d21a06"></a></td>
<td class="doxyEnumItemDescription"> (= 124)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_FD<a id="a74027296f130de8cbbe7bc543dc4285ea8f7673a5f185e5d03e0b82c20e00a482"></a></td>
<td class="doxyEnumItemDescription"> (= 125)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_FE<a id="a74027296f130de8cbbe7bc543dc4285ead28e78f91e2f75cc5ad3d84154e7438b"></a></td>
<td class="doxyEnumItemDescription"> (= 126)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MRM_FF<a id="a74027296f130de8cbbe7bc543dc4285eacb535be85414635d6cbbaa53f67167cd"></a></td>
<td class="doxyEnumItemDescription"> (= 127)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FormMask<a id="a74027296f130de8cbbe7bc543dc4285ea3ae6529df02b311ddca2a678a0bfaf64"></a></td>
<td class="doxyEnumItemDescription"> (= 127)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpSizeShift<a id="a74027296f130de8cbbe7bc543dc4285ea69c4cf9b8d68a9dfe69d17e99489590c"></a></td>
<td class="doxyEnumItemDescription">OpSize - OpSizeFixed implies instruction never needs a 0x66 prefix (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpSizeMask<a id="a74027296f130de8cbbe7bc543dc4285eaa27540a3db25622f122837aa4def5efa"></a></td>
<td class="doxyEnumItemDescription"> (= 0x3 &lt;&lt; OpSizeShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpSizeFixed<a id="a74027296f130de8cbbe7bc543dc4285eaa5ea0d5870d8a565eb576e77060af87b"></a></td>
<td class="doxyEnumItemDescription"> (= 0 &lt;&lt; OpSizeShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpSize16<a id="a74027296f130de8cbbe7bc543dc4285ea0ff8c56f8764c2a6ea4c46d3b40e064a"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; OpSizeShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpSize32<a id="a74027296f130de8cbbe7bc543dc4285ea71786270c5b7087684f0a07e97048d0c"></a></td>
<td class="doxyEnumItemDescription"> (= 2 &lt;&lt; OpSizeShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AdSizeShift<a id="a74027296f130de8cbbe7bc543dc4285ea8633d98fe5ea7d198e8c90523e7a167e"></a></td>
<td class="doxyEnumItemDescription">AsSize - AdSizeX implies this instruction determines its need of 0x67 prefix from a normal ModRM memory operand (= OpSizeShift + 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AdSizeMask<a id="a74027296f130de8cbbe7bc543dc4285ea50c2f31aba037c4ec3acceb23258ef8f"></a></td>
<td class="doxyEnumItemDescription"> (= 0x3 &lt;&lt; AdSizeShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AdSizeX<a id="a74027296f130de8cbbe7bc543dc4285eaf4478607966e96f393e64286f8f3f20a"></a></td>
<td class="doxyEnumItemDescription"> (= 0 &lt;&lt; AdSizeShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AdSize16<a id="a74027296f130de8cbbe7bc543dc4285eab2eec66c1c52ab7579af0cb9130b8ab5"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; AdSizeShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AdSize32<a id="a74027296f130de8cbbe7bc543dc4285eae324586afb9a70d93aa2aba95abcd2d0"></a></td>
<td class="doxyEnumItemDescription"> (= 2 &lt;&lt; AdSizeShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AdSize64<a id="a74027296f130de8cbbe7bc543dc4285ea4850e21be1aff3186ecd45fb97a665e7"></a></td>
<td class="doxyEnumItemDescription"> (= 3 &lt;&lt; AdSizeShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpPrefixShift<a id="a74027296f130de8cbbe7bc543dc4285ea34c4bade42aee4399e59f1563aca7941"></a></td>
<td class="doxyEnumItemDescription">OpPrefix - There are several prefix bytes that are used as opcode extensions (= AdSizeShift + 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpPrefixMask<a id="a74027296f130de8cbbe7bc543dc4285eafd3ef015d11de7b9cf6d25507774a0a9"></a></td>
<td class="doxyEnumItemDescription"> (= 0x3 &lt;&lt; OpPrefixShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PD<a id="a74027296f130de8cbbe7bc543dc4285ea8d230b4df405685c7dc1f1db718d7008"></a></td>
<td class="doxyEnumItemDescription">PD - Prefix code for packed double precision vector floating point operations performed in the SSE registers (= 1 &lt;&lt; OpPrefixShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XS<a id="a74027296f130de8cbbe7bc543dc4285ead9268658d1be801bae20dba1f1378dcf"></a></td>
<td class="doxyEnumItemDescription">XS, XD - These prefix codes are for single and double precision scalar floating point operations performed in the SSE registers (= 2 &lt;&lt; OpPrefixShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XD<a id="a74027296f130de8cbbe7bc543dc4285ea5309cc29d36de4eb6d05bae85de58f78"></a></td>
<td class="doxyEnumItemDescription"> (= 3 &lt;&lt; OpPrefixShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpMapShift<a id="a74027296f130de8cbbe7bc543dc4285eaef220b04e949318568c410c544cae09a"></a></td>
<td class="doxyEnumItemDescription">OpMap - This field determines which opcode map this instruction belongs to (= OpPrefixShift + 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpMapMask<a id="a74027296f130de8cbbe7bc543dc4285ea17bada293123ac2f889d0dece275027d"></a></td>
<td class="doxyEnumItemDescription"> (= 0xF &lt;&lt; OpMapShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OB<a id="a74027296f130de8cbbe7bc543dc4285ea3c11b5af543fcb3173f20c9ce3a6856d"></a></td>
<td class="doxyEnumItemDescription">OB - OneByte - Set if this instruction has a one byte opcode (= 0 &lt;&lt; OpMapShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TB<a id="a74027296f130de8cbbe7bc543dc4285ea6ba65e174dfdcdb111e1aea6b4299b16"></a></td>
<td class="doxyEnumItemDescription">TB - TwoByte - Set if this instruction has a two byte opcode, which starts with a 0x0F byte before the real opcode (= 1 &lt;&lt; OpMapShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">T8<a id="a74027296f130de8cbbe7bc543dc4285eaa77319fb93896ec55033cdf328e8771d"></a></td>
<td class="doxyEnumItemDescription">T8, TA - Prefix after the 0x0F prefix (= 2 &lt;&lt; OpMapShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TA<a id="a74027296f130de8cbbe7bc543dc4285ead254d64df655ab661c3c3330610385af"></a></td>
<td class="doxyEnumItemDescription"> (= 3 &lt;&lt; OpMapShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XOP8<a id="a74027296f130de8cbbe7bc543dc4285ea795f8c500afa7f68a28ab76a7ba51bb3"></a></td>
<td class="doxyEnumItemDescription">XOP8 - Prefix to include use of imm byte (= 4 &lt;&lt; OpMapShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XOP9<a id="a74027296f130de8cbbe7bc543dc4285eaad17d87f0e80d893eb6e7a94ec40e7b5"></a></td>
<td class="doxyEnumItemDescription">XOP9 - Prefix to exclude use of imm byte (= 5 &lt;&lt; OpMapShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XOPA<a id="a74027296f130de8cbbe7bc543dc4285eae5decae65076102497629dcadb77bc40"></a></td>
<td class="doxyEnumItemDescription">XOPA - Prefix to encode 0xA in VEX.MMMM of XOP instructions (= 6 &lt;&lt; OpMapShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ThreeDNow<a id="a74027296f130de8cbbe7bc543dc4285eace49aa87c8e2d2f284a9a4ce549a97c3"></a></td>
<td class="doxyEnumItemDescription">ThreeDNow - This indicates that the instruction uses the wacky 0x0F 0x0F prefix for 3DNow! (= 7 &lt;&lt; OpMapShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">T_MAP4<a id="a74027296f130de8cbbe7bc543dc4285ea3e7fd09a84517e5b18bf3a7c80b66ee5"></a></td>
<td class="doxyEnumItemDescription">MAP4, MAP5, MAP6, MAP7 - Prefix after the 0x0F prefix (= 8 &lt;&lt; OpMapShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">T_MAP5<a id="a74027296f130de8cbbe7bc543dc4285ea29f15fe4e4bffa3a29784c8a3647461e"></a></td>
<td class="doxyEnumItemDescription"> (= 9 &lt;&lt; OpMapShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">T_MAP6<a id="a74027296f130de8cbbe7bc543dc4285eada4e10341f02b847bf34cb85ddd0752a"></a></td>
<td class="doxyEnumItemDescription"> (= 10 &lt;&lt; OpMapShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">T_MAP7<a id="a74027296f130de8cbbe7bc543dc4285ea0db7e5872d53dc9cc916c975a0c1756c"></a></td>
<td class="doxyEnumItemDescription"> (= 11 &lt;&lt; OpMapShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">REXShift<a id="a74027296f130de8cbbe7bc543dc4285ea7e60f0fef398121e6fa58c269068ee86"></a></td>
<td class="doxyEnumItemDescription">REX_W - REX prefixes are instruction prefixes used in 64-bit mode (= OpMapShift + 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">REX_W<a id="a74027296f130de8cbbe7bc543dc4285ea12e1b321252ff4c31f9a6b563d8d18b7"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; REXShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmShift<a id="a74027296f130de8cbbe7bc543dc4285ea1dd6b4a0b8a24db0d0c963c4dc149718"></a></td>
<td class="doxyEnumItemDescription"> (= REXShift + 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Imm8<a id="a74027296f130de8cbbe7bc543dc4285eaa17e18db7296e9011b46e04360745760"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; ImmShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Imm8PCRel<a id="a74027296f130de8cbbe7bc543dc4285eab5657248c63984a610736477776dc9d0"></a></td>
<td class="doxyEnumItemDescription"> (= 2 &lt;&lt; ImmShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Imm8Reg<a id="a74027296f130de8cbbe7bc543dc4285ea79b6fe6fc9adb2637eb289c0b1f27613"></a></td>
<td class="doxyEnumItemDescription"> (= 3 &lt;&lt; ImmShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Imm16<a id="a74027296f130de8cbbe7bc543dc4285eac21c0e218a109e1353d239807dd4f3c9"></a></td>
<td class="doxyEnumItemDescription"> (= 4 &lt;&lt; ImmShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Imm16PCRel<a id="a74027296f130de8cbbe7bc543dc4285eaf087623728965c39e2a204de21517bc9"></a></td>
<td class="doxyEnumItemDescription"> (= 5 &lt;&lt; ImmShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Imm32<a id="a74027296f130de8cbbe7bc543dc4285ea407aca9874e804e790d0e8591d6a35da"></a></td>
<td class="doxyEnumItemDescription"> (= 6 &lt;&lt; ImmShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Imm32PCRel<a id="a74027296f130de8cbbe7bc543dc4285ea3561d150e9b34d453f2308200aa6b168"></a></td>
<td class="doxyEnumItemDescription"> (= 7 &lt;&lt; ImmShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Imm32S<a id="a74027296f130de8cbbe7bc543dc4285eade1a8fc99be62e6d15eba758f9ef4e2c"></a></td>
<td class="doxyEnumItemDescription"> (= 8 &lt;&lt; ImmShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Imm64<a id="a74027296f130de8cbbe7bc543dc4285eac5de5ce82d03ee1b2f9c10ddcaecf6bc"></a></td>
<td class="doxyEnumItemDescription"> (= 9 &lt;&lt; ImmShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ImmMask<a id="a74027296f130de8cbbe7bc543dc4285ea372e5bf78ae924c43fcba961e1ebedb8"></a></td>
<td class="doxyEnumItemDescription"> (= 15 &lt;&lt; ImmShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FPTypeShift<a id="a74027296f130de8cbbe7bc543dc4285eadfb89a9f3ab07b7a3d8ddc31a26a3dd2"></a></td>
<td class="doxyEnumItemDescription">FP <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Classification... Zero is non-fp instruction (= ImmShift + 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FPTypeMask<a id="a74027296f130de8cbbe7bc543dc4285ead9c72926f550ad00a4b35ba072ada7fc"></a></td>
<td class="doxyEnumItemDescription"> (= 7 &lt;&lt; FPTypeShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NotFP<a id="a74027296f130de8cbbe7bc543dc4285ea29c03f5fb2c53a32f54eb835fb6dce02"></a></td>
<td class="doxyEnumItemDescription">NotFP - The default, set for instructions that do not use FP registers (= 0 &lt;&lt; FPTypeShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZeroArgFP<a id="a74027296f130de8cbbe7bc543dc4285ea7a3ad350fcf1708671924bff02fa5384"></a></td>
<td class="doxyEnumItemDescription">ZeroArgFP - 0 arg FP instruction which implicitly pushes ST(0), f.e. fld0 (= 1 &lt;&lt; FPTypeShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OneArgFP<a id="a74027296f130de8cbbe7bc543dc4285ea910ed6a9ae2b24b98c26ae96e916f32c"></a></td>
<td class="doxyEnumItemDescription">OneArgFP - 1 arg FP instructions which implicitly read ST(0), such as fst (= 2 &lt;&lt; FPTypeShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OneArgFPRW<a id="a74027296f130de8cbbe7bc543dc4285ea584c8de4beec92e693e6318cd38821fb"></a></td>
<td class="doxyEnumItemDescription">OneArgFPRW - 1 arg FP instruction which implicitly read ST(0) and write a result back to ST(0) (= 3 &lt;&lt; FPTypeShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TwoArgFP<a id="a74027296f130de8cbbe7bc543dc4285eaf7281802655e34d6a26592d416090b1e"></a></td>
<td class="doxyEnumItemDescription">TwoArgFP - 2 arg FP instructions which implicitly read ST(0), and an explicit argument, storing the result to either ST(0) or the implicit argument (= 4 &lt;&lt; FPTypeShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CompareFP<a id="a74027296f130de8cbbe7bc543dc4285ea923b21f9b6b3b2a5ddfb326db177dc8a"></a></td>
<td class="doxyEnumItemDescription">CompareFP - 2 arg FP instructions which implicitly read ST(0) and an explicit argument, but have no destination (= 5 &lt;&lt; FPTypeShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CondMovFP<a id="a74027296f130de8cbbe7bc543dc4285eac8b9cf1b6c894ccfae9058503988b31a"></a></td>
<td class="doxyEnumItemDescription">CondMovFP - "2 operand" floating point conditional move instructions (= 6 &lt;&lt; FPTypeShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SpecialFP<a id="a74027296f130de8cbbe7bc543dc4285ea0c0206ff5a225b969956cfc4ae94c5fc"></a></td>
<td class="doxyEnumItemDescription">SpecialFP - Special instruction forms. Dispatch by opcode explicitly (= 7 &lt;&lt; FPTypeShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LOCKShift<a id="a74027296f130de8cbbe7bc543dc4285ea6e42fdb89aaf53348326c174b0e4db9f"></a></td>
<td class="doxyEnumItemDescription">Lock prefix (= FPTypeShift + 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LOCK<a id="a74027296f130de8cbbe7bc543dc4285ea7d42cf62fdc04de0252fec0978ca907c"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; LOCKShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">REPShift<a id="a74027296f130de8cbbe7bc543dc4285ea8a2a3b052661ac817801a39f956d616b"></a></td>
<td class="doxyEnumItemDescription">REP prefix (= LOCKShift + 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">REP<a id="a74027296f130de8cbbe7bc543dc4285ea732a88e3de2655c55ec4eb6f50958493"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; REPShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSEDomainShift<a id="a74027296f130de8cbbe7bc543dc4285eac84d4b40d46ba3f9eb98a4d65d584670"></a></td>
<td class="doxyEnumItemDescription">Execution domain for SSE instructions (= REPShift + 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EncodingShift<a id="a74027296f130de8cbbe7bc543dc4285ea90da55b0a4cd9683fb92580f75ce28be"></a></td>
<td class="doxyEnumItemDescription">Encoding (= SSEDomainShift + 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EncodingMask<a id="a74027296f130de8cbbe7bc543dc4285ead5bbb0f8b7dfd268d7ca01219b5ec3aa"></a></td>
<td class="doxyEnumItemDescription"> (= 0x3 &lt;&lt; EncodingShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LEGACY<a id="a74027296f130de8cbbe7bc543dc4285eaf345a1192eb67c66842be4eae52e9112"></a></td>
<td class="doxyEnumItemDescription">LEGACY - encoding using REX/REX2 or w/o opcode prefix (= 0 &lt;&lt; EncodingShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VEX<a id="a74027296f130de8cbbe7bc543dc4285ea6702853ec24d45d810d71e321eb9e256"></a></td>
<td class="doxyEnumItemDescription">VEX - encoding using 0xC4/0xC5 (= 1 &lt;&lt; EncodingShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XOP<a id="a74027296f130de8cbbe7bc543dc4285ea6bfb2e744793a1d413a8890afedb2503"></a></td>
<td class="doxyEnumItemDescription">XOP - Opcode prefix used by XOP instructions (= 2 &lt;&lt; EncodingShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EVEX<a id="a74027296f130de8cbbe7bc543dc4285ea1224cf85d21a6023de72b90c2f225241"></a></td>
<td class="doxyEnumItemDescription">EVEX - Specifies that this instruction use EVEX form which provides syntax support up to 32 512-bit register operands and up to 7 16-bit mask operands as well as source operand data swizzling/memory operand conversion, eviction hint, and rounding mode (= 3 &lt;&lt; EncodingShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpcodeShift<a id="a74027296f130de8cbbe7bc543dc4285ea14fa7ec83f8ca0b667a434550f53485d"></a></td>
<td class="doxyEnumItemDescription">Opcode (= EncodingShift + 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VEX_4VShift<a id="a74027296f130de8cbbe7bc543dc4285eac2df24e5732e17154611e7248fa33ad9"></a></td>
<td class="doxyEnumItemDescription">VEX_4V - Used to specify an additional AVX/SSE register (= OpcodeShift + 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VEX_4V<a id="a74027296f130de8cbbe7bc543dc4285ea8a71098306ad6ceef2c5cde6440f81ff"></a></td>
<td class="doxyEnumItemDescription"> (= 1ULL &lt;&lt; VEX_4VShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VEX_LShift<a id="a74027296f130de8cbbe7bc543dc4285ea0450439f5557e6c37638e5676554bbb1"></a></td>
<td class="doxyEnumItemDescription">VEX_L - Stands for a bit in the VEX opcode prefix meaning the current instruction uses 256-bit wide registers (= VEX_4VShift + 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VEX_L<a id="a74027296f130de8cbbe7bc543dc4285ea05c399774dc40c2b03d5ab492e1006c6"></a></td>
<td class="doxyEnumItemDescription"> (= 1ULL &lt;&lt; VEX_LShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EVEX_KShift<a id="a74027296f130de8cbbe7bc543dc4285ea0edbaab95f237fa42aba40ee204b3e49"></a></td>
<td class="doxyEnumItemDescription">EVEX_K - Set if this instruction requires masking (= VEX_LShift + 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EVEX_K<a id="a74027296f130de8cbbe7bc543dc4285eabe6298d9ba729db7fa5c2149de1b21ed"></a></td>
<td class="doxyEnumItemDescription"> (= 1ULL &lt;&lt; EVEX_KShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EVEX_ZShift<a id="a74027296f130de8cbbe7bc543dc4285ea027a1b2415e9055054ac517697eaeb35"></a></td>
<td class="doxyEnumItemDescription">EVEX_Z - Set if this instruction has EVEX.Z field set (= EVEX_KShift + 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EVEX_Z<a id="a74027296f130de8cbbe7bc543dc4285ea11f2ede3e2eee190e2ff483d2e28c8c8"></a></td>
<td class="doxyEnumItemDescription"> (= 1ULL &lt;&lt; EVEX_ZShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EVEX_L2Shift<a id="a74027296f130de8cbbe7bc543dc4285ea747dab5d73be5f1d7a49922a8c2e75d1"></a></td>
<td class="doxyEnumItemDescription">EVEX_L2 - Set if this instruction has EVEX.L' field set (= EVEX_ZShift + 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EVEX_L2<a id="a74027296f130de8cbbe7bc543dc4285ea1b5f21917d273c19ffaa38e025d6b4af"></a></td>
<td class="doxyEnumItemDescription"> (= 1ULL &lt;&lt; EVEX_L2Shift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EVEX_BShift<a id="a74027296f130de8cbbe7bc543dc4285ea1b33181b3deb2cb9cfed9327fbb704f1"></a></td>
<td class="doxyEnumItemDescription">EVEX_B - Set if this instruction has EVEX.B field set (= EVEX_L2Shift + 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EVEX_B<a id="a74027296f130de8cbbe7bc543dc4285ea4a0b5ce031c6c73572f1006babe65b47"></a></td>
<td class="doxyEnumItemDescription"> (= 1ULL &lt;&lt; EVEX_BShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CD8_Scale_Shift<a id="a74027296f130de8cbbe7bc543dc4285eac4ed14b7050985cb87f428cce5588018"></a></td>
<td class="doxyEnumItemDescription">The scaling factor for the AVX512's 8-bit compressed displacement (= EVEX_BShift + 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CD8_Scale_Mask<a id="a74027296f130de8cbbe7bc543dc4285ea7074ee69a8effa9193b243dbffb53218"></a></td>
<td class="doxyEnumItemDescription"> (= 7ULL &lt;&lt; CD8_Scale_Shift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EVEX_RCShift<a id="a74027296f130de8cbbe7bc543dc4285ea9e45d1d698e117b6a61b0bf7d307fc6b"></a></td>
<td class="doxyEnumItemDescription">Explicitly specified rounding control (= CD8_Scale_Shift + 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EVEX_RC<a id="a74027296f130de8cbbe7bc543dc4285ea0c7b9207abbba8cff7c96ce0b4439690"></a></td>
<td class="doxyEnumItemDescription"> (= 1ULL &lt;&lt; EVEX_RCShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoTrackShift<a id="a74027296f130de8cbbe7bc543dc4285ea98eda9ac02b50165fd8eef72fd7abf78"></a></td>
<td class="doxyEnumItemDescription">NOTRACK prefix (= EVEX_RCShift + 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NOTRACK<a id="a74027296f130de8cbbe7bc543dc4285ea3521268aace1e693b0af19b0e4ab54e1"></a></td>
<td class="doxyEnumItemDescription"> (= 1ULL &lt;&lt; NoTrackShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExplicitOpPrefixShift<a id="a74027296f130de8cbbe7bc543dc4285ea006241798e3beda8ebd3b796cec6dd66"></a></td>
<td class="doxyEnumItemDescription">Force REX2/VEX/EVEX encoding (= NoTrackShift + 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExplicitREX2Prefix<a id="a74027296f130de8cbbe7bc543dc4285ea1772a54ebabc4fef5070eca784c5e738"></a></td>
<td class="doxyEnumItemDescription">For instructions that require REX2 prefix even if EGPR is not used (= 1ULL &lt;&lt; ExplicitOpPrefixShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExplicitVEXPrefix<a id="a74027296f130de8cbbe7bc543dc4285ea9baef1fc0f1076e5ec80406f29befc7d"></a></td>
<td class="doxyEnumItemDescription">For instructions that use VEX encoding only when {vex}, {vex2} or {vex3} is present (= 2ULL &lt;&lt; ExplicitOpPrefixShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExplicitEVEXPrefix<a id="a74027296f130de8cbbe7bc543dc4285ea5d69ea5c6fb1fc1895b0097a1ecbca4b"></a></td>
<td class="doxyEnumItemDescription">For instructions that are promoted to EVEX space for EGPR (= 3ULL &lt;&lt; ExplicitOpPrefixShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExplicitOpPrefixMask<a id="a74027296f130de8cbbe7bc543dc4285eadf6510b84ecfe4989b28667e0260d2eb"></a></td>
<td class="doxyEnumItemDescription"> (= 3ULL &lt;&lt; ExplicitOpPrefixShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EVEX_NFShift<a id="a74027296f130de8cbbe7bc543dc4285eafca4571c960aaa8c2cca351f92afe261"></a></td>
<td class="doxyEnumItemDescription">EVEX_NF - Set if this instruction has EVEX.NF field set (= ExplicitOpPrefixShift + 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EVEX_NF<a id="a74027296f130de8cbbe7bc543dc4285eac83eba50896a8cee3fb15a329b94a21d"></a></td>
<td class="doxyEnumItemDescription"> (= 1ULL &lt;&lt; EVEX_NFShift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TwoConditionalOps_Shift<a id="a74027296f130de8cbbe7bc543dc4285ea49ac036a42b24b992c1c700968060abc"></a></td>
<td class="doxyEnumItemDescription"> (= EVEX_NFShift + 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TwoConditionalOps<a id="a74027296f130de8cbbe7bc543dc4285eae372c99c6166a9dd4cabd6e9e25e8b02"></a></td>
<td class="doxyEnumItemDescription"> (= 1ULL &lt;&lt; TwoConditionalOps_Shift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EVEX_UShift<a id="a74027296f130de8cbbe7bc543dc4285eaf3da2fd4b51d038baffcb696beb7f5b8"></a></td>
<td class="doxyEnumItemDescription"> (= TwoConditionalOps_Shift + 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EVEX_U<a id="a74027296f130de8cbbe7bc543dc4285ead138ed6232898ac1d542677dba43717f"></a></td>
<td class="doxyEnumItemDescription"> (= 1ULL &lt;&lt; EVEX_UShift)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>

</div>
</div>

### TOF {#a45cdfdabb3963ec52b198ce5d3aabc84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86II::TOF </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Operand Flag enum.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_NO_FLAG<a id="a45cdfdabb3963ec52b198ce5d3aabc84ab9508856c635578f8aaed9dd83c3f347"></a></td>
<td class="doxyEnumItemDescription">MO_NO_FLAG - No flag for the operand</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOT_ABSOLUTE_ADDRESS<a id="a45cdfdabb3963ec52b198ce5d3aabc84a5364e197f6bba28989699b6040ce96ca"></a></td>
<td class="doxyEnumItemDescription">MO_GOT_ABSOLUTE_ADDRESS - On a symbol operand, this represents a relocation of: SYMBOL_LABEL + [</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_PIC_BASE_OFFSET<a id="a45cdfdabb3963ec52b198ce5d3aabc84adca1e9b1551356bed7c8ef8cb0f1c471"></a></td>
<td class="doxyEnumItemDescription">MO_PIC_BASE_OFFSET - On a symbol operand this indicates that the immediate should get the value of the symbol minus the PIC base label: SYMBOL_LABEL - PICBASELABEL</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOT<a id="a45cdfdabb3963ec52b198ce5d3aabc84a9763861fde2dabda42072fbf46424e4c"></a></td>
<td class="doxyEnumItemDescription">MO_GOT - On a symbol operand this indicates that the immediate is the offset to the GOT entry for the symbol name from the base of the GOT</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOTOFF<a id="a45cdfdabb3963ec52b198ce5d3aabc84a23bf757b117faacb20d4521a6ab42e51"></a></td>
<td class="doxyEnumItemDescription">MO_GOTOFF - On a symbol operand this indicates that the immediate is the offset to the location of the symbol name from the base of the GOT</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOTPCREL<a id="a45cdfdabb3963ec52b198ce5d3aabc84ae39565b585476b7142228e439e80372e"></a></td>
<td class="doxyEnumItemDescription">MO_GOTPCREL - On a symbol operand this indicates that the immediate is offset to the GOT entry for the symbol name from the current code location</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOTPCREL_NORELAX<a id="a45cdfdabb3963ec52b198ce5d3aabc84a115ba6fe8930383c25e51d587e6a333b"></a></td>
<td class="doxyEnumItemDescription">MO_GOTPCREL_NORELAX - Same as MO_GOTPCREL except that R_X86_64_GOTPCREL relocations are guaranteed to be emitted by the integrated assembler instead of the relaxable R_X86_64[_REX]_GOTPCRELX relocations</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_PLT<a id="a45cdfdabb3963ec52b198ce5d3aabc84ab2b21d9c332e616e0a11c3ff76ce0bdf"></a></td>
<td class="doxyEnumItemDescription">MO_PLT - On a symbol operand this indicates that the immediate is offset to the PLT entry of symbol name from the current code location</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TLSGD<a id="a45cdfdabb3963ec52b198ce5d3aabc84ab79eb4639f668e99fa6389282bbc8983"></a></td>
<td class="doxyEnumItemDescription">MO_TLSGD - On a symbol operand this indicates that the immediate is the offset of the GOT entry with the TLS index structure that contains the module number and variable offset for the symbol</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TLSLD<a id="a45cdfdabb3963ec52b198ce5d3aabc84a0bfa33e5861d2bf5088c682b1ee1da85"></a></td>
<td class="doxyEnumItemDescription">MO_TLSLD - On a symbol operand this indicates that the immediate is the offset of the GOT entry with the TLS index for the module that contains the symbol</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TLSLDM<a id="a45cdfdabb3963ec52b198ce5d3aabc84ae0fcbd11eb4098cdb801f889349993c3"></a></td>
<td class="doxyEnumItemDescription">MO_TLSLDM - On a symbol operand this indicates that the immediate is the offset of the GOT entry with the TLS index for the module that contains the symbol</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOTTPOFF<a id="a45cdfdabb3963ec52b198ce5d3aabc84ac7ab3243c491b3b6ff673eaf87335fe5"></a></td>
<td class="doxyEnumItemDescription">MO_GOTTPOFF - On a symbol operand this indicates that the immediate is the offset of the GOT entry with the thread-pointer offset for the symbol</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_INDNTPOFF<a id="a45cdfdabb3963ec52b198ce5d3aabc84a727b000cf3292eb1594ef5ede74025e1"></a></td>
<td class="doxyEnumItemDescription">MO_INDNTPOFF - On a symbol operand this indicates that the immediate is the absolute address of the GOT entry with the negative thread-pointer offset for the symbol</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TPOFF<a id="a45cdfdabb3963ec52b198ce5d3aabc84a74affd0fa65b28e7359abbd4a0d08dca"></a></td>
<td class="doxyEnumItemDescription">MO_TPOFF - On a symbol operand this indicates that the immediate is the thread-pointer offset for the symbol</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_DTPOFF<a id="a45cdfdabb3963ec52b198ce5d3aabc84acd532d5e95fa6d3eccc0a1175abb5efa"></a></td>
<td class="doxyEnumItemDescription">MO_DTPOFF - On a symbol operand this indicates that the immediate is the offset of the GOT entry with the TLS offset of the symbol</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_NTPOFF<a id="a45cdfdabb3963ec52b198ce5d3aabc84a5c1651fb93fe6b8e7f7c1207c3eba33d"></a></td>
<td class="doxyEnumItemDescription">MO_NTPOFF - On a symbol operand this indicates that the immediate is the negative thread-pointer offset for the symbol</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOTNTPOFF<a id="a45cdfdabb3963ec52b198ce5d3aabc84a739692efcf48167fdfc70d040b21670a"></a></td>
<td class="doxyEnumItemDescription">MO_GOTNTPOFF - On a symbol operand this indicates that the immediate is the offset of the GOT entry with the negative thread-pointer offset for the symbol</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_DLLIMPORT<a id="a45cdfdabb3963ec52b198ce5d3aabc84ac7366ddd1a9010fa97b002cad95c3044"></a></td>
<td class="doxyEnumItemDescription">MO_DLLIMPORT - On a symbol operand "FOO", this indicates that the reference is actually to the "__imp_FOO" symbol</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_DARWIN_NONLAZY<a id="a45cdfdabb3963ec52b198ce5d3aabc84a67e336d92dced7f5d76b7c82c0df184b"></a></td>
<td class="doxyEnumItemDescription">MO_DARWIN_NONLAZY - On a symbol operand "FOO", this indicates that the reference is actually to the "FOO$non_lazy_ptr" symbol, which is a non-PIC-base-relative reference to a non-hidden dyld lazy pointer stub</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_DARWIN_NONLAZY_PIC_BASE<a id="a45cdfdabb3963ec52b198ce5d3aabc84a4ce2d9504cacb290d7ff8ac3bfdab373"></a></td>
<td class="doxyEnumItemDescription">MO_DARWIN_NONLAZY_PIC_BASE - On a symbol operand "FOO", this indicates that the reference is actually to "FOO$non_lazy_ptr - PICBASE", which is a PIC-base-relative reference to a non-hidden dyld lazy pointer stub</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TLVP<a id="a45cdfdabb3963ec52b198ce5d3aabc84abc06b946fa50ffaa09a13fdd648b4dbb"></a></td>
<td class="doxyEnumItemDescription">MO_TLVP - On a symbol operand this indicates that the immediate is some TLS offset</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TLVP_PIC_BASE<a id="a45cdfdabb3963ec52b198ce5d3aabc84a75edcbd216129f693a5e2765b457f4c5"></a></td>
<td class="doxyEnumItemDescription">MO_TLVP_PIC_BASE - On a symbol operand this indicates that the immediate is some TLS offset from the picbase</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_SECREL<a id="a45cdfdabb3963ec52b198ce5d3aabc84ac899fad9731b612ab9c84ac157210edc"></a></td>
<td class="doxyEnumItemDescription">MO_SECREL - On a symbol operand this indicates that the immediate is the offset from beginning of section</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_ABS8<a id="a45cdfdabb3963ec52b198ce5d3aabc84aa0e6d252881afe8f7e653d8a1e0f3c4e"></a></td>
<td class="doxyEnumItemDescription">MO_ABS8 - On a symbol operand this indicates that the symbol is known to be an absolute symbol in range [0,128), so we can use the @ABS8 symbol modifier</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_COFFSTUB<a id="a45cdfdabb3963ec52b198ce5d3aabc84a59da9a9089b55f8b8353fda32a609457"></a></td>
<td class="doxyEnumItemDescription">MO_COFFSTUB - On a symbol operand "FOO", this indicates that the reference is actually to the ".refptr.FOO" symbol</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### canUseApxExtendedReg() {#a7bdd2254738314285aa56112068b2407}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86II::canUseApxExtendedReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; Desc)</td>
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



<p>Definition at line 1260 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>References <a href="#a74027296f130de8cbbe7bc543dc4285ead5bbb0f8b7dfd268d7ca01219b5ec3aa">EncodingMask</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea1224cf85d21a6023de72b90c2f225241">EVEX</a>, <a href="#a8da88ee0688eaec097d62d33fff86992">isPseudo</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea3c11b5af543fcb3173f20c9ce3a6856d">OB</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea17bada293123ac2f889d0dece275027d">OpMapMask</a> and <a href="#a74027296f130de8cbbe7bc543dc4285ea6ba65e174dfdcdb111e1aea6b4299b16">TB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a1829580bbe3650b4649ba6094604e0fb">llvm::X86InstrInfo::getRegClass</a>.</p>

</div>
</div>

### getBaseOpcodeFor() {#ac5e00b79e046b7edec72a31f9398ea75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::X86II::getBaseOpcodeFor (uint64_t TSFlags)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the "base" <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> opcode for the specified machine instruction.</p></dd>
</dl>


<p>Definition at line 893 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>Reference <a href="#a74027296f130de8cbbe7bc543dc4285ea14fa7ec83f8ca0b667a434550f53485d">OpcodeShift</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86mccodeemitter-cpp-/x86mccodeemitter/#a326c8dcef7365124098e7573ebe4bd31">anonymous{X86MCCodeEmitter.cpp}::X86MCCodeEmitter::encodeInstruction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6ac81c73fb91e0b2c0c30ae63c671d23">llvm::getFMA3Group</a>.</p>

</div>
</div>

### getMemoryOperandNo() {#ad571a5a542b484586224d3a8df631646}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::X86II::getMemoryOperandNo (uint64_t TSFlags)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>operand # for the first field of the memory operand or -1 if no memory operands. NOTE: This ignores tied operands. If there is a tied register which is duplicated in the <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> (e.g. "EAX = addl EAX, [mem]") it is only counted as one operand.</p></dd>
</dl>


<p>Definition at line 1011 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>References <a href="#a74027296f130de8cbbe7bc543dc4285ea3db5b7855daab5b642f29a4f8743d1a9">AddCCFrm</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea5cd1bb6ca4bb8d7b507c98b61a19ae77">AddRegFrm</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eabe6298d9ba729db7fa5c2149de1b21ed">EVEX_K</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea3ae6529df02b311ddca2a678a0bfaf64">FormMask</a>, <a href="#a3bab7f646d8804292fe0561f29f0c9c0">hasNewDataDest</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eac9be8e1d01f704feb05bd77f9454d9c4">MRM0m</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea594ebf9b65f24cace8a6ed6cc4c188dc">MRM0r</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea0107a9570489e513aeb2c457c1bc4ea7">MRM0X</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea2907aae414f1869eede11975c90ca55e">MRM1m</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eaf4593f298ffcbd9b56cccee8c9b08f4f">MRM1r</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea38b0803128a680769157e24858a8fcec">MRM1X</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eab2b54a959754806bbcc10c7d415869b4">MRM2m</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea50b127ece65d9d64ecff049972c908a7">MRM2r</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea8ffd3410ef34800d44d089d1204ab80a">MRM2X</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eae6c25fb53fc239290474f16af2896017">MRM3m</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eae3f4d0f3323d02cfb646af18c329dcc1">MRM3r</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea8cd6a8196a06c9a17ef03ad258199b56">MRM3X</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea3b73d9e91703e440c64df61ab7cc1997">MRM4m</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eaf2b510dd27c823fbcb97dccc422165dc">MRM4r</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eaa594aa3985a0795387aa7af8947b1e36">MRM4X</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea0420bc5bdfc993b20046f32d50fa0753">MRM5m</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea1ccd60dae6f567df2362f05b10053f2c">MRM5r</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eab383ad975c3b9092939504e4cfe2ae1b">MRM5X</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eaf1e55f460320e2a89ccd653477a81909">MRM6m</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eafe4134fe8da389ed6dbaddff7d04e924">MRM6r</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea8b62cf7e7b7cd325706f22acc7a534d6">MRM6X</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea792ba63c3af3d1eed02519bbc1f883c2">MRM7m</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea48bbc6e11eab7158eca421cdbefb4300">MRM7r</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea7f05c49c45f8901eb86ef2cae982fb87">MRM7X</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea2af966e37189622a1946ce35593a47c1">MRM_C0</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eadf13526f9c198e6d3c44b18fade1cdaa">MRM_C1</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea189edb0057c77e393b6cd48c6a57844f">MRM_C2</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea0b8663d52f6013c3c4c44ee6b3e4c221">MRM_C3</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eaec272046d5dd90472121b5a374c10c13">MRM_C4</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea2a6bc67c716424a75afd98493ce44ca7">MRM_C5</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea1511d6f7eff51b12b38d9f86c132b3a5">MRM_C6</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea20fa7bc944e07c156d78ee9f5ee4c04c">MRM_C7</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea37445de2099407dfca0ec37ff35fe5d5">MRM_C8</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea0125d0cd4af4273d1367a6c462839199">MRM_C9</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea5b915593c95df3a2d84c96327151320d">MRM_CA</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea395918f662de770c178e7f7e544934ba">MRM_CB</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea8fbd1ccdaf11ee40122c547614c78a10">MRM_CC</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea776deddd1d12c851740c6c5a42da0fd0">MRM_CD</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea7a707f8b06bf47ba3bfe19ddd4a4de26">MRM_CE</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea4f3138e38a1ffc21e8e279506282fdc4">MRM_CF</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eaa9cc16d23eb1dbbd266f08d5b72c9d3b">MRM_D0</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea3bcf50adb50e141c86c2207c2665a914">MRM_D1</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea19e5fd422fa45df8331f702e30a3b23d">MRM_D2</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eacf475f7fa1990d9771867a43a5cb85b2">MRM_D3</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eaeaa884b20defdb5c6e68fad5b0292c5e">MRM_D4</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea0463837736d6ed75cc0575e546ad9769">MRM_D5</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea272fc77667a050402a169a058b0a4743">MRM_D6</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea3bd2db5d167f57e231a3cbda8b47328b">MRM_D7</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea7a240d439831945855485d9f668be73d">MRM_D8</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea5502e099f8608464260941952d44efd6">MRM_D9</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eab93028e02236b5c4c5d824a31d68805d">MRM_DA</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea9a3b74dbd24dd89ad5cdca90b5fd868f">MRM_DB</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea16edad2aa61ba14cb331d3741526c0bc">MRM_DC</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea571898bf7abbdc75ca1da8810cde5e0f">MRM_DD</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea248e1fc19cfe5ff9230b7ed6dbf9cd72">MRM_DE</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eaccca1bfb3adb4527dfd581b8d68540a6">MRM_DF</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea3063db197181757a6cd1e36cede73a30">MRM_E0</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea3ab2637fb82524a013ea7c723f8c8f63">MRM_E1</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea75edf85ddb193d591093ce26d7767e4f">MRM_E2</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eabd41e93afa5098b8fbdc4283a4715554">MRM_E3</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eaeeac690144cf1f43a36406182ad141ee">MRM_E4</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea2bad450ca1a94ce69ae415089410766c">MRM_E5</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea252613e02ec044540f82c75f89f36eef">MRM_E6</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea00d46302e861a9c7fd9fecff66f57d43">MRM_E7</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea5d145c66ae6d756f9e9ad6ca5679fc30">MRM_E8</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea2926981e23657a2d17b45aa1e8deeb32">MRM_E9</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eaf0e0ba20c47f32af24167f89de05ea2b">MRM_EA</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea5e1a684c375625f7e37e9fe1e51e8b11">MRM_EB</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea404988f54ad3626aa9083dffa10af417">MRM_EC</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea6d741c96d1bb53548d70ba69e64dd87f">MRM_ED</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eadfb7936fa0afa17e28a206fcdbc56f0c">MRM_EE</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eae82cd5ecc861d5194f989105b9b1a703">MRM_EF</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea936de17cbfd634fac5595a37a533f95f">MRM_F0</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ead6e835cdd73242accfc715f15582d01d">MRM_F1</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ead97baea9720ca2d954726b6740b7809d">MRM_F2</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea1956e66a1c51c45ba25231fcb34a6aaa">MRM_F3</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eabc0b630f1cb9d56814a374cc7c8e70c7">MRM_F4</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea88119e0502acf1a1ec6650f4435f9924">MRM_F5</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea421213d9262af8d681a60931da2ea361">MRM_F6</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea599cbf1248343a8255a40b76010a699f">MRM_F7</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eaaf1c2bcbf66b594cb5ef0710023eaa2a">MRM_F8</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea44d10b054bc67d9b6f1a07b9dc0d18ee">MRM_F9</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea2d11d20093f76b091589d4ef0eaceae4">MRM_FA</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea6f05cf3244440c8e67134b48bc940c36">MRM_FB</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eac2a2c7a6e424ee9aa0011460a4d21a06">MRM_FC</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea8f7673a5f185e5d03e0b82c20e00a482">MRM_FD</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ead28e78f91e2f75cc5ad3d84154e7438b">MRM_FE</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eacb535be85414635d6cbbaa53f67167cd">MRM_FF</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea8de627e0b4d8f49621aaffaf22768ccf">MRMDestMem</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea39ff7e3b87758fceb290c859e5525b92">MRMDestMem4VOp3CC</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eaa9e2dd541cca69dae4eb2b19c12a920a">MRMDestMemCC</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea5a693dd88d31ce75ba797dca591201dc">MRMDestMemFSIB</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eabe42ba2fb12010736a3d91ff51c00f91">MRMDestReg</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea7ea417afb58cc07fa2cfcae87905361c">MRMDestRegCC</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea47511fb3305bca93e2f5a8b5c06cd434">MRMr0</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eabeb3b7e6c5b8fde8b53c453b462f0aae">MRMSrcMem</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea71ff3202ae1a689c037fdde29b3ef3d2">MRMSrcMem4VOp3</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea1ba28eab105e932f7173e256119df199">MRMSrcMemCC</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea912fe30bf2fb6db485900f399a0f6919">MRMSrcMemFSIB</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eabfcb56e85f0547829052a6f31803159b">MRMSrcMemOp4</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eab5eb1a156b44a8263348720cefb0f078">MRMSrcReg</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eaec9007fc8d5e45ac8c8ca70cbc20527c">MRMSrcReg4VOp3</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eac7457861e859e2d45b248505b1ce4d64">MRMSrcRegCC</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eaa5752d9fbf4eaf48924623fb22345d78">MRMSrcRegOp4</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea580f946ce0c61ee2cb39a53181487908">MRMXm</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eaae046536d1fe7157266801c5446581f1">MRMXmCC</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea6d334921612f3043e206d194dc882494">MRMXr</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eaa674367c0dc04c60557b71d6cb873cc0">MRMXrCC</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea3f6747b02d6858c6b951b760c4117325">PrefixByte</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eac147ba1bbcbb4cbda038e4fbd6e5bb31">Pseudo</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea0418cac03c72116432f2161ba81a9477">RawFrm</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea336cd3807e9712aee813c92ab1cbd3c7">RawFrmDst</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea0ebbf8b9bdbf40355e1786a06fe3ebdb">RawFrmDstSrc</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eab246efb880b0f5ea54ddf3879bced8e3">RawFrmImm16</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea682f4bde7ea50ebb5d09cfc9f8283d87">RawFrmImm8</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eaf45ee1f86f45fd23ef8e084b0069aa17">RawFrmMemOffs</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eab93edaca89956bd35deb0830c0a83c32">RawFrmSrc</a> and <a href="#a74027296f130de8cbbe7bc543dc4285ea8a71098306ad6ceef2c5cde6440f81ff">VEX_4V</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86-mc/x86mcinstranalysis/#a1f1d390a3cd743e24f556b00c7afb432">llvm::X86_MC::X86MCInstrAnalysis::evaluateMemoryOperandAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a8c994afd924c660f656f4deb351a1e96">llvm::X86InstrInfo::getAddrModeFromMemoryOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86avoidstoreforwardingblocks-cpp/#a692ef5b00648c4f2fc1fc4bf29504a5e">getAddrOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a279395a00a782f7e3d6141bc3328a249">llvm::X86::getFirstAddrOperandIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a1562d024e0f385ec92982cd3493001d7">getJumpTableIndexFromAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a4870646ffc5b5a7d4425edd55d6f93de">llvm::X86InstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-mc/x86mcinstranalysis/#a32469aadc2b1ab4993d6656074d0fa91">llvm::X86_MC::X86MCInstrAnalysis::getMemoryOperandRelocationOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp/#a37e080a7316f05f6394fcd7747d13846">isRIPRelative</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instprintercommon/#a9e01cbc62f1eb3379712051ded643013">llvm::X86InstPrinterCommon::printInstFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp/#adbcc7553355eafc7694a35f45b614e5b">usedAsAddr</a>.</p>

</div>
</div>

### getOperandBias() {#af0baab1b1dfea49cbffeb8727aebd429}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86II::getOperandBias (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; Desc)</td>
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

<p>Compute whether all of the def operands are repeated in the uses and therefore should be skipped.</p>


<p>This determines the start of the unique operand list. We need to determine if all of the defs have a corresponding tied operand in the uses. Unfortunately, the tied operand information is encoded in the uses not the defs so we have to use some heuristics to find which operands to query.</p>


<p>Definition at line 968 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#aaa8eb58fd1b8466eb64a43df890cb8c1ae01b27a05209c02ca1bdb5a6033731fb">llvm::MCOI::TIED_TO</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86mccodeemitter-cpp-/x86mccodeemitter/#a380773ba72f8745ffdea347917d48a95">anonymous{X86MCCodeEmitter.cpp}::X86MCCodeEmitter::emitPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mccodeemitter-cpp-/x86mccodeemitter/#a326c8dcef7365124098e7573ebe4bd31">anonymous{X86MCCodeEmitter.cpp}::X86MCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-mc/x86mcinstranalysis/#a1f1d390a3cd743e24f556b00c7afb432">llvm::X86_MC::X86MCInstrAnalysis::evaluateMemoryOperandAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a8c994afd924c660f656f4deb351a1e96">llvm::X86InstrInfo::getAddrModeFromMemoryOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86avoidstoreforwardingblocks-cpp/#a692ef5b00648c4f2fc1fc4bf29504a5e">getAddrOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a279395a00a782f7e3d6141bc3328a249">llvm::X86::getFirstAddrOperandIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a1562d024e0f385ec92982cd3493001d7">getJumpTableIndexFromAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a4870646ffc5b5a7d4425edd55d6f93de">llvm::X86InstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/x86-mc/x86mcinstranalysis/#a32469aadc2b1ab4993d6656074d0fa91">llvm::X86_MC::X86MCInstrAnalysis::getMemoryOperandRelocationOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp/#a3682f9c28dce92228badc39d606d2664">isPCRel32Branch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp/#a37e080a7316f05f6394fcd7747d13846">isRIPRelative</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instprintercommon/#a9e01cbc62f1eb3379712051ded643013">llvm::X86InstPrinterCommon::printInstFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp/#adbcc7553355eafc7694a35f45b614e5b">usedAsAddr</a>.</p>

</div>
</div>

### getSizeOfImm() {#ab80f6be5c11059e150772326c6a5e293}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86II::getSizeOfImm (uint64_t TSFlags)</td>
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

<p>Decode the "size of immediate" field from the TSFlags field of the specified instruction.</p>

<p>Definition at line 901 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>References <a href="#a74027296f130de8cbbe7bc543dc4285eac21c0e218a109e1353d239807dd4f3c9">Imm16</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eaf087623728965c39e2a204de21517bc9">Imm16PCRel</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea407aca9874e804e790d0e8591d6a35da">Imm32</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea3561d150e9b34d453f2308200aa6b168">Imm32PCRel</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eade1a8fc99be62e6d15eba758f9ef4e2c">Imm32S</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eac5de5ce82d03ee1b2f9c10ddcaecf6bc">Imm64</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eaa17e18db7296e9011b46e04360745760">Imm8</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eab5657248c63984a610736477776dc9d0">Imm8PCRel</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea79b6fe6fc9adb2637eb289c0b1f27613">Imm8Reg</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea372e5bf78ae924c43fcba961e1ebedb8">ImmMask</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86mccodeemitter-cpp-/x86mccodeemitter/#a326c8dcef7365124098e7573ebe4bd31">anonymous{X86MCCodeEmitter.cpp}::X86MCCodeEmitter::encodeInstruction</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp/#a2f19df74000cc1d12eb853e57c867afb">getImmFixupKind</a>.</p>

</div>
</div>

### hasImm() {#a3b8bc7d5e78603d3c61a536fd4217eba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86II::hasImm (uint64_t TSFlags)</td>
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



<p>Definition at line 897 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>Reference <a href="#a74027296f130de8cbbe7bc543dc4285ea372e5bf78ae924c43fcba961e1ebedb8">ImmMask</a>.</p>

</div>
</div>

### hasNewDataDest() {#a3bab7f646d8804292fe0561f29f0c9c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86II::hasNewDataDest (uint64_t TSFlags)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the instruction has a NDD (new data destination).</p></dd>
</dl>


<p>Definition at line 1001 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>References <a href="#a74027296f130de8cbbe7bc543dc4285ea4a0b5ce031c6c73572f1006babe65b47">EVEX_B</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea17bada293123ac2f889d0dece275027d">OpMapMask</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea3e7fd09a84517e5b18bf3a7c80b66ee5">T_MAP4</a> and <a href="#a74027296f130de8cbbe7bc543dc4285ea8a71098306ad6ceef2c5cde6440f81ff">VEX_4V</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86compressevex-cpp/#a9d982c894cfe302bb2d90c1f5d4c1c37">CompressEVEXImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mccodeemitter-cpp-/x86mccodeemitter/#a326c8dcef7365124098e7573ebe4bd31">anonymous{X86MCCodeEmitter.cpp}::X86MCCodeEmitter::encodeInstruction</a> and <a href="#ad571a5a542b484586224d3a8df631646">getMemoryOperandNo</a>.</p>

</div>
</div>

### is32ExtendedReg() {#a3ccb37bba2965d7b115cbcbbb196b088}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86II::is32ExtendedReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the MemoryOperand is a 32 extended (zmm16 or higher) registers, e.g. zmm21, etc.</p></dd>
</dl>


<p>Definition at line 1302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### isApxExtendedReg() {#aed3a5dba6b8da462e693c4965ec7c911}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86II::isApxExtendedReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <span class="doxyComputerOutput">Reg</span> is an apx extended register.</p></dd>
</dl>


<p>Definition at line 1186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#ae63be8b012497f28a863be8cfa255a87">isX86_64ExtendedReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mccodeemitter-cpp-/x86opcodeprefixhelper/#a245a9ad332271056de5ccb99557da2b4">anonymous{X86MCCodeEmitter.cpp}::X86OpcodePrefixHelper::setBB2</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mccodeemitter-cpp-/x86opcodeprefixhelper/#ae615af7d199d5d5580d40d8ca084195d">anonymous{X86MCCodeEmitter.cpp}::X86OpcodePrefixHelper::setV2</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mccodeemitter-cpp-/x86opcodeprefixhelper/#a9ad671bf99f1134de7f39aabfc137704">anonymous{X86MCCodeEmitter.cpp}::X86OpcodePrefixHelper::setX</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mccodeemitter-cpp-/x86opcodeprefixhelper/#a577909faac8e8a04c43b5207dd236ab5">anonymous{X86MCCodeEmitter.cpp}::X86OpcodePrefixHelper::setXX2</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86compressevex-cpp/#afdc3f396ced2d97e9feb5f89e6733457">usesExtendedRegister</a>.</p>

</div>
</div>

### isImmPCRel() {#aa0654eb4aaf0d4dae00f58a0b176c114}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86II::isImmPCRel (uint64_t TSFlags)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the immediate of the specified instruction's TSFlags indicates that it is pc relative.</p></dd>
</dl>


<p>Definition at line 923 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>References <a href="#a74027296f130de8cbbe7bc543dc4285eac21c0e218a109e1353d239807dd4f3c9">Imm16</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eaf087623728965c39e2a204de21517bc9">Imm16PCRel</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea407aca9874e804e790d0e8591d6a35da">Imm32</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea3561d150e9b34d453f2308200aa6b168">Imm32PCRel</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eade1a8fc99be62e6d15eba758f9ef4e2c">Imm32S</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eac5de5ce82d03ee1b2f9c10ddcaecf6bc">Imm64</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eaa17e18db7296e9011b46e04360745760">Imm8</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eab5657248c63984a610736477776dc9d0">Imm8PCRel</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea79b6fe6fc9adb2637eb289c0b1f27613">Imm8Reg</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea372e5bf78ae924c43fcba961e1ebedb8">ImmMask</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp/#a2f19df74000cc1d12eb853e57c867afb">getImmFixupKind</a>.</p>

</div>
</div>

### isImmSigned() {#afe8aadc3acd1babeaaa102408ac9973b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86II::isImmSigned (uint64_t TSFlags)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the immediate of the specified instruction's TSFlags indicates that it is signed.</p></dd>
</dl>


<p>Definition at line 943 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>References <a href="#a74027296f130de8cbbe7bc543dc4285eac21c0e218a109e1353d239807dd4f3c9">Imm16</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eaf087623728965c39e2a204de21517bc9">Imm16PCRel</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea407aca9874e804e790d0e8591d6a35da">Imm32</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea3561d150e9b34d453f2308200aa6b168">Imm32PCRel</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eade1a8fc99be62e6d15eba758f9ef4e2c">Imm32S</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eac5de5ce82d03ee1b2f9c10ddcaecf6bc">Imm64</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eaa17e18db7296e9011b46e04360745760">Imm8</a>, <a href="#a74027296f130de8cbbe7bc543dc4285eab5657248c63984a610736477776dc9d0">Imm8PCRel</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea79b6fe6fc9adb2637eb289c0b1f27613">Imm8Reg</a>, <a href="#a74027296f130de8cbbe7bc543dc4285ea372e5bf78ae924c43fcba961e1ebedb8">ImmMask</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp/#a2f19df74000cc1d12eb853e57c867afb">getImmFixupKind</a>.</p>

</div>
</div>

### isKMasked() {#ac5feea989366c35ad4b85148a305f116}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86II::isKMasked (uint64_t TSFlags)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this is a masked instruction.</p></dd>
</dl>


<p>Definition at line 1314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>Reference <a href="#a74027296f130de8cbbe7bc543dc4285eabe6298d9ba729db7fa5c2149de1b21ed">EVEX_K</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a2c3415ef8f310c64d20ff8772825e0b5">llvm::X86InstrInfo::findCommutedOpIndices</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a5272a0a447e8c15711a3b35d7b0d90a9">getSrcIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#ad8060c87b20d86f00a914d4b35539eed">getThreeSrcCommuteCase</a>, <a href="#a07b28b4355ad8daca32f6087453982a0">isKMergeMasked</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#abadd3db62d81d4ecaa7630291dc36573">printDstRegisterName</a>.</p>

</div>
</div>

### isKMergeMasked() {#a07b28b4355ad8daca32f6087453982a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86II::isKMergeMasked (uint64_t TSFlags)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this is a merge masked instruction.</p></dd>
</dl>


<p>Definition at line 1319 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>References <a href="#a74027296f130de8cbbe7bc543dc4285ea11f2ede3e2eee190e2ff483d2e28c8c8">EVEX_Z</a> and <a href="#ac5feea989366c35ad4b85148a305f116">isKMasked</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a2c3415ef8f310c64d20ff8772825e0b5">llvm::X86InstrInfo::findCommutedOpIndices</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a5272a0a447e8c15711a3b35d7b0d90a9">getSrcIdx</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#abadd3db62d81d4ecaa7630291dc36573">printDstRegisterName</a>.</p>

</div>
</div>

### isPrefix() {#a2b188aa442133e25413fa69e3a0223b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86II::isPrefix (uint64_t TSFlags)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the instruction with given opcode is a prefix.</p></dd>
</dl>


<p>Definition at line 882 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>References <a href="#a74027296f130de8cbbe7bc543dc4285ea3ae6529df02b311ddca2a678a0bfaf64">FormMask</a> and <a href="#a74027296f130de8cbbe7bc543dc4285ea3f6747b02d6858c6b951b760c4117325">PrefixByte</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp/#ad30c0dba88d2e5f9cc2a9e74fd1e1078">isPrefix</a>.</p>

</div>
</div>

### isPseudo() {#a8da88ee0688eaec097d62d33fff86992}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86II::isPseudo (uint64_t TSFlags)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the instruction with given opcode is a pseudo.</p></dd>
</dl>


<p>Definition at line 887 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>References <a href="#a74027296f130de8cbbe7bc543dc4285ea3ae6529df02b311ddca2a678a0bfaf64">FormMask</a> and <a href="#a74027296f130de8cbbe7bc543dc4285eac147ba1bbcbb4cbda038e4fbd6e5bb31">Pseudo</a>.</p>


<p>Referenced by <a href="#a7bdd2254738314285aa56112068b2407">canUseApxExtendedReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mccodeemitter-cpp-/x86mccodeemitter/#a380773ba72f8745ffdea347917d48a95">anonymous{X86MCCodeEmitter.cpp}::X86MCCodeEmitter::emitPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mccodeemitter-cpp-/x86mccodeemitter/#a326c8dcef7365124098e7573ebe4bd31">anonymous{X86MCCodeEmitter.cpp}::X86MCCodeEmitter::encodeInstruction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a279395a00a782f7e3d6141bc3328a249">llvm::X86::getFirstAddrOperandIdx</a>.</p>

</div>
</div>

### isX86\_64ExtendedReg() {#ae63be8b012497f28a863be8cfa255a87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86II::isX86_64ExtendedReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> is a x86-64 extended (r8 or higher) register, e.g. r8, xmm8, xmm13, etc.</p></dd>
</dl>


<p>Definition at line 1193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>References <a href="#aed3a5dba6b8da462e693c4965ec7c911">isApxExtendedReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/x86/#aade8574cba756ffdc426344718ada414">llvm::X86::optimizeInstFromVEX3ToVEX2</a>.</p>

</div>
</div>

### isX86\_64NonExtLowByteReg() {#a5f97093f1f56f60672b73a8285ce9c96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86II::isX86_64NonExtLowByteReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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



<p>Definition at line 1308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### isXMMReg() {#aa9fd738474c4c822202e6d73a9509904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86II::isXMMReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the register is a XMM.</p></dd>
</dl>


<p>Definition at line 1159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp/#a185fac36097d2118ff0b494a0e6bb560">getVectorRegSize</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a8cf7c7a8670a44172ba5543a081d8a61">llvm::X86Operand::isMem32_RC128X</a> and <a href="/web-llvm/docs/api/structs/llvm/x86operand/#af696541557d6fc4e1c83ad89a588c338">llvm::X86Operand::isMem64_RC128X</a>.</p>

</div>
</div>

### isYMMReg() {#acc7da017f8afea15479e578fcc10a2e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86II::isYMMReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the register is a YMM.</p></dd>
</dl>


<p>Definition at line 1169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp/#a185fac36097d2118ff0b494a0e6bb560">getVectorRegSize</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a4dd65473993a62586ddcab7dde6b26a4">llvm::X86Operand::isMem32_RC256X</a> and <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a0ad279fcfec0f9227f547633afd2de7e">llvm::X86Operand::isMem64_RC256X</a>.</p>

</div>
</div>

### isZMMReg() {#a301d6276fae739378e945ebbe0c8dd9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86II::isZMMReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the register is a ZMM.</p></dd>
</dl>


<p>Definition at line 1179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-cpp/#a185fac36097d2118ff0b494a0e6bb560">getVectorRegSize</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a5c7738b6d6730bbc74899674260e826e">llvm::X86Operand::isMem32_RC512</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a8ee7a3ded94c63083e2627cdd7388013">llvm::X86Operand::isMem64_RC512</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86compressevex-cpp/#afdc3f396ced2d97e9feb5f89e6733457">usesExtendedRegister</a>.</p>

</div>
</div>

### needSIB() {#ab9df9a1addf48641771cbae1137661aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86II::needSIB (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> BaseReg, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> IndexReg, bool In64BitMode)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the intruction needs a SIB.</p></dd>
</dl>


<p>Definition at line 1324 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcregister/#af8403cc977c65b910e618ebcb6a12c32">llvm::MCRegister::id</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
