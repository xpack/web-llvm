---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/x86disassembler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `X86Disassembler` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::X86Disassembler { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/x86disassembler/operandspecifier">OperandSpecifier</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The specification for how to extract and interpret one operand. <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/operandspecifier/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/x86disassembler/instructionspecifier">InstructionSpecifier</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The specification for how to extract and interpret a full instruction and its operands. <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/instructionspecifier/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The x86 internal instruction, which is produced by the decoder. <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">uint16_t <a href="#a48739e7e428e4607c5699d7417498956">InstrUID</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">attributeBits { <a href="#a6417cabaf5514433877aa0592985e761">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">InstructionContext { <a href="#a9624616e08932c8bf5b3a987e939f968">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OpcodeType { <a href="#aaab12f79117070dc035099f1daed2b8e">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ModRMDecisionType { <a href="#ac063173220632f668a30cc362d88c849">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OperandEncoding { <a href="#ab16c22bdc7e0ea6d8639f8ebf70a8956">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OperandType { <a href="#aab366fca16308a4d6a59305aec58b6f8">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DisassemblerMode { <a href="#a2770a7b5455f322436ac3d7723979ab8">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decoding mode for the Intel disassembler. <a href="#a2770a7b5455f322436ac3d7723979ab8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">EABase { <a href="#a0dd85da44c5f9e9cb2bc1901a2e40d2c">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All possible values of the base field for effective-address computations, a.k.a. <a href="#a0dd85da44c5f9e9cb2bc1901a2e40d2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">SIBIndex { <a href="#ae905569d5e7d96d9e1f4150c289660b6">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All possible values of the SIB index field. <a href="#ae905569d5e7d96d9e1f4150c289660b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">SIBBase { <a href="#aaefe05b2150554a84b796b4bca71f706">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All possible values of the SIB base field. <a href="#aaefe05b2150554a84b796b4bca71f706">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">EADisplacement { <a href="#ae01fc319973355e6cd69eb9224ce6caf">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Possible displacement types for effective-address computations. <a href="#ae01fc319973355e6cd69eb9224ce6caf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Reg { <a href="#a1e59b79e1d09149912cad9c0ef2809ad">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All possible values of the reg field in the ModR/M byte. <a href="#a1e59b79e1d09149912cad9c0ef2809ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">SegmentOverride { <a href="#afcacc827be10451e9900946844350afe">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All possible segment overrides. <a href="#afcacc827be10451e9900946844350afe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">VEXLeadingOpcodeByte { <a href="#a1394fd7f59cd599a2a6adda29e6778c1">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Possible values for the VEX.m-mmmm field. <a href="#a1394fd7f59cd599a2a6adda29e6778c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">XOPMapSelect { <a href="#aed5529bc9c207a9ecdc6a2a93fe0ab97">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">VEXPrefixCode { <a href="#addd2d05002ebd2dc83a9d353a3d0231a">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Possible values for the VEX.pp/EVEX.pp field. <a href="#addd2d05002ebd2dc83a9d353a3d0231a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">VectorExtensionType { <a href="#a88730ad84a956ffad5205b3b79a93b78">...</a> }</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaffc3a446bebe193a08a84998cc1362d">X86_MAX_OPERANDS</a> = 6</td>
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

### InstrUID {#a48739e7e428e4607c5699d7417498956}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef uint16_t llvm::X86Disassembler::InstrUID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### attributeBits {#a6417cabaf5514433877aa0592985e761}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86Disassembler::attributeBits </td>
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
<td class="doxyEnumItemName">ATTR_NONE<a id="a6417cabaf5514433877aa0592985e761a521817f03b22ca3e9b694bbeb40ffc13"></a></td>
<td class="doxyEnumItemDescription"> (= 0x00)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_64BIT<a id="a6417cabaf5514433877aa0592985e761a2cc98ac6cfff9525a9c517d58203abee"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1 &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_XS<a id="a6417cabaf5514433877aa0592985e761adbeb757d43fe751b0f290a3d49a549a2"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1 &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_XD<a id="a6417cabaf5514433877aa0592985e761ae7eba06f9636876052509d9c5f518daf"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1 &lt;&lt; 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_REXW<a id="a6417cabaf5514433877aa0592985e761ac4f7746f0e0278f882f6496bc332a0a7"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1 &lt;&lt; 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_OPSIZE<a id="a6417cabaf5514433877aa0592985e761a05118adcbdc4f3ebee3866375280e240"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1 &lt;&lt; 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_ADSIZE<a id="a6417cabaf5514433877aa0592985e761ae76db82f3abbd861fe788a368d902e43"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1 &lt;&lt; 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_VEX<a id="a6417cabaf5514433877aa0592985e761aad13de5e7b76aca8e7d8dc6f737087ab"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1 &lt;&lt; 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_VEXL<a id="a6417cabaf5514433877aa0592985e761ae9c5b2d19120317db54112e3d0af53f0"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1 &lt;&lt; 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_EVEX<a id="a6417cabaf5514433877aa0592985e761a68d1c0efd3c5566345791f2e44a43874"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1 &lt;&lt; 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_EVEXL2<a id="a6417cabaf5514433877aa0592985e761a95b4afd8b259682602966fa5c8206bbf"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1 &lt;&lt; 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_EVEXK<a id="a6417cabaf5514433877aa0592985e761ab0cfe5f1f7bae377cd3801519ca647a6"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1 &lt;&lt; 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_EVEXKZ<a id="a6417cabaf5514433877aa0592985e761a195fabd1f33778497ed05370718fe0d9"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1 &lt;&lt; 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_EVEXB<a id="a6417cabaf5514433877aa0592985e761abb2f873faafb26778dd88f53a8b0e3a3"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1 &lt;&lt; 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_REX2<a id="a6417cabaf5514433877aa0592985e761a3fb7e2387d06f224bc1910dd8f34e5a3"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1 &lt;&lt; 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_EVEXNF<a id="a6417cabaf5514433877aa0592985e761ac4e663a6ca5c2fef0a020c592995391e"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1 &lt;&lt; 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_EVEXU<a id="a6417cabaf5514433877aa0592985e761a46799a13899b611916f13c2d157f6855"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1 &lt;&lt; 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ATTR_max<a id="a6417cabaf5514433877aa0592985e761aa88fe147c591ed4a45026a8353fe758b"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1 &lt;&lt; 16)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### DisassemblerMode {#a2770a7b5455f322436ac3d7723979ab8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86Disassembler::DisassemblerMode </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Decoding mode for the Intel disassembler.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MODE_16BIT<a id="a2770a7b5455f322436ac3d7723979ab8a92735b4f723ce305b1b618c0bafae971"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MODE_32BIT<a id="a2770a7b5455f322436ac3d7723979ab8ae4207458cc887c4e1b45709cc318113e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MODE_64BIT<a id="a2770a7b5455f322436ac3d7723979ab8a0a0a664b4e04945bb7338a796271eaf7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>16-bit, 32-bit, and 64-bit mode are supported, and represent real mode, IA-32e, and IA-32e in 64-bit mode, respectively.</p>


