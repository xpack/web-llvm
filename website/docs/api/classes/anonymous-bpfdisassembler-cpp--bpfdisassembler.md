---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-bpfdisassembler-cpp-/bpfdisassembler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BPFDisassembler` Class Reference

<p>A disassembler class for <a href="/web-llvm/docs/api/namespaces/llvm/bpf">BPF</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{BPFDisassembler.cpp}::BPFDisassembler { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Superclass for all disassemblers. <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">BPF_CLASS { <a href="#a514b7a2eccf1a2eaf5bc4e5beefb4288">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">BPF_SIZE { <a href="#ade936963c6f83779f0ba64bba6c66ebf">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">BPF_MODE { <a href="#abe794c19752bc3465ee44ec936482796">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99697c0528d06f60b89b8a9af1f19649">BPFDisassembler</a> (const MCSubtargetInfo &amp;STI, MCContext &amp;Ctx)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57749a04c6ead98dcf39cd39aca7751d">~BPFDisassembler</a> () override=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6a">DecodeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5046a0024e7712f11848e29914c387b6">getInstruction</a> (MCInst &amp;Instr, uint64_t &amp;Size, ArrayRef&lt; uint8_t &gt; Bytes, uint64_t Address, raw_ostream &amp;CStream) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the disassembly of a single instruction. <a href="#a5046a0024e7712f11848e29914c387b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07829738e89f5065c695eef49947982e">getInstClass</a> (uint64_t Inst) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4fe77ef690cd2a6b861b720d0e8ca2c">getInstSize</a> (uint64_t Inst) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e965ada822d3594809ce2c122235e3d">getInstMode</a> (uint64_t Inst) const</td>
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

<p>A disassembler class for <a href="/web-llvm/docs/api/namespaces/llvm/bpf">BPF</a>.</p>

<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/disassembler/bpfdisassembler-cpp">BPFDisassembler.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### BPF\_CLASS {#a514b7a2eccf1a2eaf5bc4e5beefb4288}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{BPFDisassembler.cpp}::BPFDisassembler::BPF_CLASS </td>
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
<td class="doxyEnumItemName">BPF_LD<a id="a514b7a2eccf1a2eaf5bc4e5beefb4288acc2e4c8eebf112283d138102f1d86683"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BPF_LDX<a id="a514b7a2eccf1a2eaf5bc4e5beefb4288a1709c49a11e35bff7338bf1d699f4893"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BPF_ST<a id="a514b7a2eccf1a2eaf5bc4e5beefb4288ada170cc690d8fbd5f25d3824f1cb9814"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BPF_STX<a id="a514b7a2eccf1a2eaf5bc4e5beefb4288a68dc8a7c8f3585fd014f97d18f79832d"></a></td>
<td class="doxyEnumItemDescription"> (= 0x3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BPF_ALU<a id="a514b7a2eccf1a2eaf5bc4e5beefb4288a2d67b4010abcefa8d3e1f833f17742c5"></a></td>
<td class="doxyEnumItemDescription"> (= 0x4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BPF_JMP<a id="a514b7a2eccf1a2eaf5bc4e5beefb4288ac9a1e272948ec13af12bab1ac1868fdc"></a></td>
<td class="doxyEnumItemDescription"> (= 0x5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BPF_JMP32<a id="a514b7a2eccf1a2eaf5bc4e5beefb4288ad9a08cb48af6bbe8c0379d503d3e53bd"></a></td>
<td class="doxyEnumItemDescription"> (= 0x6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BPF_ALU64<a id="a514b7a2eccf1a2eaf5bc4e5beefb4288a9c984fbf01ee664860700d8998844e1e"></a></td>
<td class="doxyEnumItemDescription"> (= 0x7)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/disassembler/bpfdisassembler-cpp">BPFDisassembler.cpp</a>.</p>

</div>
</div>

### BPF\_MODE {#abe794c19752bc3465ee44ec936482796}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{BPFDisassembler.cpp}::BPFDisassembler::BPF_MODE </td>
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
<td class="doxyEnumItemName">BPF_IMM<a id="abe794c19752bc3465ee44ec936482796a02627b423d542a8039c5a071b4bfba27"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BPF_ABS<a id="abe794c19752bc3465ee44ec936482796a0bebdd745d3936b594a2ab1c33a17237"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BPF_IND<a id="abe794c19752bc3465ee44ec936482796ab0d45b037dc97e6a5c676e5def2e07a4"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BPF_MEM<a id="abe794c19752bc3465ee44ec936482796a94d6fe26f0fbbc68b58a4ae57bbb5bf7"></a></td>
<td class="doxyEnumItemDescription"> (= 0x3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BPF_MEMSX<a id="abe794c19752bc3465ee44ec936482796aa7a91c254ee8375455308ef950880d30"></a></td>
<td class="doxyEnumItemDescription"> (= 0x4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BPF_ATOMIC<a id="abe794c19752bc3465ee44ec936482796adc3f003bcdcfeccbfd82d1a22ae4ca24"></a></td>
<td class="doxyEnumItemDescription"> (= 0x6)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/disassembler/bpfdisassembler-cpp">BPFDisassembler.cpp</a>.</p>

</div>
</div>

### BPF\_SIZE {#ade936963c6f83779f0ba64bba6c66ebf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{BPFDisassembler.cpp}::BPFDisassembler::BPF_SIZE </td>
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
<td class="doxyEnumItemName">BPF_W<a id="ade936963c6f83779f0ba64bba6c66ebfa1e5c469a38db3fba1ead759ba48735da"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BPF_H<a id="ade936963c6f83779f0ba64bba6c66ebfa67c8d3e43cc241cad5cae905aa528b85"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BPF_B<a id="ade936963c6f83779f0ba64bba6c66ebfacb38a958e048055e1b7189ec99956ad5"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BPF_DW<a id="ade936963c6f83779f0ba64bba6c66ebfac564088e591d8b34354ebdd61a41e2be"></a></td>
<td class="doxyEnumItemDescription"> (= 0x3)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/disassembler/bpfdisassembler-cpp">BPFDisassembler.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### BPFDisassembler() {#a99697c0528d06f60b89b8a9af1f19649}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{BPFDisassembler.cpp}::BPFDisassembler::BPFDisassembler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/disassembler/bpfdisassembler-cpp">BPFDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a07639073d0bfe2f90b94ced7f2944596">llvm::MCDisassembler::MCDisassembler</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/disassembler/bpfdisassembler-cpp/#aecf7dc4f4aa8a0a72b876c3ff27114dc">createBPFDisassembler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~BPFDisassembler() {#a57749a04c6ead98dcf39cd39aca7751d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{BPFDisassembler.cpp}::BPFDisassembler::~BPFDisassembler ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/disassembler/bpfdisassembler-cpp">BPFDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="#a5046a0024e7712f11848e29914c387b6">getInstruction</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getInstClass() {#a07829738e89f5065c695eef49947982e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t anonymous{BPFDisassembler.cpp}::BPFDisassembler::getInstClass (uint64_t Inst)</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/disassembler/bpfdisassembler-cpp">BPFDisassembler.cpp</a>.</p>


<p>Referenced by <a href="#a5046a0024e7712f11848e29914c387b6">getInstruction</a>.</p>

</div>
</div>

### getInstMode() {#a1e965ada822d3594809ce2c122235e3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t anonymous{BPFDisassembler.cpp}::BPFDisassembler::getInstMode (uint64_t Inst)</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/disassembler/bpfdisassembler-cpp">BPFDisassembler.cpp</a>.</p>


<p>Referenced by <a href="#a5046a0024e7712f11848e29914c387b6">getInstruction</a>.</p>

</div>
</div>

### getInstruction() {#a5046a0024e7712f11848e29914c387b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecodeStatus BPFDisassembler::getInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Instr, uint64_t &amp; Size, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Bytes, uint64_t Address, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; CStream)</td>
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

<p>Returns the disassembly of a single instruction.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Instr</td>
<td class="doxyParamItemDescription"><p>- An MCInst to populate with the contents of the instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>- A value to populate with the size of the instruction, or the number of bytes consumed while attempting to decode an invalid instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Address</td>
<td class="doxyParamItemDescription"><p>- The address, in the memory space of region, of the first byte of the instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Bytes</td>
<td class="doxyParamItemDescription"><p>- A reference to the actual bytes of the instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CStream</td>
<td class="doxyParamItemDescription"><p>- The stream to print comments and annotations on.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- MCDisassembler::Success if the instruction is valid, MCDisassembler::SoftFail if the instruction was disassemblable but invalid, MCDisassembler::Fail if the instruction was invalid.</p></dd>
</dl>


<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/disassembler/bpfdisassembler-cpp">BPFDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36a43f2a8aab5cba317e9ad9fe8589df00a">Address</a>, <a href="#abe794c19752bc3465ee44ec936482796adc3f003bcdcfeccbfd82d1a22ae4ca24">BPF_ATOMIC</a>, <a href="#ade936963c6f83779f0ba64bba6c66ebfac564088e591d8b34354ebdd61a41e2be">BPF_DW</a>, <a href="#a514b7a2eccf1a2eaf5bc4e5beefb4288a1709c49a11e35bff7338bf1d699f4893">BPF_LDX</a>, <a href="#abe794c19752bc3465ee44ec936482796a94d6fe26f0fbbc68b58a4ae57bbb5bf7">BPF_MEM</a>, <a href="#a514b7a2eccf1a2eaf5bc4e5beefb4288a68dc8a7c8f3585fd014f97d18f79832d">BPF_STX</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a8eb822283e8f3200ca4b2a1ba0174e6aa537a26dac8694f2000c729a35e2ead30">llvm::MCDisassembler::Fail</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a3faa10cafd0be721018fc1b9bc2c5488">llvm::MCDisassembler::getContext</a>, <a href="#a07829738e89f5065c695eef49947982e">getInstClass</a>, <a href="#a1e965ada822d3594809ce2c122235e3d">getInstMode</a>, <a href="#aa4fe77ef690cd2a6b861b720d0e8ca2c">getInstSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af54e0572ecf26033ac3fe4513016dfbe">llvm::Make_64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/disassembler/bpfdisassembler-cpp/#a3fcc2328b16aab5f5620750b7e9b4c41">readInstruction64</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a67d53a6acc509ff577f17d00ddeac34d">llvm::MCDisassembler::STI</a>.</p>


<p>Referenced by <a href="#a57749a04c6ead98dcf39cd39aca7751d">~BPFDisassembler</a>.</p>

</div>
</div>

### getInstSize() {#aa4fe77ef690cd2a6b861b720d0e8ca2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t anonymous{BPFDisassembler.cpp}::BPFDisassembler::getInstSize (uint64_t Inst)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/disassembler/bpfdisassembler-cpp">BPFDisassembler.cpp</a>.</p>


<p>Referenced by <a href="#a5046a0024e7712f11848e29914c387b6">getInstruction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/disassembler/bpfdisassembler-cpp">BPFDisassembler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
