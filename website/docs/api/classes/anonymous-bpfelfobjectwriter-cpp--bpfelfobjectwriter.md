---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-bpfelfobjectwriter-cpp-/bpfelfobjectwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BPFELFObjectWriter` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{BPFELFObjectWriter.cpp}::BPFELFObjectWriter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter">MCELFObjectTargetWriter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0f96d7058684da68aa071165c685f14">BPFELFObjectWriter</a> (uint8_t OSABI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2127725016f07552a00003422d01f29a">~BPFELFObjectWriter</a> () override=default</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a865396f00972a6e0d0c4f731128e31">getRelocType</a> (MCContext &amp;Ctx, const MCValue &amp;Target, const MCFixup &amp;Fixup, bool IsPCRel) const override</td>
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


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfelfobjectwriter-cpp">BPFELFObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BPFELFObjectWriter() {#ac0f96d7058684da68aa071165c685f14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BPFELFObjectWriter::BPFELFObjectWriter (uint8_t OSABI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfelfobjectwriter-cpp">BPFELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter/#ae6c6e76c9d8e0c912542fe4f8375e8ce">llvm::MCELFObjectTargetWriter::MCELFObjectTargetWriter</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~BPFELFObjectWriter() {#a2127725016f07552a00003422d01f29a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{BPFELFObjectWriter.cpp}::BPFELFObjectWriter::~BPFELFObjectWriter ()</td>
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



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfelfobjectwriter-cpp">BPFELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a> and <a href="#a6a865396f00972a6e0d0c4f731128e31">getRelocType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getRelocType() {#a6a865396f00972a6e0d0c4f731128e31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned BPFELFObjectWriter::getRelocType (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, bool IsPCRel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfelfobjectwriter-cpp">BPFELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a0f7a8485c2c761bc5e870fe2b6466372">llvm::FK_PCRel_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a751b491a3c8dd06f9b616ee717dbdbae">llvm::FK_SecRel_8</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf/#a19048a597f3c3778eefb67f07d3d8bc9">llvm::MCSectionELF::getFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ab7d669d1338ce8b4ddf910da10c51607">llvm::MCSymbol::getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a2899e74730516967f04d81966bb4f881">llvm::MCSymbol::isDefined</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#acb1c818c7e94eb25afce63fc2f91c0e2">llvm::MCSymbol::isTemporary</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a5da6bc7c194a345891a15fa856f0ec7c">llvm::ELF::SHF_ALLOC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015affae0e6af56cc351c85d9c208e27af02">llvm::ELF::SHF_EXECINSTR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015ae4bcae1b3b4fa53eba0886cbd799f0a8">llvm::ELF::SHF_WRITE</a>.</p>


<p>Referenced by <a href="#a2127725016f07552a00003422d01f29a">~BPFELFObjectWriter</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfelfobjectwriter-cpp">BPFELFObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
