---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/ppcii
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `PPCII` Namespace Reference

<p><a href="/web-llvm/docs/api/namespaces/llvm/ppcii">PPCII</a> - This namespace holds all of the PowerPC target-specific per-instruction flags. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::PPCII { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#aff74ce051ea8820db7384ee6826d0471">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">PPC970_Unit { <a href="#aebfd14c5a918997e894a9698f27c58e6">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a9deac633b8c0fc89619d76d4d05e273d">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">TOF { <a href="#ae73836094d8b0399ba10a6e540a363ff">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> Operand Flag enum. <a href="#ae73836094d8b0399ba10a6e540a363ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/namespaces/llvm/ppcii">PPCII</a> - This namespace holds all of the PowerPC target-specific per-instruction flags.</p>


<p>These must match the corresponding definitions in PPC.td and PPCInstrFormats.td.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#aff74ce051ea8820db7384ee6826d0471}

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
<td class="doxyEnumItemName">PPC970_First<a id="aff74ce051ea8820db7384ee6826d0471a89de693ba41c59ed962f9571eb6f20b5"></a></td>
<td class="doxyEnumItemDescription">PPC970_First - This instruction starts a new dispatch group, so it will always be the first one in the group (= 0x1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PPC970_Single<a id="aff74ce051ea8820db7384ee6826d0471acb11d47c910b37516bd9a4fb15c7de43"></a></td>
<td class="doxyEnumItemDescription">PPC970_Single - This instruction starts a new dispatch group and terminates it, so it will be the sole instruction in the group (= 0x2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PPC970_Cracked<a id="aff74ce051ea8820db7384ee6826d0471a8b8512a8f2e954aeeb98c8f24eda1447"></a></td>
<td class="doxyEnumItemDescription">PPC970_Cracked - This instruction is cracked into two pieces, requiring two dispatch pipes to be available to issue (= 0x4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PPC970_Shift<a id="aff74ce051ea8820db7384ee6826d0471a9de8ef894c3658424828ffc22ea43575"></a></td>
<td class="doxyEnumItemDescription">PPC970_Mask/Shift - This is a bitmask that selects the pipeline type that an instruction is issued to (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PPC970_Mask<a id="aff74ce051ea8820db7384ee6826d0471a7cec875ed7c232b602c5433ef76e6e73"></a></td>
<td class="doxyEnumItemDescription"> (= 0x07 &lt;&lt; PPC970_Shift)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-h">PPCMCTargetDesc.h</a>.</p>

</div>
</div>

### anonymous enum  {#a9deac633b8c0fc89619d76d4d05e273d}

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
<td class="doxyEnumItemName">NewDef_Shift<a id="a9deac633b8c0fc89619d76d4d05e273da4b5f73325be34c748d292f6aac6b9095"></a></td>
<td class="doxyEnumItemDescription">Shift count to bypass PPC970 flags (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XFormMemOp<a id="a9deac633b8c0fc89619d76d4d05e273daabe404a41cd6c42173c719a7911563c5"></a></td>
<td class="doxyEnumItemDescription">This instruction is an X-Form memory operation (= 0x1 &lt;&lt; NewDef_Shift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Prefixed<a id="a9deac633b8c0fc89619d76d4d05e273da57c485b93de14e13066ec4f32f99345d"></a></td>
<td class="doxyEnumItemDescription">This instruction is prefixed (= 0x1 &lt;&lt; (NewDef_Shift + 1))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SExt32To64<a id="a9deac633b8c0fc89619d76d4d05e273da4ff4fdb7188d27bc3d4968e5d675f0c4"></a></td>
<td class="doxyEnumItemDescription">This instruction produced a sign extended result (= 0x1 &lt;&lt; (NewDef_Shift + 2))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ZExt32To64<a id="a9deac633b8c0fc89619d76d4d05e273da0d0051d873cb4b1b2ec86509b76c3cca"></a></td>
<td class="doxyEnumItemDescription">This instruction produced a zero extended result (= 0x1 &lt;&lt; (NewDef_Shift + 3))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MemriOp<a id="a9deac633b8c0fc89619d76d4d05e273da9723544a832c302e4b7d8c04425b05d1"></a></td>
<td class="doxyEnumItemDescription">This instruction takes a register+immediate memory operand (= 0x1 &lt;&lt; (NewDef_Shift + 4))</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-h">PPCMCTargetDesc.h</a>.</p>

</div>
</div>

### PPC970\_Unit {#aebfd14c5a918997e894a9698f27c58e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::PPCII::PPC970_Unit </td>
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
<td class="doxyEnumItemName">PPC970_Pseudo<a id="aebfd14c5a918997e894a9698f27c58e6ad2c577175ece5487d0aa1cba0f3f21cf"></a></td>
<td class="doxyEnumItemDescription">These are the various PPC970 execution unit pipelines (= 0 &lt;&lt; PPC970_Shift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PPC970_FXU<a id="aebfd14c5a918997e894a9698f27c58e6ab2e7d507b6cb4772d11fcc18fed5f80f"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; PPC970_Shift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PPC970_LSU<a id="aebfd14c5a918997e894a9698f27c58e6a2a7334a88276120f2238e6d4d1a7a51e"></a></td>
<td class="doxyEnumItemDescription"> (= 2 &lt;&lt; PPC970_Shift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PPC970_FPU<a id="aebfd14c5a918997e894a9698f27c58e6a8fd98b2e3c101aa85bbc07409022b6ed"></a></td>
<td class="doxyEnumItemDescription"> (= 3 &lt;&lt; PPC970_Shift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PPC970_CRU<a id="aebfd14c5a918997e894a9698f27c58e6ad81768864759a838d64839c7b75d958c"></a></td>
<td class="doxyEnumItemDescription"> (= 4 &lt;&lt; PPC970_Shift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PPC970_VALU<a id="aebfd14c5a918997e894a9698f27c58e6a48b808627be5e642a62d9cca1d68dd7e"></a></td>
<td class="doxyEnumItemDescription"> (= 5 &lt;&lt; PPC970_Shift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PPC970_VPERM<a id="aebfd14c5a918997e894a9698f27c58e6a4b7f050b44fba7f1b01e3a0df85f0138"></a></td>
<td class="doxyEnumItemDescription"> (= 6 &lt;&lt; PPC970_Shift)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PPC970_BRU<a id="aebfd14c5a918997e894a9698f27c58e6ad3d339fe9c9bdedb6a7c90a2c58f4fad"></a></td>
<td class="doxyEnumItemDescription"> (= 7 &lt;&lt; PPC970_Shift)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-h">PPCMCTargetDesc.h</a>.</p>

</div>
</div>

### TOF {#ae73836094d8b0399ba10a6e540a363ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::PPCII::TOF </td>
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
<td class="doxyEnumItemName">MO_NO_FLAG<a id="ae73836094d8b0399ba10a6e540a363ffa9340a84aaf673899ce86db9f926ecc83"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_PLT<a id="ae73836094d8b0399ba10a6e540a363ffab055ede9c173349e17e7aada20410b93"></a></td>
<td class="doxyEnumItemDescription">On <a href="/web-llvm/docs/api/namespaces/llvm/ppc">PPC</a>, the 12 bits are not enough for all target operand flags</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_PIC_FLAG<a id="ae73836094d8b0399ba10a6e540a363ffaf464d229c08e6d5eb945d7b905a7c9fd"></a></td>
<td class="doxyEnumItemDescription">MO_PIC_FLAG - If this bit is set, the symbol reference is relative to the function's picbase, e.g</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_PCREL_FLAG<a id="ae73836094d8b0399ba10a6e540a363ffa777b254f8a19bf466553840f89ecaf31"></a></td>
<td class="doxyEnumItemDescription">MO_PCREL_FLAG - If this bit is set, the symbol reference is relative to the current instruction address(pc), e.g., var@pcrel</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOT_FLAG<a id="ae73836094d8b0399ba10a6e540a363ffa8884a7365b40eb87c9dbc760b641a55a"></a></td>
<td class="doxyEnumItemDescription">MO_GOT_FLAG - If this bit is set the symbol reference is to be computed via the GOT</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_PCREL_OPT_FLAG<a id="ae73836094d8b0399ba10a6e540a363ffaf4ba2908fdc36ea179a9e3f8eda40637"></a></td>
<td class="doxyEnumItemDescription">MO_PCREL_OPT_FLAG - If this bit is set the operand is part of a PC Relative linker optimization</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TLSGD_FLAG<a id="ae73836094d8b0399ba10a6e540a363ffae65924f7be0d235dfb37b97894d631b6"></a></td>
<td class="doxyEnumItemDescription">MO_TLSGD_FLAG - If this bit is set the symbol reference is relative to TLS General Dynamic model for Linux and the variable offset of TLS General Dynamic model for AIX</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TPREL_FLAG<a id="ae73836094d8b0399ba10a6e540a363ffac09dc26b3c7ea75dfd6da305042926cb"></a></td>
<td class="doxyEnumItemDescription">MO_TPREL_FLAG - If this bit is set, the symbol reference is relative to the thread pointer and the symbol can be used for the TLS Initial Exec and Local Exec models</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TLSLDM_FLAG<a id="ae73836094d8b0399ba10a6e540a363ffa1dcd064e63645a232083e4de59b09110"></a></td>
<td class="doxyEnumItemDescription">MO_TLSLDM_FLAG - on AIX the ML relocation type is only valid for a reference to a TOC symbol from the symbol itself, and right now its only user is the symbol "_$TLSML"</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TLSLD_FLAG<a id="ae73836094d8b0399ba10a6e540a363ffa77f81a23f8ce498f9ef4bbc5433c116b"></a></td>
<td class="doxyEnumItemDescription">MO_TLSLD_FLAG - If this bit is set the symbol reference is relative to TLS Local Dynamic model</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TLSGDM_FLAG<a id="ae73836094d8b0399ba10a6e540a363ffa6003030015cbe98f30d697c9c8a155bf"></a></td>
<td class="doxyEnumItemDescription">MO_TLSGDM_FLAG - If this bit is set the symbol reference is relative to the region handle of TLS General Dynamic model for AIX</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOT_TLSGD_PCREL_FLAG<a id="ae73836094d8b0399ba10a6e540a363ffaf045b588ae476aff3ea48b77c042f7b1"></a></td>
<td class="doxyEnumItemDescription">MO_GOT_TLSGD_PCREL_FLAG - A combintaion of flags, if these bits are set they should produce the relocation @got@tlsgd@pcrel</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOT_TLSLD_PCREL_FLAG<a id="ae73836094d8b0399ba10a6e540a363ffad1af346db81472a462b7f04fa9498ab4"></a></td>
<td class="doxyEnumItemDescription">MO_GOT_TLSLD_PCREL_FLAG - A combintaion of flags, if these bits are set they should produce the relocation @got@tlsld@pcrel</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOT_TPREL_PCREL_FLAG<a id="ae73836094d8b0399ba10a6e540a363ffa467b829ca0e160907522584b98b618a0"></a></td>
<td class="doxyEnumItemDescription">MO_GOT_TPREL_PCREL_FLAG - A combintaion of flags, if these bits are set they should produce the relocation @got@tprel@pcrel</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_LO<a id="ae73836094d8b0399ba10a6e540a363ffacfbc322d45d593103140a6a0dd75e9cd"></a></td>
<td class="doxyEnumItemDescription">MO_LO, MO_HA - lo16(symbol) and ha16(symbol)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_HA<a id="ae73836094d8b0399ba10a6e540a363ffaf3ceb6d8d3d044088a869d52777a6ed6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TPREL_LO<a id="ae73836094d8b0399ba10a6e540a363ffac1c555a378ab914a0dcae6234359aa73"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TPREL_HA<a id="ae73836094d8b0399ba10a6e540a363ffaa7929b1029f09db9b9b538e0d200fdd8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_DTPREL_LO<a id="ae73836094d8b0399ba10a6e540a363ffab5ab92a983f7ba2046b20389312e0512"></a></td>
<td class="doxyEnumItemDescription">These values identify relocations on immediates folded into memory operations</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TLSLD_LO<a id="ae73836094d8b0399ba10a6e540a363ffa0ab30789f6ac6df962adba01f53c2888"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TOC_LO<a id="ae73836094d8b0399ba10a6e540a363ffad512bc138c5c6766b7ee4f66e43d47b4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TLS<a id="ae73836094d8b0399ba10a6e540a363ffab99c6c8402edd4e84a137d89ad71169c"></a></td>
<td class="doxyEnumItemDescription">Symbol for VK_PPC_TLS fixup attached to an ADD instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_PIC_HA_FLAG<a id="ae73836094d8b0399ba10a6e540a363ffad28153a155549829b1d3c7c2c1f94eb3"></a></td>
<td class="doxyEnumItemDescription">MO_PIC_HA_FLAG = MO_PIC_FLAG | MO_HA</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_PIC_LO_FLAG<a id="ae73836094d8b0399ba10a6e540a363ffa374d4accc53d2911f6b45d9ae3c35941"></a></td>
<td class="doxyEnumItemDescription">MO_PIC_LO_FLAG = MO_PIC_FLAG | MO_LO</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TPREL_PCREL_FLAG<a id="ae73836094d8b0399ba10a6e540a363ffa4590d1594bf15001842f0bc03068dc7e"></a></td>
<td class="doxyEnumItemDescription">MO_TPREL_PCREL_FLAG = MO_PCREL_FLAG | MO_TPREL_FLAG</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_TLS_PCREL_FLAG<a id="ae73836094d8b0399ba10a6e540a363ffa81fba654d0446dd40efd2d2409643759"></a></td>
<td class="doxyEnumItemDescription">MO_TPREL_PCREL_FLAG = MO_PCREL_FLAG | MO_TLS</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MO_GOT_PCREL_FLAG<a id="ae73836094d8b0399ba10a6e540a363ffa52449b426fd1a25588ddde25cca33a82"></a></td>
<td class="doxyEnumItemDescription">MO_GOT_PCREL_FLAG = MO_PCREL_FLAG | MO_GOT_FLAG</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppc-h">PPC.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-h">PPCMCTargetDesc.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppc-h">PPC.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