<p>Definition at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### EABase {#a0dd85da44c5f9e9cb2bc1901a2e40d2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86Disassembler::EABase </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All possible values of the base field for effective-address computations, a.k.a.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EA_BASE_NONE<a id="a0dd85da44c5f9e9cb2bc1901a2e40d2cab34ee88b4e6eef0b907540f0fcbe7b5d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EA_max<a id="a0dd85da44c5f9e9cb2bc1901a2e40d2ca62eef77c4757a6b186fa4114415204c7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>the Mod and R/M fields of the ModR/M byte. We distinguish between bases (EA_BASE_*) and registers that just happen to be referred to when Mod == 0b11 (EA_REG_*).</p>


<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### EADisplacement {#ae01fc319973355e6cd69eb9224ce6caf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86Disassembler::EADisplacement </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Possible displacement types for effective-address computations.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EA_DISP_NONE<a id="ae01fc319973355e6cd69eb9224ce6cafa6a4d6cb5da191b70c6888d28b52bb179"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EA_DISP_8<a id="ae01fc319973355e6cd69eb9224ce6cafa896daef79c9641dee49c81683b68ea92"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EA_DISP_16<a id="ae01fc319973355e6cd69eb9224ce6cafac5a5b3bdf65b29024eb8126150657538"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EA_DISP_32<a id="ae01fc319973355e6cd69eb9224ce6cafa05caf1ba85c551141bdd17f67c404812"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 617 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### InstructionContext {#a9624616e08932c8bf5b3a987e939f968}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86Disassembler::InstructionContext </td>
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
<td class="doxyEnumItemName">IC_max<a id="a9624616e08932c8bf5b3a987e939f968ad6bbe299fbc3aec5de4c8045e0d27e19"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### ModRMDecisionType {#ac063173220632f668a30cc362d88c849}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86Disassembler::ModRMDecisionType </td>
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
<td class="doxyEnumItemName">MODRM_max<a id="ac063173220632f668a30cc362d88c849af309372802ea84a6b162983f4d5dab66"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### OpcodeType {#aaab12f79117070dc035099f1daed2b8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86Disassembler::OpcodeType </td>
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
<td class="doxyEnumItemName">ONEBYTE<a id="aaab12f79117070dc035099f1daed2b8eaf9d21d7b85f3134f59025667d1a87901"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TWOBYTE<a id="aaab12f79117070dc035099f1daed2b8ea4a57a751955088217dbec4ddde73a0d9"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">THREEBYTE_38<a id="aaab12f79117070dc035099f1daed2b8ea326a3b9aff421046aeed72135f644612"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">THREEBYTE_3A<a id="aaab12f79117070dc035099f1daed2b8eaee435c44f7c8fb5577d8e247d86fe47f"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XOP8_MAP<a id="aaab12f79117070dc035099f1daed2b8eae2591c94eee2f2450337a7f76f0c4f35"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XOP9_MAP<a id="aaab12f79117070dc035099f1daed2b8eaaf4fbb23ce6ffcb23876627445eb119c"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XOPA_MAP<a id="aaab12f79117070dc035099f1daed2b8ea3fc124ba62a6f907eaa9253a4b0aa183"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">THREEDNOW_MAP<a id="aaab12f79117070dc035099f1daed2b8ea0275a2adeb2bee7333ebddd77bc2dbe2"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MAP4<a id="aaab12f79117070dc035099f1daed2b8ea7c46af55213eba7d7104354bf073cbbe"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MAP5<a id="aaab12f79117070dc035099f1daed2b8ea6934a4600c92849aec9b177ba29b95f7"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MAP6<a id="aaab12f79117070dc035099f1daed2b8ea3168b0000bb711c5f33b0bc976272952"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MAP7<a id="aaab12f79117070dc035099f1daed2b8ea632479f320c04b5fc5d78d25d507b434"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### OperandEncoding {#ab16c22bdc7e0ea6d8639f8ebf70a8956}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86Disassembler::OperandEncoding </td>
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
<td class="doxyEnumItemName">ENCODING_max<a id="ab16c22bdc7e0ea6d8639f8ebf70a8956abdc5acd0d244c547f4c73f03222721db"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### OperandType {#aab366fca16308a4d6a59305aec58b6f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86Disassembler::OperandType </td>
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
<td class="doxyEnumItemName">TYPE_max<a id="aab366fca16308a4d6a59305aec58b6f8ab9b5f41fe027079c05bfeecc4585bb1a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### Reg {#a1e59b79e1d09149912cad9c0ef2809ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86Disassembler::Reg </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All possible values of the reg field in the ModR/M byte.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MODRM_REG_max<a id="a1e59b79e1d09149912cad9c0ef2809ada54dc94c727dea7fb0223f6d3ff336d9b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 621 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### SegmentOverride {#afcacc827be10451e9900946844350afe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86Disassembler::SegmentOverride </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All possible segment overrides.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SEG_OVERRIDE_NONE<a id="afcacc827be10451e9900946844350afea478c6c27632ee99e02062c6b078596ab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SEG_OVERRIDE_CS<a id="afcacc827be10451e9900946844350afead5a5b066d5cf1c312135a98292843022"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SEG_OVERRIDE_SS<a id="afcacc827be10451e9900946844350afea5fa4e0d53239f1adf986ae2b0e51293c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SEG_OVERRIDE_DS<a id="afcacc827be10451e9900946844350afeaff8f03b6101c7edf8dbcd94da14eb929"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SEG_OVERRIDE_ES<a id="afcacc827be10451e9900946844350afeaf13dc03e7f4ce19d67915d5f718c3cc1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SEG_OVERRIDE_FS<a id="afcacc827be10451e9900946844350afea55a575ffdef756ea97c0b82f93a27035"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SEG_OVERRIDE_GS<a id="afcacc827be10451e9900946844350afeab788e7576e087f48bad3f1bc41b37bf9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SEG_OVERRIDE_max<a id="afcacc827be10451e9900946844350afea3bd55b352ef9e15d7d40e21fbe3fdb39"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### SIBBase {#aaefe05b2150554a84b796b4bca71f706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86Disassembler::SIBBase </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All possible values of the SIB base field.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SIB_BASE_NONE<a id="aaefe05b2150554a84b796b4bca71f706a7cea6ea4847ad1bfdcfa78ec0f2d4a6c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SIB_BASE_max<a id="aaefe05b2150554a84b796b4bca71f706acd2e3e7468fc75a1e5e1d8ba6c8e84b5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### SIBIndex {#ae905569d5e7d96d9e1f4150c289660b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86Disassembler::SIBIndex </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All possible values of the SIB index field.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SIB_INDEX_NONE<a id="ae905569d5e7d96d9e1f4150c289660b6a6f17dadc7b55217d06e4a20efeb747ee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SIB_INDEX_max<a id="ae905569d5e7d96d9e1f4150c289660b6ae580648edefbbcb4c5e015ddad4cca6b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>borrows entries from ALL_EA_BASES with the special case that sib is synonymous with NONE. Vector SIB: index can be XMM or YMM.</p>


