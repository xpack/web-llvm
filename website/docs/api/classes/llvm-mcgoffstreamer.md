---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcgoffstreamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MCGOFFStreamer` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MCGOFFStreamer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcgoffstreamer-h">llvm/MC/MCGOFFStreamer.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8a08d827421a34ca4a21fbc081ce677">MCGOFFStreamer</a> (MCContext &amp;Context, std::unique_ptr&lt; MCAsmBackend &gt; MAB, std::unique_ptr&lt; MCObjectWriter &gt; OW, std::unique_ptr&lt; MCCodeEmitter &gt; Emitter)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab69cae85d6b0abd72ed04d9eedba461a">~MCGOFFStreamer</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbf06b5a62c72ea8ba4dc8a374cfe139">emitSymbolAttribute</a> (MCSymbol *Symbol, MCSymbolAttr Attribute) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the given <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></span> to <span class="doxyComputerOutput">Symbol</span>. <a href="#abbf06b5a62c72ea8ba4dc8a374cfe139">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adab07493b4bfc338a3e76e5e9ad301de">emitCommonSymbol</a> (MCSymbol *Symbol, uint64_t Size, Align ByteAlignment) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a common symbol. <a href="#adab07493b4bfc338a3e76e5e9ad301de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c9ffef12ec8c201d54a9007aec0fa88">emitInstToData</a> (const MCInst &amp;Inst, const MCSubtargetInfo &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30a247c66cf6cdee3130a13310248676">emitZerofill</a> (MCSection *Section, MCSymbol *Symbol=nullptr, uint64_t Size=0, Align ByteAlignment=Align(1), SMLoc Loc=SMLoc()) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the zerofill section and an optional symbol. <a href="#a30a247c66cf6cdee3130a13310248676">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcgoffstreamer-h">MCGOFFStreamer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCGOFFStreamer() {#ad8a08d827421a34ca4a21fbc081ce677}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCGOFFStreamer::MCGOFFStreamer (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &gt; MAB, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcobjectwriter">MCObjectWriter</a> &gt; OW, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mccodeemitter">MCCodeEmitter</a> &gt; Emitter)</td>
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



<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcgoffstreamer-h">MCGOFFStreamer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#a4e37c99d7f846fd82966c68def83c4fc">Emitter</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9ad1da683a018add519fd96cd22cc785">llvm::MCObjectStreamer::MCObjectStreamer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MCGOFFStreamer() {#ab69cae85d6b0abd72ed04d9eedba461a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCGOFFStreamer::~MCGOFFStreamer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcgoffstreamer-h">MCGOFFStreamer.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcgoffstreamer-cpp">MCGOFFStreamer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitCommonSymbol() {#adab07493b4bfc338a3e76e5e9ad301de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCGOFFStreamer::emitCommonSymbol (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ByteAlignment)</td>
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

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcgoffstreamer-h">MCGOFFStreamer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### emitInstToData() {#a6c9ffef12ec8c201d54a9007aec0fa88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCGOFFStreamer::emitInstToData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp;)</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcgoffstreamer-h">MCGOFFStreamer.h</a>.</p>

</div>
</div>

### emitSymbolAttribute() {#abbf06b5a62c72ea8ba4dc8a374cfe139}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCGOFFStreamer::emitSymbolAttribute (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol, <a href="/web-llvm/docs/api/namespaces/llvm/#af74c787f7a33e251485729416d260243">MCSymbolAttr</a> Attribute)</td>
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

<p>Add the given <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></span> to <span class="doxyComputerOutput">Symbol</span>.</p>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcgoffstreamer-h">MCGOFFStreamer.h</a>.</p>

</div>
</div>

### emitZerofill() {#a30a247c66cf6cdee3130a13310248676}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCGOFFStreamer::emitZerofill (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Section, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Symbol=nullptr, uint64_t Size=0, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> ByteAlignment=<a href="/web-llvm/docs/api/structs/llvm/align">Align</a>(1), <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>())</td>
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

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcgoffstreamer-h">MCGOFFStreamer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcgoffstreamer-h">MCGOFFStreamer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcgoffstreamer-cpp">MCGOFFStreamer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
