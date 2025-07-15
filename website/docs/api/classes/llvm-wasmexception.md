---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/wasmexception
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `WasmException` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::WasmException { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wasmexception-h">CodeGen/AsmPrinter/WasmException.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ehstreamer">EHStreamer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits exception handling directives. <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef95e7cb1b029601fa05185d266b0474">WasmException</a> (AsmPrinter *A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab671a798b9580f337321bc4a8523fe25">endModule</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit all sections that should come after the content. <a href="#ab671a798b9580f337321bc4a8523fe25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af41f93281694a77b5a9ed1f0e36a2cb3">beginFunction</a> (const MachineFunction *MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gather pre-function debug information. <a href="#af41f93281694a77b5a9ed1f0e36a2cb3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3f7a2c3431323c5e22c2c175ebef9cb">endFunction</a> (const MachineFunction *MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gather post-function debug information. <a href="#ae3f7a2c3431323c5e22c2c175ebef9cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8db890ae03cb072b7198ebcc5d52028b">computeCallSiteTable</a> (SmallVectorImpl&lt; CallSiteEntry &gt; &amp;CallSites, SmallVectorImpl&lt; CallSiteRange &gt; &amp;CallSiteRanges, const SmallVectorImpl&lt; const LandingPadInfo * &gt; &amp;LandingPads, const SmallVectorImpl&lt; unsigned &gt; &amp;FirstActions) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the call-site table and the call-site ranges. <a href="#a8db890ae03cb072b7198ebcc5d52028b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wasmexception-h">WasmException.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WasmException() {#aef95e7cb1b029601fa05185d266b0474}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::WasmException::WasmException (<a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * A)</td>
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



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wasmexception-h">WasmException.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#ae951249a56bafbb7b57c4f571f9b4a3a">llvm::EHStreamer::EHStreamer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### beginFunction() {#af41f93281694a77b5a9ed1f0e36a2cb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::WasmException::beginFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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

<p>Gather pre-function debug information.</p>


<p>Every beginFunction(MF) call should be followed by an endFunction(MF) call.</p>


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wasmexception-h">WasmException.h</a>.</p>

</div>
</div>

### endFunction() {#ae3f7a2c3431323c5e22c2c175ebef9cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WasmException::endFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
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

<p>Gather post-function debug information.</p>

<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wasmexception-h">WasmException.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wasmexception-cpp">WasmException.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a346d40526a13ec03f632cd9fd1b51ca9">llvm::EHStreamer::Asm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a9914b597552aa4b4bcbb8acaa04d632a">llvm::MCSymbolRefExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcbinaryexpr/#af766134165065939f49fb0662c246f66">llvm::MCBinaryExpr::createSub</a>, <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a420cc4a7a63b33a52659768b133b5f1b">llvm::EHStreamer::emitExceptionTable</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa3fd81545fc9f10418752ee043f8645f">llvm::MachineFunction::getLandingPads</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#abf987be38a5674763d9143ca02452540">llvm::MachineFunction::hasWasmLandingPadIndex</a>.</p>

</div>
</div>

### endModule() {#ab671a798b9580f337321bc4a8523fe25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WasmException::endModule ()</td>
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

<p>Emit all sections that should come after the content.</p>

<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wasmexception-h">WasmException.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wasmexception-cpp">WasmException.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a346d40526a13ec03f632cd9fd1b51ca9">llvm::EHStreamer::Asm</a> and <a href="/web-llvm/docs/api/classes/llvm/mangler/#aa1c9296fd511eb96bb487befbf5e7cea">llvm::Mangler::getNameWithPrefix</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### computeCallSiteTable() {#a8db890ae03cb072b7198ebcc5d52028b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WasmException::computeCallSiteTable (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/ehstreamer/callsiteentry">CallSiteEntry</a> &gt; &amp; CallSites, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/ehstreamer/callsiterange">CallSiteRange</a> &gt; &amp; CallSiteRanges, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/landingpadinfo">LandingPadInfo</a> * &gt; &amp; LandingPads, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; FirstActions)</td>
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

<p>Compute the call-site table and the call-site ranges.</p>


<p>Compute the call-site table.</p>


<p>The entry for an invoke has a try-range containing the call, a non-zero landing pad and an appropriate action. The entry for an ordinary call has a try-range containing the call and zero for the landing pad and the action. Calls marked 'nounwind' have no entry and must not be contained in the try-range of any entry - they form gaps in the table. Entries must be ordered by try-range address. CallSiteRanges vector is only populated for Itanium exception handling.</p>


<p>The entry for an invoke has a try-range containing the call, a non-zero landing pad, and an appropriate action. The entry for an ordinary call has a try-range containing the call and zero for the landing pad and the action. Calls marked 'nounwind' have no entry and must not be contained in the try-range of any entry - they form gaps in the table. Entries must be ordered by try-range address.</p>


<p>Call-sites are split into one or more call-site ranges associated with different sections of the function.</p>


<ul class="doxyList ">
<li>Without -basic-block-sections, all call-sites are grouped into one call-site-range corresponding to the function section.</li>
<li>With -basic-block-sections, one call-site range is created for each section, with its FragmentBeginLabel and FragmentEndLabel respectively</li>
</ul>

<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wasmexception-h">WasmException.h</a>, definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wasmexception-cpp">WasmException.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a346d40526a13ec03f632cd9fd1b51ca9">llvm::EHStreamer::Asm</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a8f0403c2e238dbeeb4e98b0baf2aa13f">llvm::MachineFunction::getWasmLandingPadIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#abf987be38a5674763d9143ca02452540">llvm::MachineFunction::hasWasmLandingPadIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wasmexception-cpp">WasmException.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/wasmexception-h">WasmException.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
