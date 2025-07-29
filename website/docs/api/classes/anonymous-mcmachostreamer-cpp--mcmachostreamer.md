---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MCMachOStreamer` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{MCMachOStreamer.cpp}::MCMachOStreamer { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer">MCObjectStreamer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Streaming object file generation interface. <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bd111c579cbfedf31833c63a942e56d">MCMachOStreamer</a> (MCContext &amp;Context, std::unique_ptr&lt; MCAsmBackend &gt; MAB, std::unique_ptr&lt; MCObjectWriter &gt; OW, std::unique_ptr&lt; MCCodeEmitter &gt; Emitter, bool label)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7d07de8f8ddcc6840351b77b4e95a38">reset</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>state management <a href="#ac7d07de8f8ddcc6840351b77b4e95a38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machobjectwriter">MachObjectWriter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a42090118f78814bc7429038d910869">getWriter</a> ()</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7706c9c0d6f2fc339bead845ff21a74">emitInstToData</a> (const MCInst &amp;Inst, const MCSubtargetInfo &amp;STI) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80bd089959cf2a2793c1713dbcf4f46e">emitDataRegion</a> (MachO::DataRegionType Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a344099e9f53d64f8a79553e4eea93e9e">emitDataRegionEnd</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80477ccc1d151b86b7586ed78104f0d5">LabelSections</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LabelSections - true if each section change should emit a linker local label for use in relocations for assembler local references. <a href="#a80477ccc1d151b86b7586ed78104f0d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> *, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad830ed9bf761736e7718478affc36c36">HasSectionLabel</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HasSectionLabel - map of which sections have already had a non-local label emitted to them. <a href="#ad830ed9bf761736e7718478affc36c36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## MCStreamer Interface Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb372de94b1d4298c2bd4518af8e14bd">changeSection</a> (MCSection *Sect, uint32_t Subsection=0) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is called by popSection and switchSection, if the current section changes. <a href="#afb372de94b1d4298c2bd4518af8e14bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a886379efdc1ac575d1a38dd8b01775">emitLabel</a> (MCSymbol *Symbol, SMLoc Loc=SMLoc()) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a label for <span class="doxyComputerOutput">Symbol</span> into the current section. <a href="#a3a886379efdc1ac575d1a38dd8b01775">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34ce30f596de6334b5f17323b15e4fa4">emitAssignment</a> (MCSymbol *Symbol, const MCExpr *Value) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit an assignment of <span class="doxyComputerOutput">Value</span> to <span class="doxyComputerOutput">Symbol</span>. <a href="#a34ce30f596de6334b5f17323b15e4fa4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4b7284c767b0b63e76c11e3c1c8c3db">emitEHSymAttributes</a> (const MCSymbol *Symbol, MCSymbol *EHSymbol) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eb571ea4b693cfa886b7ab49f8eb07c">emitAssemblerFlag</a> (MCAssemblerFlag Flag) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Note in the output the specified <span class="doxyComputerOutput">Flag</span>. <a href="#a8eb571ea4b693cfa886b7ab49f8eb07c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20df437db4d5607918482b6758bd9ffa">emitLinkerOptions</a> (ArrayRef&lt; std::string &gt; Options) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the given list <span class="doxyComputerOutput">Options</span> of strings as linker options into the output. <a href="#a20df437db4d5607918482b6758bd9ffa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a125094f2b526fe5c975b36c2fa59113f">emitDataRegion</a> (MCDataRegionType Kind) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Note in the output the specified region <span class="doxyComputerOutput">Kind</span>. <a href="#a125094f2b526fe5c975b36c2fa59113f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54b409598660523f6cc25d472089fc05">emitVersionMin</a> (MCVersionMinType Kind, unsigned Major, unsigned Minor, unsigned Update, VersionTuple SDKVersion) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specify the Mach-O minimum deployment target version. <a href="#a54b409598660523f6cc25d472089fc05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaefc9558efc4b58f37049b3e4656011f">emitBuildVersion</a> (unsigned Platform, unsigned Major, unsigned Minor, unsigned Update, VersionTuple SDKVersion) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit/Specify Mach-O build version command. <a href="#aaefc9558efc4b58f37049b3e4656011f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a109ba15aa1760d974d280d73a7b632b9">emitDarwinTargetVariantBuildVersion</a> (unsigned Platform, unsigned Major, unsigned Minor, unsigned Update, VersionTuple SDKVersion) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b711b3a69c236fd97741567932418dd">emitThumbFunc</a> (MCSymbol *Func) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Note in the output that the specified <span class="doxyComputerOutput">Func</span> is a Thumb mode function (ARM target only). <a href="#a8b711b3a69c236fd97741567932418dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a798fb78a6525095a294fda8d027edeb6">emitSymbolAttribute</a> (MCSymbol *Symbol, MCSymbolAttr Attribute) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the given <span class="doxyComputerOutput">Attribute</span> to <span class="doxyComputerOutput">Symbol</span>. <a href="#a798fb78a6525095a294fda8d027edeb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5369560155ea22c4431734d7a2d571f">emitSymbolDesc</a> (MCSymbol *Symbol, unsigned DescValue) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the <span class="doxyComputerOutput">DescValue</span> for the <span class="doxyComputerOutput">Symbol</span>. <a href="#af5369560155ea22c4431734d7a2d571f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1da8e248a188abfab9a12525b3290ed">emitCommonSymbol</a> (MCSymbol *Symbol, uint64_t Size, Align ByteAlignment) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a common symbol. <a href="#af1da8e248a188abfab9a12525b3290ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac361b5e6ec19ddb003ca8d13ad57354d">emitLocalCommonSymbol</a> (MCSymbol *Symbol, uint64_t Size, Align ByteAlignment) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a local common (.lcomm) symbol. <a href="#ac361b5e6ec19ddb003ca8d13ad57354d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af20b6581bfb880b0df6d552b229739f9">emitZerofill</a> (MCSection *Section, MCSymbol *Symbol=nullptr, uint64_t Size=0, Align ByteAlignment=Align(1), SMLoc Loc=SMLoc()) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the zerofill section and an optional symbol. <a href="#af20b6581bfb880b0df6d552b229739f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cc7ffb47b770c4b442fd456d6c66963">emitTBSSSymbol</a> (MCSection *Section, MCSymbol *Symbol, uint64_t Size, Align ByteAlignment=Align(1)) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a thread local bss (.tbss) symbol. <a href="#a2cc7ffb47b770c4b442fd456d6c66963">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaf863fa4e92ee4e97252cff47377cf2">emitIdent</a> (StringRef IdentString) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the "identifiers" directive. <a href="#acaf863fa4e92ee4e97252cff47377cf2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb494b131350ac649ee801a9effc9b11">emitLOHDirective</a> (MCLOHType Kind, const MCLOHArgs &amp;Args) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a Linker Optimization Hint (LOH) directive. <a href="#aeb494b131350ac649ee801a9effc9b11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58e3c2a4ec9c34e4a8c8388fb66946ae">emitCGProfileEntry</a> (const MCSymbolRefExpr *From, const MCSymbolRefExpr *To, uint64_t Count) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fcfdc05d17713d4bd5c4bd4aaaea0ae">finishImpl</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Streamer specific finalization. <a href="#a0fcfdc05d17713d4bd5c4bd4aaaea0ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03ebbddf5185beab8e633649235fe873">finalizeCGProfileEntry</a> (const MCSymbolRefExpr *&amp;SRE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc76b392eb3df7f2d5456efe795060c3">finalizeCGProfile</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b9193e77b26973b0c65a96716330b87">createAddrSigSection</a> ()</td>
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


<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCMachOStreamer() {#a9bd111c579cbfedf31833c63a942e56d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::MCMachOStreamer (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &gt; MAB, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter">MCObjectWriter</a> &gt; OW, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &gt; Emitter, bool label)</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#a4e37c99d7f846fd82966c68def83c4fc">Emitter</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9ad1da683a018add519fd96cd22cc785">llvm::MCObjectStreamer::MCObjectStreamer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5b42169c0c7db325d62e91eae0950fa6">llvm::createMachOStreamer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getWriter() {#a7a42090118f78814bc7429038d910869}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachObjectWriter &amp; anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::getWriter ()</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>.</p>


<p>Referenced by <a href="#a8eb571ea4b693cfa886b7ab49f8eb07c">emitAssemblerFlag</a>, <a href="#aaefc9558efc4b58f37049b3e4656011f">emitBuildVersion</a>, <a href="#a58e3c2a4ec9c34e4a8c8388fb66946ae">emitCGProfileEntry</a>, <a href="#a109ba15aa1760d974d280d73a7b632b9">emitDarwinTargetVariantBuildVersion</a>, <a href="#a20df437db4d5607918482b6758bd9ffa">emitLinkerOptions</a>, <a href="#aeb494b131350ac649ee801a9effc9b11">emitLOHDirective</a>, <a href="#a798fb78a6525095a294fda8d027edeb6">emitSymbolAttribute</a>, <a href="#a54b409598660523f6cc25d472089fc05">emitVersionMin</a> and <a href="#adc76b392eb3df7f2d5456efe795060c3">finalizeCGProfile</a>.</p>

</div>
</div>

### reset() {#ac7d07de8f8ddcc6840351b77b4e95a38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::reset ()</td>
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

<p>state management</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a085ffc1a6ae032696e1a665600f04124">llvm::MCObjectStreamer::reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### emitDataRegion() {#a80bd089959cf2a2793c1713dbcf4f46e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCMachOStreamer::emitDataRegion (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac782e0c3ae71664c3cb1a0430e894bc0">MachO::DataRegionType</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>

</div>
</div>

### emitDataRegionEnd() {#a344099e9f53d64f8a79553e4eea93e9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCMachOStreamer::emitDataRegionEnd ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>

</div>
</div>

### emitInstToData() {#ad7706c9c0d6f2fc339bead845ff21a74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCMachOStreamer::emitInstToData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### HasSectionLabel {#ad830ed9bf761736e7718478affc36c36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MCSection*, bool&gt; anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::HasSectionLabel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>HasSectionLabel - map of which sections have already had a non-local label emitted to them.</p>


<p>Used so we don't emit extraneous linker local labels in the middle of the section.</p>


<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>

</div>
</div>

### LabelSections {#a80477ccc1d151b86b7586ed78104f0d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::LabelSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LabelSections - true if each section change should emit a linker local label for use in relocations for assembler local references.</p>


<p>Obviates the need for local relocations. False by default.</p>


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## MCStreamer Interface

### changeSection {#afb372de94b1d4298c2bd4518af8e14bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCMachOStreamer::changeSection (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section, uint32_t)</td>
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

<p>This is called by popSection and switchSection, if the current section changes.</p>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a6f19f34683888bee863e73af9a082535">llvm::MCObjectStreamer::changeSectionImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>.</p>


<p>Referenced by <a href="#a5b9193e77b26973b0c65a96716330b87">createAddrSigSection</a> and <a href="#adc76b392eb3df7f2d5456efe795060c3">finalizeCGProfile</a>.</p>

</div>
</div>

### createAddrSigSection {#a5b9193e77b26973b0c65a96716330b87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCMachOStreamer::createAddrSigSection ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#afb372de94b1d4298c2bd4518af8e14bd">changeSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#ac28ea8ba1e28d8b3a3ca7234e1bc1083">llvm::MCSection::curFragList</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter/#a8cd9936953941196b85a3e2ff1c2abf7">llvm::MCObjectWriter::getEmitAddrsigSection</a> and <a href="/web-llvm/docs/api/structs/llvm/mcsection/fraglist/#a3642f400a4586489d672ba4501c486b6">llvm::MCSection::FragList::Head</a>.</p>


<p>Referenced by <a href="#a0fcfdc05d17713d4bd5c4bd4aaaea0ae">finishImpl</a>.</p>

</div>
</div>

### emitAssemblerFlag {#a8eb571ea4b693cfa886b7ab49f8eb07c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCMachOStreamer::emitAssemblerFlag (<a href="/web-llvm/docs/api/namespaces/llvm/#aa09571f0b44fd6bd8fae33d6ead290c1">MCAssemblerFlag</a> Flag)</td>
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

<p>Note in the output the specified <span class="doxyComputerOutput">Flag</span>.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="#a7a42090118f78814bc7429038d910869">getWriter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa09571f0b44fd6bd8fae33d6ead290c1a97f114ed47db100e48185ee6d6ad531b">llvm::MCAF_Code16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa09571f0b44fd6bd8fae33d6ead290c1ad77d445deab9f2715c6d2b48aee116ea">llvm::MCAF_Code32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa09571f0b44fd6bd8fae33d6ead290c1a836c6b17b1d82a5d54d61120d3a99f8a">llvm::MCAF_Code64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa09571f0b44fd6bd8fae33d6ead290c1adeea37757529c5d5cfeb922221d0f6f0">llvm::MCAF_SubsectionsViaSymbols</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa09571f0b44fd6bd8fae33d6ead290c1a4673762188cd819fd32979a26c1c67b5">llvm::MCAF_SyntaxUnified</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter/#aa831236685f5dade77165be0679ae1f8">llvm::MCObjectWriter::setSubsectionsViaSymbols</a>.</p>

</div>
</div>

### emitAssignment {#a34ce30f596de6334b5f17323b15e4fa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCMachOStreamer::emitAssignment (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Value)</td>
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

<p>Emit an assignment of <span class="doxyComputerOutput">Value</span> to <span class="doxyComputerOutput">Symbol</span>.</p>


<p>This corresponds to an assembler statement such as: symbol = value</p>


<p>The assignment generates no code, but has the side effect of binding the value in the current context. For the assembly streamer, this prints the binding into the .s file.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The symbol being assigned to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Value</td>
<td class="doxyParamItemDescription"><p>- The value for the symbol.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a2cff84e102389b6f127a6051d9ff062a">llvm::MCObjectStreamer::emitAssignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a435bfff1f2697dbccd406b2e03112443">llvm::MCValue::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#aced07a0d8eb8031ff0c2a6d691277667">llvm::MCValue::getSymA</a> and <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#a9e7a76b67d50b7136eabb2599982ae41">llvm::MCValue::getSymB</a>.</p>

</div>
</div>

### emitBuildVersion {#aaefc9558efc4b58f37049b3e4656011f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCMachOStreamer::emitBuildVersion (unsigned Platform, unsigned Major, unsigned Minor, unsigned Update, <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> SDKVersion)</td>
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

<p>Emit/Specify Mach-O build version command.</p>


<p><span class="doxyComputerOutput">Platform</span> should be one of MachO::PlatformType.</p>


<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>References <a href="#a7a42090118f78814bc7429038d910869">getWriter</a> and <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#af3936ecdc3e1dad30506a50cbadb3ae9">llvm::MachObjectWriter::setBuildVersion</a>.</p>

</div>
</div>

### emitCGProfileEntry {#a58e3c2a4ec9c34e4a8c8388fb66946ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::emitCGProfileEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr">MCSymbolRefExpr</a> * From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr">MCSymbolRefExpr</a> * To, uint64_t Count)</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a048f077746d95f142d02e56586862bf2">llvm::MCSymbolRefExpr::getSymbol</a>, <a href="#a7a42090118f78814bc7429038d910869">getWriter</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#acb1c818c7e94eb25afce63fc2f91c0e2">llvm::MCSymbol::isTemporary</a>.</p>

</div>
</div>

### emitCommonSymbol {#af1da8e248a188abfab9a12525b3290ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCMachOStreamer::emitCommonSymbol (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ByteAlignment)</td>
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

<p>Emit a common symbol.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The common symbol to emit.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>- The size of the common symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ByteAlignment</td>
<td class="doxyParamItemDescription"><p>- The alignment of the symbol.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### emitDarwinTargetVariantBuildVersion {#a109ba15aa1760d974d280d73a7b632b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCMachOStreamer::emitDarwinTargetVariantBuildVersion (unsigned Platform, unsigned Major, unsigned Minor, unsigned Update, <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> SDKVersion)</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>References <a href="#a7a42090118f78814bc7429038d910869">getWriter</a> and <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a08b1cd34ac4caf308aac4476c51adb7a">llvm::MachObjectWriter::setTargetVariantBuildVersion</a>.</p>

</div>
</div>

### emitDataRegion {#a125094f2b526fe5c975b36c2fa59113f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCMachOStreamer::emitDataRegion (<a href="/web-llvm/docs/api/namespaces/llvm/#a515cb4eba75abc2f0e9dbfffb0137008">MCDataRegionType</a> Kind)</td>
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

<p>Note in the output the specified region <span class="doxyComputerOutput">Kind</span>.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac782e0c3ae71664c3cb1a0430e894bc0accb839a7d74393e10b7ee3ca4a09d38d">llvm::MachO::DICE_KIND_DATA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac782e0c3ae71664c3cb1a0430e894bc0a5e3fb2332a165876f4bbcf525e4a1df1">llvm::MachO::DICE_KIND_JUMP_TABLE16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac782e0c3ae71664c3cb1a0430e894bc0a627069d039d10e4ff2016ff6a83449d1">llvm::MachO::DICE_KIND_JUMP_TABLE32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ac782e0c3ae71664c3cb1a0430e894bc0a0acfff833cecc8082390fc5118f77c68">llvm::MachO::DICE_KIND_JUMP_TABLE8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a515cb4eba75abc2f0e9dbfffb0137008a05d6258eaccbe86ca4c18e36910fda79">llvm::MCDR_DataRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a515cb4eba75abc2f0e9dbfffb0137008a0178c9475f859cfd8a0f552b8e22f412">llvm::MCDR_DataRegionEnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a515cb4eba75abc2f0e9dbfffb0137008adc2335b540bd652d82bf3bcbed5a87d4">llvm::MCDR_DataRegionJT16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a515cb4eba75abc2f0e9dbfffb0137008ac0586422896e4472fa7aa7118d9a4ecb">llvm::MCDR_DataRegionJT32</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a515cb4eba75abc2f0e9dbfffb0137008a1183f27779c00ba04ce7aec4344952d2">llvm::MCDR_DataRegionJT8</a>.</p>

</div>
</div>

### emitEHSymAttributes {#ae4b7284c767b0b63e76c11e3c1c8c3db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCMachOStreamer::emitEHSymAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * EHSymbol)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a798fb78a6525095a294fda8d027edeb6">emitSymbolAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243aa1e94c23156e37812e4d6e078af1d728">llvm::MCSA_Global</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a39ad38d82f889bf4c82e539beb859d05">llvm::MCSA_PrivateExtern</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a9cd0febd9a535eb96c33815707bab481">llvm::MCSA_WeakDefinition</a>.</p>

</div>
</div>

### emitIdent {#acaf863fa4e92ee4e97252cff47377cf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::emitIdent (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IdentString)</td>
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

<p>Emit the "identifiers" directive.</p>


<p>This implements the '.ident "version foo"' assembler directive.</p>


<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### emitLabel {#a3a886379efdc1ac575d1a38dd8b01775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCMachOStreamer::emitLabel (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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

<p>Emit a label for <span class="doxyComputerOutput">Symbol</span> into the current section.</p>


<p>This corresponds to an assembler statement such as: foo:</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The symbol to emit. A given symbol should only be emitted as a label once, and symbols emitted as a label should never be used in an assignment.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9924d739e3dc812b561931a1ad6eb5cf">llvm::MCObjectStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a941f547c39a7daf0a48452cc945a835c">llvm::MCObjectStreamer::insert</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/machobjectwriter-cpp/#adee15ddf2796a0e230bf8ec9465e9cdc">isSymbolLinkerVisible</a>.</p>


<p>Referenced by <a href="#af20b6581bfb880b0df6d552b229739f9">emitZerofill</a>.</p>

</div>
</div>

### emitLinkerOptions {#a20df437db4d5607918482b6758bd9ffa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCMachOStreamer::emitLinkerOptions (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::string &gt; Kind)</td>
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

<p>Emit the given list <span class="doxyComputerOutput">Options</span> of strings as linker options into the output.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#af7756b275710eb6ea0b5f9f0b501bef2">llvm::MachObjectWriter::getLinkerOptions</a>, <a href="#a7a42090118f78814bc7429038d910869">getWriter</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>

</div>
</div>

### emitLocalCommonSymbol {#ac361b5e6ec19ddb003ca8d13ad57354d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCMachOStreamer::emitLocalCommonSymbol (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ByteAlignment)</td>
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

<p>Emit a local common (.lcomm) symbol.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The common symbol to emit.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>- The size of the common symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ByteAlignment</td>
<td class="doxyParamItemDescription"><p>- The alignment of the common symbol in bytes.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>References <a href="#af20b6581bfb880b0df6d552b229739f9">emitZerofill</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### emitLOHDirective {#aeb494b131350ac649ee801a9effc9b11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::emitLOHDirective (<a href="/web-llvm/docs/api/namespaces/llvm/#aadff17100a7bcc6ddd2940e098ddbcf5">MCLOHType</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a62129b64f06d9bc8df1c60845451432b">MCLOHArgs</a> &amp; Args)</td>
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

<p>Emit a Linker Optimization Hint (LOH) directive.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Args</td>
<td class="doxyParamItemDescription"><p>- Arguments of the LOH.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>Reference <a href="#a7a42090118f78814bc7429038d910869">getWriter</a>.</p>

</div>
</div>

### emitSymbolAttribute {#a798fb78a6525095a294fda8d027edeb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCMachOStreamer::emitSymbolAttribute (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243">MCSymbolAttr</a> Attribute)</td>
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

<p>Add the given <span class="doxyComputerOutput">Attribute</span> to <span class="doxyComputerOutput">Symbol</span>.</p>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae1b3cf074436ef5b527071540e13bd58">llvm::MCStreamer::getCurrentSectionOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a95a5423ec4f5177c9eaaaf2a60eb876d">llvm::MachObjectWriter::getIndirectSymbols</a>, <a href="#a7a42090118f78814bc7429038d910869">getWriter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a452eae0b6838f1340eb75102bdfabd47">llvm::MCSA_AltEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243ab79bc663bb12acbf83bd10cdcfdd037e">llvm::MCSA_Cold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a9edfe2cb31eba126ff7c30b999c56646">llvm::MCSA_ELF_TypeCommon</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243ad0efc318f7416b800a38c5cc42ddbfa9">llvm::MCSA_ELF_TypeFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243ad07ba742431c4f5e789624beae77683a">llvm::MCSA_ELF_TypeGnuUniqueObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a5d62f59d328d117d64c99526e77c68df">llvm::MCSA_ELF_TypeIndFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a7eadfaef3a6cc05735b52d92ff0540e9">llvm::MCSA_ELF_TypeNoType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243acf016837e7bf7ff2387b46d789c1f5d4">llvm::MCSA_ELF_TypeObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a86783fdbba192be49198856191150827">llvm::MCSA_ELF_TypeTLS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a345961d937ffac378faab680906913d6">llvm::MCSA_Exported</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243ab11aa8a54bc3faf1ef7db38e4bf4fb60">llvm::MCSA_Extern</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243aa1e94c23156e37812e4d6e078af1d728">llvm::MCSA_Global</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243ae472359b991bb5235c8f6714f4cacb6a">llvm::MCSA_Hidden</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a9c4d91f21dab6846f0eb7cdd8608c16a">llvm::MCSA_IndirectSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a3b2ee46211db7e561d0b732b5ae4fe5e">llvm::MCSA_Internal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243af3367f8319e21bf0779da14146221c55">llvm::MCSA_Invalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a6f8590ba0f71b1b8b0e937695e303208">llvm::MCSA_LazyReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243ae5c5c7dd59c0c23f91be2b9c8f2594c9">llvm::MCSA_LGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a02f22ce66e6bacb5fbaba644ec799653">llvm::MCSA_Local</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a17067e9f600d7ededa1cd3a6f236d5a7">llvm::MCSA_Memtag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243afb34d5700d536c3f8f8a5004985d1f57">llvm::MCSA_NoDeadStrip</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a39ad38d82f889bf4c82e539beb859d05">llvm::MCSA_PrivateExtern</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a1f47433b83f2818076a3cf55b500233a">llvm::MCSA_Protected</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a80891606fbdc946b4085496f58aafd62">llvm::MCSA_Reference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a83196df34bcdda178fae802a4a06a6dc">llvm::MCSA_SymbolResolver</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a83df6138e7dba38c0c80380486544ea0">llvm::MCSA_Weak</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243aa96e85228ec0460e2b923801660b33f9">llvm::MCSA_WeakAntiDep</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a0506d51c6914f1b55fec60c97d4d8cc9">llvm::MCSA_WeakDefAutoPrivate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a9cd0febd9a535eb96c33815707bab481">llvm::MCSA_WeakDefinition</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243a42ec27e2fd185b27d0fbf1aaf0bfd214">llvm::MCSA_WeakReference</a>.</p>


<p>Referenced by <a href="#ae4b7284c767b0b63e76c11e3c1c8c3db">emitEHSymAttributes</a>.</p>

</div>
</div>

### emitSymbolDesc {#af5369560155ea22c4431734d7a2d571f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCMachOStreamer::emitSymbolDesc (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, unsigned DescValue)</td>
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

<p>Set the <span class="doxyComputerOutput">DescValue</span> for the <span class="doxyComputerOutput">Symbol</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The symbol to have its n_desc field set.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">DescValue</td>
<td class="doxyParamItemDescription"><p>- The value to set into the n_desc field.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>.</p>

</div>
</div>

### emitTBSSSymbol {#a2cc7ffb47b770c4b442fd456d6c66963}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCMachOStreamer::emitTBSSSymbol (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ByteAlignment=<a href="/web-llvm/docs/api/structs/llvm/align">Align</a>(1))</td>
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

<p>Emit a thread local bss (.tbss) symbol.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Section</td>
<td class="doxyParamItemDescription"><p>- The thread local common section.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The thread local common symbol to emit.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>- The size of the symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ByteAlignment</td>
<td class="doxyParamItemDescription"><p>- The alignment of the thread local common symbol.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>References <a href="#af20b6581bfb880b0df6d552b229739f9">emitZerofill</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### emitThumbFunc {#a8b711b3a69c236fd97741567932418dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCMachOStreamer::emitThumbFunc (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Func)</td>
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

<p>Note in the output that the specified <span class="doxyComputerOutput">Func</span> is a Thumb mode function (ARM target only).</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>.</p>

</div>
</div>

### emitVersionMin {#a54b409598660523f6cc25d472089fc05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCMachOStreamer::emitVersionMin (<a href="/web-llvm/docs/api/namespaces/llvm/#a7b22b2a20e7587321d17cb029ea8626e">MCVersionMinType</a> Type, unsigned Major, unsigned Minor, unsigned Update, <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> SDKVersion)</td>
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

<p>Specify the Mach-O minimum deployment target version.</p>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>References <a href="#a7a42090118f78814bc7429038d910869">getWriter</a> and <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#af13dd44b52d16a2aacf2d74fa529ac7a">llvm::MachObjectWriter::setVersionMin</a>.</p>

</div>
</div>

### emitZerofill {#af20b6581bfb880b0df6d552b229739f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCMachOStreamer::emitZerofill (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol=nullptr, uint64_t Size=0, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ByteAlignment=<a href="/web-llvm/docs/api/structs/llvm/align">Align</a>(1), <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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

<p>Emit the zerofill section and an optional symbol.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Section</td>
<td class="doxyParamItemDescription"><p>- The zerofill section to create and or to put the symbol</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Symbol</td>
<td class="doxyParamItemDescription"><p>- The zerofill symbol to emit, if non-NULL.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>- The size of the zerofill symbol.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ByteAlignment</td>
<td class="doxyParamItemDescription"><p>- The alignment of the zerofill symbol.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>References <a href="#a3a886379efdc1ac575d1a38dd8b01775">emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a21d70037ecf679b5f8d13af07f8f136a">llvm::MCObjectStreamer::emitValueToAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae77a5b8d3af591a461aeac723de33240">llvm::MCStreamer::emitZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a216005880453270b48e5d5d7daeec6d4">llvm::MCStreamer::popSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ab095568f88bb32f8a744aaeab0d2c4d0">llvm::MCStreamer::pushSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac4f84451dc4abc997c960d484953b1d2">llvm::MCStreamer::switchSection</a>.</p>


<p>Referenced by <a href="#ac361b5e6ec19ddb003ca8d13ad57354d">emitLocalCommonSymbol</a> and <a href="#a2cc7ffb47b770c4b442fd456d6c66963">emitTBSSSymbol</a>.</p>

</div>
</div>

### finalizeCGProfile {#adc76b392eb3df7f2d5456efe795060c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCMachOStreamer::finalizeCGProfile ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsection/#add652e7ff42f6239bfb6aeef0e86c6f1">llvm::MCSection::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#afb372de94b1d4298c2bd4518af8e14bd">changeSection</a>, <a href="#a03ebbddf5185beab8e633649235fe873">finalizeCGProfileEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionkind/#a13a2c76a48665ee3f4782fba7ddd72e1">llvm::SectionKind::getMetadata</a> and <a href="#a7a42090118f78814bc7429038d910869">getWriter</a>.</p>


<p>Referenced by <a href="#a0fcfdc05d17713d4bd5c4bd4aaaea0ae">finishImpl</a>.</p>

</div>
</div>

### finalizeCGProfileEntry {#a03ebbddf5185beab8e633649235fe873}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCMachOStreamer::finalizeCGProfileEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr">MCSymbolRefExpr</a> *&amp; SRE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a048f077746d95f142d02e56586862bf2">llvm::MCSymbolRefExpr::getSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a41a90289b3b4b0ce7aa1b450fd38607d">llvm::MCSymbol::setExternal</a>.</p>


<p>Referenced by <a href="#adc76b392eb3df7f2d5456efe795060c3">finalizeCGProfile</a>.</p>

</div>
</div>

### finishImpl {#a0fcfdc05d17713d4bd5c4bd4aaaea0ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCMachOStreamer::finishImpl ()</td>
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

<p>Streamer specific finalization.</p>

<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a5b9193e77b26973b0c65a96716330b87">createAddrSigSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#ad65b998727eb009e1a448a4aa3f2e1b3">llvm::MCObjectStreamer::emitFrames</a>, <a href="#adc76b392eb3df7f2d5456efe795060c3">finalizeCGProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#aa8d1c93368ccaad9bdc429b25633f943">llvm::MCObjectStreamer::finishImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3e9a3c0090b1184f7371fa5ad4ce57c9">llvm::MCObjectStreamer::getAssembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0b2ca98dc28c61793ff5c90d23e5f14e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::lookup</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcmachostreamer-cpp">MCMachOStreamer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
