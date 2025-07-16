---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/armasmbackenddarwin
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ARMAsmBackendDarwin` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::ARMAsmBackendDarwin { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackenddarwin-h">Target/ARM/MCTargetDesc/ARMAsmBackendDarwin.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/armasmbackend">ARMAsmBackend</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a9aeec3d6dbf964fefb7758055cf0d6">ARMAsmBackendDarwin</a> (const Target &amp;T, const MCSubtargetInfo &amp;STI, const MCRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcobjecttargetwriter">MCObjectTargetWriter</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2935786c14fa2e0046436f0ab89e2507">createObjectTargetWriter</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0734a023f800982945eec5cff4e9fb22">generateCompactUnwindEncoding</a> (const MCDwarfFrameInfo *FI, const MCContext *Ctxt) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate compact unwind encoding for the function based on the CFI instructions. <a href="#a0734a023f800982945eec5cff4e9fb22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac0a77607de60a6a00b7a3ff4fc7de35d">MachO::CPUSubTypeARM</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52d085323ec902436d3c57bba568d11c">Subtype</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafce970ca31d01cb9d26213ec7737832">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87955dc572cd17404ed7760c7a8f3077">TT</a></td>
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


<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackenddarwin-h">ARMAsmBackendDarwin.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ARMAsmBackendDarwin() {#a8a9aeec3d6dbf964fefb7758055cf0d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ARMAsmBackendDarwin::ARMAsmBackendDarwin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp; MRI)</td>
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



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackenddarwin-h">ARMAsmBackendDarwin.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#a60d4755db8b2fc2adc714cbab2f5cece">llvm::ARMAsmBackend::ARMAsmBackend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#afae525cefbe3d0179a73a5ffb555160b">getCPUSubType</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#a273ed0afd8646fd6073bfa147eb1dea1">llvm::ARMAsmBackend::isThumb</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="#a52d085323ec902436d3c57bba568d11c">Subtype</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createObjectTargetWriter() {#a2935786c14fa2e0046436f0ab89e2507}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MCObjectTargetWriter &gt; llvm::ARMAsmBackendDarwin::createObjectTargetWriter ()</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackenddarwin-h">ARMAsmBackendDarwin.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a557703a10ec1c70a6248fb6399b06323">llvm::createARMMachObjectWriter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ada5bfd87ed7d3e85e1447626b2692055">llvm::MachO::getCPUType</a> and <a href="#a52d085323ec902436d3c57bba568d11c">Subtype</a>.</p>

</div>
</div>

### generateCompactUnwindEncoding() {#a0734a023f800982945eec5cff4e9fb22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t ARMAsmBackendDarwin::generateCompactUnwindEncoding (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo">MCDwarfFrameInfo</a> * FI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> * Ctxt)</td>
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

<p>Generate compact unwind encoding for the function based on the CFI instructions.</p>


<p>If the CFI instructions describe a frame that cannot be encoded in compact unwind, the method returns UNWIND_ARM_MODE_DWARF which tells the runtime to fallback and unwind using dwarf.</p>


<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackenddarwin-h">ARMAsmBackendDarwin.h</a>, definition at line 1195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp">ARMAsmBackend.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac0a77607de60a6a00b7a3ff4fc7de35da924279e3d69d7d0cbdebe029eecc11ed">llvm::MachO::CPU_SUBTYPE_ARM_V7K</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a3fcdc9f30e5e8b9ea4da99868a8ae4a9">DEBUG_WITH_TYPE</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a7374fa80c820bab9544f60931b8ca408">llvm::MCContext::emitCompactUnwindNonCanonical</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#ad678a6927d2876e9eb5fba111da70584">llvm::MCDwarfFrameInfo::Instructions</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a919e61fbc03b7b8a1660337897db7094">llvm::MCAsmBackend::isDarwinCanonicalPersonality</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0b2ca98dc28c61793ff5c90d23e5f14e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::lookup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6ecacbbd41f459c6cea155b66a7ba10f1058">llvm::MCCFIInstruction::OpDefCfa</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca5822faf65b27795cd48bd44712d48927">llvm::MCCFIInstruction::OpDefCfaOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca238c64d5f2c2fea57085c0238948b04f">llvm::MCCFIInstruction::OpDefCfaRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca74ec33979cec7221719caa137b50da3f">llvm::MCCFIInstruction::OpOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#aaf905b9d7696f2b8da2e4c89c860f6eca829be22c6230d5b270c57913ab767d66">llvm::MCCFIInstruction::OpRelOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarfframeinfo/#a3c371b9d29a2da49e836e29ac73b359b">llvm::MCDwarfFrameInfo::Personality</a> and <a href="#a52d085323ec902436d3c57bba568d11c">Subtype</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Subtype {#a52d085323ec902436d3c57bba568d11c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachO::CPUSubTypeARM llvm::ARMAsmBackendDarwin::Subtype</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackenddarwin-h">ARMAsmBackendDarwin.h</a>.</p>


<p>Referenced by <a href="#a8a9aeec3d6dbf964fefb7758055cf0d6">ARMAsmBackendDarwin</a>, <a href="#a2935786c14fa2e0046436f0ab89e2507">createObjectTargetWriter</a> and <a href="#a0734a023f800982945eec5cff4e9fb22">generateCompactUnwindEncoding</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MRI {#aafce970ca31d01cb9d26213ec7737832}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCRegisterInfo&amp; llvm::ARMAsmBackendDarwin::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackenddarwin-h">ARMAsmBackendDarwin.h</a>.</p>

</div>
</div>

### TT {#a87955dc572cd17404ed7760c7a8f3077}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple llvm::ARMAsmBackendDarwin::TT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackenddarwin-h">ARMAsmBackendDarwin.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackend-cpp">ARMAsmBackend.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armasmbackenddarwin-h">ARMAsmBackendDarwin.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
