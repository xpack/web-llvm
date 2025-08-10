---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/target
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Target` Class

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> - Wrapper for <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> specific information. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::Target { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8246d27a463d60ef213642d571744a98">ArchMatchFnTy</a> = bool(*)(<a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154">Triple::ArchType</a> Arch)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a7cbba18b8a0911bea364fd3f3451d5">MCAsmInfoCtorFnTy</a> = <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> *(*)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;TT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> &amp;<a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a393c1c83bc743826cdf2b3175fd5f7ac">MCObjectFileInfoCtorFnTy</a> = <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo">MCObjectFileInfo</a> *(*)(<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;Ctx, bool <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>, bool LargeCodeModel)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7784e775d3c5b060da5dff2688a25c95">MCInstrInfoCtorFnTy</a> = <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> *(*)()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a700498ee2ebe75f1d1ed6454b8074455">MCInstrAnalysisCtorFnTy</a> = <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis">MCInstrAnalysis</a> *(*)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> *<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75a0ab6413b8ed39da567eeb7810f9f1">MCRegInfoCtorFnTy</a> = <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> *(*)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;TT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1056bfbe7e8c7721ae6cce94313350e3">MCSubtargetInfoCtorFnTy</a> = <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> *(*)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Features)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae50a6e34e0b78a4bd13981d9ab7b1453">TargetMachineCtorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> *(*)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp;T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Features, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a> &amp;<a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a> &gt; RM, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a> &gt; CM, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> OL, bool JIT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adca9c871226ade6697c7b13e20e21580">AsmPrinterCtorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> *(*)( <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp;TM, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &gt; &amp;&amp;Streamer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43026d9c7072215fa3933cf0fc414708">MCAsmBackendCtorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> *(*)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp;T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp;STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> &amp;<a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9a613f34829802f87fb3f5febb6507a">MCAsmParserCtorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser">MCTargetAsmParser</a> *(*)( <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp;STI, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser">MCAsmParser</a> &amp;<a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp;MII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> &amp;<a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a415b455751a15f39ce122ea02400618c">MCDisassemblerCtorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> *(*)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp;T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp;STI, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8d3098e1eb0b664f3f1b50909c57467">MCInstPrinterCtorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a> *(*)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;T, unsigned SyntaxVariant, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &amp;MAI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp;MII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ad2dda902207f20a0d0dc24f65409d4">MCCodeEmitterCtorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> *(*)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9bb9d7728ece754179abcfa58fe94d2">ELFStreamerCtorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> *(*)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;T, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;Ctx, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &gt; &amp;&amp;TAB, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter">MCObjectWriter</a> &gt; &amp;&amp;OW, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &gt; &amp;&amp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#a4e37c99d7f846fd82966c68def83c4fc">Emitter</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61a694976d191b3e94c01df7f3efab4b">MachOStreamerCtorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> *(*)(<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;Ctx, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &gt; &amp;&amp;TAB, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter">MCObjectWriter</a> &gt; &amp;&amp;OW, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &gt; &amp;&amp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#a4e37c99d7f846fd82966c68def83c4fc">Emitter</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ddfc1e7a4084500bc92a086a7dab3df">COFFStreamerCtorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> *(*)(<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;Ctx, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &gt; &amp;&amp;TAB, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter">MCObjectWriter</a> &gt; &amp;&amp;OW, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &gt; &amp;&amp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#a4e37c99d7f846fd82966c68def83c4fc">Emitter</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06b59c2924092e0864c7ae7d7c1ccf4d">XCOFFStreamerCtorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> *(*)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;T, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;Ctx, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &gt; &amp;&amp;TAB, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter">MCObjectWriter</a> &gt; &amp;&amp;OW, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &gt; &amp;&amp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#a4e37c99d7f846fd82966c68def83c4fc">Emitter</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0943239d079f17f9648dc01f81896d72">NullTargetStreamerCtorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer">MCTargetStreamer</a> *(*)(<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp;S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f02ea797774ee98efc46489b1df8350">AsmTargetStreamerCtorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer">MCTargetStreamer</a> *(*)(<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp;S, <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> &amp;OS, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a> *InstPrint)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e9d8a9646a89b1557207b43b6d80ad8">ObjectTargetStreamerCtorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer">MCTargetStreamer</a> *(*)( <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp;S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06a2eeff5612f9ee5509e1e2014ae52f">MCRelocationInfoCtorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo">MCRelocationInfo</a> *(*)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;TT, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab22797c3d4d9f28541b31bbd5999ddd1">MCSymbolizerCtorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer">MCSymbolizer</a> *(*)( <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;TT, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gaa8eb7ea1e53fd6e7a11b6aa4749c6e60">LLVMOpInfoCallback</a> GetOpInfo, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga05ffa603beb390898904a06b14ee5537">LLVMSymbolLookupCallback</a> SymbolLookUp, void *DisInfo, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> *Ctx, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo">MCRelocationInfo</a> &gt; &amp;&amp;RelInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8011a7ecf12feff066c1b6f2095f9b6d">CustomBehaviourCtorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/mca/custombehaviour">mca::CustomBehaviour</a> *(*)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp;STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mca/sourcemgr">mca::SourceMgr</a> &amp;<a href="/web-llvm/docs/api/namespaces/llvm/#a5f3f23062c5d5636bee27c54f4a407f0">SrcMgr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp;MCII)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bb81212652860a7e5418351dcb2d5d6">InstrPostProcessCtorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/mca/instrpostprocess">mca::InstrPostProcess</a> *(*)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp;STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp;MCII)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d4453ee8cbb971aa3132a67ee7d1131">InstrumentManagerCtorTy</a> = <a href="/web-llvm/docs/api/classes/llvm/mca/instrumentmanager">mca::InstrumentManager</a> *(*)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp;STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp;MCII)</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f286c9149837e86060dfe60951546c8">TargetRegistry</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14d24f8712acaf204fe7277fc4889f42">Target</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbc0ab66f80da2b0f9003cb0a7ce565e">Next</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Next - The next registered target in the linked list, maintained by the <a href="/web-llvm/docs/api/structs/llvm/targetregistry">TargetRegistry</a>. <a href="#abbc0ab66f80da2b0f9003cb0a7ce565e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8246d27a463d60ef213642d571744a98">ArchMatchFnTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a794a6fa8299757ed83dc083093ecbb8d">ArchMatchFn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The target function for checking if an architecture is supported. <a href="#a794a6fa8299757ed83dc083093ecbb8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac66716c289178e3cb2005b71e0de1d7a">Name</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Name - The target name. <a href="#ac66716c289178e3cb2005b71e0de1d7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1171dbc965a69054fac67cf0169df603">ShortDesc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ShortDesc - A short description of the target. <a href="#a1171dbc965a69054fac67cf0169df603">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa583e418e794683f7e049e42688eb8fb">BackendName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BackendName - The name of the backend implementation. <a href="#aa583e418e794683f7e049e42688eb8fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bcb7cec0dc863b121f4c1f8e15cce5f">HasJIT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HasJIT - Whether this target supports the JIT. <a href="#a4bcb7cec0dc863b121f4c1f8e15cce5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0a7cbba18b8a0911bea364fd3f3451d5">MCAsmInfoCtorFnTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08f26ba59243c36239c65680793b7237">MCAsmInfoCtorFn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MCAsmInfoCtorFn - Constructor function for this target's <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a>, if registered. <a href="#a08f26ba59243c36239c65680793b7237">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a393c1c83bc743826cdf2b3175fd5f7ac">MCObjectFileInfoCtorFnTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a09ea53534558eb32d8cb7f2c2ff614">MCObjectFileInfoCtorFn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructor function for this target's <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo">MCObjectFileInfo</a>, if registered. <a href="#a0a09ea53534558eb32d8cb7f2c2ff614">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7784e775d3c5b060da5dff2688a25c95">MCInstrInfoCtorFnTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af87d0434adedc4ff4a20995f488f92a5">MCInstrInfoCtorFn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MCInstrInfoCtorFn - Constructor function for this target's <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a>, if registered. <a href="#af87d0434adedc4ff4a20995f488f92a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a700498ee2ebe75f1d1ed6454b8074455">MCInstrAnalysisCtorFnTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4079a63d73fe565c865dec85c50f970">MCInstrAnalysisCtorFn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MCInstrAnalysisCtorFn - Constructor function for this target's <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis">MCInstrAnalysis</a>, if registered. <a href="#ad4079a63d73fe565c865dec85c50f970">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a75a0ab6413b8ed39da567eeb7810f9f1">MCRegInfoCtorFnTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a547873864e29b40f110cf856654b175e">MCRegInfoCtorFn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MCRegInfoCtorFn - Constructor function for this target's <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a>, if registered. <a href="#a547873864e29b40f110cf856654b175e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1056bfbe7e8c7721ae6cce94313350e3">MCSubtargetInfoCtorFnTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6469c0622e3ede83f2d7cefeff0ad6c3">MCSubtargetInfoCtorFn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MCSubtargetInfoCtorFn - Constructor function for this target's <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a>, if registered. <a href="#a6469c0622e3ede83f2d7cefeff0ad6c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae50a6e34e0b78a4bd13981d9ab7b1453">TargetMachineCtorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a836d4bb4deefdb80c6aca8c309bf8a01">TargetMachineCtorFn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TargetMachineCtorFn - Construction function for this target's <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a>, if registered. <a href="#a836d4bb4deefdb80c6aca8c309bf8a01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a43026d9c7072215fa3933cf0fc414708">MCAsmBackendCtorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6afd806c7f60aa08bba98b454fada308">MCAsmBackendCtorFn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MCAsmBackendCtorFn - Construction function for this target's <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a>, if registered. <a href="#a6afd806c7f60aa08bba98b454fada308">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af9a613f34829802f87fb3f5febb6507a">MCAsmParserCtorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a984c48b556d12de6b24cfaad60f9e5b1">MCAsmParserCtorFn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MCAsmParserCtorFn - Construction function for this target's <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser">MCTargetAsmParser</a>, if registered. <a href="#a984c48b556d12de6b24cfaad60f9e5b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#adca9c871226ade6697c7b13e20e21580">AsmPrinterCtorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec09caf5bf681cba84515581ef4a6864">AsmPrinterCtorFn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AsmPrinterCtorFn - Construction function for this target's <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a>, if registered. <a href="#aec09caf5bf681cba84515581ef4a6864">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a415b455751a15f39ce122ea02400618c">MCDisassemblerCtorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b51f27fc541e67758268e765fffe2d9">MCDisassemblerCtorFn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MCDisassemblerCtorFn - Construction function for this target's <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a>, if registered. <a href="#a7b51f27fc541e67758268e765fffe2d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af8d3098e1eb0b664f3f1b50909c57467">MCInstPrinterCtorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6286bb70bb9f3612e9a01a168a440c9b">MCInstPrinterCtorFn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MCInstPrinterCtorFn - Construction function for this target's <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a>, if registered. <a href="#a6286bb70bb9f3612e9a01a168a440c9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1ad2dda902207f20a0d0dc24f65409d4">MCCodeEmitterCtorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98357fd11b39db4c5863f9c0fad3a4da">MCCodeEmitterCtorFn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MCCodeEmitterCtorFn - Construction function for this target's CodeEmitter, if registered. <a href="#a98357fd11b39db4c5863f9c0fad3a4da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a4ddfc1e7a4084500bc92a086a7dab3df">COFFStreamerCtorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca901f37870c4c27403d6604d8659edd">COFFStreamerCtorFn</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a61a694976d191b3e94c01df7f3efab4b">MachOStreamerCtorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02dee7d66805f5e05cc15d9ee7493480">MachOStreamerCtorFn</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af9bb9d7728ece754179abcfa58fe94d2">ELFStreamerCtorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4202ce4aeb7050603310a3a4238089d">ELFStreamerCtorFn</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a06b59c2924092e0864c7ae7d7c1ccf4d">XCOFFStreamerCtorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ccfa0d4e0f4c4f70c68e1f5cc44d128">XCOFFStreamerCtorFn</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0943239d079f17f9648dc01f81896d72">NullTargetStreamerCtorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18d57a5e007488c92b4c15d6b2ce38ae">NullTargetStreamerCtorFn</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construction function for this target's null TargetStreamer, if registered (default = nullptr). <a href="#a18d57a5e007488c92b4c15d6b2ce38ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a4f02ea797774ee98efc46489b1df8350">AsmTargetStreamerCtorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a439bd7e787b4e807c6cd246f072b74da">AsmTargetStreamerCtorFn</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construction function for this target's asm TargetStreamer, if registered (default = nullptr). <a href="#a439bd7e787b4e807c6cd246f072b74da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a4e9d8a9646a89b1557207b43b6d80ad8">ObjectTargetStreamerCtorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6644bb3e273a2ad4d4128e5ffe9a403e">ObjectTargetStreamerCtorFn</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construction function for this target's obj TargetStreamer, if registered (default = nullptr). <a href="#a6644bb3e273a2ad4d4128e5ffe9a403e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a06a2eeff5612f9ee5509e1e2014ae52f">MCRelocationInfoCtorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb4baa1689c6b111a62b1e9a10081826">MCRelocationInfoCtorFn</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MCRelocationInfoCtorFn - Construction function for this target's <a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo">MCRelocationInfo</a>, if registered (default = <a href="/web-llvm/docs/api/namespaces/llvm/#a657175eb945f907a0a871a07f18f26aa">llvm::createMCRelocationInfo</a>) <a href="#adb4baa1689c6b111a62b1e9a10081826">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab22797c3d4d9f28541b31bbd5999ddd1">MCSymbolizerCtorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4704767c6d8cde28c9ce2b4b0085956b">MCSymbolizerCtorFn</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MCSymbolizerCtorFn - Construction function for this target's <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer">MCSymbolizer</a>, if registered (default = <a href="/web-llvm/docs/api/namespaces/llvm/#a57a4ff5fb7791a4f919412e1cde59971">llvm::createMCSymbolizer</a>) <a href="#a4704767c6d8cde28c9ce2b4b0085956b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8011a7ecf12feff066c1b6f2095f9b6d">CustomBehaviourCtorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7d24feb37d5aaec2299de6f2a6894c4">CustomBehaviourCtorFn</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CustomBehaviourCtorFn - Construction function for this target's CustomBehaviour, if registered (default = nullptr). <a href="#ad7d24feb37d5aaec2299de6f2a6894c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0bb81212652860a7e5418351dcb2d5d6">InstrPostProcessCtorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3901aa830a1f50acbae80ef20d1e58e7">InstrPostProcessCtorFn</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>InstrPostProcessCtorFn - Construction function for this target's InstrPostProcess, if registered (default = nullptr). <a href="#a3901aa830a1f50acbae80ef20d1e58e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0d4453ee8cbb971aa3132a67ee7d1131">InstrumentManagerCtorTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f29d7b3798a3ea404128332742d6669">InstrumentManagerCtorFn</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>InstrumentManagerCtorFn - Construction function for this target's InstrumentManager, if registered (default = nullptr). <a href="#a4f29d7b3798a3ea404128332742d6669">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Target Information Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37066fd75be83e78af71d60cb99fd60e">getNext</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30cdafd656830b62aa8070242810c405">getName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getName - Get the target name. <a href="#a30cdafd656830b62aa8070242810c405">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6ca3b3b4350e97f01a52c70d15e83b5">getShortDescription</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getShortDescription - Get a short description of the target. <a href="#ac6ca3b3b4350e97f01a52c70d15e83b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0608efcb1a82286faf590e5a8583384">getBackendName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getBackendName - Get the backend name. <a href="#aa0608efcb1a82286faf590e5a8583384">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Feature Predicates Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd97090c1c5dad543bcf52bd692844d7">hasJIT</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasJIT - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this targets supports the just-in-time compilation. <a href="#acd97090c1c5dad543bcf52bd692844d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a58fb9a5a63983fdba176e2f8dd7b2c">hasTargetMachine</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasTargetMachine - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this target supports code generation. <a href="#a2a58fb9a5a63983fdba176e2f8dd7b2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97e50bd32b8f9b4067ab7f28f9b55dd1">hasMCAsmBackend</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasMCAsmBackend - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this target supports .o generation. <a href="#a97e50bd32b8f9b4067ab7f28f9b55dd1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56f12330f3aa625d11be552f90fe78f6">hasMCAsmParser</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasMCAsmParser - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this target supports assembly parsing. <a href="#a56f12330f3aa625d11be552f90fe78f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Feature Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a65dcb8a1d47b55360f95a575dedb62">createMCAsmInfo</a> (const MCRegisterInfo &amp;MRI, StringRef TheTriple, const MCTargetOptions &amp;Options) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createMCAsmInfo - Create a <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> implementation for the specified target triple. <a href="#a9a65dcb8a1d47b55360f95a575dedb62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo">MCObjectFileInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34b1bcd57f9c18a520b55819365ea9bb">createMCObjectFileInfo</a> (MCContext &amp;Ctx, bool PIC, bool LargeCodeModel=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo">MCObjectFileInfo</a> implementation for the specified target triple. <a href="#a34b1bcd57f9c18a520b55819365ea9bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbeb195717f888bfc2ba9f54e9623bae">createMCInstrInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createMCInstrInfo - Create a <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> implementation. <a href="#afbeb195717f888bfc2ba9f54e9623bae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis">MCInstrAnalysis</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbefc8e1344572c929eec9b2aae2aab4">createMCInstrAnalysis</a> (const MCInstrInfo *Info) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createMCInstrAnalysis - Create a <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis">MCInstrAnalysis</a> implementation. <a href="#abbefc8e1344572c929eec9b2aae2aab4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7291082412f4df3356f434aac4685911">createMCRegInfo</a> (StringRef TT) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createMCRegInfo - Create a <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> implementation. <a href="#a7291082412f4df3356f434aac4685911">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b11020c76ae0245d4aee684528e8a73">createMCSubtargetInfo</a> (StringRef TheTriple, StringRef CPU, StringRef Features) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createMCSubtargetInfo - Create a <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> implementation. <a href="#a3b11020c76ae0245d4aee684528e8a73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97b31e68ba164458a37e49e7d1053fc1">createTargetMachine</a> (StringRef TT, StringRef CPU, StringRef Features, const TargetOptions &amp;Options, std::optional&lt; Reloc::Model &gt; RM, std::optional&lt; CodeModel::Model &gt; CM=std::nullopt, CodeGenOptLevel OL=CodeGenOptLevel::Default, bool JIT=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createTargetMachine - Create a target specific machine implementation for the specified <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></span>. <a href="#a97b31e68ba164458a37e49e7d1053fc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c0bf2185facd6d2d548d7a5b8a68201">createMCAsmBackend</a> (const MCSubtargetInfo &amp;STI, const MCRegisterInfo &amp;MRI, const MCTargetOptions &amp;Options) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createMCAsmBackend - Create a target specific assembly parser. <a href="#a4c0bf2185facd6d2d548d7a5b8a68201">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser">MCTargetAsmParser</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8cf5696af398427141dd319bde94386">createMCAsmParser</a> (const MCSubtargetInfo &amp;STI, MCAsmParser &amp;Parser, const MCInstrInfo &amp;MII, const MCTargetOptions &amp;Options) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createMCAsmParser - Create a target specific assembly parser. <a href="#ab8cf5696af398427141dd319bde94386">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af99edadf5e6ea4da9f9d4b92567b8767">createAsmPrinter</a> (TargetMachine &amp;TM, std::unique_ptr&lt; MCStreamer &gt; &amp;&amp;Streamer) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createAsmPrinter - Create a target specific assembly printer pass. <a href="#af99edadf5e6ea4da9f9d4b92567b8767">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9453c999bd3483858dec967aa3b8fca2">createMCDisassembler</a> (const MCSubtargetInfo &amp;STI, MCContext &amp;Ctx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aecbb4df7336a0a60255508e24e93d3">createMCInstPrinter</a> (const Triple &amp;T, unsigned SyntaxVariant, const MCAsmInfo &amp;MAI, const MCInstrInfo &amp;MII, const MCRegisterInfo &amp;MRI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a305a6e954c6b56c92ad0761f4ec1fa55">createMCCodeEmitter</a> (const MCInstrInfo &amp;II, MCContext &amp;Ctx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createMCCodeEmitter - Create a target specific code emitter. <a href="#a305a6e954c6b56c92ad0761f4ec1fa55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c1c0e56c4d13dab0c027120fadcafe7">createMCObjectStreamer</a> (const Triple &amp;T, MCContext &amp;Ctx, std::unique_ptr&lt; MCAsmBackend &gt; TAB, std::unique_ptr&lt; MCObjectWriter &gt; OW, std::unique_ptr&lt; MCCodeEmitter &gt; Emitter, const MCSubtargetInfo &amp;STI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a target specific <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a>. <a href="#a7c1c0e56c4d13dab0c027120fadcafe7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e145aae51e0dbfdc45799f2b81d314c">createMCObjectStreamer</a> (const Triple &amp;T, MCContext &amp;Ctx, std::unique_ptr&lt; MCAsmBackend &gt; &amp;&amp;TAB, std::unique_ptr&lt; MCObjectWriter &gt; &amp;&amp;OW, std::unique_ptr&lt; MCCodeEmitter &gt; &amp;&amp;Emitter, const MCSubtargetInfo &amp;STI, bool, bool, bool) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef9d1d02691bc877336d27be1c71a1c6">createAsmStreamer</a> (MCContext &amp;Ctx, std::unique_ptr&lt; formatted_raw_ostream &gt; OS, MCInstPrinter *IP, std::unique_ptr&lt; MCCodeEmitter &gt; CE, std::unique_ptr&lt; MCAsmBackend &gt; TAB) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a711b9c28d7cb0fa600468e32dab39cf9">createAsmStreamer</a> (MCContext &amp;Ctx, std::unique_ptr&lt; formatted_raw_ostream &gt; OS, bool IsVerboseAsm, bool UseDwarfDirectory, MCInstPrinter *IP, std::unique_ptr&lt; MCCodeEmitter &gt; &amp;&amp;CE, std::unique_ptr&lt; MCAsmBackend &gt; &amp;&amp;TAB, bool ShowInst) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer">MCTargetStreamer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eb8dbeb29b86c07753a74ae92b81809">createAsmTargetStreamer</a> (MCStreamer &amp;S, formatted_raw_ostream &amp;OS, MCInstPrinter *InstPrint) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59d9de82e1d3a109ea0967665e1b95a4">createNullStreamer</a> (MCContext &amp;Ctx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mctargetstreamer">MCTargetStreamer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeac54b169af1459825e0271735ff0fc7">createNullTargetStreamer</a> (MCStreamer &amp;S) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo">MCRelocationInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6130eb3698f30c46e09f6f1b826c8e50">createMCRelocationInfo</a> (StringRef TT, MCContext &amp;Ctx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createMCRelocationInfo - Create a target specific <a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo">MCRelocationInfo</a>. <a href="#a6130eb3698f30c46e09f6f1b826c8e50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer">MCSymbolizer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41d5b78272429261ccbbc0581e7e5a97">createMCSymbolizer</a> (StringRef TT, LLVMOpInfoCallback GetOpInfo, LLVMSymbolLookupCallback SymbolLookUp, void *DisInfo, MCContext *Ctx, std::unique_ptr&lt; MCRelocationInfo &gt; &amp;&amp;RelInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createMCSymbolizer - Create a target specific <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer">MCSymbolizer</a>. <a href="#a41d5b78272429261ccbbc0581e7e5a97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/custombehaviour">mca::CustomBehaviour</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c7919dc813775925a2a5a3cfafa270a">createCustomBehaviour</a> (const MCSubtargetInfo &amp;STI, const mca::SourceMgr &amp;SrcMgr, const MCInstrInfo &amp;MCII) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createCustomBehaviour - Create a target specific CustomBehaviour. <a href="#a7c7919dc813775925a2a5a3cfafa270a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/instrpostprocess">mca::InstrPostProcess</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e63a46f75c5bbd0639ad9ffe0469754">createInstrPostProcess</a> (const MCSubtargetInfo &amp;STI, const MCInstrInfo &amp;MCII) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createInstrPostProcess - Create a target specific InstrPostProcess. <a href="#a9e63a46f75c5bbd0639ad9ffe0469754">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/instrumentmanager">mca::InstrumentManager</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe779c24ae53b84f626c8803a5abe9ae">createInstrumentManager</a> (const MCSubtargetInfo &amp;STI, const MCInstrInfo &amp;MCII) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createInstrumentManager - Create a target specific InstrumentManager. <a href="#afe779c24ae53b84f626c8803a5abe9ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> - Wrapper for <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> specific information.</p>


<p>For registration purposes, this is a POD type so that targets can be registered without the use of static constructors.</p>


<p>Targets should implement a single global instance of this class (which will be zero initialized), and pass that instance to the <a href="/web-llvm/docs/api/structs/llvm/targetregistry">TargetRegistry</a> as part of their initialization.</p>


<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ArchMatchFnTy {#a8246d27a463d60ef213642d571744a98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::ArchMatchFnTy =  bool (*)(Triple::ArchType Arch)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### AsmPrinterCtorTy {#adca9c871226ade6697c7b13e20e21580}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::AsmPrinterCtorTy =  AsmPrinter *(*)(
      TargetMachine &amp;TM, std::unique_ptr&lt;MCStreamer&gt; &amp;&amp;Streamer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### AsmTargetStreamerCtorTy {#a4f02ea797774ee98efc46489b1df8350}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::AsmTargetStreamerCtorTy = 
      MCTargetStreamer *(*)(MCStreamer &amp;S, formatted_raw_ostream &amp;OS,
                            MCInstPrinter *InstPrint)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### COFFStreamerCtorTy {#a4ddfc1e7a4084500bc92a086a7dab3df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::COFFStreamerCtorTy = 
      MCStreamer *(*)(MCContext &amp;Ctx, std::unique_ptr&lt;MCAsmBackend&gt; &amp;&amp;TAB,
                      std::unique_ptr&lt;MCObjectWriter&gt; &amp;&amp;OW,
                      std::unique_ptr&lt;MCCodeEmitter&gt; &amp;&amp;Emitter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### CustomBehaviourCtorTy {#a8011a7ecf12feff066c1b6f2095f9b6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::CustomBehaviourCtorTy = 
      mca::CustomBehaviour *(*)(const MCSubtargetInfo &amp;STI,
                                const mca::SourceMgr &amp;SrcMgr,
                                const MCInstrInfo &amp;MCII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### ELFStreamerCtorTy {#af9bb9d7728ece754179abcfa58fe94d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::ELFStreamerCtorTy = 
      MCStreamer *(*)(const Triple &amp;T, MCContext &amp;Ctx,
                      std::unique_ptr&lt;MCAsmBackend&gt; &amp;&amp;TAB,
                      std::unique_ptr&lt;MCObjectWriter&gt; &amp;&amp;OW,
                      std::unique_ptr&lt;MCCodeEmitter&gt; &amp;&amp;Emitter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### InstrPostProcessCtorTy {#a0bb81212652860a7e5418351dcb2d5d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::InstrPostProcessCtorTy = 
      mca::InstrPostProcess *(*)(const MCSubtargetInfo &amp;STI,
                                 const MCInstrInfo &amp;MCII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### InstrumentManagerCtorTy {#a0d4453ee8cbb971aa3132a67ee7d1131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::InstrumentManagerCtorTy = 
      mca::InstrumentManager *(*)(const MCSubtargetInfo &amp;STI,
                                  const MCInstrInfo &amp;MCII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MachOStreamerCtorTy {#a61a694976d191b3e94c01df7f3efab4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::MachOStreamerCtorTy = 
      MCStreamer *(*)(MCContext &amp;Ctx, std::unique_ptr&lt;MCAsmBackend&gt; &amp;&amp;TAB,
                      std::unique_ptr&lt;MCObjectWriter&gt; &amp;&amp;OW,
                      std::unique_ptr&lt;MCCodeEmitter&gt; &amp;&amp;Emitter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCAsmBackendCtorTy {#a43026d9c7072215fa3933cf0fc414708}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::MCAsmBackendCtorTy =  MCAsmBackend *(*)(const Target &amp;T,
                                               const MCSubtargetInfo &amp;STI,
                                               const MCRegisterInfo &amp;MRI,
                                               const MCTargetOptions &amp;Options)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCAsmInfoCtorFnTy {#a0a7cbba18b8a0911bea364fd3f3451d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::MCAsmInfoCtorFnTy =  MCAsmInfo *(*)(const MCRegisterInfo &amp;MRI,
                                           const Triple &amp;TT,
                                           const MCTargetOptions &amp;Options)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCAsmParserCtorTy {#af9a613f34829802f87fb3f5febb6507a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::MCAsmParserCtorTy =  MCTargetAsmParser *(*)(
      const MCSubtargetInfo &amp;STI, MCAsmParser &amp;P, const MCInstrInfo &amp;MII,
      const MCTargetOptions &amp;Options)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCCodeEmitterCtorTy {#a1ad2dda902207f20a0d0dc24f65409d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::MCCodeEmitterCtorTy =  MCCodeEmitter *(*)(const MCInstrInfo &amp;II,
                                                 MCContext &amp;Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCDisassemblerCtorTy {#a415b455751a15f39ce122ea02400618c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::MCDisassemblerCtorTy =  MCDisassembler *(*)(const Target &amp;T,
                                                   const MCSubtargetInfo &amp;STI,
                                                   MCContext &amp;Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCInstPrinterCtorTy {#af8d3098e1eb0b664f3f1b50909c57467}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::MCInstPrinterCtorTy =  MCInstPrinter *(*)(const Triple &amp;T,
                                                 unsigned SyntaxVariant,
                                                 const MCAsmInfo &amp;MAI,
                                                 const MCInstrInfo &amp;MII,
                                                 const MCRegisterInfo &amp;MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCInstrAnalysisCtorFnTy {#a700498ee2ebe75f1d1ed6454b8074455}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::MCInstrAnalysisCtorFnTy =  MCInstrAnalysis *(*)(const MCInstrInfo *Info)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCInstrInfoCtorFnTy {#a7784e775d3c5b060da5dff2688a25c95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::MCInstrInfoCtorFnTy =  MCInstrInfo *(*)()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCObjectFileInfoCtorFnTy {#a393c1c83bc743826cdf2b3175fd5f7ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::MCObjectFileInfoCtorFnTy =  MCObjectFileInfo *(*)(MCContext &amp;Ctx,
                                                         bool PIC,
                                                         bool LargeCodeModel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCRegInfoCtorFnTy {#a75a0ab6413b8ed39da567eeb7810f9f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::MCRegInfoCtorFnTy =  MCRegisterInfo *(*)(const Triple &amp;TT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCRelocationInfoCtorTy {#a06a2eeff5612f9ee5509e1e2014ae52f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::MCRelocationInfoCtorTy =  MCRelocationInfo *(*)(const Triple &amp;TT,
                                                       MCContext &amp;Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCSubtargetInfoCtorFnTy {#a1056bfbe7e8c7721ae6cce94313350e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::MCSubtargetInfoCtorFnTy =  MCSubtargetInfo *(*)(const Triple &amp;TT,
                                                       StringRef CPU,
                                                       StringRef Features)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCSymbolizerCtorTy {#ab22797c3d4d9f28541b31bbd5999ddd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::MCSymbolizerCtorTy =  MCSymbolizer *(*)(
      const Triple &amp;TT, LLVMOpInfoCallback GetOpInfo,
      LLVMSymbolLookupCallback SymbolLookUp, void *DisInfo, MCContext *Ctx,
      std::unique_ptr&lt;MCRelocationInfo&gt; &amp;&amp;RelInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### NullTargetStreamerCtorTy {#a0943239d079f17f9648dc01f81896d72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::NullTargetStreamerCtorTy =  MCTargetStreamer *(*)(MCStreamer &amp;S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### ObjectTargetStreamerCtorTy {#a4e9d8a9646a89b1557207b43b6d80ad8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::ObjectTargetStreamerCtorTy =  MCTargetStreamer *(*)(
      MCStreamer &amp;S, const MCSubtargetInfo &amp;STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### TargetMachineCtorTy {#ae50a6e34e0b78a4bd13981d9ab7b1453}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::TargetMachineCtorTy =  TargetMachine
      *(*)(const Target &amp;T, const Triple &amp;TT, StringRef CPU, StringRef Features,
           const TargetOptions &amp;Options, std::optional&lt;Reloc::Model&gt; RM,
           std::optional&lt;CodeModel::Model&gt; CM, CodeGenOptLevel OL, bool JIT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### XCOFFStreamerCtorTy {#a06b59c2924092e0864c7ae7d7c1ccf4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Target::XCOFFStreamerCtorTy = 
      MCStreamer *(*)(const Triple &amp;T, MCContext &amp;Ctx,
                      std::unique_ptr&lt;MCAsmBackend&gt; &amp;&amp;TAB,
                      std::unique_ptr&lt;MCObjectWriter&gt; &amp;&amp;OW,
                      std::unique_ptr&lt;MCCodeEmitter&gt; &amp;&amp;Emitter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### TargetRegistry {#a7f286c9149837e86060dfe60951546c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/targetregistry">TargetRegistry</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="#a7f286c9149837e86060dfe60951546c8">TargetRegistry</a>.</p>


<p>Referenced by <a href="#a7f286c9149837e86060dfe60951546c8">TargetRegistry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Target() {#a14d24f8712acaf204fe7277fc4889f42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Target::Target ()</td>
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



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Referenced by <a href="#a37066fd75be83e78af71d60cb99fd60e">getNext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ArchMatchFn {#a794a6fa8299757ed83dc083093ecbb8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArchMatchFnTy llvm::Target::ArchMatchFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The target function for checking if an architecture is supported.</p>

<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### AsmPrinterCtorFn {#aec09caf5bf681cba84515581ef4a6864}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmPrinterCtorTy llvm::Target::AsmPrinterCtorFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AsmPrinterCtorFn - Construction function for this target's <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a>, if registered.</p>

<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### AsmTargetStreamerCtorFn {#a439bd7e787b4e807c6cd246f072b74da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmTargetStreamerCtorTy llvm::Target::AsmTargetStreamerCtorFn = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construction function for this target's asm TargetStreamer, if registered (default = nullptr).</p>

<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### BackendName {#aa583e418e794683f7e049e42688eb8fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::Target::BackendName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>BackendName - The name of the backend implementation.</p>


<p>This must match the name of the 'def X : <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> ...' in <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a>.</p>


<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### COFFStreamerCtorFn {#aca901f37870c4c27403d6604d8659edd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">COFFStreamerCtorTy llvm::Target::COFFStreamerCtorFn = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### CustomBehaviourCtorFn {#ad7d24feb37d5aaec2299de6f2a6894c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CustomBehaviourCtorTy llvm::Target::CustomBehaviourCtorFn = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CustomBehaviourCtorFn - Construction function for this target's CustomBehaviour, if registered (default = nullptr).</p>

<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### ELFStreamerCtorFn {#ab4202ce4aeb7050603310a3a4238089d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ELFStreamerCtorTy llvm::Target::ELFStreamerCtorFn = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### HasJIT {#a4bcb7cec0dc863b121f4c1f8e15cce5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Target::HasJIT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>HasJIT - Whether this target supports the JIT.</p>

<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### InstrPostProcessCtorFn {#a3901aa830a1f50acbae80ef20d1e58e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrPostProcessCtorTy llvm::Target::InstrPostProcessCtorFn = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>InstrPostProcessCtorFn - Construction function for this target's InstrPostProcess, if registered (default = nullptr).</p>

<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### InstrumentManagerCtorFn {#a4f29d7b3798a3ea404128332742d6669}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrumentManagerCtorTy llvm::Target::InstrumentManagerCtorFn = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>InstrumentManagerCtorFn - Construction function for this target's InstrumentManager, if registered (default = nullptr).</p>

<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MachOStreamerCtorFn {#a02dee7d66805f5e05cc15d9ee7493480}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachOStreamerCtorTy llvm::Target::MachOStreamerCtorFn = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCAsmBackendCtorFn {#a6afd806c7f60aa08bba98b454fada308}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmBackendCtorTy llvm::Target::MCAsmBackendCtorFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MCAsmBackendCtorFn - Construction function for this target's <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a>, if registered.</p>

<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCAsmInfoCtorFn {#a08f26ba59243c36239c65680793b7237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmInfoCtorFnTy llvm::Target::MCAsmInfoCtorFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MCAsmInfoCtorFn - Constructor function for this target's <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a>, if registered.</p>

<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCAsmParserCtorFn {#a984c48b556d12de6b24cfaad60f9e5b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmParserCtorTy llvm::Target::MCAsmParserCtorFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MCAsmParserCtorFn - Construction function for this target's <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser">MCTargetAsmParser</a>, if registered.</p>

<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCCodeEmitterCtorFn {#a98357fd11b39db4c5863f9c0fad3a4da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCodeEmitterCtorTy llvm::Target::MCCodeEmitterCtorFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MCCodeEmitterCtorFn - Construction function for this target's CodeEmitter, if registered.</p>

<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCDisassemblerCtorFn {#a7b51f27fc541e67758268e765fffe2d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDisassemblerCtorTy llvm::Target::MCDisassemblerCtorFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MCDisassemblerCtorFn - Construction function for this target's <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a>, if registered.</p>

<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCInstPrinterCtorFn {#a6286bb70bb9f3612e9a01a168a440c9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstPrinterCtorTy llvm::Target::MCInstPrinterCtorFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MCInstPrinterCtorFn - Construction function for this target's <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a>, if registered.</p>

<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCInstrAnalysisCtorFn {#ad4079a63d73fe565c865dec85c50f970}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstrAnalysisCtorFnTy llvm::Target::MCInstrAnalysisCtorFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MCInstrAnalysisCtorFn - Constructor function for this target's <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis">MCInstrAnalysis</a>, if registered.</p>

<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCInstrInfoCtorFn {#af87d0434adedc4ff4a20995f488f92a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstrInfoCtorFnTy llvm::Target::MCInstrInfoCtorFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MCInstrInfoCtorFn - Constructor function for this target's <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a>, if registered.</p>

<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCObjectFileInfoCtorFn {#a0a09ea53534558eb32d8cb7f2c2ff614}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCObjectFileInfoCtorFnTy llvm::Target::MCObjectFileInfoCtorFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Constructor function for this target's <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo">MCObjectFileInfo</a>, if registered.</p>

<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCRegInfoCtorFn {#a547873864e29b40f110cf856654b175e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegInfoCtorFnTy llvm::Target::MCRegInfoCtorFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MCRegInfoCtorFn - Constructor function for this target's <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a>, if registered.</p>

<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCRelocationInfoCtorFn {#adb4baa1689c6b111a62b1e9a10081826}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRelocationInfoCtorTy llvm::Target::MCRelocationInfoCtorFn = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MCRelocationInfoCtorFn - Construction function for this target's <a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo">MCRelocationInfo</a>, if registered (default = <a href="/web-llvm/docs/api/namespaces/llvm/#a657175eb945f907a0a871a07f18f26aa">llvm::createMCRelocationInfo</a>)</p>

<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCSubtargetInfoCtorFn {#a6469c0622e3ede83f2d7cefeff0ad6c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSubtargetInfoCtorFnTy llvm::Target::MCSubtargetInfoCtorFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MCSubtargetInfoCtorFn - Constructor function for this target's <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a>, if registered.</p>

<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### MCSymbolizerCtorFn {#a4704767c6d8cde28c9ce2b4b0085956b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbolizerCtorTy llvm::Target::MCSymbolizerCtorFn = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MCSymbolizerCtorFn - Construction function for this target's <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer">MCSymbolizer</a>, if registered (default = <a href="/web-llvm/docs/api/namespaces/llvm/#a57a4ff5fb7791a4f919412e1cde59971">llvm::createMCSymbolizer</a>)</p>

<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### Name {#ac66716c289178e3cb2005b71e0de1d7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::Target::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Name - The target name.</p>

<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### Next {#abbc0ab66f80da2b0f9003cb0a7ce565e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Target* llvm::Target::Next</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Next - The next registered target in the linked list, maintained by the <a href="/web-llvm/docs/api/structs/llvm/targetregistry">TargetRegistry</a>.</p>

<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### NullTargetStreamerCtorFn {#a18d57a5e007488c92b4c15d6b2ce38ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NullTargetStreamerCtorTy llvm::Target::NullTargetStreamerCtorFn = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construction function for this target's null TargetStreamer, if registered (default = nullptr).</p>

<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### ObjectTargetStreamerCtorFn {#a6644bb3e273a2ad4d4128e5ffe9a403e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjectTargetStreamerCtorTy llvm::Target::ObjectTargetStreamerCtorFn = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construction function for this target's obj TargetStreamer, if registered (default = nullptr).</p>

<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### ShortDesc {#a1171dbc965a69054fac67cf0169df603}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::Target::ShortDesc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ShortDesc - A short description of the target.</p>

<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### TargetMachineCtorFn {#a836d4bb4deefdb80c6aca8c309bf8a01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetMachineCtorTy llvm::Target::TargetMachineCtorFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>TargetMachineCtorFn - Construction function for this target's <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a>, if registered.</p>

<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### XCOFFStreamerCtorFn {#a7ccfa0d4e0f4c4f70c68e1f5cc44d128}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XCOFFStreamerCtorTy llvm::Target::XCOFFStreamerCtorFn = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Target Information

### getBackendName {#aa0608efcb1a82286faf590e5a8583384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::Target::getBackendName ()</td>
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

<p>getBackendName - Get the backend name.</p>

<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### getName {#a30cdafd656830b62aa8070242810c405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::Target::getName ()</td>
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

<p>getName - Get the target name.</p>

<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/tablemanager/#aa7e3f0047da154572ebef76ceee273d3">llvm::jitlink::TableManager&lt; TableManagerImplT &gt;::getEntryForTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/pergraphgotandpltstubsbuilder/#a2244b4880f35fd1d8a1d32996c9cd40b">llvm::jitlink::PerGraphGOTAndPLTStubsBuilder&lt; BuilderImplT &gt;::getGOTEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/pergraphgotandpltstubsbuilder/#a09ca3d3fe297f0961217ae08820b75c3">llvm::jitlink::PerGraphGOTAndPLTStubsBuilder&lt; BuilderImplT &gt;::getPLTStub</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a9c098d5087a761f4ff5d1862ae8dfcbe">llvm::MachObjectWriter::getSymbolAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#a8638f60405edc6a322054d16515119a8">llvm::logicalview::LVScope::markMissingParents</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbol/#a582e7a4351e53bf506bf3e95bfd02cb9">llvm::logicalview::LVSymbol::markMissingParents</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtype/#ad8b98c4f60bd4d4cfef54b21fd145839">llvm::logicalview::LVType::markMissingParents</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64machobjectwriter-cpp-/aarch64machobjectwriter/#ab0bd2f62658fdbaf0b7206e161932596">anonymous{AArch64MachObjectWriter.cpp}::AArch64MachObjectWriter::recordRelocation</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/tablemanager/#ace7f4ad413507742c3a483f951e357cf">llvm::jitlink::TableManager&lt; TableManagerImplT &gt;::registerPreExistingEntry</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a85892c8cb2a8b36248f88a963d8a09ca">anonymous{WholeProgramDevirt.cpp}::DevirtModule::tryVirtualConstProp</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch32/stubsmanager-prev7/#aa7eba3616569c9358af8634c9b93361c">llvm::jitlink::aarch32::StubsManager_prev7::visitEdge</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch32/stubsmanager-v7/#a70ad29c3ed54a2bf6137e081d60a179c">llvm::jitlink::aarch32::StubsManager_v7::visitEdge</a>.</p>

</div>
</div>

### getNext {#a37066fd75be83e78af71d60cb99fd60e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Target * llvm::Target::getNext ()</td>
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



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="#a14d24f8712acaf204fe7277fc4889f42">Target</a>.</p>

</div>
</div>

### getShortDescription {#ac6ca3b3b4350e97f01a52c70d15e83b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::Target::getShortDescription ()</td>
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

<p>getShortDescription - Get a short description of the target.</p>

<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#aa0dea2adf7c230e9226a20ecc348464e">llvm::TargetRegistry::printRegisteredTargetsForVersion</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Feature Predicates

### hasJIT {#acd97090c1c5dad543bcf52bd692844d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Target::hasJIT ()</td>
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

<p>hasJIT - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this targets supports the just-in-time compilation.</p>

<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### hasMCAsmBackend {#a97e50bd32b8f9b4067ab7f28f9b55dd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Target::hasMCAsmBackend ()</td>
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

<p>hasMCAsmBackend - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this target supports .o generation.</p>

<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### hasMCAsmParser {#a56f12330f3aa625d11be552f90fe78f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Target::hasMCAsmParser ()</td>
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

<p>hasMCAsmParser - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this target supports assembly parsing.</p>

<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### hasTargetMachine {#a2a58fb9a5a63983fdba176e2f8dd7b2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Target::hasTargetMachine ()</td>
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

<p>hasTargetMachine - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this target supports code generation.</p>

<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Feature Constructors

### createAsmPrinter {#af99edadf5e6ea4da9f9d4b92567b8767}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmPrinter * llvm::Target::createAsmPrinter (<a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &gt; &amp;&amp; Streamer)</td>
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

<p>createAsmPrinter - Create a target specific assembly printer pass.</p>


<p>This takes ownership of the <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> object.</p>


<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#acf14ffe7608cbfcc75f2858e0eaa38e7">llvm::CodeGenTargetMachineImpl::addAsmPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a6070d53ab3c5060589362b14a68b17f0">llvm::CodeGenTargetMachineImpl::addPassesToEmitMC</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#a7472bfb367d052f75ef1e00fa660be70">llvm::dwarf_linker::classic::DwarfStreamer::init</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfemitterimpl/#a66fa607c96a11d3a9e973d33e733ac37">llvm::dwarf_linker::parallel::DwarfEmitterImpl::init</a>.</p>

</div>
</div>

### createAsmStreamer {#aef9d1d02691bc877336d27be1c71a1c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCStreamer * Target::createAsmStreamer (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> &gt; OS, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a> * IP, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &gt; CE, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &gt; TAB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/targetregistry-cpp">TargetRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a24b9ec99014d8eeef69271383962ef91">llvm::createAsmStreamer</a> and <a href="#a6eb8dbeb29b86c07753a74ae92b81809">createAsmTargetStreamer</a>.</p>


<p>Referenced by <a href="#a711b9c28d7cb0fa600468e32dab39cf9">createAsmStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a2ae05dfd9a73d466a7c9279380fd3783">llvm::CodeGenTargetMachineImpl::createMCStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#a7472bfb367d052f75ef1e00fa660be70">llvm::dwarf_linker::classic::DwarfStreamer::init</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfemitterimpl/#a66fa607c96a11d3a9e973d33e733ac37">llvm::dwarf_linker::parallel::DwarfEmitterImpl::init</a>.</p>

</div>
</div>

### createAsmStreamer {#a711b9c28d7cb0fa600468e32dab39cf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCStreamer * Target::createAsmStreamer (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> &gt; OS, bool IsVerboseAsm, bool UseDwarfDirectory, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a> * IP, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &gt; &amp;&amp; CE, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &gt; &amp;&amp; TAB, bool ShowInst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 548 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>, definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/targetregistry-cpp">TargetRegistry.cpp</a>.</p>


<p>Reference <a href="#aef9d1d02691bc877336d27be1c71a1c6">createAsmStreamer</a>.</p>

</div>
</div>

### createAsmTargetStreamer {#a6eb8dbeb29b86c07753a74ae92b81809}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCTargetStreamer * llvm::Target::createAsmTargetStreamer (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; S, <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a> * InstPrint)</td>
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



<p>Definition at line 553 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="#a6eb8dbeb29b86c07753a74ae92b81809">createAsmTargetStreamer</a>.</p>


<p>Referenced by <a href="#aef9d1d02691bc877336d27be1c71a1c6">createAsmStreamer</a> and <a href="#a6eb8dbeb29b86c07753a74ae92b81809">createAsmTargetStreamer</a>.</p>

</div>
</div>

### createCustomBehaviour {#a7c7919dc813775925a2a5a3cfafa270a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mca::CustomBehaviour * llvm::Target::createCustomBehaviour (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mca/sourcemgr">mca::SourceMgr</a> &amp; SrcMgr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MCII)</td>
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

<p>createCustomBehaviour - Create a target specific CustomBehaviour.</p>


<p>This class is used by llvm-mca and requires backend functionality.</p>


<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a5f3f23062c5d5636bee27c54f4a407f0">llvm::SrcMgr</a>.</p>

</div>
</div>

### createInstrPostProcess {#a9e63a46f75c5bbd0639ad9ffe0469754}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mca::InstrPostProcess * llvm::Target::createInstrPostProcess (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MCII)</td>
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

<p>createInstrPostProcess - Create a target specific InstrPostProcess.</p>


<p>This class is used by llvm-mca and requires backend functionality.</p>


<p>Definition at line 619 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### createInstrumentManager {#afe779c24ae53b84f626c8803a5abe9ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mca::InstrumentManager * llvm::Target::createInstrumentManager (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MCII)</td>
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

<p>createInstrumentManager - Create a target specific InstrumentManager.</p>


<p>This class is used by llvm-mca and requires backend functionality.</p>


<p>Definition at line 630 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>

</div>
</div>

### createMCAsmBackend {#a4c0bf2185facd6d2d548d7a5b8a68201}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmBackend * llvm::Target::createMCAsmBackend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> &amp; Options)</td>
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

<p>createMCAsmBackend - Create a target specific assembly parser.</p>

<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a6070d53ab3c5060589362b14a68b17f0">llvm::CodeGenTargetMachineImpl::addPassesToEmitMC</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a2ae05dfd9a73d466a7c9279380fd3783">llvm::CodeGenTargetMachineImpl::createMCStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#a7472bfb367d052f75ef1e00fa660be70">llvm::dwarf_linker::classic::DwarfStreamer::init</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfemitterimpl/#a66fa607c96a11d3a9e973d33e733ac37">llvm::dwarf_linker::parallel::DwarfEmitterImpl::init</a>.</p>

</div>
</div>

### createMCAsmInfo {#a9a65dcb8a1d47b55360f95a575dedb62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmInfo * llvm::Target::createMCAsmInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TheTriple, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> &amp; Options)</td>
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

<p>createMCAsmInfo - Create a <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> implementation for the specified target triple.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">TheTriple</td>
<td class="doxyParamItemDescription"><p>This argument is used to determine the target machine feature set; it should always be provided. Generally this should be either the target triple from the module, or the target triple of the host if that does not exist.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#a7472bfb367d052f75ef1e00fa660be70">llvm::dwarf_linker::classic::DwarfStreamer::init</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfemitterimpl/#a66fa607c96a11d3a9e973d33e733ac37">llvm::dwarf_linker::parallel::DwarfEmitterImpl::init</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga0ed319f9f853493c0b38e551ec2adfc5">LLVMCreateDisasmCPUFeatures</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#ad1c77f840dadc1ffb03432c9e688e4c6">llvm::logicalview::LVBinaryReader::loadGenericTargetInfo</a>.</p>

</div>
</div>

### createMCAsmParser {#ab8cf5696af398427141dd319bde94386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCTargetAsmParser * llvm::Target::createMCAsmParser (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser">MCAsmParser</a> &amp; Parser, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> &amp; Options)</td>
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

<p>createMCAsmParser - Create a target specific assembly parser.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Parser</td>
<td class="doxyParamItemDescription"><p>The target independent parser implementation to use for parsing and lexing.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>

</div>
</div>

### createMCCodeEmitter {#a305a6e954c6b56c92ad0761f4ec1fa55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCodeEmitter * llvm::Target::createMCCodeEmitter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; II, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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

<p>createMCCodeEmitter - Create a target specific code emitter.</p>

<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a2ae05dfd9a73d466a7c9279380fd3783">llvm::CodeGenTargetMachineImpl::createMCStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#a7472bfb367d052f75ef1e00fa660be70">llvm::dwarf_linker::classic::DwarfStreamer::init</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfemitterimpl/#a66fa607c96a11d3a9e973d33e733ac37">llvm::dwarf_linker::parallel::DwarfEmitterImpl::init</a>.</p>

</div>
</div>

### createMCDisassembler {#a9453c999bd3483858dec967aa3b8fca2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDisassembler * llvm::Target::createMCDisassembler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga0ed319f9f853493c0b38e551ec2adfc5">LLVMCreateDisasmCPUFeatures</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#ad1c77f840dadc1ffb03432c9e688e4c6">llvm::logicalview::LVBinaryReader::loadGenericTargetInfo</a>.</p>

</div>
</div>

### createMCInstPrinter {#a9aecbb4df7336a0a60255508e24e93d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstPrinter * llvm::Target::createMCInstPrinter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T, unsigned SyntaxVariant, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &amp; MAI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; MII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp; MRI)</td>
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



<p>Definition at line 504 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a2ae05dfd9a73d466a7c9279380fd3783">llvm::CodeGenTargetMachineImpl::createMCStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#a7472bfb367d052f75ef1e00fa660be70">llvm::dwarf_linker::classic::DwarfStreamer::init</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfemitterimpl/#a66fa607c96a11d3a9e973d33e733ac37">llvm::dwarf_linker::parallel::DwarfEmitterImpl::init</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga0ed319f9f853493c0b38e551ec2adfc5">LLVMCreateDisasmCPUFeatures</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gad1cbbd5aa7b51f04687926e8f9e4aebb">LLVMSetDisasmOptions</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#ad1c77f840dadc1ffb03432c9e688e4c6">llvm::logicalview::LVBinaryReader::loadGenericTargetInfo</a>.</p>

</div>
</div>

### createMCInstrAnalysis {#abbefc8e1344572c929eec9b2aae2aab4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstrAnalysis * llvm::Target::createMCInstrAnalysis (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> * Info)</td>
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

<p>createMCInstrAnalysis - Create a <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis">MCInstrAnalysis</a> implementation.</p>

<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>.</p>

</div>
</div>

### createMCInstrInfo {#afbeb195717f888bfc2ba9f54e9623bae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstrInfo * llvm::Target::createMCInstrInfo ()</td>
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

<p>createMCInstrInfo - Create a <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> implementation.</p>

<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#a7472bfb367d052f75ef1e00fa660be70">llvm::dwarf_linker::classic::DwarfStreamer::init</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfemitterimpl/#a66fa607c96a11d3a9e973d33e733ac37">llvm::dwarf_linker::parallel::DwarfEmitterImpl::init</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga0ed319f9f853493c0b38e551ec2adfc5">LLVMCreateDisasmCPUFeatures</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#ad1c77f840dadc1ffb03432c9e688e4c6">llvm::logicalview::LVBinaryReader::loadGenericTargetInfo</a>.</p>

</div>
</div>

### createMCObjectFileInfo {#a34b1bcd57f9c18a520b55819365ea9bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCObjectFileInfo * llvm::Target::createMCObjectFileInfo (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, bool PIC, bool LargeCodeModel=false)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo">MCObjectFileInfo</a> implementation for the specified target triple.</p>

<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a9ce8843410ce45dd5ca786651889b45b">llvm::MCObjectFileInfo::initMCObjectFileInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#a7472bfb367d052f75ef1e00fa660be70">llvm::dwarf_linker::classic::DwarfStreamer::init</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfemitterimpl/#a66fa607c96a11d3a9e973d33e733ac37">llvm::dwarf_linker::parallel::DwarfEmitterImpl::init</a>.</p>

</div>
</div>

### createMCObjectStreamer {#a7c1c0e56c4d13dab0c027120fadcafe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCStreamer * Target::createMCObjectStreamer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &gt; TAB, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter">MCObjectWriter</a> &gt; OW, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &gt; Emitter, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a target specific <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">T</td>
<td class="doxyParamItemDescription"><p>The target triple.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ctx</td>
<td class="doxyParamItemDescription"><p>The target context.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TAB</td>
<td class="doxyParamItemDescription"><p>The target assembler backend object. Takes ownership.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">OW</td>
<td class="doxyParamItemDescription"><p>The stream object.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Emitter</td>
<td class="doxyParamItemDescription"><p>The target independent assembler object.Takes ownership.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 528 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>, definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/targetregistry-cpp">TargetRegistry.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201aa943abc041caa1cc4c074bbf38b76267">llvm::Triple::COFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac739b73fab1d38f4ec8a2a9f2e86b2e3">llvm::createDXContainerStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a32337ea1e38b878e9d49d18531d147fe">llvm::createELFStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad78786951b989f470f69d6a4c1fa03ff">llvm::createGOFFStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5b42169c0c7db325d62e91eae0950fa6">llvm::createMachOStreamer</a>, <a href="#a7c1c0e56c4d13dab0c027120fadcafe7">createMCObjectStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#addeab61525f94c5212dea16310bf8feb">llvm::createSPIRVStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad5ec3e5ee553aba5637f24572b966e92">llvm::createWasmStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a382f97aab858a35311f657a88f998a68">llvm::Triple::DXContainer</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a456b64e26b8bcdbd8294689615d8a055">llvm::Triple::ELF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#a4e37c99d7f846fd82966c68def83c4fc">Emitter</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a7d71851eea2209e547ae06c9c03768f5">llvm::Triple::GOFF</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a2ed78f59e2d35011e1d1ed0ad96cf411">llvm::Triple::MachO</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201ae057411e10951f5a7dc545e6199c5490">llvm::Triple::SPIRV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201af2f88d8b470958614a01866d4714b5a4">llvm::Triple::UnknownObjectFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a660d4029da29691e97daf8c8aabb1ffb">llvm::Triple::Wasm</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a1f7d761ca747e66d2ac0caa0d54b1824">llvm::Triple::XCOFF</a>.</p>


<p>Referenced by <a href="#a2e145aae51e0dbfdc45799f2b81d314c">createMCObjectStreamer</a>, <a href="#a7c1c0e56c4d13dab0c027120fadcafe7">createMCObjectStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#a7472bfb367d052f75ef1e00fa660be70">llvm::dwarf_linker::classic::DwarfStreamer::init</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfemitterimpl/#a66fa607c96a11d3a9e973d33e733ac37">llvm::dwarf_linker::parallel::DwarfEmitterImpl::init</a>.</p>

</div>
</div>

### createMCObjectStreamer {#a2e145aae51e0dbfdc45799f2b81d314c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCStreamer * Target::createMCObjectStreamer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &gt; &amp;&amp; TAB, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter">MCObjectWriter</a> &gt; &amp;&amp; OW, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &gt; &amp;&amp; Emitter, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI, bool, bool, bool)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 534 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/targetregistry-cpp">TargetRegistry.cpp</a>.</p>


<p>References <a href="#a7c1c0e56c4d13dab0c027120fadcafe7">createMCObjectStreamer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#a4e37c99d7f846fd82966c68def83c4fc">Emitter</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### createMCRegInfo {#a7291082412f4df3356f434aac4685911}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegisterInfo * llvm::Target::createMCRegInfo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TT)</td>
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

<p>createMCRegInfo - Create a <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> implementation.</p>

<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#a7472bfb367d052f75ef1e00fa660be70">llvm::dwarf_linker::classic::DwarfStreamer::init</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfemitterimpl/#a66fa607c96a11d3a9e973d33e733ac37">llvm::dwarf_linker::parallel::DwarfEmitterImpl::init</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga0ed319f9f853493c0b38e551ec2adfc5">LLVMCreateDisasmCPUFeatures</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#ad1c77f840dadc1ffb03432c9e688e4c6">llvm::logicalview::LVBinaryReader::loadGenericTargetInfo</a>.</p>

</div>
</div>

### createMCRelocationInfo {#a6130eb3698f30c46e09f6f1b826c8e50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRelocationInfo * llvm::Target::createMCRelocationInfo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TT, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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

<p>createMCRelocationInfo - Create a target specific <a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo">MCRelocationInfo</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">TT</td>
<td class="doxyParamItemDescription"><p>The target triple.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ctx</td>
<td class="doxyParamItemDescription"><p>The target context.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 577 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a657175eb945f907a0a871a07f18f26aa">llvm::createMCRelocationInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga0ed319f9f853493c0b38e551ec2adfc5">LLVMCreateDisasmCPUFeatures</a>.</p>

</div>
</div>

### createMCSubtargetInfo {#a3b11020c76ae0245d4aee684528e8a73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSubtargetInfo * llvm::Target::createMCSubtargetInfo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TheTriple, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Features)</td>
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

<p>createMCSubtargetInfo - Create a <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> implementation.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">TheTriple</td>
<td class="doxyParamItemDescription"><p>This argument is used to determine the target machine feature set; it should always be provided. Generally this should be either the target triple from the module, or the target triple of the host if that does not exist.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CPU</td>
<td class="doxyParamItemDescription"><p>This specifies the name of the target CPU.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Features</td>
<td class="doxyParamItemDescription"><p>This specifies the string representation of the additional target features.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#a7472bfb367d052f75ef1e00fa660be70">llvm::dwarf_linker::classic::DwarfStreamer::init</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfemitterimpl/#a66fa607c96a11d3a9e973d33e733ac37">llvm::dwarf_linker::parallel::DwarfEmitterImpl::init</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga0ed319f9f853493c0b38e551ec2adfc5">LLVMCreateDisasmCPUFeatures</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#ad1c77f840dadc1ffb03432c9e688e4c6">llvm::logicalview::LVBinaryReader::loadGenericTargetInfo</a>.</p>

</div>
</div>

### createMCSymbolizer {#a41d5b78272429261ccbbc0581e7e5a97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbolizer * llvm::Target::createMCSymbolizer (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TT, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gaa8eb7ea1e53fd6e7a11b6aa4749c6e60">LLVMOpInfoCallback</a> GetOpInfo, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga05ffa603beb390898904a06b14ee5537">LLVMSymbolLookupCallback</a> SymbolLookUp, void * DisInfo, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> * Ctx, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcrelocationinfo">MCRelocationInfo</a> &gt; &amp;&amp; RelInfo)</td>
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

<p>createMCSymbolizer - Create a target specific <a href="/web-llvm/docs/api/classes/llvm/mcsymbolizer">MCSymbolizer</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">TT</td>
<td class="doxyParamItemDescription"><p>The target triple.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GetOpInfo</td>
<td class="doxyParamItemDescription"><p>The function to get the symbolic information for operands.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SymbolLookUp</td>
<td class="doxyParamItemDescription"><p>The function to lookup a symbol name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DisInfo</td>
<td class="doxyParamItemDescription"><p>The pointer to the block of symbolic information for above call back.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ctx</td>
<td class="doxyParamItemDescription"><p>The target context.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RelInfo</td>
<td class="doxyParamItemDescription"><p>The relocation information for this target. Takes ownership.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 597 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a57a4ff5fb7791a4f919412e1cde59971">llvm::createMCSymbolizer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga0ed319f9f853493c0b38e551ec2adfc5">LLVMCreateDisasmCPUFeatures</a>.</p>

</div>
</div>

### createNullStreamer {#a59d9de82e1d3a109ea0967665e1b95a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCStreamer * llvm::Target::createNullStreamer (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
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



<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4e46107a5ab09823ab3b860d45fdaabd">llvm::createNullStreamer</a> and <a href="#aeac54b169af1459825e0271735ff0fc7">createNullTargetStreamer</a>.</p>

</div>
</div>

### createNullTargetStreamer {#aeac54b169af1459825e0271735ff0fc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCTargetStreamer * llvm::Target::createNullTargetStreamer (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; S)</td>
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



<p>Definition at line 567 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>Referenced by <a href="#a59d9de82e1d3a109ea0967665e1b95a4">createNullStreamer</a>.</p>

</div>
</div>

### createTargetMachine {#a97b31e68ba164458a37e49e7d1053fc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetMachine * llvm::Target::createTargetMachine (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Features, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a> &amp; Options, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a> &gt; RM, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a> &gt; CM=std::nullopt, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> OL=<a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a7a1920d61156abc05a60135aefe8bc67">CodeGenOptLevel::Default</a>, bool JIT=false)</td>
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

<p>createTargetMachine - Create a target specific machine implementation for the specified <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">TT</td>
<td class="doxyParamItemDescription"><p>This argument is used to determine the target machine feature set; it should always be provided. Generally this should be either the target triple from the module, or the target triple of the host if that does not exist.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a7a1920d61156abc05a60135aefe8bc67">llvm::Default</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/thinltocodegeneratorimpl/targetmachinebuilder/#a057a55d2ecdfd54087c9d8ffbe9f9c2a">llvm::ThinLTOCodeGeneratorImpl::TargetMachineBuilder::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a020a49618af317a9da7a8193a54338e5">createTargetMachine</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#abfc7ebfffc7baaf23279854fec1412ac">createTargetMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codegen/#a8f10e936389f0129adc2f5ded44fdd9a">llvm::codegen::createTargetMachineForTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#a7472bfb367d052f75ef1e00fa660be70">llvm::dwarf_linker::classic::DwarfStreamer::init</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfemitterimpl/#a66fa607c96a11d3a9e973d33e733ac37">llvm::dwarf_linker::parallel::DwarfEmitterImpl::init</a>, <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a7ef5bb146eb2c0e3a609a6a169ac4f44">llvm::EngineBuilder::selectTarget</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6d9c43797976f73bdbe0c75995f84865">llvm::SPIRVTranslate</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/targetregistry-cpp">TargetRegistry.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
