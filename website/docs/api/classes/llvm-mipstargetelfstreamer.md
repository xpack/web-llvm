---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mipstargetelfstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MipsTargetELFStreamer` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MipsTargetELFStreamer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">Target/Mips/MipsTargetStreamer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer">MipsTargetStreamer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17d3b4679a104b0852f1679b817d2070">MipsTargetELFStreamer</a> (MCStreamer &amp;S, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a8e507f067affa4ac024d11f18ef157">isMicroMipsEnabled</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer">MCELFStreamer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af55b1dd717e3cffbb927f3a75cbcad7f">getStreamer</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a115028b22eef8a71ee985dea545958e8">setPic</a> (bool Value) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a843ec2afb472e21a5fcdc5480c1dd80c">emitLabel</a> (MCSymbol *Symbol) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe024d1ff04b006e2e963a401d4aee86">emitAssignment</a> (MCSymbol *Symbol, const MCExpr *Value) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94031e736c9e04044ac7181147a54bf6">finish</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a817e80b597165a9bfb2b7467f4062d0b">emitDirectiveSetMicroMips</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1be25a9d5ee50515a6b62665c8c8cb71">emitDirectiveSetNoMicroMips</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f35d1865701f1fc5e5ba821ca25cbdf">setUsesMicroMips</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac73d14121a5bc81c1cc4980d87779553">emitDirectiveSetMips16</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1456cf103019565abddab6554f0ad9a">emitDirectiveSetNoReorder</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d9e8e23e14d63569e6f0121aabd33ce">emitDirectiveEnd</a> (StringRef Name) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada024897e55f47f93f6de1fe7fffc305">emitDirectiveEnt</a> (const MCSymbol &amp;Symbol) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a945d64319bc6aee0921a6c5e25da9115">emitDirectiveAbiCalls</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b6e07764a3927c660c41da9b38a1b4b">emitDirectiveNaN2008</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5329a4017d925074c75c1c45d5e7151">emitDirectiveNaNLegacy</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfc77f75475b22f5004a1dad47cc8470">emitDirectiveOptionPic0</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48372e23fb9db6705128137e3fd87da5">emitDirectiveOptionPic2</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d36c8fdfd59414c759cd42c7c202fb2">emitDirectiveInsn</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9fe69c4c82bcd2d3a4b6ea55dd4a806">emitFrame</a> (unsigned StackReg, unsigned StackSize, unsigned ReturnReg) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92dae47a85f706dd4bec6cc0ea7f1959">emitMask</a> (unsigned CPUBitmask, int CPUTopSavedRegOff) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eeac4cc804bfa81fbf7da9e1dcff8f9">emitFMask</a> (unsigned FPUBitmask, int FPUTopSavedRegOff) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08fd27bcf2c6777016d5ea10cd83e548">emitDirectiveCpAdd</a> (unsigned RegNo) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1760c43fadfe8ae62e75e7debd68fad5">emitDirectiveCpLoad</a> (unsigned RegNo) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90e588bcf9297ddf422207faca2f001e">emitDirectiveCpLocal</a> (unsigned RegNo) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64e7586a1feca4613439ac07eabce3f0">emitDirectiveCpRestore</a> (int Offset, function_ref&lt; unsigned()&gt; GetATReg, SMLoc IDLoc, const MCSubtargetInfo *STI) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a219c7bb0dc91e12b2b43dfc1595ce234">emitDirectiveCpsetup</a> (unsigned RegNo, int RegOrOffset, const MCSymbol &amp;Sym, bool IsReg) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac108b4db53de8c6f7f8d905f4db03722">emitDirectiveCpreturn</a> (unsigned SaveLocation, bool SaveLocationIsRegister) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afeed6d8af2306405a117845c04177102">emitMipsAbiFlags</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d4ba5affec539a5642c94b8c62a71ee">MicroMipsEnabled</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03dbc945d8fd5db31225f2aa689397e2">STI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac678bba4cd0ff79f06d1d66a48f59404">Pic</a></td>
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


<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MipsTargetELFStreamer() {#a17d3b4679a104b0852f1679b817d2070}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsTargetELFStreamer::MipsTargetELFStreamer (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 801 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a0149c6589bbda5a439786064155ba1ca">llvm::MipsTargetStreamer::ABI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3ad1a8bde0f4dfbb87097614e8ee8fd879">llvm::ELF::EF_MIPS_ARCH_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3a96a2c5b6cc968b313cb31cbb54c41729">llvm::ELF::EF_MIPS_ARCH_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3af537bb5707aa1884a93d49e6dc940811">llvm::ELF::EF_MIPS_ARCH_3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3a5bfa50f70e1f0420574b45a614c11c90">llvm::ELF::EF_MIPS_ARCH_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3aa0ed8a78fdee916f775538ddf809a0df">llvm::ELF::EF_MIPS_ARCH_32R2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3a3eeb99b011318e43413b3016a2b5742c">llvm::ELF::EF_MIPS_ARCH_32R6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3a6b168f6de4d2ba8c7ddcce1faeed1993">llvm::ELF::EF_MIPS_ARCH_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3a6c542130d3a2289ab3fa5259fac68483">llvm::ELF::EF_MIPS_ARCH_5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3a5ba5b5ae4c98017c449330ccc4e101fd">llvm::ELF::EF_MIPS_ARCH_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3ab06357feff3d1b30b70a45ae45efb112">llvm::ELF::EF_MIPS_ARCH_64R2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3ae484313416c10f9de49e4181e9fe0736">llvm::ELF::EF_MIPS_ARCH_64R6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3a612b1c7070cef47b9ab1950be872822c">llvm::ELF::EF_MIPS_MACH_OCTEON</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3a807a864455816ddfbd0b2fee48a0f620">llvm::ELF::EF_MIPS_NAN2008</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a0675ed1bdbf987d94ef2360cb18c6eae">llvm::MCAssembler::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a01d6d82d18a5da901c50a546932c4264">llvm::MCContext::getObjectFileInfo</a>, <a href="#af55b1dd717e3cffbb927f3a75cbcad7f">getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a88517f360c788177b14d3d3d85182145">llvm::MCELFStreamer::getWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a97edf1bb7914cfc9e329b9d2d103e2fe">llvm::MCObjectFileInfo::isPositionIndependent</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a867c596b0454c5bbeeb1ff490b9d70bc">llvm::Triple::mips</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5fb4823bc5bbdad4684399b118ccace8">llvm::Triple::mipsel</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#ad51f80b3e6e2aaa02181cff60e90f6d4">llvm::MipsTargetStreamer::MipsTargetStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsabiinfo/#a5e17d38855b4505b183e0a3d75040c81">llvm::MipsABIInfo::N64</a> and <a href="/web-llvm/docs/api/classes/llvm/mipsabiinfo/#a11526f61f6c73d495cd72ff6bd688dfd">llvm::MipsABIInfo::O32</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitAssignment() {#abe024d1ff04b006e2e963a401d4aee86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::emitAssignment (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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



<p>Declaration at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 965 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a29b00051aee706fc5bbc604742a66f55a920f3ac6d4e61d6e58a5377436c31587">llvm::ELF::STO_MIPS_MICROMIPS</a> and <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606fa8cbc19c1660252a30c030fa945999a91">llvm::MCExpr::SymbolRef</a>.</p>

</div>
</div>

### emitDirectiveAbiCalls() {#a945d64319bc6aee0921a6c5e25da9115}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::emitDirectiveAbiCalls ()</td>
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



<p>Declaration at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 1068 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3adc4df0836451d7c1fc330fac0bc4ff86">llvm::ELF::EF_MIPS_CPIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3a9330a8f4ffc830b04e77b732faf1ab23">llvm::ELF::EF_MIPS_PIC</a>, <a href="#af55b1dd717e3cffbb927f3a75cbcad7f">getStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a88517f360c788177b14d3d3d85182145">llvm::MCELFStreamer::getWriter</a>.</p>

</div>
</div>

### emitDirectiveCpAdd() {#a08fd27bcf2c6777016d5ea10cd83e548}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::emitDirectiveCpAdd (unsigned RegNo)</td>
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



<p>Declaration at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 1141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a37f96e5964d71bf0607bfe9332dcf551">llvm::MipsTargetStreamer::emitAddu</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a1cf24d43b8f82be97b761b1b9004be1a">llvm::MipsTargetStreamer::forbidModuleDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#ac6bbf7825f8f4017bd11b8af805876df">llvm::MipsTargetStreamer::getABI</a> and <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a1bb3fa998cee14aa1f6e453beec1d489">llvm::MipsTargetStreamer::GPReg</a>.</p>

</div>
</div>

### emitDirectiveCpLoad() {#a1760c43fadfe8ae62e75e7debd68fad5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::emitDirectiveCpLoad (unsigned RegNo)</td>
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



<p>Declaration at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 1152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aecd4e9369c30b88c8e528489f69e0c8e">llvm::MCInst::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#a0087423de073ff81b2249bdea54eab40">llvm::MipsMCExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a92d2d1c2ac97f1151ed8f38d854e8b34">llvm::MCObjectStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a1cf24d43b8f82be97b761b1b9004be1a">llvm::MipsTargetStreamer::forbidModuleDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#ac6bbf7825f8f4017bd11b8af805876df">llvm::MipsTargetStreamer::getABI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a0675ed1bdbf987d94ef2360cb18c6eae">llvm::MCAssembler::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ac11eef690074972378846024abbe8722">llvm::MCContext::getOrCreateSymbol</a>, <a href="#af55b1dd717e3cffbb927f3a75cbcad7f">getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a1bb3fa998cee14aa1f6e453beec1d489">llvm::MipsTargetStreamer::GPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70a8ac2bfc0d79177cf5b86d149b0c5e9d4">llvm::MipsMCExpr::MEK_HI</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70aa2690d1ded3eb1d272f24462311161e8">llvm::MipsMCExpr::MEK_LO</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ae26e9b713a9b85d7a56343c78794269c">llvm::MCAssembler::registerSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>

</div>
</div>

### emitDirectiveCpLocal() {#a90e588bcf9297ddf422207faca2f001e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::emitDirectiveCpLocal (unsigned RegNo)</td>
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



<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 1209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a660db22c7980498afae281f2ee34f921">llvm::MipsTargetStreamer::emitDirectiveCpLocal</a>.</p>

</div>
</div>

### emitDirectiveCpRestore() {#a64e7586a1feca4613439ac07eabce3f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsTargetELFStreamer::emitDirectiveCpRestore (int Offset, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; unsigned()&gt; GetATReg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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



<p>Declaration at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 1214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#abda7d403af17ee4b867b707bdb9d638b">llvm::MipsTargetStreamer::emitDirectiveCpRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a271310bf77ed9982cec75ffad22d2a98">llvm::MipsTargetStreamer::emitStoreWithImmOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#ac6bbf7825f8f4017bd11b8af805876df">llvm::MipsTargetStreamer::getABI</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a1bb3fa998cee14aa1f6e453beec1d489">llvm::MipsTargetStreamer::GPReg</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### emitDirectiveCpreturn() {#ac108b4db53de8c6f7f8d905f4db03722}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::emitDirectiveCpreturn (unsigned SaveLocation, bool SaveLocationIsRegister)</td>
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



<p>Declaration at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 1278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a92d2d1c2ac97f1151ed8f38d854e8b34">llvm::MCObjectStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a1cf24d43b8f82be97b761b1b9004be1a">llvm::MipsTargetStreamer::forbidModuleDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#ac6bbf7825f8f4017bd11b8af805876df">llvm::MipsTargetStreamer::getABI</a>, <a href="#af55b1dd717e3cffbb927f3a75cbcad7f">getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a1bb3fa998cee14aa1f6e453beec1d489">llvm::MipsTargetStreamer::GPReg</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>.</p>

</div>
</div>

### emitDirectiveCpsetup() {#a219c7bb0dc91e12b2b43dfc1595ce234}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::emitDirectiveCpsetup (unsigned RegNo, int RegOrOffset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; Sym, bool IsReg)</td>
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



<p>Declaration at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 1235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#af29afc8458b5cc153a5cb5e1e8f0252f">llvm::MipsMCExpr::createGpOff</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a187cf8bd0c76fa7b07a76bdf6938c47e">llvm::MipsTargetStreamer::emitRRI</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#ab3776e68a5559151ee83323b88e9c19a">llvm::MipsTargetStreamer::emitRRR</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a8b10941b3ac644fb3508bc6cdc8aa6d5">llvm::MipsTargetStreamer::emitRRX</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a2b33055c2d9eb274c2d980428f7a1c24">llvm::MipsTargetStreamer::emitRX</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a1cf24d43b8f82be97b761b1b9004be1a">llvm::MipsTargetStreamer::forbidModuleDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#ac6bbf7825f8f4017bd11b8af805876df">llvm::MipsTargetStreamer::getABI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a0675ed1bdbf987d94ef2360cb18c6eae">llvm::MCAssembler::getContext</a>, <a href="#af55b1dd717e3cffbb927f3a75cbcad7f">getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a1bb3fa998cee14aa1f6e453beec1d489">llvm::MipsTargetStreamer::GPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70a8ac2bfc0d79177cf5b86d149b0c5e9d4">llvm::MipsMCExpr::MEK_HI</a> and <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ab8bb54401d51992af131ce600f468f70aa2690d1ded3eb1d272f24462311161e8">llvm::MipsMCExpr::MEK_LO</a>.</p>

</div>
</div>

### emitDirectiveEnd() {#a4d9e8e23e14d63569e6f0121aabd33ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::emitDirectiveEnd (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Declaration at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 1016 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a971830cc1546210be8cc86fa568be8d0">llvm::MCStreamer::emitIntValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a822ae1a4f19b7b00a297a100749f9b8a">llvm::MCStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae3d6e5ea7b855357014a16db766dddfd">llvm::MCStreamer::emitValueImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a065561651519e275e024f18954cafd11">llvm::MipsTargetStreamer::FPRBitMask</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a84cd9ea9478febeb0b364d0d1a064cf8">llvm::MipsTargetStreamer::FPRInfoSet</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#adfbfc160bd1afee7c52ccc6d70003b03">llvm::MipsTargetStreamer::FPROffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#ad4b5a6f9e52848eeba6bbfb48ce4cb6f">llvm::MipsTargetStreamer::FrameInfoSet</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a177a753c8303e0b7a5558894e80a5e7f">llvm::MipsTargetStreamer::FrameOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#af0c812798a63fc4f676d5942454af192">llvm::MipsTargetStreamer::FrameReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a0675ed1bdbf987d94ef2360cb18c6eae">llvm::MCAssembler::getContext</a>, <a href="#af55b1dd717e3cffbb927f3a75cbcad7f">getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#acb0558d4415697ff95ef175530d52505">llvm::MipsTargetStreamer::GPRBitMask</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a5d4a317e4d7fd84d1ae2a193a46d5d76">llvm::MipsTargetStreamer::GPRInfoSet</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a73e12ea8a2a8bac766fbee36aac4ee20">llvm::MipsTargetStreamer::GPROffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a216005880453270b48e5d5d7daeec6d4">llvm::MCStreamer::popSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ab095568f88bb32f8a744aaeab0d2c4d0">llvm::MCStreamer::pushSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a7ab24f34b1f8811a662826063b66f8d1">llvm::MipsTargetStreamer::ReturnReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a028a2916c58908b43c9866673f0b651c">llvm::MCSection::setAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca18ae5a64ac74a4265698b956bc797b32">llvm::ELF::SHT_PROGBITS</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac4f84451dc4abc997c960d484953b1d2">llvm::MCStreamer::switchSection</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a>.</p>

</div>
</div>

### emitDirectiveEnt() {#ada024897e55f47f93f6de1fe7fffc305}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::emitDirectiveEnt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; Symbol)</td>
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



<p>Declaration at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 1061 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a84cd9ea9478febeb0b364d0d1a064cf8">llvm::MipsTargetStreamer::FPRInfoSet</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#ad4b5a6f9e52848eeba6bbfb48ce4cb6f">llvm::MipsTargetStreamer::FrameInfoSet</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a5d4a317e4d7fd84d1ae2a193a46d5d76">llvm::MipsTargetStreamer::GPRInfoSet</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a28ceebccd9f41f8a7e2359ac45c59f66">llvm::ELF::STT_FUNC</a>.</p>

</div>
</div>

### emitDirectiveInsn() {#a2d36c8fdfd59414c759cd42c7c202fb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::emitDirectiveInsn ()</td>
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



<p>Declaration at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 1110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mipselfstreamer/#ab2beebc6dcbab3b3223a55482805605c">llvm::MipsELFStreamer::createPendingLabelRelocs</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#aca10e0f5ea5cf41e21cbaece649e895f">llvm::MipsTargetStreamer::emitDirectiveInsn</a> and <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#ac5c639960b526c507f505f9e3ebb915d">llvm::MCTargetStreamer::Streamer</a>.</p>

</div>
</div>

### emitDirectiveNaN2008() {#a1b6e07764a3927c660c41da9b38a1b4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::emitDirectiveNaN2008 ()</td>
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



<p>Declaration at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 1075 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3a807a864455816ddfbd0b2fee48a0f620">llvm::ELF::EF_MIPS_NAN2008</a>, <a href="#af55b1dd717e3cffbb927f3a75cbcad7f">getStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a88517f360c788177b14d3d3d85182145">llvm::MCELFStreamer::getWriter</a>.</p>

</div>
</div>

### emitDirectiveNaNLegacy() {#af5329a4017d925074c75c1c45d5e7151}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::emitDirectiveNaNLegacy ()</td>
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



<p>Declaration at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 1082 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="#af55b1dd717e3cffbb927f3a75cbcad7f">getStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a88517f360c788177b14d3d3d85182145">llvm::MCELFStreamer::getWriter</a>.</p>

</div>
</div>

### emitDirectiveOptionPic0() {#acfc77f75475b22f5004a1dad47cc8470}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::emitDirectiveOptionPic0 ()</td>
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



<p>Declaration at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 1089 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="#af55b1dd717e3cffbb927f3a75cbcad7f">getStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a88517f360c788177b14d3d3d85182145">llvm::MCELFStreamer::getWriter</a>.</p>

</div>
</div>

### emitDirectiveOptionPic2() {#a48372e23fb9db6705128137e3fd87da5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::emitDirectiveOptionPic2 ()</td>
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



<p>Declaration at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 1098 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3adc4df0836451d7c1fc330fac0bc4ff86">llvm::ELF::EF_MIPS_CPIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3a9330a8f4ffc830b04e77b732faf1ab23">llvm::ELF::EF_MIPS_PIC</a>, <a href="#af55b1dd717e3cffbb927f3a75cbcad7f">getStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a88517f360c788177b14d3d3d85182145">llvm::MCELFStreamer::getWriter</a>.</p>

</div>
</div>

### emitDirectiveSetMicroMips() {#a817e80b597165a9bfb2b7467f4062d0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::emitDirectiveSetMicroMips ()</td>
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



<p>Declaration at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 983 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a1cf24d43b8f82be97b761b1b9004be1a">llvm::MipsTargetStreamer::forbidModuleDirective</a>.</p>

</div>
</div>

### emitDirectiveSetMips16() {#ac73d14121a5bc81c1cc4980d87779553}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::emitDirectiveSetMips16 ()</td>
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



<p>Declaration at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 1000 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3acb92d092527a26fd0a3a62d0fb9cba05">llvm::ELF::EF_MIPS_ARCH_ASE_M16</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a1cf24d43b8f82be97b761b1b9004be1a">llvm::MipsTargetStreamer::forbidModuleDirective</a>, <a href="#af55b1dd717e3cffbb927f3a75cbcad7f">getStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a88517f360c788177b14d3d3d85182145">llvm::MCELFStreamer::getWriter</a>.</p>

</div>
</div>

### emitDirectiveSetNoMicroMips() {#a1be25a9d5ee50515a6b62665c8c8cb71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::emitDirectiveSetNoMicroMips ()</td>
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



<p>Declaration at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 988 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a1cf24d43b8f82be97b761b1b9004be1a">llvm::MipsTargetStreamer::forbidModuleDirective</a>.</p>

</div>
</div>

### emitDirectiveSetNoReorder() {#af1456cf103019565abddab6554f0ad9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::emitDirectiveSetNoReorder ()</td>
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



<p>Declaration at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 1008 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3acfca5e63fdcf0f47863df37e97f278c0">llvm::ELF::EF_MIPS_NOREORDER</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a1cf24d43b8f82be97b761b1b9004be1a">llvm::MipsTargetStreamer::forbidModuleDirective</a>, <a href="#af55b1dd717e3cffbb927f3a75cbcad7f">getStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a88517f360c788177b14d3d3d85182145">llvm::MCELFStreamer::getWriter</a>.</p>

</div>
</div>

### emitFMask() {#a9eeac4cc804bfa81fbf7da9e1dcff8f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::emitFMask (unsigned FPUBitmask, int FPUTopSavedRegOff)</td>
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



<p>Declaration at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 1134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a065561651519e275e024f18954cafd11">llvm::MipsTargetStreamer::FPRBitMask</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a84cd9ea9478febeb0b364d0d1a064cf8">llvm::MipsTargetStreamer::FPRInfoSet</a> and <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#adfbfc160bd1afee7c52ccc6d70003b03">llvm::MipsTargetStreamer::FPROffset</a>.</p>

</div>
</div>

### emitFrame() {#aa9fe69c4c82bcd2d3a4b6ea55dd4a806}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::emitFrame (unsigned StackReg, unsigned StackSize, unsigned ReturnReg)</td>
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



<p>Declaration at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 1116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#ad4b5a6f9e52848eeba6bbfb48ce4cb6f">llvm::MipsTargetStreamer::FrameInfoSet</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a177a753c8303e0b7a5558894e80a5e7f">llvm::MipsTargetStreamer::FrameOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#af0c812798a63fc4f676d5942454af192">llvm::MipsTargetStreamer::FrameReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a0675ed1bdbf987d94ef2360cb18c6eae">llvm::MCAssembler::getContext</a>, <a href="#af55b1dd717e3cffbb927f3a75cbcad7f">getStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a7ab24f34b1f8811a662826063b66f8d1">llvm::MipsTargetStreamer::ReturnReg</a>.</p>

</div>
</div>

### emitLabel() {#a843ec2afb472e21a5fcdc5480c1dd80c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::emitLabel (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol)</td>
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



<p>Declaration at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 881 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="#af55b1dd717e3cffbb927f3a75cbcad7f">getStreamer</a>, <a href="#a4a8e507f067affa4ac024d11f18ef157">isMicroMipsEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ae26e9b713a9b85d7a56343c78794269c">llvm::MCAssembler::registerSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a29b00051aee706fc5bbc604742a66f55a920f3ac6d4e61d6e58a5377436c31587">llvm::ELF::STO_MIPS_MICROMIPS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a28ceebccd9f41f8a7e2359ac45c59f66">llvm::ELF::STT_FUNC</a>.</p>

</div>
</div>

### emitMask() {#a92dae47a85f706dd4bec6cc0ea7f1959}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::emitMask (unsigned CPUBitmask, int CPUTopSavedRegOff)</td>
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



<p>Declaration at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 1127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#acb0558d4415697ff95ef175530d52505">llvm::MipsTargetStreamer::GPRBitMask</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a5d4a317e4d7fd84d1ae2a193a46d5d76">llvm::MipsTargetStreamer::GPRInfoSet</a> and <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#a73e12ea8a2a8bac766fbee36aac4ee20">llvm::MipsTargetStreamer::GPROffset</a>.</p>

</div>
</div>

### emitMipsAbiFlags() {#afeed6d8af2306405a117845c04177102}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::emitMipsAbiFlags ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 1302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#affd5266462270aa47e8e8f2e1c7e3193">llvm::MipsTargetStreamer::ABIFlagsSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a0675ed1bdbf987d94ef2360cb18c6eae">llvm::MCAssembler::getContext</a>, <a href="#af55b1dd717e3cffbb927f3a75cbcad7f">getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a028a2916c58908b43c9866673f0b651c">llvm::MCSection::setAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbcae59ae3f9cca08f13d50c02322a876521">llvm::ELF::SHT_MIPS_ABIFLAGS</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac4f84451dc4abc997c960d484953b1d2">llvm::MCStreamer::switchSection</a>.</p>


<p>Referenced by <a href="#a94031e736c9e04044ac7181147a54bf6">finish</a>.</p>

</div>
</div>

### finish() {#a94031e736c9e04044ac7181147a54bf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::finish ()</td>
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



<p>Declaration at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 892 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3a9d8b43b807e34e544561521493f25a68">llvm::ELF::EF_MIPS_32BITMODE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3aef43d2fc48c3be26437234a0b1b692f7">llvm::ELF::EF_MIPS_ABI2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3a56d27f725f88f3654dc9b073b8737498">llvm::ELF::EF_MIPS_ABI_O32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3adc4df0836451d7c1fc330fac0bc4ff86">llvm::ELF::EF_MIPS_CPIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3a9330a8f4ffc830b04e77b732faf1ab23">llvm::ELF::EF_MIPS_PIC</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#ad6394338481d436a665bb4572e9e1ffc">llvm::MCObjectStreamer::emitCodeAlignment</a>, <a href="#afeed6d8af2306405a117845c04177102">emitMipsAbiFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/mipselfstreamer/#a490da3720e22d1d52084ac84d4966f2c">llvm::MipsELFStreamer::EmitMipsOptionRecords</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a1df557a00a6e2c67a971eccd3a06ece4">llvm::MCELFStreamer::emitValueToAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a0fa8088b7ca6c8fccd88370bc5be4afa">llvm::MCSection::ensureMinAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetstreamer/#ac6bbf7825f8f4017bd11b8af805876df">llvm::MipsTargetStreamer::getABI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a6de12269943e6388af512d8b96cbd9e8">llvm::MCObjectFileInfo::getBSSSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a0675ed1bdbf987d94ef2360cb18c6eae">llvm::MCAssembler::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#afd9ae84447d7be72e18fd897b3f036d2">llvm::MCObjectFileInfo::getDataSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a01d6d82d18a5da901c50a546932c4264">llvm::MCContext::getObjectFileInfo</a>, <a href="#af55b1dd717e3cffbb927f3a75cbcad7f">getStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#af1e49c4350a67d9c442c39ab1dc211eb">llvm::MCObjectFileInfo::getTextSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a88517f360c788177b14d3d3d85182145">llvm::MCELFStreamer::getWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#ac5c639960b526c507f505f9e3ebb915d">llvm::MCTargetStreamer::Streamer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac4f84451dc4abc997c960d484953b1d2">llvm::MCStreamer::switchSection</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>

</div>
</div>

### getStreamer() {#af55b1dd717e3cffbb927f3a75cbcad7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCELFStreamer &amp; MipsTargetELFStreamer::getStreamer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 979 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer/#ac5c639960b526c507f505f9e3ebb915d">llvm::MCTargetStreamer::Streamer</a>.</p>


<p>Referenced by <a href="#a945d64319bc6aee0921a6c5e25da9115">emitDirectiveAbiCalls</a>, <a href="#a1760c43fadfe8ae62e75e7debd68fad5">emitDirectiveCpLoad</a>, <a href="#ac108b4db53de8c6f7f8d905f4db03722">emitDirectiveCpreturn</a>, <a href="#a219c7bb0dc91e12b2b43dfc1595ce234">emitDirectiveCpsetup</a>, <a href="#a4d9e8e23e14d63569e6f0121aabd33ce">emitDirectiveEnd</a>, <a href="#a1b6e07764a3927c660c41da9b38a1b4b">emitDirectiveNaN2008</a>, <a href="#af5329a4017d925074c75c1c45d5e7151">emitDirectiveNaNLegacy</a>, <a href="#acfc77f75475b22f5004a1dad47cc8470">emitDirectiveOptionPic0</a>, <a href="#a48372e23fb9db6705128137e3fd87da5">emitDirectiveOptionPic2</a>, <a href="#ac73d14121a5bc81c1cc4980d87779553">emitDirectiveSetMips16</a>, <a href="#af1456cf103019565abddab6554f0ad9a">emitDirectiveSetNoReorder</a>, <a href="#aa9fe69c4c82bcd2d3a4b6ea55dd4a806">emitFrame</a>, <a href="#a843ec2afb472e21a5fcdc5480c1dd80c">emitLabel</a>, <a href="#afeed6d8af2306405a117845c04177102">emitMipsAbiFlags</a>, <a href="#a94031e736c9e04044ac7181147a54bf6">finish</a>, <a href="#a17d3b4679a104b0852f1679b817d2070">MipsTargetELFStreamer</a> and <a href="#a2f35d1865701f1fc5e5ba821ca25cbdf">setUsesMicroMips</a>.</p>

</div>
</div>

### isMicroMipsEnabled() {#a4a8e507f067affa4ac024d11f18ef157}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsTargetELFStreamer::isMicroMipsEnabled ()</td>
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



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipselfstreamer/#ab2beebc6dcbab3b3223a55482805605c">llvm::MipsELFStreamer::createPendingLabelRelocs</a> and <a href="#a843ec2afb472e21a5fcdc5480c1dd80c">emitLabel</a>.</p>

</div>
</div>

### setPic() {#a115028b22eef8a71ee985dea545958e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MipsTargetELFStreamer::setPic (bool Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>

</div>
</div>

### setUsesMicroMips() {#a2f35d1865701f1fc5e5ba821ca25cbdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsTargetELFStreamer::setUsesMicroMips ()</td>
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



<p>Declaration at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>, definition at line 993 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a4ea62c477a7f8c0d987a7d2139bef2b3a3197d22f662c76cef6adeffc22306d94">llvm::ELF::EF_MIPS_MICROMIPS</a>, <a href="#af55b1dd717e3cffbb927f3a75cbcad7f">getStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a88517f360c788177b14d3d3d85182145">llvm::MCELFStreamer::getWriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MicroMipsEnabled {#a9d4ba5affec539a5642c94b8c62a71ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsTargetELFStreamer::MicroMipsEnabled</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>

</div>
</div>

### Pic {#ac678bba4cd0ff79f06d1d66a48f59404}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsTargetELFStreamer::Pic</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>

</div>
</div>

### STI {#a03dbc945d8fd5db31225f2aa689397e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSubtargetInfo&amp; llvm::MipsTargetELFStreamer::STI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp">MipsTargetStreamer.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetstreamer-h">MipsTargetStreamer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
