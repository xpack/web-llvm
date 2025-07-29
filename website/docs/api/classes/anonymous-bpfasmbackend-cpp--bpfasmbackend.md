---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-bpfasmbackend-cpp-/bpfasmbackend
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BPFAsmBackend` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{BPFAsmBackend.cpp}::BPFAsmBackend { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generic interface to target specific assembler backends. <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a396fdeafae6e611173d383ec0418c129">BPFAsmBackend</a> (llvm::endianness Endian)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabfb60b52e7e4a345801a1016407863c">~BPFAsmBackend</a> () override=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8042e91ea8d66d25a0e45e9f03465395">applyFixup</a> (const MCAssembler &amp;Asm, const MCFixup &amp;Fixup, const MCValue &amp;Target, MutableArrayRef&lt; char &gt; Data, uint64_t Value, bool IsResolved, const MCSubtargetInfo *STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply the <span class="doxyComputerOutput">Value</span> for given <span class="doxyComputerOutput">Fixup</span> into the provided data fragment, at the offset specified by the fixup and following the fixup kind as appropriate. <a href="#a8042e91ea8d66d25a0e45e9f03465395">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcobjecttargetwriter">MCObjectTargetWriter</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54ab4998e5567703d91669ad3ed49c87">createObjectTargetWriter</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a171638d34c85f7885a688c5cf47bf3f3">getNumFixupKinds</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of target specific fixup kinds. <a href="#a171638d34c85f7885a688c5cf47bf3f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo">MCFixupKindInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91c13851bc0b6eeda9287787050fe33f">getFixupKindInfo</a> (MCFixupKind Kind) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get information on a fixup kind. <a href="#a91c13851bc0b6eeda9287787050fe33f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76091bf4479abff002d36ef10260f4ee">writeNopData</a> (raw_ostream &amp;OS, uint64_t Count, const MCSubtargetInfo *STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write an (optimal) nop sequence of Count bytes to the given output. <a href="#a76091bf4479abff002d36ef10260f4ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfasmbackend-cpp">BPFAsmBackend.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BPFAsmBackend() {#a396fdeafae6e611173d383ec0418c129}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{BPFAsmBackend.cpp}::BPFAsmBackend::BPFAsmBackend (<a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a> Endian)</td>
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



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfasmbackend-cpp">BPFAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a071344506034666f000a89f98ec79768">llvm::MCAsmBackend::Endian</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a3dd30d6980185ef34e42333191453867">llvm::MCAsmBackend::MCAsmBackend</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a3f10b1906b3a80e0fec6c3c2f999f56f">llvm::createBPFAsmBackend</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6dfb8d65b9b76ff9dd27dabf32fe36a8">llvm::createBPFbeAsmBackend</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~BPFAsmBackend() {#aabfb60b52e7e4a345801a1016407863c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{BPFAsmBackend.cpp}::BPFAsmBackend::~BPFAsmBackend ()</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfasmbackend-cpp">BPFAsmBackend.cpp</a>.</p>


<p>References <a href="#a8042e91ea8d66d25a0e45e9f03465395">applyFixup</a>, <a href="#a54ab4998e5567703d91669ad3ed49c87">createObjectTargetWriter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### applyFixup() {#a8042e91ea8d66d25a0e45e9f03465395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BPFAsmBackend::applyFixup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; char &gt; Data, uint64_t Value, bool IsResolved, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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

<p>Apply the <span class="doxyComputerOutput">Value</span> for given <span class="doxyComputerOutput">Fixup</span> into the provided data fragment, at the offset specified by the fixup and following the fixup kind as appropriate.</p>


<p>Errors (such as an out of range fixup value) should be reported via <span class="doxyComputerOutput">Ctx</span>. The <span class="doxyComputerOutput">STI</span> is present only for fragments of type MCRelaxableFragment and MCDataFragment with hasInstructions() == true.</p>


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfasmbackend-cpp">BPFAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a071344506034666f000a89f98ec79768">llvm::MCAsmBackend::Endian</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bpf/#aae3746000e14e086696c5e63aa810812a7d2fd911c9275dbfc182765904ce1bdc">llvm::BPF::FK_BPF_PCRel_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a11803cd0814af72a9d078ac0f7a33137">llvm::FK_PCRel_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a0f7a8485c2c761bc5e870fe2b6466372">llvm::FK_PCRel_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a751b491a3c8dd06f9b616ee717dbdbae">llvm::FK_SecRel_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a71eb44a745361d5437d4a53f9f30dd3d">llvm::support::endian::write32be</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a4f05956d010455624c13f5eb2217bc8b">llvm::support::endian::write32le</a>.</p>


<p>Referenced by <a href="#aabfb60b52e7e4a345801a1016407863c">~BPFAsmBackend</a>.</p>

</div>
</div>

### createObjectTargetWriter() {#a54ab4998e5567703d91669ad3ed49c87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MCObjectTargetWriter &gt; BPFAsmBackend::createObjectTargetWriter ()</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfasmbackend-cpp">BPFAsmBackend.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ad2943023d307e4a9b43fb234916fc2dd">llvm::createBPFELFObjectWriter</a>.</p>


<p>Referenced by <a href="#aabfb60b52e7e4a345801a1016407863c">~BPFAsmBackend</a>.</p>

</div>
</div>

### getFixupKindInfo() {#a91c13851bc0b6eeda9287787050fe33f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCFixupKindInfo &amp; BPFAsmBackend::getFixupKindInfo (<a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58">MCFixupKind</a> Kind)</td>
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

<p>Get information on a fixup kind.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfasmbackend-cpp">BPFAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a02772a67f2052ae04bb9ef1ff9dc3cf8">llvm::FirstTargetFixupKind</a>, <a href="/web-llvm/docs/api/structs/llvm/mcfixupkindinfo/#a8f6613f5c0a6dc7dfebce3761963659da9bd8af688090f2f81c405bd995079007">llvm::MCFixupKindInfo::FKF_IsPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#ad4777f004ef52f665e6ec6defc1cb32a">llvm::MCAsmBackend::getFixupKindInfo</a>, <a href="#a171638d34c85f7885a688c5cf47bf3f3">getNumFixupKinds</a> and <a href="/web-llvm/docs/api/namespaces/llvm/bpf/#aae3746000e14e086696c5e63aa810812ad893a70e32515a266adf5accafabd248">llvm::BPF::NumTargetFixupKinds</a>.</p>

</div>
</div>

### getNumFixupKinds() {#a171638d34c85f7885a688c5cf47bf3f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{BPFAsmBackend.cpp}::BPFAsmBackend::getNumFixupKinds ()</td>
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

<p>Get the number of target specific fixup kinds.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfasmbackend-cpp">BPFAsmBackend.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/bpf/#aae3746000e14e086696c5e63aa810812ad893a70e32515a266adf5accafabd248">llvm::BPF::NumTargetFixupKinds</a>.</p>


<p>Referenced by <a href="#a91c13851bc0b6eeda9287787050fe33f">getFixupKindInfo</a>.</p>

</div>
</div>

### writeNopData() {#a76091bf4479abff002d36ef10260f4ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BPFAsmBackend::writeNopData (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, uint64_t Count, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI)</td>
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

<p>Write an (optimal) nop sequence of Count bytes to the given output.</p>


<p>If the target cannot generate such a sequence, it should return an error.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- True on success.</p></dd>
</dl>


<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfasmbackend-cpp">BPFAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a071344506034666f000a89f98ec79768">llvm::MCAsmBackend::Endian</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfasmbackend-cpp">BPFAsmBackend.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
