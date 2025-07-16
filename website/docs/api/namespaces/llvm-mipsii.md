---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/mipsii
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `MipsII` Namespace Reference

<p><a href="/web-llvm/docs/api/namespaces/llvm/mipsii">MipsII</a> - This namespace holds all of the target specific flags that instruction info tracks. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::MipsII { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TOF { <a href="#ab0cf5f5ed4db649fc89a1b41f8b5771f">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Operand Flag enum. <a href="#ab0cf5f5ed4db649fc89a1b41f8b5771f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#aa15730b4ade780fcc4cc70b956af313e">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">OperandType : unsigned { <a href="#afb16240cf3bc3d72d12221ab2c0777c7">...</a> }</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/mipsii">MipsII</a> - This namespace holds all of the target specific flags that instruction info tracks.</p>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#aa15730b4ade780fcc4cc70b956af313e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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
<td class="doxyEnumItemName">Pseudo<a id="aa15730b4ade780fcc4cc70b956af313ea8bea820bb9a84757d24d35912acfdb9b"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FrmR<a id="aa15730b4ade780fcc4cc70b956af313eae0307a8051fb3c72f5dcdd8672cebc11"></a></td>
<td class="doxyEnumItemDescription">FrmR - This form is for instructions of the format R (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FrmI<a id="aa15730b4ade780fcc4cc70b956af313ea7fcd17f89e35180c7bab9419926994e1"></a></td>
<td class="doxyEnumItemDescription">FrmI - This form is for instructions of the format I (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FrmJ<a id="aa15730b4ade780fcc4cc70b956af313ea8996a0a89eb26019e0e726a11447dfdb"></a></td>
<td class="doxyEnumItemDescription">FrmJ - This form is for instructions of the format J (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FrmFR<a id="aa15730b4ade780fcc4cc70b956af313eab4f0b5581a14dbcdd01e4de807678548"></a></td>
<td class="doxyEnumItemDescription">FrmFR - This form is for instructions of the format FR (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FrmFI<a id="aa15730b4ade780fcc4cc70b956af313ea9e3e2503b6f9249256182c1e3ec7235d"></a></td>
<td class="doxyEnumItemDescription">FrmFI - This form is for instructions of the format FI (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FrmOther<a id="aa15730b4ade780fcc4cc70b956af313ea7070fe677b5cf5ad78abdffd8c5e4476"></a></td>
<td class="doxyEnumItemDescription">FrmOther - This form is for instructions that have no specific format (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FormMask<a id="aa15730b4ade780fcc4cc70b956af313ea95a92f586fd8597f2b376bb7c415a752"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsCTI<a id="aa15730b4ade780fcc4cc70b956af313ea1bc5a446bd5b475f853dbb9642e070b9"></a></td>
<td class="doxyEnumItemDescription">IsCTI - <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> is a Control Transfer <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> (= 1 &lt;&lt; 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HasForbiddenSlot<a id="aa15730b4ade780fcc4cc70b956af313eaa073124a362de1f2a0c6ff15a51da563"></a></td>
<td class="doxyEnumItemDescription">HasForbiddenSlot - <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> has a forbidden slot (= 1 &lt;&lt; 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HasFCCRegOperand<a id="aa15730b4ade780fcc4cc70b956af313ea41621e62ad62ad83ed2ea6b34cd525a7"></a></td>
<td class="doxyEnumItemDescription">HasFCCRegOperand - <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> uses an $fcc&lt;x&gt; register (= 1 &lt;&lt; 6)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsbaseinfo-h">MipsBaseInfo.h</a>.</p>

</div>
</div>

### OperandType {#afb16240cf3bc3d72d12221ab2c0777c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MipsII::OperandType : unsigned</td>
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
<td class="doxyEnumItemName">OPERAND_FIRST_MIPS_MEM_IMM<a id="afb16240cf3bc3d72d12221ab2c0777c7ac344b021782f708939b2cd57ec87ef4b"></a></td>
<td class="doxyEnumItemDescription"> (= MCOI::OPERAND_FIRST_TARGET)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_MEM_SIMM9<a id="afb16240cf3bc3d72d12221ab2c0777c7a614dc461189332a71124ff99f8312ca2"></a></td>
<td class="doxyEnumItemDescription"> (= OPERAND_FIRST_MIPS_MEM_IMM)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_LAST_MIPS_MEM_IMM<a id="afb16240cf3bc3d72d12221ab2c0777c7aeae3140bed4147309e29c89da8292269"></a></td>
<td class="doxyEnumItemDescription"> (= OPERAND_MEM_SIMM9)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsbaseinfo-h">MipsBaseInfo.h</a>.</p>

</div>
</div>

### TOF {#ab0cf5f5ed4db649fc89a1b41f8b5771f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MipsII::TOF </td>
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
<td class="doxyEnumItemName">MO_NO_FLAG<a id="ab0cf5f5ed4db649fc89a1b41f8b5771fa2b90ab603f8ca08839a861300606d205"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOT<a id="ab0cf5f5ed4db649fc89a1b41f8b5771fa1a2e2730911aa3bb70313c56b63951e2"></a></td>
<td class="doxyEnumItemDescription">MO_GOT - Represents the offset into the global offset table at which the address the relocation entry symbol resides during execution</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOT_CALL<a id="ab0cf5f5ed4db649fc89a1b41f8b5771fa07de8fa3199be2175e9f096d59778431"></a></td>
<td class="doxyEnumItemDescription">MO_GOT_CALL - Represents the offset into the global offset table at which the address of a call site relocation entry symbol resides during execution</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GPREL<a id="ab0cf5f5ed4db649fc89a1b41f8b5771facc686a80ae02879bbbe0426839c64b2a"></a></td>
<td class="doxyEnumItemDescription">MO_GPREL - Represents the offset from the current gp value to be used for the relocatable object file being produced</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_ABS_HI<a id="ab0cf5f5ed4db649fc89a1b41f8b5771fa5fbdfe4fb09a0dac0b32cce2d9d68624"></a></td>
<td class="doxyEnumItemDescription">MO_ABS_HI/LO - Represents the hi or low part of an absolute symbol address</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_ABS_LO<a id="ab0cf5f5ed4db649fc89a1b41f8b5771fa23c1a6183ec3becd204af9f074a6a10e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TLSGD<a id="ab0cf5f5ed4db649fc89a1b41f8b5771fac6c8fd74637cf047e18f442117c554e4"></a></td>
<td class="doxyEnumItemDescription">MO_TLSGD - Represents the offset into the global offset table at which</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TLSLDM<a id="ab0cf5f5ed4db649fc89a1b41f8b5771fa90d21f29c16296571a24bef17adc20d6"></a></td>
<td class="doxyEnumItemDescription">MO_TLSLDM - Represents the offset into the global offset table at which</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_DTPREL_HI<a id="ab0cf5f5ed4db649fc89a1b41f8b5771fa4b22f53419fa8f6239a48a75ab3097c2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_DTPREL_LO<a id="ab0cf5f5ed4db649fc89a1b41f8b5771fad15659773f43e297a5f00bc6e74c476b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOTTPREL<a id="ab0cf5f5ed4db649fc89a1b41f8b5771fa3bcf76298491174cfa096a159fcfa1bd"></a></td>
<td class="doxyEnumItemDescription">MO_GOTTPREL - Represents the offset from the thread pointer (Initial</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TPREL_HI<a id="ab0cf5f5ed4db649fc89a1b41f8b5771fa0b6a4b5240837361e781d83d33e47f7d"></a></td>
<td class="doxyEnumItemDescription">MO_TPREL_HI/LO - Represents the hi and low part of the offset from</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TPREL_LO<a id="ab0cf5f5ed4db649fc89a1b41f8b5771fa017c78afd95cb34d547e5b12d7e82cf2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GPOFF_HI<a id="ab0cf5f5ed4db649fc89a1b41f8b5771faaa8df1a598df32869fd86fbf2ddeb7db"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GPOFF_LO<a id="ab0cf5f5ed4db649fc89a1b41f8b5771fa9c46e428d47c726405f2a7461d360709"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOT_DISP<a id="ab0cf5f5ed4db649fc89a1b41f8b5771fa909d916f4557a43b18dc4af1cd7ad54d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOT_PAGE<a id="ab0cf5f5ed4db649fc89a1b41f8b5771fac2b1d63e911d3f10faaff19adc5b175f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOT_OFST<a id="ab0cf5f5ed4db649fc89a1b41f8b5771fafd34cc5a05cd588c7c54984311b3a0ba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_HIGHER<a id="ab0cf5f5ed4db649fc89a1b41f8b5771fae9a6bcb93bd478212b515dedbcf7d07b"></a></td>
<td class="doxyEnumItemDescription">MO_HIGHER/HIGHEST - Represents the highest or higher half word of a 64-bit symbol address</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_HIGHEST<a id="ab0cf5f5ed4db649fc89a1b41f8b5771fab607eb14b7755148dd000a00762e46a8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOT_HI16<a id="ab0cf5f5ed4db649fc89a1b41f8b5771fa80550b616f5cf1b51608f8f61c544204"></a></td>
<td class="doxyEnumItemDescription">MO_GOT_HI16/LO16, MO_CALL_HI16/LO16 - Relocations used for large GOTs</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOT_LO16<a id="ab0cf5f5ed4db649fc89a1b41f8b5771fa29a813390a5f2ab8c2c72f3f298fd2d8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_CALL_HI16<a id="ab0cf5f5ed4db649fc89a1b41f8b5771faa34ae20e1ab04ab32424d69695d84a7d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_CALL_LO16<a id="ab0cf5f5ed4db649fc89a1b41f8b5771faf24a8ce33e62490e77f5e85ae38f4217"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_JALR<a id="ab0cf5f5ed4db649fc89a1b41f8b5771fa1ad85da6e7dae2e1d6b2e9878a76d56f"></a></td>
<td class="doxyEnumItemDescription">Helper operand used to generate R_MIPS_JALR</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_DLLIMPORT<a id="ab0cf5f5ed4db649fc89a1b41f8b5771fab985de2c979ebcdba6e5456b31a00222"></a></td>
<td class="doxyEnumItemDescription">MO_DLLIMPORT - On a symbol operand "FOO", this indicates that the reference is actually to the "__imp_FOO" symbol (= 0x20)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsbaseinfo-h">MipsBaseInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsbaseinfo-h">MipsBaseInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