<p>Definition at line 592 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### VectorExtensionType {#a88730ad84a956ffad5205b3b79a93b78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86Disassembler::VectorExtensionType </td>
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
<td class="doxyEnumItemName">TYPE_NO_VEX_XOP<a id="a88730ad84a956ffad5205b3b79a93b78ab831cfec071b3ebe687235b3ef5b96f9"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_VEX_2B<a id="a88730ad84a956ffad5205b3b79a93b78a594bf13c39d9785f9603aad71559006b"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_VEX_3B<a id="a88730ad84a956ffad5205b3b79a93b78ad63c6ef1f04c8aa18d74c2700d1f559e"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_EVEX<a id="a88730ad84a956ffad5205b3b79a93b78afd8e9c8ad31d8d77fbde6adfa808f8d4"></a></td>
<td class="doxyEnumItemDescription"> (= 0x3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TYPE_XOP<a id="a88730ad84a956ffad5205b3b79a93b78a526cd04f63e6634ccad1e962577e59b8"></a></td>
<td class="doxyEnumItemDescription"> (= 0x4)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### VEXLeadingOpcodeByte {#a1394fd7f59cd599a2a6adda29e6778c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86Disassembler::VEXLeadingOpcodeByte </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Possible values for the VEX.m-mmmm field.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VEX_LOB_0F<a id="a1394fd7f59cd599a2a6adda29e6778c1a93f5f8f993e9a66fc0aec7fd5ea2cef3"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VEX_LOB_0F38<a id="a1394fd7f59cd599a2a6adda29e6778c1ad65b6581c00cd9c364212601abce3425"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VEX_LOB_0F3A<a id="a1394fd7f59cd599a2a6adda29e6778c1ab15ddc5f81ae3bda7a9a37f3ba0f1ad0"></a></td>
<td class="doxyEnumItemDescription"> (= 0x3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VEX_LOB_MAP4<a id="a1394fd7f59cd599a2a6adda29e6778c1a3be852f1723249739425f72103b16cb8"></a></td>
<td class="doxyEnumItemDescription"> (= 0x4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VEX_LOB_MAP5<a id="a1394fd7f59cd599a2a6adda29e6778c1aa89162786f0b4410592313133ff4abe8"></a></td>
<td class="doxyEnumItemDescription"> (= 0x5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VEX_LOB_MAP6<a id="a1394fd7f59cd599a2a6adda29e6778c1a43eeebcc793cebba4c0af0aaa0061075"></a></td>
<td class="doxyEnumItemDescription"> (= 0x6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VEX_LOB_MAP7<a id="a1394fd7f59cd599a2a6adda29e6778c1aba0ff20e0515edd91a78fee4a63c3ec4"></a></td>
<td class="doxyEnumItemDescription"> (= 0x7)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 642 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### VEXPrefixCode {#addd2d05002ebd2dc83a9d353a3d0231a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86Disassembler::VEXPrefixCode </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Possible values for the VEX.pp/EVEX.pp field.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VEX_PREFIX_NONE<a id="addd2d05002ebd2dc83a9d353a3d0231aa543616853caed3a04d81fc0790f9c9c8"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VEX_PREFIX_66<a id="addd2d05002ebd2dc83a9d353a3d0231aa00dabef1990963986326bf8a846de59c"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VEX_PREFIX_F3<a id="addd2d05002ebd2dc83a9d353a3d0231aa4017792b6132c73f0635b09eb5af1c78"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VEX_PREFIX_F2<a id="addd2d05002ebd2dc83a9d353a3d0231aaae1ab4d6adc50b57d220950665786ac1"></a></td>
<td class="doxyEnumItemDescription"> (= 0x3)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 659 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### XOPMapSelect {#aed5529bc9c207a9ecdc6a2a93fe0ab97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86Disassembler::XOPMapSelect </td>
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
<td class="doxyEnumItemName">XOP_MAP_SELECT_8<a id="aed5529bc9c207a9ecdc6a2a93fe0ab97a2c36789f4611c843ffa073d50cc4c851"></a></td>
<td class="doxyEnumItemDescription"> (= 0x8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XOP_MAP_SELECT_9<a id="aed5529bc9c207a9ecdc6a2a93fe0ab97ac2c3119b84ccd3e86fee2daa73f0217b"></a></td>
<td class="doxyEnumItemDescription"> (= 0x9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XOP_MAP_SELECT_A<a id="aed5529bc9c207a9ecdc6a2a93fe0ab97acb45a816f871c105bdc85dba0b29acb1"></a></td>
<td class="doxyEnumItemDescription"> (= 0xA)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 652 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### X86\_MAX\_OPERANDS {#aaffc3a446bebe193a08a84998cc1362d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::X86Disassembler::X86_MAX_OPERANDS = 6</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
